/* WAP to input any number. compare condition and check whether the number is positive, negative 
  or zero */
#include<stdio.h>

void main()
{
	int no;
	
	printf("\n Enter any number :");
	scanf("%d",&no); //0
	
	
	//following condition must be true to show output "number is positive"
	if(no>0)
	{
		printf("\n number is positive");
	}

	if(no<0)
	{
		printf("\n number is negative");
	}
	
	if(no==0)
	{
		printf("\n number is zero");
	}

}
