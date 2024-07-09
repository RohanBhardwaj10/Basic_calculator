# Basic_calculator
#include<iostream>
using namespace std;
int main(){
    int a,b;
    cout<<"enter the value of a :";
    cin>>a;
    cout<<"enter the value of b :";
    cin>>b;
    char o;
    cout<< "enter the operator to perform operation :";
    cin>>o;

    switch(o){
        case '+': cout<<'Addition';
        cout<< a+b; 
        break;

        case '-': cout<<'Subtraction:';
        cout<< a-b; 
        break;

        case '/': cout<<'Division :';
        cout<< a/b;break;
        
        case '*': cout<<'Multiplication :';
        cout<< a*b;break;

        case '%': cout<<'Modulus';
        cout<< a%b; break;

        default : cout<< 'Invalid operator'; 
    }return 0;
}
