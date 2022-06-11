# additionofpointer
#include<stdio.h>
void amta(int*,int*);
int main()
{
	int v1=25;
	int v2=20;
	amta(&v1,&v2);
	printf("v1+v2:%d\n",v1);
	printf("v1-v2 :%d\n",v2);
}
void amta(int *i,int*j)
{
	int t1,t2;
	t1=*i;
	t2=*j;
	*i=t1+t2;
	*j=t1-t2;
}
