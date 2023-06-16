//qn: function to find the power of any given real number
#include <stdio.h>

void power(float x, int n){
    float pwr = 1;
    if(n>0){
        for(int i=0;i<n;i++){
            pwr*=x;
        }
        printf("%f",pwr);
    }
    else{
        n=n*(-1);
        for(int i=0;i<n;i++){
            float pwer = 1;
            pwer*=x;
            pwr=1/pwer;
        }
        printf("%f",pwr);
    }
}


int main() {
    float a;
    int n;
    printf("enter the number\n");
    scanf("%f",&a);
    printf("enter the power\n");
    scanf("%d",&n);
    power(a,n);
    return 0;
}
