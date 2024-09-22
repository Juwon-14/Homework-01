//Juwon Hong
// CIS 25
// 21/09/2024

#include <iostream>
using namespace std;

int main() {
    int number;
    
    cout << "Enter a positive integer: ";
    cin >> number;
    
    if (number == 0) {
        cout << "Binary: 0" << endl;
        return 0;
    }
   
    if (number < 0) {
        cout << "Please enter a positive integer." << endl;
        return 1;
    }

    string binary = "";
    
    while (number > 0) {
        binary = to_string(number % 2) + binary;
        number /= 2;
    }

    cout << "Binary: " << binary << endl;

    return 0;
}
