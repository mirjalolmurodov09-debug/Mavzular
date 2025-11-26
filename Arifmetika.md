# Dev c++ --- Dastlabki Dasturingizni Yaratish
## 📚 Mazmuni
-   1.  Katalog yaratish
-   2.  Dev c++ ni ishga tushirish
-   3.  Yangi loyiha yaratish
-   4.  Loyiha faylini ochish
-   5.  Tayyor dastur (C++)
-   6.  Dastur ishga tushirish va saqlash
-   7.  Kod haqida tushuntirish
-   8.  A + B masalasi uchun namunaviy yechim
-   9.  Yechimni topshirish tartibi
## 📁 1. Katalog yaratish
Kompyuteringizda dasturlarni saqlaydigan papka yarating. Masalan:
**Hobbit**.
## 🚀 2. Dev c++ dasturini ishga tushirish
Dev c++-ni quyidagi usullardan biri orqali ochish mumkin: - Ish
stolida joylashgan yorliq orqali; - **Pusk → Все программы → Dev c++**; - Qidiruv orqali; 
## 🆕 3. Yangi loyiha yaratish
1.  **File → New → Project...**
2.  **Console Application → Go**
3.  **C++ → Next**
4.  Loyiha nomi: **Hello**
5.  Papka: **Hobbit**
6.  **Next → Finish**
## 📄 4. Loyiha faylini ochish
Chap tomondan: **Management → Projects → Sources → main.cpp**
## 💻 5. Tayyor dastur (C++)
``` cpp
#include <iostream>
using namespace std;

int main(){
  cout << "Hello world!" << endl;
  return 0;
}
```
## ▶️ 6. Dastur ishga tushirish va saqlash
-   Ishga tushirish: **F11**
-   Saqlash: **Ctrl + S**
## 📘 7. Kod haqida tushuntirish
-   `//` --- kommentariya
-   `#include <iostream>` --- kiritish/chiqarish
-   `using namespace std;`
-   `main()` --- asosiy funksiya

Universal kutubxona:

``` cpp
#include <bits/stdc++.h>
```
## 🧮 8. A + B masalasi uchun namunaviy yechim
``` cpp
#include <bits/stdc++.h>
using namespace std;
int a, b;
int main(){
  cin >> a >> b;
  cout << a + b;
  return 0;
}
```
## 📤 9. Yechimni topshirish tartibi
1.  Kodni maydonga joylashtiring
