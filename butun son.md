# 📘 C++ Darslik: O'zgaruvchilar va Butun Sonlar

![C++ Logo](https://upload.wikimedia.org/wikipedia/commons/1/18/ISO_C%2B%2B_Logo.svg)

---

## 🧩 O‘zgaruvchilar nima?

O‘zgaruvchilar — bu **dasturda ma’lumot saqlaydigan konteynerlar**.

Har bir o‘zgaruvchi:
- **nomga ega**
- **qiymatga ega**
- **tipga ega**

C++ tilida har bir o‘zgaruvchi ishlatilishidan oldin **e’lon qilinishi shart**.

### 🔤 Nomlash qoidalari:
- Harf bilan boshlanadi  
- Keyingi belgilar — harf + raqam  
- `A` va `a` — bu **turli o‘zgaruvchilar**

---

## 💻 Misol: O‘zgaruvchilar bilan ishlash

```cpp
#include <iostream>
#include <string>

using namespace std;

const double pi=3.14159;           
int age=14, b;                     
double height, weight;             
char c='A', p;                     
string name, B="Visual C++";       

int main(){
  name = "Ivan";
  weight = age*pi + 12.456;

  cout << name << " is " << age << " years old." << endl;
  cout << name << "'s weight makes about " << weight << " kg." << endl;

  return 0;
}
```
# 🔢 C++ Butun Son Turlari

| Tip | Qiymatlar | Xotira |
|-----|-----------|--------|
| `char` | -128 … 127 | 1 bayt |
| `unsigned char` | 0 … 255 | 1 bayt |
| `short` | -32768 … 32767 | 2 bayt |
| `unsigned short` | 0 … 65535 | 2 bayt |
| `int` | -2147483648 … 2147483647 | 4 bayt |
| `unsigned int` | 0 … 4294967295 | 4 bayt |
| `long long` | -9.22e18 … 9.22e18 | 8 bayt |
| `unsigned long long` | 0 … 1.84e19 | 8 bayt |

> ⚠️ Amaliyotda `int` va `long long` yetarli bo‘ladi.

---

## ➗ Amallar

| Amal | Ma’nosi |
|------|---------|
| `+` | qo‘shish |
| `-` | ayirish |
| `*` | ko‘paytirish |
| `/` | butun bo‘lib bo‘lish |
| `%` | qoldiq topish |

---

## 🧮 Bo‘lish va Qoldiq

Misol:  
- `13 / 5 = 2`  
- `13 % 5 = 3`

---

## 📘 Kod misoli

```cpp
#include <iostream>
using namespace std;

int a=167, b=6, c;

int main(){
  cout << 13/5 << endl;         
  cout << 13%5 << endl;         
  cout << a/b << endl;          
  cout << a%b << endl;          
  cout << 13/5.0 << endl;       
  cout << double(13)/5 << endl; 
  cout << 1.0*a/b << endl;      
  cout << double(a)/b << endl;  
  c = double(a)/b;
  cout << c << endl;            
  return 0;
}
```
## 🎉 Yakuniy xulosa

## Bu bo‘lim C++ o‘zgaruvchilar va butun sonlar haqida eng muhim bilimlarni o‘z ichiga oladi.
