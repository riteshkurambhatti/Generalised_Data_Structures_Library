# 🏗️ Generalised Data Structures Library

A **C++ generic library** that provides **object-oriented implementations** of essential **linear** and **non-linear data structures**, along with commonly used **searching and sorting algorithms**.  
Designed with **templates** for type independence and modular, reusable components.

---

## 🚀 Features

### 📂 Linear Data Structures
- **Singly Linear Linked List**
- **Singly Circular Linked List**
- **Doubly Linear Linked List**
- **Doubly Circular Linked List**
- **Stack (LIFO)**
- **Queue (FIFO)**

### 🌳 Non-Linear Data Structures
- **Binary Search Tree (BST)**  
  Supports insertion, deletion, and traversal operations.

### 🔎 Algorithms
- **Searching**: Linear Search, Binary Search, etc.
- **Sorting**: Bubble Sort, Selection Sort, Insertion Sort, and more.

### ⚙️ Utility Functions
- Palindrome detection
- Addition of even and odd elements
- Reverse number
- Maximum/Minimum/Second Maximum
- Prime and Perfect number identification
- Digit-based operations (sum, product, smallest/largest digit)
- And many other helper functions for practice and real-world usage.

---

## 🛠️ Technology Stack
- **Language**: C++  
- **Paradigm**: Object-Oriented Programming (OOP)  
- **Key Concept**: Generic Programming using **C++ Templates**  

The same implementation works for integers, floats, strings, or custom objects.

---

## 📂 Project Structure
```
Generalized_Data_Structure_Library.cpp   # Core template-based implementations
README.md                                # Project documentation
```

---

## 🧩 Learning Outcomes
- Strong understanding of **linear & non-linear data structures**.
- Mastery of **C++ OOP** and **template programming**.
- Hands-on practice in building **reusable libraries**.
- Practical knowledge of **searching & sorting algorithms**.

---

## ⚡ Getting Started

1. **Clone the repository**  
   ```bash
   git clone https://github.com/<your-username>/data-structures-library.git
   cd data-structures-library
   ```

2. **Compile the code**  
   ```bash
   g++ Generalized_Data_Structure_Library.cpp -o ds_library
   ```

3. **Run**  
   ```bash
   ./ds_library
   ```

4. **Integrate as a Library**  
   - Include the header/source file in your project.  
   - Use the provided template classes (e.g., `SinglyLLL<int>`, `StackX<string>`).

---

## 🧑‍💻 Example Usage
```cpp
#include "Generalized_Data_Structure_Library.cpp"

int main() {
    StackX<int> s;
    s.Push(10);
    s.Push(20);
    s.Display();     // Output: |20| |10|
    cout << "Count: " << s.Count() << endl;
    return 0;
}
```


## 👨‍💻 Author

Developed by **Ritesh laxmikant Kurambhatti**
📧 Contact: riteshkurambhatti2006@gmail.com (mailto: riteshkurambhatti2006@gmail.com)
