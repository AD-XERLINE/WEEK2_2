# WEEK2_2
โปรแกรมรายสัปดาห์ที่ 2 อันที่ 2

#include <stdio.h>
#include<math.h>
     
     int main() {  
     double a;
     double b;
     double c;
     //A3 Heron 's Fomula
   
     printf("Enter sides of a triangle (such as :3 4 5) : ");
     scanf("%lf %lf %lf", &a ,&b ,&c);
	 double s = (a+b+c)/2;
	 double A = s*(s-a)*(s-b)*(s-c) ;
	 printf("%lf",sqrt(A));
}
