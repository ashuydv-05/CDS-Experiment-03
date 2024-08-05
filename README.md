# CDS-Experiment-03
## AIM :- to study and implement operators in cpp

## Theory :-
Operators are symbols in C++ that manipulate variables and values. Boolean expressions are evaluated by logical operators ({&&}, {||}, {!}) which return true or false. In addition to producing boolean results, relational operators ({=={, {!=}, {{, {>}, {=}, {>=}) compare two values. Basic mathematical operations are carried out using arithmetic operators ({+}, {-}, {*}, {/}, {%}). For conditional statements to maintain control flow, logical operators are essential. In decision-making structures, comparison of values requires the use of relational operators. The foundation of computations are arithmetic operators. Combining these operators allows for the creation of sophisticated expressions and control structures, which makes C++ an effective language for a wide range of programming jobs, from simple arithmetic computations to complex logical comparisons and conditions.

## Code :-
```
#include #include // For pow function using namespace std;

int main() { int a = 10, b = 5; bool x = true, y = false; int p = 15, q = 20;

// Arithmetic Operators
cout << "Arithmetic Operators:\n";
cout << "Addition: " << a + b << "\n";
cout << "Subtraction: " << a - b << "\n";
cout << "Multiplication: " << a * b << "\n";
cout << "Division: " << a / b << "\n";
cout << "Modulus: " << a % b << "\n";
cout << "Exponentiation: " << pow(a, b) << "\n";
cout << "Floor Division: " << a / b << "\n\n";

// Logical Operators
cout << "Logical Operators:\n";
cout << (x && y) << "\n";
cout << (x || y) << "\n";
cout << (!x) << "\n";
cout << (!y) << "\n\n";

// Relational Operators
cout << "Relational Operators:\n";
cout << (p == q) << "\n";
cout << (p != q) << "\n";
cout << (p > q) << "\n";
cout << (p < q) << "\n";
cout << (p >= q) << "\n";
cout << (p <= q) << "\n";

return 0;
}
```

## Output:-
1[exp3](https://github.com/ashuydv-05/CDS-Experiment-03/blob/main/Screenshot%202024-07-30%20160855.png)

## Conclusion :-
The experiment covered various operators in C++, including arithmetic, relational, logical, bitwise, assignment, increment/decrement, and the conditional operator. Understanding and correctly implementing these operators is essential for performing different types of operations and controlling the flow of a C++ program. This experiment provided practical knowledge of how these operators work and their applications in a program.
