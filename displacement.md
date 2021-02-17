# /* C program for finding displacement (s=u*t+0.5*a*t*t)*/

```c
#include<stdio.h>
#include<conio.h>
int main()
{
	float s,u,t,a;
	clrscr();
    printf("enter the values of u,t,a");
	scanf("%f%f%f",&u,&t,&a);
	s=(u*t)+(0.5*a*t*t);
	printf("\ns=%f",s);
	getch();
	return 0;
}
```

