//Sum of Natural Number using for loop
#include <stdio.h>
void main()
{
    int i,n,sum=0;
    
    printf("Enter the number :");
    scanf("%d",&n);
    for(i=1;i<=n;i=i+1)
    {
        sum=sum+i;
        printf("\nsum of numbers is %d",sum);
    }
}
