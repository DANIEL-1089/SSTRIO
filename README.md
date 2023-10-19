#include <iostream>
#include <cstdlib>
#include <ctime>
#include <wchar.h>
#include <Windows.h>
#include <algorithm>
#include <vector>
#include <string>
#include <cstring>
#include <conio.h>
#include <iomanip>


using namespace std;



int main()
{
    string full_name, nickname, address;
    string greeting("Hello, ");

    cout << "Enter your name: ";
    getline(cin, full_name);
    cout << "Enter yout name: " << full_name << endl;

    cout << "Enter your alias: ";
    cin >> nickname;

    greeting += nickname;
    cout << greeting << endl;

    cout << "Enter your address in a few lines\n";
    cout << "End of input character $\n";
    getline(cin, address, '$');
    cout << "Your address: " << address << endl;
    return 0;
}
