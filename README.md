#include <stdio.h>

int main() {
   int start,end, sum=0,i;
   printf("enter the starting number:\n");
   scanf("%d",&start);
   printf("enter the ending number:\n");
   scanf("%d",&end);
   printf("even numbers are:\n");
   for(int i=start;i<=end;i++)
   {
       if(i%2==0)//i%2==1 for odd numbers
       {
       printf("sum of the even numbers:%d",sum);
}
 printf("%d\n",i);
           sum+=i;
       }

    return 0;
}
