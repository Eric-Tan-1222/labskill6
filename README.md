# labskill6
//LABSKILL5&6
#include<iostream>
#include<conio.h>
#include <iomanip>
using namespace std;
int main (){
    double fahrenheit_1,celsius_1=40,fahrenheit_2=120,celsius_2;

    cout<<"Celsius \tFahrenheit \t| \tFahrenheit \tCelsius\n";

 do
    {

         celsius_2= (fahrenheit_2-32)*5/9;
        fahrenheit_1= (9.0 / 5) * celsius_1+ 32;


        cout<<fixed<<setprecision(1);
        cout<<celsius_1<<"\t\t"<<fahrenheit_1<<"\t\t|\t"<<fahrenheit_2<<"\t\t"<<celsius_2<<"\t\n";
        celsius_1--;
        fahrenheit_2-=10;
    }
     while(celsius_1>=31&&fahrenheit_2>=30);

}
