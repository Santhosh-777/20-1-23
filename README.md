#include<stdio.h>
 int main()
{
    int i=1,n,c=0;
    printf("enter the value of n\n");
    scanf("%d",&n);
    while(i<=n)
    {
        if(n%i==0)
        {
            c++;
        }
    }
    if(c==2)
    printf("prime no");
    else
    printf("not prime");
}
