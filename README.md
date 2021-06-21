# Check-the-set-bit-in-any-number-
#include <stdio.h>
int main()
{   
    int n,k;
    printf("Please provide a number that check set bit:\n");
    scanf("%d",&n);
    printf("Enter bits number that you check set or not:\n");
    scanf("%d",&k);
    if((n&(1<<(k-1)))==0)
   {
       printf("In these number the bit is not set bit:");
       
   }
    else
    printf("In these number the bit is set bit:");

    return 0;
}
