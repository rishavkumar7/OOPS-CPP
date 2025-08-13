*Here we are just joining to implement the Class and Object concepts we learnt in the previous tutorial.*  
  
```
#include <bits/stdc++.h>
using namespace std;

class HumanBeing {
    public:
        string name;

        void introduce() {
            cout<<"Hi i am "<<name<<endl;
        }
};

int main() {
    HumanBeing male;
	male.name = "Rishav";
	male.introduce();

	HumanBeing female;
    female.name = "Shivangi";
	female.introduce();
	
    return 0;
}
```
  
## Output  
> Hi i am Rishav  
> Hi i am Shivangi  
