# program-6d
# 🧪 C Programming Lab
## 📘 Experiment No: 6d
### 🔹
**Date:** 19/3/2026  
**Name:** AKshara.k 
**Register No:** 25003090 

---

## 🎯 AIM
Create a C Program to store the student information and display it using structure.
---

## 🧠 ALGORITHM

---

## 💻 PROGRAM
```
#include<stdio.h>
struct student
{
    char name[100];
    int roll;
    float marks;
};

int main()
{
    struct student s;
    scanf("%s %d %f",s.name,&s.roll,&s.marks);
    printf("Displaying Information:\n");
    printf("Name: %s\n",s.name);
    printf("Roll number: %d\n",s.roll);
    printf("Marks: %.1f",s.marks);
}
```

## 🖼️ OUTPUT SCREENSHOT
<img width="687" height="184" alt="image" src="https://github.com/user-attachments/assets/1ea8725f-b098-45a5-8ff2-37606fa70d2b" />



---

## ✅ RESULT
Thus the C program to store the student information and display it using structure is executed successfully.
