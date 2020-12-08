# code
```c++
#include<iostream>
#include<climits>

int main() {
	using namespace std;
	int n_int = INT_MAX;
	short n_short = SHRT_MAX;
	long n_long = LONG_MAX;
	long long n_llong = LLONG_MAX;

	cout << "int is " << sizeof(int) << " byte." << endl;
	cout << "short is " << sizeof n_short << " byte." << endl;
	cout << "long is " << sizeof n_long << " byte." << endl;
	cout << "long long is " << sizeof n_llong << " byte." << endl;

	cout << "maximum values:" << endl;
	cout << "int: " << n_int << endl;
	cout << "short: " << n_short << endl;
	cout << "long: " << n_long << endl;
	cout << "long long: " << n_llong << endl;

	cout << "minimum int value = " << INT_MIN << endl;
	cout << "bits per byte = " << CHAR_BIT << endl;

	return 0;
}
int stonetolb(int sts) {
	return 14 * sts;
}
```
# output
    int is 4 byte.
    short is 2 byte.
    long is 4 byte.
    long long is 8 byte.
    maximum values:
    int: 2147483647
    short: 32767
    long: 2147483647
    long long: 9223372036854775807
    minimum int value = -2147483648
    bits per byte = 8
