#include <stdio.h>


float arithmetic(float a, float b);
int operation(int c);

int main() {
    float a, b, x;
    a=1;
    b= 1;
    x = a+b;
    printf("%f plus %f is %f\n", a,b, x);
    float arithmetic(float a, float b);

    int operation;
    operation = x;
    
switch(operation){
    case 0:
        x = a+b;
        break;
    case 1:
        x = a-b;
        break;
    case 2:
        x = a*b;
        break;
    case 3:
        x = a/b;
        break;
    default:
    printf("Illegal operation %ld", x);
    break;
    return x;
}
  printf("%f",x);
}
