# function1
#include <iostream>
using namespace std;
 
 void printSquareandCube(double x){
    double sq=x*x;
    double cube=x*x*x;
    cout<<x<<endl;
    cout<< "kub"<<cube<<endl;
    cout<< "kvadrat"<<sq<<endl;
 }
 int main(){
     double n;
     cout<<"eded daxil edin";
     cin>>n;
     printSquareandCube(n);
    return 0;
}
