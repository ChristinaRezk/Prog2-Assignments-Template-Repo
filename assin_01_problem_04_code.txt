//christina rezk nady
//20216594
//p2
#include <iostream>
using namespace std;

int main()
{
  float a,b,c; 
 
  cin>> a >> b >> c  ;
 if(a>b && a>c && b>c) {cout<<c <<"\n" << b <<"\n" << a <<"\n";}
  else if(a>b && a>c && b<c) {cout<<b <<"\n" << c <<"\n" << a <<"\n";}
  else if(a<b && a>c && b>c) {cout<<c <<"\n" << a <<"\n" << b <<"\n";}
  else if(a<b && a<c && b>c) {cout<<a <<"\n" << c <<"\n" << b <<"\n";}
  else if(a>b && a<c && b<c) {cout<<b <<"\n" << a <<"\n" << c <<"\n";}
  else if(a<b && a<c && b<c) {cout<<a <<"\n" << b <<"\n"
  << c <<"\n";}
  

 cout<<a <<"\n" << b <<"\n" << c;
    return 0;
}
