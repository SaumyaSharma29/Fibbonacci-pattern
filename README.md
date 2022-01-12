# Fibbonacci-pattern

#include<stdio.h>
int fibonacci(int n)
{
if((n==1)||(n==0))
{
return(n)
}
else
{
return(fibonnaci(n-1)+fibonnaci(n-2))
}
int main()
{
int n,i=0;
printf("Input the number of terms for Fibonacci Series:");
scanf("%d",&n);
printf("\nFibonnaci Series is as follows\n");
while(i<n)
{
printf("%d",fibonnaci(i));
i++
}
return 0;
}
