# BTech_G2D_deewakarsahani_7
C programs
#include <stdio.h> 
int main() {
float s1, s2, s3, s4, s5, sum, percentage; 
printf("Enter marks of 5 subjects: ");
scanf("%f %f %f %f %f", &s1, &s2, &s3, &s4, &s5); 
sum = s1 + s2 + s3 + s4 + s5;
percentage = (sum / 500) * 100; 
printf("Sum: %.2f\n", sum);
printf("Percentage: %.2f%%\n", percentage); 
return 0;
}

