# Experiment-3
## Aim -
To study and implement operators in c++
## Theory -
Operators are essential symbols used to perform various operations on variables and values in programming. They are fundamental for calculations, assignments, decision-making, logical computations, and comparisons. Here’s a breakdown of the key types of operators and their uses:

### Arithmetic Operators :
Arithmetic operators are essential tools in programming and mathematics for performing basic calculations. They include addition, subtraction, multiplication, division, modulus (remainder), exponentiation (powers), and floor division (rounding down). These operators enable efficient manipulation of numerical data for various computational tasks.

+: Addition (e.g., a + b)
-: Subtraction (e.g., a - b)
*: Multiplication (e.g., a * b)
/: Division (e.g., a / b)
%: Modulus (remainder, e.g., a % b)

### Assignment Operators :
Assignment operators assign values to variables in programming. The basic operator is =, while compound operators like +=, -=, *=, and /= combine an operation with assignment, simplifying code by updating variables in a single step. These operators are essential for efficient data manipulation.

=: Assigns value (e.g., x = 5)

+=: Adds and assigns (e.g., x += 5)

-=: Subtracts and assigns (e.g., x -= 5)

*=: Multiplies and assigns (e.g., x *= 5)

/=: Divides and assigns (e.g., x /= 5)

%=: Modulus and assigns (e.g., x %= 5)

### Logical Operators :
Logical operators in programming, such as *AND* (&&), *OR* (||), and *NOT* (!), are used to perform operations on Boolean values. *AND* returns true if both conditions are true, *OR* returns true if at least one condition is true, and *NOT* inverts the Boolean value. These operators are essential for controlling the flow of a program by evaluating multiple conditions.

&&: AND (true if both are true, e.g., a > 5 && b < 10)

||: OR (true if at least one is true, e.g., a > 5 || b < 10)

!: NOT (inverts boolean value, e.g., !(a > 5))

^: XOR (true if exactly one is true)

### Comparison Operators :
Comparison operators compare two values in programming and return true or false. Key operators include ==, !=, >, <, >=, and <=. They are crucial for decision-making in code, enabling condition evaluation and control of program flow.

==: Equal to (e.g., a == b)

!=: Not equal to (e.g., a != b)

> : Greater than (e.g., a > b)

<: Less than (e.g., a < b)

> =: Greater than or equal to (e.g., a >= b)

<=: Less than or equal to (e.g., a <= b)

These operators are used to perform basic calculations, make decisions, and compare values in programming.
## Code-
### 1.Arithmetic operators
```
//Soham
//23070123084
//entc b1
//experiment 3
#include<iostream>
using namespace std;
int main()
{
    //arithmetic operators
    int a,b;
    int sum,subtraction,multiplication,division;
    cout<<"Enter the number-";
    cin>>a>>b;
    sum=a+b;
    subtraction=a-b;
    multiplication=a*b;
    division=a/b;
    cout<<"sum="<<sum<< endl;
    cout<<"subtraction="<<subtraction<< endl;
    cout<<"multiplication="<<multiplication<< endl;
    cout<<"division="<<division<< endl;
    return 0;
}
```
### 2.Assignment operators
```
//Soham
//23070123084
//entc b1
//experiment 3
#include<iostream>
using namespace std;
int main()
{
    //assignment operators
    int a,b,c,d;
    cout<<"Enter the value of a,b,c,d";
    cin>>a>>b>>c>>d;
    a-=3;
    b*=3;
    c/=3;
    d&=3;
    cout<<"a="<<a<<endl;
    cout<<"b="<<b<<endl;
    cout<<"c=<<"<<c<<endl;
    cout<<"d="<<d<<endl;
    return 0;
}
```
### 3.Logical operators
```
//Soham
//23070123084
//entc b1
//experiment 3C
#include<iostream>
using namespace std;
int main()
{
    //logical operators
     int a,b,c,d,e;
    cout<<"Enter the first number:";
    cin>>a;
    cout<<"Enter the second number:";
    cin>>b;
    cout<<"\n" << (a > 1 && b < 10)<<endl;
    cout<<"\n" << (a > 1 || b < 10)<<endl;
    cout <<"\n"<<(!(a >1 && b <10))<<endl;
    return 0;
}
```
### 4.Comparison operators
```
//Soham
//23070123084
//entc b1
//experiment 3B
#include<iostream>
using namespace std;
int main()
{
    //comparison operators
    int a,b;
    cout<<"Enter the values of a,b";
    cin>>a>>b;
    if(a==b)
    {
        cout<<"a==b"<<endl;
    }
   else if(a!=b)
    {
        cout<<"a!=b"<<endl;
    }
    if(a>b)
    {
        cout<<"a>b"<<endl;
    }
   else if(a<b)
    {
        cout<<"a<b"<<endl;
    }
    return 0;
}
```
## Explanation -
Arithmetic Operators: Demonstrate basic mathematical operations such as addition, subtraction, multiplication, division, and modulus.
Assignment Operators: Show how to assign values to variables using =, +=, -=, *=, /=, and %=.
logical operators: show how to perform logical computations && AND, || OR, ! NOT, exclusive OR.
Comparison Operators: Illustrate how to compare values using ==, !=, <, >, <=, and >=.
## Output -
### 1.Arithmetic Operators ![image](https://github.com/user-attachments/assets/e72567c9-9888-44b0-8e7f-ca46983f8067)
### 2.Assignment Operators ![image](https://github.com/user-attachments/assets/493058f1-412d-4fe6-b162-52ab33021b98)
### 3.Logical Operators ![image](https://github.com/user-attachments/assets/92151680-00f1-4bff-be95-6efc0e849ae7)
### 4.Comparison Operators ![image](https://github.com/user-attachments/assets/cc4fab20-a209-4872-b012-f8a1c45a44a2)
## Conclusion-
These programs provide a clear understanding of how to use various operators in C++. Mastery of operators is essential for performing mathematical calculations, making decisions, assigning values,comparing values and controlling the flow of a program.
