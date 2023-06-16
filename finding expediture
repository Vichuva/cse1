//gross pay problem
#include <stdio.h>

int amount(int pay,float hra){
    int c = pay * hra;
    int amt = pay +c;
    printf("%d\n",amt);
    return amt;
}

int finale(int py){
    float x;
    if(py<750){
        x = 0.08;
    }
    else if(py>=1000){
        x = 0.09;
    }
    int ca = py * x;
    int at = py +ca;
    printf("%d",at);
    return at;
}

int main(){
    int gp;
    float x;
    printf("enter the gross pay: ");
    scanf("%d",&gp);
    if(gp<750){
        x = 0.03;
        amount(gp,x);
        finale(gp);
    }
    else if(gp>=1000){
        x = 0.04;
        amount(gp,x);
        finale(gp);
    }
    return 0;
}
