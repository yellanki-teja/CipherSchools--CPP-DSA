#include <iostream>
using namespace std;

void PrintHi(){
    cout<<"Hi"<<endl;
    return;
}
int sum(int a,int b){
    int c;
    c=a+b;
    return c;
}
// int swap(int a,int b)     
int swap(int &a,int &b){     // include & befor a and b to change actual parameters 
    
    cout<<"Before swap: "<<a<<" "<<b<<endl;
    int temp;
    temp=a;
    a=b;
    b=temp;
    cout<<"After swap inside the function: "<<a<<" "<<b<<endl;
    
    return 0;
}
void fun(int &a, int b){    // passing by reference "&"
    a=99999;
    b=99999;
    cout<<"The values of a and b inside the fun function is: "<<a<<" "<<b<<endl;
}
int main() {
    PrintHi();
    
    int a,b;
    a=3;
    b=5;
    cout<<"The values of a and b outside before the fun function is: "<<a<<" "<<b<<endl;
    // int d;
    // d= sum(a,b);
    // cout<<"The sum is equal to "<<d<<endl;
    
    // int e = swap(a,b);
    // cout<<"After swap outside the function: "<<a<<" "<<b<<endl;
    fun(a,b);
    cout<<"The values of a and b outside after the fun function is: "<<a<<" "<<b<<endl;
    
    return 0;
    
}
