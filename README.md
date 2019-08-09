#include<stdio.h>
int main()
{
int x,y;
float p;
printf("enter x and p values")
scanf("%d %f",x,p);
printf("\n\n");
if(x>=0&&x<=10000&&p>=1&&p<=100)
{
for(y=x;y>0;y--)
{
  x=x-(p/100)*x;
  y=y+x;
 }
 }
 else
  printf("enter correct values");
 if(x==0)
 printf("amount to be paid:%d",y);
 return 0;
}
