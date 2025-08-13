```
#include <bits/stdc++.h>
using namespace std;

class HumanBeing {
    public:
        string name;

        void speak() {
            cout<<"Hi "<<name<<endl;
        }
};

int main() {
    HumanBeing person1;     // object is stored in stack memory.
    person1.name = "Rishav";
    person1.speak();

    HumanBeing *person2 = new HumanBeing();      // object is stored in heap memory.
    person2->name = "Shivangi";
    person2->speak();
    
    return 0;
}
```

The object *person1* is created **statically** allocated memory whereas the object *person2* is **dynamically** allocated memory.  
The use of **new** keyword returns a **pointer** therefore **arrow operator** is used instead of dot operator.
