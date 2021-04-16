#include<stdio.h>
int main()
{

float a,b,c;
char ch;
printf("1st no:\n");
scanf("%f",&a);
printf("2nd no:\n");
scanf("%f",&b);
printf("type:\n1.Addition\n2.Subtraction\n3.Multiplication\n4.Division:\n\n----------->");
scanf("%d",&ch);

switch(ch)
{
	case 1:
		c=a+b;
		printf("\n%f + %f = %f",a,b,c);
		break;
	case 2:
		c=a-b;
		printf("\n%f - %f = %f",a,b,c);
		break;
	case 3:
		c=a*b;
		printf("\n%f x %f = %f",a,b,c);
		break;
	case 4:
		c=a/b;
		printf("\n%f / %f = %f",a,b,c);
		break;
	default:
	    printf("\nInvalid choice");
		break;	
}



return 0;
}
