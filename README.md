# PRIME-NUMBER-OR-NOT-IN-C.
#include&lt;stdio.h> int main() {     int i,a,count=0;     printf("Enter the number to check :");     scanf("%d",&amp;a);     for(i=1;i&lt;=a;i++)     {         if(a%i==0)         {             count=count+1;         }     }     if(count&lt;=2)     {         printf("prime number");     }     else     {         printf("not a prime number");     }     return 0; }
