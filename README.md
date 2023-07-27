# PRIME-NUMBER-OR-NOT-IN-C.
#include<stdio.h>
int main()
{
    int i,a,count=0;
    printf("Enter the number to check :");
    scanf("%d",&a);
    for(i=1;i<=a;i++)
    {
        if(a%i==0)
        {
            count=count+1;
        }
    }
    if(count<=2)
    {
        printf("prime number");
    }
    else
    {
        printf("not a prime number");
    }
    return 0;
}
