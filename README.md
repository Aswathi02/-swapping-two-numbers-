//swapping two numbers
#include<stdio.h>
voidmain() 
{
   int a,b;
  printf("Enter the value of a: ");
  scanf("%d", &a);
  printf("Enter the value of b: ");
  scanf("%d", &b);
  // swapping numbers 
  a=a+b;
  b=a-b;
  a=a-b;
  printf("\nAfter swapping the first  value = %d\n",a);
  printf("After swapping the second value  = %d",b);
  return 0;
}
