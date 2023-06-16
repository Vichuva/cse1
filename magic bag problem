#include<iostream>
#include<string.h>
using namespace std;


class magic{
public:
string object;

void push(int bg){
    int input;
    cin>>input;
    bg+=input;
}

void push(float bg){
    float input;
    cin>>input;
    bg+=input;
}

void push(){
    char input[25];
    cin>>input;
    object=input;
    
}
};


int main(){
    int size;
    magic obj;
    int bag=0;
    char bags[100];
    cin>>size;
    for(int i = 0;i<size+1;i++){
        if(i<size){
            obj.push(bag); 
            obj.push();
        }
        else{
            cout<<"Bag is full";
        }
        
    }
    return 0;
}
