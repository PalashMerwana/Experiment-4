# Experiment 4
# Aim
To study and implement C++ Bitwise Operators

# software used
VS code

# Theory
Bitwise Operators are the operators that are used to perform operations on the bit level on the integers. While performing this operation integers are considered as sequences of binary digits. In C++, we have various types of Bitwise Operators.

Bitwise AND (&) Bitwise OR (|) Bitwise XOR (^) Bitwise NOT (~) Left Shift (<<) Right Shift (>>)

# code 
~~~
#include<iostream>
using namespace std;

int main()
{
    int a,b;
    cout<<"enter the value of a ";
    cin>>a; 
    
    cout<<"enter the value of b: ";
    cin>>b; 

    cout<< "the bitwise AND is: "<<(a&b)<<endl;
    cout<< "the bitwise OR is: "<<(a|b)<<endl;
    cout<< "the bitwise XOR is: "<<(a^b)<<endl;
    cout<< "the bitwise NOT is: "<< (a-b)<<endl;
    cout<< "the bitwise LEFT SHIFT is: "<<(a<<b)<<endl;
    cout<< "the bitwise RIGHT SHIFT is: "<< (a>>b)<<endl;

    return 0; 
}
~~~
output: 
![image](https://github.com/user-attachments/assets/1cd3fef2-a916-4656-a1ab-d2b62d10e885)
