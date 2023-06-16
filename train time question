#include <iostream>
using namespace std;
int time(int x, int y, int z,int h=10,int m=20,int s=10)
{
    int a,b,c;
    a=x+h;
    b=y+m;
    c=z+s;
    if (a>24)
    {
        a-=24;
    }
    if (b>60)
    {
        b-=60;
        a+=1;
    }
    if (c>60)
    {
        c-=60;
        b+=1;
        if (b>60)
        {
            b-=60;
            a+=1;
        }
    }
    cout<<a<<":"<<b<<":"<<c;
}
int main()
{
  int p,q,r;
  cin>>p>>q>>r;
  time(p,q,r);
  return 0;
}
