# 07-average-alechavez26
07-average-alechavez26 created by GitHub Classroom
/*
 * Alejandra Chávez Cruz
 * 06/sept/18
 * A01411970@itesm.mx
*/
#include<stdio.h>

int main(){

	// Declaration of  the variables
	int v;
	int h;
	int m;
	int average;


	do{
		printf("Write a number: ");
		scanf("%",m &v);
		h+=v;
		m++;
	}while(v=0);

	h-=1;
	average=m/h; // I do the operations
	printf("\n%h", average);
return 0;
}
