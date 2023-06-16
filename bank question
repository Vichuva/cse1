#include <iostream>
 
using namespace std;
 
class BankAccount{
	int balanceamt;
	public:
	void deposit();
	void withdraw();
	void balance();
};
 
void BankAccount::withdraw(){
	int amtw;
    cout<<"Enter amount to withdraw:";
    cin>>amtw;
    balanceamt=balanceamt-amtw;
    cout<<"Balnce amount after withdrawl:"<<balanceamt<<endl;
}
 
void BankAccount::balance(){
    cout<<"Balnce amount in account is:"<<balanceamt<<endl;
}
 
void BankAccount::deposit(){
	int amt;
    cout<<"Enter amount to be deposited:";
    cin>>amt;
	balanceamt=balanceamt+amt;
    cout<<"Blance amount after deposition:"<<balanceamt<<endl;
}
	
int main()
{
    int n;
	BankAccount bank;
	while(n!=4){
        cout<<"1-DEPOSIT**2-WITHDRAW**3-CHECK BALANCE"<<endl;
    	
        cin>>n;
    	if(n==1){
        	
            bank.deposit();
    	}
    	else if(n==2){
        	
            bank.withdraw();
    	}
    	else if(n==3){
            bank.balance();
    	}
    	else{
            printf("not in options");
    	}
	}
	
	return 0;
}
