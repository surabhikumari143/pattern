#include<stdio.h>
int main()
{
    int i,j,k,n;
    printf("Enter the number of rows : ");
    scanf("%d",&n);
    for(i=1;i<=n;i++)
    {
        for(j=1,k=0;j<=i*2;j++,k++)
        {
            printf("%d",k%2);
        }
        printf("\n");
    }
}
