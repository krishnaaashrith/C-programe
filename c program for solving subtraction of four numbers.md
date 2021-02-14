# /* c program for solving subtraction of four numbers */

```c
#include<stdio.h>
#include<conio.h>
int main()
{
    float a,b,c,d,e;
    clrscr();
    printf("enter values");
    scanf("%f%f%f%f",&a,&b,&c,&d);
    e=a-b-c-d;
    printf("\n result = %f",e);
    getch();
    return 0;
}


