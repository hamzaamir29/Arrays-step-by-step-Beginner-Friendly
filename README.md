🧠 What is an Array?

👉 One-line definition:
An array is a collection of variables of the same type stored together under one name.

🔎 Real-Life Example: Egg Tray

Tray name = Array name

Each egg slot = Array element

Slot numbers (0, 1, 2, …) = Indexes

Instead of creating 10 different variables like:

int num1, num2, num3, num4, num5, ...;


We can simply write:

int num[10]; // one array to hold 10 integers

📝 Declaring an Array
type arrayName[size];


Example:

int marks[5]; // array to store 5 integers

📥 Initializing an Array

Manual initialization

int marks[5] = {50, 60, 70, 80, 90};


Partial initialization

int marks[5] = {50, 60}; // rest become 0


Without size (compiler counts automatically)

int marks[] = {10, 20, 30, 40};

📌 Accessing Array Elements

Each element has a position number (index).

In C, the index starts at 0.

Example:

int marks[3] = {10, 20, 30};
printf("%d", marks[0]); // prints 10
printf("%d", marks[2]); // prints 30

🧪 Program 1 – Print 5 Numbers (Static Array)
#include <stdio.h>
int main() {
    int numbers[5] = {2, 4, 6, 8, 10};
    printf("First number = %d\n", numbers[0]);
    printf("Second number = %d\n", numbers[1]);
    printf("Fifth number = %d\n", numbers[4]);
    return 0;
}

🔍 Explanation

numbers[0] → 2

numbers[1] → 4

numbers[4] → 10

✨ This makes your book readable, structured, and professional — like real class notes that can later be published.

Do you want me to continue Class 8 with more programs on arrays (like input from user, sum of array, finding largest number, etc.) so your book section looks complete?

You said:
also create this post on linkedin post
ChatGPT said:

Perfect ✅ I’ll turn your Class 8 (Arrays in C) lesson into a LinkedIn-ready post — professional, easy to read, and engaging (just like your earlier class summaries).

Here’s the draft:

Cyber Security | C Programming | Class 8 – Arrays (Step-by-Step & Beginner-Friendly)
Guided by Instructor Hafizullah Khokhar at Aptech Pakistan

In today’s class, I learned about one of the most important concepts in programming – Arrays.

🔹 What is an Array?
An array is a collection of variables of the same type stored together under one name.

💡 Real-life example: Think of an egg tray →

Tray = array name

Egg slots = elements

Slot numbers = indexes (0,1,2,3...)

📚 Key Takeaways

✔ Declaring an array → int marks[5];
✔ Initializing arrays → full, partial, or without size
✔ Accessing elements using index → marks[0], marks[2]
✔ Using loops with arrays to process data

🧪 Sample Program – Print 5 Numbers
#include <stdio.h>
int main() {
    int numbers[5] = {2, 4, 6, 8, 10};
    printf("First number = %d\n", numbers[0]);
    printf("Second number = %d\n", numbers[1]);
    printf("Fifth number = %d\n", numbers[4]);
    return 0;
}


📌 Output Explanation:

numbers[0] → 2

numbers[1] → 4

numbers[4] → 10

✨ This session helped me understand how arrays make coding simpler and more efficient, instead of using multiple variables. 
#CProgramming #Arrays #CyberSecurity #Aptech #CodingJourney #GitHub.
