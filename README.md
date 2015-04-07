# Fixthisyuk\

#include <iostream>
using namespace std;



int main(){

    int number;
    cout<<"Here is a lost of 100 integers and FizzBuzz\n\n";
        for (number = 1; number < 101;number++){
              //cout<<number<<" ";
              if (number % 10 == 0) cout<<"\n";
              if (number % 3 == 0){
                  cout<<"Fizz";
              } else {cout<<number<<" "; }
              if (number % 5 == 0){
                  cout<<"Buzz ";
              }
              if ((number % 3 ==0)&&(number % 5 == 0)){
                cout<<"FizzBuzz";
              }
          }
          {sprintf(buffer, "%f",number);
}
return 0;
  }
