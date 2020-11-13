# xu-progrom
no
#include<stdio.h>
int main()
{
	int a = 5,b = 3;
	printf("输出前：a=%d b=%d\n",a,b);
	a = a^b;
	b = a^b;
	a = a^b;
	printf("输出后：a=%d b=%d\n",a,b);
	return 0;
}


