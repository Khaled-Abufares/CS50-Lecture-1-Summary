CS50 Lecture 1: Introduction to C

---

 What is C?

C is a fast and powerful programming language.

It’s close to how computers really work.

Learning C helps you understand memory, logic, and performance.

---

 Basic Program Structure

#include <stdio.h>

int main(void)
{
printf("Hello, world!\n");
return 0;
}

Explanation

#include <stdio.h> → lets you use printf

main(void) → where the program starts

printf(...) → prints text to the screen

return 0; → means the program ended successfully

---

 Data Types

int → whole numbers like int age = 18;

float → decimal numbers like float pi = 3.14;

double → more precise decimal numbers

char → a single letter like 'A'

bool → true or false (requires #include <stdbool.h>)

---

 Math Operators

Symbol	Use

- Addition
- Subtraction
- Multiplication
/	Division
%	Remainder

---

 Loops

for loop

for (int i = 0; i < 5; i++)
{

printf("%i\n", i);

}

while loop


int j = 0;

while (j < 5)

{

printf("%i\n", j);

j++;

}

do-while loop


int k = 0;

do

{

printf("%i\n", k);

k++;

}

while (k < 5);

---

 Conditions

if (x > 0)

{

printf("Positive\n");

}

else if (x < 0)

{

printf("Negative\n");

}

else

{

printf("Zero\n");

}

---

 Arrays

int numbers[3] = {10, 20, 30};

printf("%i\n", numbers[1]); // 

prints 20

---

 Functions

int add(int a, int b)
{
return a + b;
}

int result = add(3, 5); // result = 8

---

 Input with CS50 Library

#include <cs50.h>

string name = get_string("What’s your name? ");

int age = get_int("How old are you? ");


Note: cs50.h simplifies input for 
beginners in this course.

---

 Important Concepts

Concept	Meaning

Algorithm	A clear set of steps to solve a problem
Efficiency	Using time and memory wisely
Abstraction	Hiding complexity through simple tools

---

 Learning Tips

Don’t memorize — understand what each part does

Break your code and try fixing it — great way to learn

Build small projects to apply concepts

Add comments to explain your code

Be patient and consistent

---