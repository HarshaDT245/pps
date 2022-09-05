# pps
//Time taken to complete a work by two people
#include<stdio.h>
void main()
{
float A,B,t,T;
printf("Enter the time taken by person A\n"); 
scanf("%f",&A);
printf("Enter the time taken by person B\n");
scanf("%f",&B);
t=1/(A)+1/(B);
printf("t= %f\n",t);
T=1/(t)*60;
printf("The total time taken to complete the work: %f  minutes\n",T);
}
