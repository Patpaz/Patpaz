## Hello world :wave:
My name is Patrick Paz (aka *Patpa*), i've been studying Computer Science at **UTEC** since 2020. 
I'am a student of 4th semester and currently i'm learning how to program in C++ and Python.

## Interests 👍
- Cryptography
- Freestyle Master Series
- Anime *&* manga
- Football

## Random code:
``` c++
#include<iostream>
using namespace std;
class Name{
  private:
    string name;
    string lsname;
  public:
    Name(string name, string lsname):name(name),lsname(lsname){}
    void show(){
      cout << "Nombre: " << name << endl;
      cout << "Apellido: " << lsname << endl;  
    }
};
int main() {
  Name person("Patrick Giordano", "Paredes Paz");
  person.show();
  return 0;
  }
