#include <stdio.h>

struct bank{
    int accnum;
    int pin;
    int balance;
};

int main()
{
    bank temp;
    bank bank1 = calloc(sizeof(temp),4);
    
    for(int i=0;i<4;i++){
        bank1[i].accnum = i+1;
        bank1[i].pin = i+4;
        bank1[i].balance = i+25000;
    }
    
    int pin1, accountnum,wdraw;
    scanf("%d",&pin1);
    scanf("%d",&accountnum);
    
    for(int i=0;i<4;i++){
        if(accountnum == bank1[i].accnum){
            printf("%d",bank1[i].accnum);
            printf("%d",bank1[i].balance);
            if(pin1 == bank1[i].pin){
                printf("pin verification successful");
                printf("enter the amount to withdraw");
                scanf("%d",&wdraw);
                if(wdraw<bank1[i].balance){
                    bank1[i].balance-=wdraw;
                    printf("cash successfully withdraw");
                }
                else{
                    printf("amount exceeded balance");
                }
            }
            
        }
        
    }
    
    
    
    

    return 0;
}
