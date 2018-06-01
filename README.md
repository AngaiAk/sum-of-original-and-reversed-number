#include<stdio.h>
int main()
{
    int i,r=0,n,sum;
    printf("the number is:");
    scanf("%d",&n);
    i=n;
    while(i!=0)
    {
        r=r*10;
        r=r+(i%10);
        i=i/10;
    }
    printf("\nThe reversed  number is %d:",r);
    sum=n+r;
    printf("\nThe sum is:%d",sum);
    return 0;
}
