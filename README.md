#include<stdio.h>
#include<conio.h> 
int main()
{

   int a,b,c,larg;
   printf("Enter two numbers :\n");
   scanf("%d %d",&a,&b);
   larg a>b?a:b;
   printf("largest number of the two numbers is : %d\n",larg);
   printf("Enter the third number :\n");
   scanf("%d",&c);
   larg = larg c?larg:c;
   printf("largest number of the three numbers is: %d\n",larg);
   return 0;

}
