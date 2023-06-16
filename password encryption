//password encrypter
#include<stdio.h>
#include<string.h>

int main(){
    int n;
    char pwd[130];
    printf("enter the number of passwords: \n");
    scanf("%d",&n);
    
    for(int i=0;i<n+1;i++){
        gets(pwd);
        //printf("%s",pwd);
        int L;
        L= strlen(pwd);
        if(L%2==0){
            if(pwd[0]==pwd[L]){
                pwd[L-1]='-';
            }
            else if(pwd[0]<pwd[L]){
                pwd[L-1]='+';
            }
            else{
                pwd[L]='$';
            }
            for(int j=0;j<L;j++){
                if(j%2!=0){
                    pwd[j]='*';
                }
            }
            printf("%s",pwd);
        }
        else{
            int m = L/2;
            if(pwd[m]>pwd[L-1]){
                char temp;
                temp = pwd[m-1];
                pwd[m-1]=pwd[L-1];
                pwd[L-1]=temp;
            }
            else if(pwd[m]<pwd[L-1]){
                char temp;
                temp = pwd[m+1];
                pwd[m+1]=pwd[0];
                pwd[0]=temp;
            }
            else if(pwd[m]==pwd[L-1]){
                for(int k=0;k<L;k++){
                    if(k%2==0){
                        pwd[k]='=';
                    }
                }
            }
            printf("%s",pwd);
        }
        
    }
    return 0;
}
