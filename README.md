#include<stdio.h>
void main()
{
    int a,b,c,d,mul;
    printf("Enter a value:");
    scanf("%d",&a);
    printf("Enter b value:");
    scanf("%d",&b);
    printf("Enter c value:");
    scanf("%d",&c);
    printf("Enter d value:");
    scanf("%d",&d);
    mul=(a+b)*(c-d);
    printf("The multiplication is:%d",mul);
}
