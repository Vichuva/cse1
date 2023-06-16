#include <iostream>
using namespace std;

class base{
    public:
    int s;
    int l,b;
    int r;
    //int a,b;
};

class polygons: public base{
    public:
    int a,b;
    int ar;
    int area(){
        ar = a*b;
        return ar;
    }
};

class square: public polygons{
    public:
    
    square(int s){
        a=s;
        b=s;
    }
    
};

class circle: public base{
    public:
    double ar;
    circle(int r){
        this->r=r;
    }
    void area(){
        ar = 3.14 * r * r;
        cout<<ar<<endl;
    }
};

class rectangle: public polygons{
    public:
    
    rectangle(int l,int b){
        a = l;
        this->b = b;
    }
    
};

class paralellogram: public polygons{
    public:
    paralellogram(int b,int h){
        this->a=b;
        this->b=h;
    }
};




int main()
{
    square side(2);
    side.area();
    cout<<side.ar<<endl;
    
    rectangle par(2,3);
    par.area();
    cout<<par.ar<<endl;
    
    paralellogram pars(3,4);
    pars.area();
    cout<<pars.ar<<endl;
    

    return 0;
}
