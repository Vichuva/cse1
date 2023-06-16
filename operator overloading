#include <iostream>

using namespace std;

class ops{
    int a;
    public:
    ops(int a = 0){
        this-> a = a;
    }
    ops operator+(ops obj){
        ops res;
        res.a = a - obj.a;
        return res;
    }
    ops operator++(){
        ++a;
        return a;
    }
    ops operator++(int){
        a++;
        return a;
    }
    ops operator-(ops obj1){
        ops res;
        res.a = a+obj1.a;
        return res;
    }
    void print(){
        cout<<a<<endl;
    }
};

int main(){
    ops c1(3);
    ops c2(4);
    ops c3 = c1+c2;
    ++c1;
    c2++;
    c1.print();
    c2.print();
    c3.print();
    ops c4= c1-c2;
    c4.print();
    return 0;
}
