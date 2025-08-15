# Private Access Specifier
  
The private members of a class can be used **only inside that class**.  
We can access private members of a class using public members of that class.  

```
#include <bits/stdc++.h>
using namespace std;

class HumanBeing {
    private:
        int age;
        
    public:
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
