# error-1

#include<stdio.h>

int main()
{
	int fahr,celsius,lower,upper;
	
	printf("lower:");
	scanf("%d",&lower);
	printf("upper:");
	scanf("%d",&upper);
	
	for(fahr=lower;fahr<=upper;fahr++)
	celsius=(5.0/9.0)*(fahr-32);
	
	printf("%d%\n%lf\n",fahr,celsius);
	
	return 0;
	
  
  
  程序今天有些错误，scanf里面的指针忘记写了，找了好久，都没找到，目前代码还是有问题，达不到自己想要的那个排序，等会在研究一下
  
  应该早些从事it的，半路出家，更应该多学多练习，多思考，多研究，
  
  感谢尼克，
  
  文章感恩节过了，但现在还是要感恩同学，老师，遇见的那么多人，我会好好加油的。。
