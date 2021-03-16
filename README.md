# Reverse-an-Integer
C programming
#include <stdio.h>

int main()
{
    int n,a,sum=0;
    printf("entre a number=");
    scanf("%d",&n);
    while(n>0){
        a=n%10;
        sum=sum*10+a;
        n=n/10;
    }
    printf("Reversed number = %d", sum);
    return 0;
    
}
