#include<stdio.h>
#include<stdlib.h>
int main()
{
	int m, n,i,j,sum=0;
	int **a;
		printf("Enter no. of rows and columns: ");
	scanf("%d%d", &m, &n);
	a = (int **) malloc(m * sizeof(int *));	//Allocate memory to matrix
	for(i=0; i<m; i++)
	{
		a[i] = (int *) malloc(n * sizeof(int));
	}
	printf("Enter matrix elements: ");	//Read elements into matrix
	for( i=0; i<m; i++)
	{
		for(j=0; j<n; j++)
		{
			scanf("%d", &a[i][j]);
		}
	}
	printf("Matrix elements are: \n");	//Print elements in the matrix
	for( i=0; i<m; i++)
	{
		for(j=0; j<n; j++)
		{
			printf("%d ", a[i][j]);
		}
		printf("\n");
	}
	for(i=0;i<m;i++)//sum of diagonal elements
		{
				sum=sum + a[i][i];
		}
	printf("The sum of diagonal elements of given matrix is %d",sum);
	return 0;
}
