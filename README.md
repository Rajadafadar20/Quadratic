# Quadratic
// check roots of a quadratic equation
// is it real or imaginary
#include<stdio.h>
#include<math.h>

int main(){
    int a,b,c;
    float D;
    printf("enter the equation's a,b and c");
    printf("\n where a= coefficient of x^2\n b = coefficient of x\n c =coefficient of 1\n");
    printf("a=");
    scanf("%d",&a);
    printf("b=");
    scanf("%d",&b);
    printf("c=");
    scanf("%d",&c);
    D = pow(b,2)- 4*a*c;
    if(D<0){
        printf("roots are imaginary");
    }
    else
    if(D>0){
        printf("roots are real");
    }
    else{
        printf("roots are real and equal");
    }
    return 0;
}
