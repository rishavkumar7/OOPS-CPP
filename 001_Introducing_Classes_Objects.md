#Class

A class is basically a **user defined datatype**  or simply a **blueprint**.
Its a collection of attributes (data) and behaviours (actions).
If a class is created inside a function then that class will be accessible inside that function only.
The name of the function to be begun with a Capital Letter.

#Object

An object is an **instance** of a class.
It is a runtime variable of the class.

```
#include <bits/stdc++.h>
using namespace std;

class HumanBeing {
    public:
        void speak() {
            cout<<"Hello i'm a Human Being.";
        }
};

int main() {
    HumanBeing rishav;
    rishav.speak();
    
    return 0;
}
```
