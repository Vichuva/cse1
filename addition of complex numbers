//complex number addition
#include <iostream>

using namespace std;

class Complex{
    int real, imag;
    public:
    Complex(int real=0, int imag=0){
        this->real = real;
        this->imag = imag;
    }
    Complex operator+(Complex const& obj){
        Complex res;
        res.real = real + obj.real;
        res.imag = imag + obj.imag;
        return res;
    }
    void print(){
        cout<<real<<'\t'<<imag<<endl;
    }
};

int main()
{
    Complex c1(8,1);
    Complex c2(4,2);
    Complex c3 = c1+c2;
    c3.print();

    return 0;
}
