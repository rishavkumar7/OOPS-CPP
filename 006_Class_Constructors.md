# Constructors  

Constructors have the **same name** of class and **no return** type.  
It is used to **initialise** the properties of the class.  
It can also be defined outside the class using scope resolution operator.  
Its automatically called while creating the instance of that class and cannot be called manually.  
If no constructors are created then by default a constructor is called with no statements in it.  
It must be defined within the public access specifier.  

```
#include <bits/stdc++.h>
using namespace std;

class HumanBeing {
    private:
        int age;
        
    public:
        HumanBeing() {
            age = 0;
            cout<<"Constructor created now"<<endl;
        }
    
        void setAge(int value) {
            age = value;
        }
        
        void displayAge() {
            cout<<"My age is "<<age<<endl;
        }
};

int main() {
    HumanBeing person;
    person.setAge(26);
    person.displayAge();
    
    return 0;
}
```
