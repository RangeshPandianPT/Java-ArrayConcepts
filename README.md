🧠 Java Arrays: Concept & Usage
Welcome to the Java Arrays mini-concept guide! This repository provides a simple and beginner-friendly explanation of arrays in Java — one of the most fundamental data structures used for storing multiple values of the same type.

📚 What is an Array?
An array in Java is a container object that holds a fixed number of elements of a single type. Once created, its size is fixed and cannot be changed.

🚀 Key Points
Arrays are zero-indexed: the first element is at index 0.
You must specify the type and size at creation.
Java arrays are objects, so they are stored in the heap memory.
The default values for arrays depend on the data type: e.g., 0 for int, null for objects, false for boolean.

🔍 Types of Arrays
One-Dimensional Arrays: Basic arrays like int[] arr.
Multi-Dimensional Arrays: Arrays of arrays (e.g., 2D arrays like int[][] matrix).

⚠️ ArrayIndexOutOfBoundsException
Trying to access an index outside the bounds of the array will throw this runtime exception.
java
Copy
Edit
int[] arr = new int[3];
System.out.println(arr[5]); // Error!

📦 Applications of Arrays
Storing collections of data (scores, names, etc.)
Foundations for advanced structures (lists, matrices, etc.)
Used in sorting, searching, and algorithm design

📌 Conclusion
Arrays are essential for efficient data handling in Java. Understanding them is a foundational step toward mastering Java programming and data structures.
