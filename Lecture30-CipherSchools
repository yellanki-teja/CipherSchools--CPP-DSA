#include <iostream>
using namespace std;

class Complex
{
    private:
    float real;
    float img;
    
    public:
    
    Complex(int real_value, int img_value){
        real = real_value;
        img = img_value;
    }
    void set_parameters(int real,int img){
        this->real = real;
        this->img=img;
    }
    void distancefromOrigin(){
        float dist;
        dist = real*real + img*img;
        cout<<"The distance from the Origin is "<<dist<<endl;
    
        return;
    }
    
};

class New_account{
    public:
    int amount;
    int days;
    
    // constructor has no return type, we don't need to write anything at the start like int
    
    New_account(int amount_initial, int days_initial){
        amount = amount_initial;
        days = days_initial;
        
        cout<<"The constructor is called now "<<endl;
        
        // No need to return anything in constructor
    }
    
    void print_account_details(){
        cout<<"The amount is "<<amount<<endl;
        cout<<"The days are "<<days<<endl;
    }
    
    ~New_account(){
        cout<<"Now the use of the object is complete and the object is getting destroyed"<<endl;
    }
};

class motorbike{
    public:
    int num_wheels;
    int lights;
};
int main(){
    // Now I will try to do this while the object is being created itself
    New_account a(0,0);
    a.print_account_details();
    New_account b(100,5);
    b.print_account_details();
    cout<<"Here all the function and calculations take place "<<endl;
    Complex(3,3);
    
    
    
    // a.initial();
    // This function needs to be called everytime the object is created to set the parameters
    
    // Complex a,b;
    
    // a.set_parameters(3,4);
    // a.distancefromOrigin();
   return 0;
}
