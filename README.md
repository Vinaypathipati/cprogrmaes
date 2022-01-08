#include<stdio.h>
int main(void)
{
int a,b,c;
printf("enter a,b,c values");
scanf("%d%d%d",&a,&b,&c);
if (a==b && b==c && c==a)
{
printf("it is an equilateral triangle");
}
else if (a==b||b==c||c==a)
{
printf("it is an isosceles triangle");
}
else 
{
printf("it is an scalen triangle");
}
}

