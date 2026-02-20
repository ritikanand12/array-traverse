Array Traversal in C

This project demonstrates how to input and traverse an array in C programming language.

The program takes user input for array elements and then prints (traverses) the array using a loop.

📌 Description

In this program:

The user enters the number of elements.

The user inputs array elements.

The program traverses the array using a for loop.

All elements are printed in the same order they were entered.

This is a basic example to understand array traversal in C.

🧠 What is Array Traversal?

Array Traversal means visiting each element of an array one by one to:

Display elements

Modify elements

Perform operations like sum, search, etc.

Traversal is usually done using a loop:

for(i = 0; i < n; i++)
📂 Program Flow

Declare an array of size 100.

Input number of elements (n).

Read n elements into the array.

Print all elements using a loop.

▶️ Sample Input
Enter number of elements: 5
Enter 5 elements:
10
20
30
40
50
▶️ Sample Output
Array elements are:
10 20 30 40 50
⚙️ How to Compile and Run
1️⃣ Compile the program
gcc array_traversal.c -o array_traversal
2️⃣ Run the program
./array_traversal
⏱️ Time & Space Complexity

Time Complexity: O(n)
(Each element is visited once)

Space Complexity: O(n)
(Array storage)

Where:

n = Number of elements

📚 Concepts Covered

Arrays in C

User Input using scanf()

Looping (for loop)

Array Traversal

⚠️ Limitations

Maximum array size is fixed at 100.

No validation for invalid input.

👨‍💻 Author

Ritik Chauhan

If you want, I can also provide:

Menu-driven array operations program

Array operations like search, insert, delete

Version with input validation
