//qn: find the reverse of the input number
#include <stdio.h>

void reversenum(int n){
    int count;
    int a;
    a=n;
    while(a!=0){
        a=a/10;
        count+=1;
    }
    int arr[count];
    for(int i=0;i<count;i++){
        int c=n%10;
        arr[i]=c;
        n=n/10;
    }
    for(int i=0;i<count;i++){
        printf("%d",arr[i]);
    }
}


int main() {
    int a;
    scanf("%d",&a);
    reversenum(a);
    return 0;
}
