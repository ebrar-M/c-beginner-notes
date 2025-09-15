![Stars](https://img.shields.io/github/stars/ebrar-M/css-beginner-notes?style=flat&logo=github)
![Forks](https://img.shields.io/github/forks/ebrar-M/css-beginner-notes?style=flat&logo=github)
![Last Commit](https://img.shields.io/github/last-commit/ebrar-M/css-beginner-notes?color=brightgreen)
![C](https://img.shields.io/badge/C-Programming-A8B9CC?logo=c&logoColor=white)

**---**

## 🌍 Languages
- 🇹🇷 [Türkçe](#-tr-türkçe)
- 🇬🇧 [English](#-gb-english)

---

## 🇹🇷 TR Türkçe

# 🟦 C Programlama Dili - Temelleri

## 1. 📖 C Nedir?
- **C**, Dennis Ritchie tarafından 1972’de geliştirilmiş bir programlama dilidir.  
- Hızlı ⏱️, düşük seviyeli (donanım yakın) ama güçlüdür.  
- İşletim sistemleri (Linux, Windows çekirdeği), gömülü sistemler ve performans odaklı projelerde kullanılır.  
- Birçok modern dilin (C++, Java, C#, Go) atasıdır.  

---

## 2. 🏗️ İlk C Programı
```c
#include <stdio.h>

int main() {
    printf("Merhaba C 🚀\n");
    return 0;
}
```

📌 Açıklama:  
- `#include <stdio.h>` → standart giriş/çıkış kütüphanesini ekler.  
- `main()` → programın başlangıç noktasıdır.  
- `printf()` → ekrana yazdırır.  
- `return 0;` → programı başarıyla bitirir.  

---

## 3. 🔑 Değişkenler ve Veri Tipleri
```c
int sayi = 10;        // Tam sayı
float pi = 3.14;      // Ondalık sayı
char harf = 'A';      // Tek karakter
double buyukPi = 3.141592653; // Daha hassas ondalık
```

---

## 4. 🧮 Operatörler
```c
int a = 5, b = 2;
printf("%d\n", a + b);  // Toplama
printf("%d\n", a - b);  // Çıkarma
printf("%d\n", a * b);  // Çarpma
printf("%d\n", a / b);  // Bölme
printf("%d\n", a % b);  // Mod
```

---

## 5. 🔁 Koşullar ve Döngüler

### If - Else
```c
int yas = 18;
if (yas >= 18) {
    printf("Reşitsiniz ✅\n");
} else {
    printf("Reşit değilsiniz ❌\n");
}
```

### Switch
```c
int gun = 3;
switch (gun) {
    case 1: printf("Pazartesi\n"); break;
    case 2: printf("Salı\n"); break;
    case 3: printf("Çarşamba\n"); break;
    default: printf("Bilinmiyor\n");
}
```

### For Döngüsü
```c
for (int i = 1; i <= 5; i++) {
    printf("%d\n", i);
}
```

### While Döngüsü
```c
int sayac = 0;
while (sayac < 3) {
    printf("Sayaç: %d\n", sayac);
    sayac++;
}
```

---

## 6. 📦 Fonksiyonlar
```c
#include <stdio.h>

int kare(int x) {
    return x * x;
}

int main() {
    printf("%d\n", kare(5));
    return 0;
}
```

---

## 7. 📚 Diziler
```c
int sayilar[5] = {1, 2, 3, 4, 5};
for (int i = 0; i < 5; i++) {
    printf("%d\n", sayilar[i]);
}
```

---

## 8. 🧩 İşaretçiler (Pointers)
```c
int sayi = 10;
int *ptr = &sayi;

printf("Deger: %d\n", sayi);
printf("Adres: %p\n", &sayi);
printf("Pointer ile değer: %d\n", *ptr);
```

📌 İşaretçiler C’nin en güçlü (ve en kafa karıştırıcı 😅) özelliklerinden biridir.  

---

## 9. 🌈 İpuçları
✔️ `printf` → ekrana yazdırmak için  
✔️ `scanf` → kullanıcıdan giriş almak için  
✔️ Bellek yönetimini öğren → `malloc`, `free`  
❌ Dizilerde sınırın dışına çıkma → segfault (program çökebilir)  

---

## 🎯 Mini Alıştırmalar
1. Kullanıcıdan 2 sayı al → toplamasını ve çarpmasını ekrana yazdır.  
2. 1’den 100’e kadar olan sayıların toplamını bulan program yaz.  
3. Bir dizideki en büyük sayıyı bulan program yaz.  

---

## 📌 Son Söz
C dili, yazılım dünyasının temel taşlarından biridir.  
Düşük seviyeli kontrol (bellek, donanım) sağlar ama aynı zamanda hızlıdır.  
Kısacası: **C öğrenmek, diğer dilleri daha kolay kavramanı sağlar. 🔥**


---

## 🇬🇧 GB English

# 🟦 C Programming Language - Fundamentals

## 1. 📖 What is C?
- **C** is a programming language developed by Dennis Ritchie in 1972.
- It is fast, low-level (close to hardware), but powerful.
- It is used in operating systems (Linux, Windows kernel), embedded systems, and performance-oriented projects.
- It is the ancestor of many modern languages ​​(C++, Java, C#, Go).

---

## 2. 🏗️ The First C Program
```c
#include <stdio.h>

int main() {
printf("Hello C 🚀\n");
return 0;
}
```

📌 Description:
- `#include <stdio.h>` → Adds the standard input/output library.
- `main()` → the starting point of the program.
- `printf()` → prints to the screen.
- `return 0;` → terminates the program successfully.

---

## 3. 🔑 Variables and Data Types
```c
int number = 10; // Integer
float pi = 3.14; // Decimal number
char letter = 'A'; // Single character
double bigPi = 3.141592653; // More precise decimal
```

---

## 4. 🧮 Operators
```c
int a = 5, b = 2;
printf("%d\n", a + b); // Addition
printf("%d\n", a - b); // Subtraction
printf("%d\n", a * b); // Multiplication
printf("%d\n", a / b); // Division
printf("%d\n", a % b); // Mode
```

---
## 5. 🔁 Conditions and Loops

### If - Else
```c
int age = 18;
if (age >= 18) {
printf("You are a minor ✅\n");
} else {
printf("You are a minor ❌\n");
}
```

### Switch
```c
int day = 3;
switch (day) {
case 1: printf("Monday\n"); break;
case 2: printf("Tuesday\n"); break;
case 3: printf("Wednesday\n"); break;
default: printf("Unknown\n");
}
```

### For Loop
```c
for (int i = 1; i <= 5; i++) {
printf("%d\n", i);
}
```

### While Loop
```c
int counter = 0;
while (counter < 3) {
printf("Counter: %d\n", counter);
counter++;
}
```

---

## 6. 📦 Functions
```c
#include <stdio.h>

int square(int x) {
return x * x;
}

int main() {
printf("%d\n", square(5));
return 0;
}
```

---

## 7. 📚 Arrays
```c
int nums[5] = {1, 2, 3, 4, 5};
for (int i = 0; i < 5; i++) {
printf("%d\n", nums[i]);
}
```

---

## 8. 🧩 Pointers
```c
int nums = 10;
int *ptr = &nums;

printf("Value: %d\n", nums);
printf("Address: %p\n", &nums);
printf("Value with pointer: %d\n", *ptr);
```

📌 Pointers are one of C's most powerful (and most confusing 😅) features.

---

## 9. 🌈 Tips
✔️ `printf` → print to the screen
✔️ `scanf` → get user input
✔️ Learn memory management → `malloc`, `free`
❌ Out-of-bounds in arrays → segfault (may crash the program)

---

## 🎯 Mini Exercises
1. Get 2 numbers from the user → print their addition and multiplication.
2. Write a program to find the sum of numbers from 1 to 100.
3. Write a program to find the largest number in an array.

---

## 📌 Final Word
The C language is one of the cornerstones of the software world.
It provides low-level control (memory, hardware) but is also fast.
In short: **Learning C will make it easier to grasp other languages. 🔥**
