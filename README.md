错颜
定义函数，转义字符，while、for循环分支语句

#include<stdio.h>
int add(int a,int b)
{
    int c=0;
    c=a+b;
    return c;
}
int main() {
    int d = 0;
    int e = 0;
    int f=1;
    char g;
    scanf("%d%d",&d,&e);
    int num=add(d,e);
    printf("num=%d\n",num);

    if(num<=2)
        printf("dfgh\122vhg\n\0ghj");
    else if(num>4 && num<=6)
    {
        g=getchar();
        printf("%c\n",g);
    }   
    else if(num>6 && num<8)
        printf("hehe\n");
    else
    while(f<3)
    {
        printf("第%d个\n",f);
        f++;
    }

    for(int i=1;i<5;i++)
    {
        printf("%d\n",i);
    }
    return 0;
}

