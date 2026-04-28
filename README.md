#include<stdio.h>
int main()
{
int n,c;
n=2;
c=1;
do
{
  printf("%d*%d=%d\n",n,c,n*c);
  c=c+1;
}
while(c<=10);
}
output
2*1=2
2*2=4
2*3=6
2*4=8
2*5=10
2*6=12
2*7=14
2*8=16
2*9=18
2*10=20
