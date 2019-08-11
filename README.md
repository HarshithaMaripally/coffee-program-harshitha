#include<stdio.h>
#include<math.h>
int main()
{
float p,q;
scanf("%f %f",&p,&q);
float r,s;
int ans=0;
while(p!=0)
{
s=q/100*p;
r=floor(p-s);
ans=ans+p;
p=r;
}
printf("%d\n",res);
}
