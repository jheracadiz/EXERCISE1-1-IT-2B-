#include <iostream>
using namespace std;

int main() {	
    int n1, n2, n3;

    cout << "Enter three values: ";
    cin >> n1 >> n2 >> n3;

    if(n1 >= n2 && n1 >= n3)
        cout << "The maximum is: " << n1;

    else if(n2 >= n1 && n2 >= n3)
        cout << "The maximum is: " << n2;
    
    else 
        cout << "The maximum is: " << n3;
  
    return 0;
}
