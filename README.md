# takes-nothing-return-something
This is a program for functions in C programing in the way of takes nothing return something type.
#include<stdio.h>
#include<conio.h>
void main()
{
	int account();
	int s;
    printf(" New account: \n \n ");
	s=account();
}
int account()
{
	int a,b,c;
	printf("Enter value of a:");
	scanf("%d",&a);
	printf("\n Enter value of b:");
	scanf("%d",&b);
	printf("\n Enter value of c:");
	scanf("%d",&c);
	if(a*b<=c)
	{
		if(a*b==c)
		{
			printf("\n Your account has created ");
			printf("\n You can access it by clicking on agree option");
		}
		else
		{
			printf("\n Your account has created");
			printf("\n You have to give a valid security proof to access it");
		}
	}
	else
	{
		printf("\n Sorry");
		printf("\n You have entered invalid information");
	}
	return(c);
}
int varification()
{
	int a,b;
	printf("Enter value of a:");
	scanf("%d",&a);
	printf("\n Enter value of b:");
	scanf("%d",&b);
	if(a%b==0)
	{
		printf("\n Your account has verified ");
		printf("\n You can use it");
		printf("\n It is safe for your device");
	}
	else
	{
		printf("\n Some bugs are identified");
		printf("\n Advised to remove it for security of your device");
	}
}
