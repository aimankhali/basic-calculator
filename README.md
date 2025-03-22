# 🧮 Basic Calculator - My First C++ Project!

## 🚀 About This Project
This is my first C++ project! 🎉 I created a simple calculator to test my understanding of C++ basics after just **40 minutes** of learning. This project is purely for practice and fun. 😃

---

## 📸 Preview

![Calculator Icon]([https://github.com/aimankhali/basic-calculator/blob/main/calculator.gif?raw=true])

---

## 🔧 Features
✅ Supports basic arithmetic operations: `+`, `-`, `*`, `/`  
✅ Simple command-line interface 🖥️  
✅ Lightweight & fast ⚡  
✅ Easy to modify and improve 🔧  

---

## 📜 Code Example
Here's a snippet of the calculator:
```cpp
#include <iostream>
using namespace std;

int main() {

    system("title Calculator test");

    int x;
    int y;
    string op;

    cout << "first c++ project of making a calculator \nthis is only a test if i know the basics of c++ \nlearned in 40 minutes . made by aimankhali \n";

    cout << "first number: ";
    cin >> x;

    cout << "second number: ";
    cin >> y;

    cout << "operator: ";
    cin >> op;

    if (op == "+") {
        cout << "your number is: " << x + y << "\n";
    }
    else if (op == "-") {
        cout << "your number is: " << x - y << "\n";
    }
    else if (op == "x" or op == "*") {
        cout << "your number is: " << x * y << "\n";
    }
    else if (op == "/" or op == "÷") {
        cout << "your number is: "<< x / y <<"\n";
    }

    cout << "Press Enter to exit...";
    cin.ignore();
    cin.get();

    return 0;
}
```

## 📥 Installation & Usage
1. Install a C++ compiler (e.g., GCC, MSVC) 🛠️
2. or you can also run it in a website (e.g., programiz, OnlineGBD) 🛠️
3. paste the code from the code example 📜
4. compile and have fun ⛏️📦


## 🏆 Credits
Made with ❤️ by **aimankhali** ✨

---

## 📢 Feedback & Contributions
Feel free to fork the project, so you can learn yourself! 🚀

---
