#                   /* C program to find Area and Perimeter of a Circle*/



```c
#include<stdio.h>

#include<conio.h>

#define pi 3.14 

int main()

{

int r;

float A,P;

clrscr();

printf("enter the radius of circle");

scanf("%d",&r);

A=pi*r*r;

printf("\narea of circle=%f",A);

P=2*pi*r;

printf("\nperimeter of circle=%f",P);

getch();

return 0;

}
```

