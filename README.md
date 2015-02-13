# maths_function.c
My maths function
#include <stdio.h>
int main()
{
int a, b, c;
printf("Enter two numbers\n");
scanf("%d%d", &a, &b);
c = a + b;
c = a - b;
c = a / b;
printf("Sum of numbers = %d\n", c);
return 0;
}
