#include <iostream>
using namespace std;
int main() {
    int x,y;
    char choice;
    cout<<"Please enter the first number : ";
    cin>>x;
      cout<<"--------------------------------------------------------------------"<<endl;
    cout<<"Please enter the second number : ";
    cin>>y;
      cout<<"--------------------------------------------------------------------"<<endl;
    cout<<"Please enter the operation you want to perform "<<endl<<"+ , - , * , / : ";
    cin>>choice;
      cout<<"--------------------------------------------------------------------"<<endl;
    switch(choice){
       { case '+':
        cout<<"Addition of "<<x<<" and "<<y<<" is : "<<x+y;
        break;
       }
        { case '-':
        cout<<"Substraction of "<<x<<" and "<<y<<" is : "<<x-y;
        break;
       }
        { case '*':
        cout<<"Multiplication of "<<x<<" and "<<y<<" is : "<<x*y;
        break;
       }
        { case '/':
        cout<<"Division of "<<x<<" and "<<y<<" is : "<<x/y;
        break;
       }
       default : cout<<"Invalid operaton";
    } 
    return 0;
}
