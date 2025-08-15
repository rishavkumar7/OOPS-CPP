# Scope Resolution Operators  

We can define the declared methods of the class outside the class using scope resolution operator.  
We can initialise only the static properties of the class outside the class using scope resolution operator.  

```
#include <bits/stdc++.h>
using namespace std;

class HumanBeing {
    public:
        string name;
        
        void speak();
};

// string HumanBeing::name = "Shivangi";       only static properties can be initialized outside the class

void HumanBeing::speak() {
    cout<<"My name is "<<HumanBeing::name<<endl;
} 

int main() {
    HumanBeing person;
    person.name = "Rishav";
    person.speak();
    
    return 0;
}
```
