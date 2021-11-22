#include<stdio.h> //Header file
int fact(int n){   //Declaring function
	if(n==0||n==1){ //Codes inside the function
		return 1;
	}
	else{
		return n*(n-1);
	}
}
int main(){
	int a;
	printf("Enter the number for factorial: ");
	scanf("%d",&a);
	printf("The factorial of %d is : %d",a,fact(a));
	return 0;
}
