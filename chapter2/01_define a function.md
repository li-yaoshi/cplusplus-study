# code
```c++
#include<iostream>
int stonetolb(int);	//function protype

int main() {
	using namespace std;
	int stone;
	cout << "enter the weight in stone: ";
	cin >> stone;
	int pounds = stonetolb(stone);
	cout << stone << " stone = " << pounds << " pounds.";
	
	return 0;
}
int stonetolb(int sts) {
	return 14 * sts;
}
```
# output
    enter the weight in stone: 15
    15 stone = 210 pounds.
