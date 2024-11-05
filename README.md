```
#include <iostream>
#include <string>

using namespace std;

int main()
{ 
  int width, heigth;
  cout << "Укажите высоту и ширину:" << endl;
  cin >> width >> heigth;


  int j = 0;
  for(j; j < heigth; j++){

    for(int i = 0; i < width; i++) {
    cout << "*";
    }
    cout << endl;

  }
}
```
