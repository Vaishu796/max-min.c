#include<stdio.h>

int main()
{
int a,b,c;
printf("ENTER THE VALUE:");
scanf("%d%d%d",&a,&b,&c);

if((a>b)&&(a>c))
{
    printf("MAXIMUM NUMBER:%d",a);
}
else if((b>a)&&(b>c))
{
    printf("MAXIMUM VALUE:%d",b);
}
else
{
    printf("MAXIMUM NUMBER:%d",c);
}
 return 0;
}








