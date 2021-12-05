#include <iostream>
#include <string>
#include <array>
#include <math.h>


using namespace std;


int main()
{
	int x = 2;
	cout << x * x << endl;

	cout << "The cube of 8 is " << pow(8, 3) << endl;
	cout << "The square-root of 8 is " << sqrt(8) << endl;
	cout << "The square-root of 4 is " << pow(4, 1/2) << endl;
	cout << "The cube-root of 8 is " << cbrt(8) << endl;
	cout << "The cube-root of 8 is " << pow(8, 1/3)<< endl;

	return 0;
}
{
	double number;
	cout << "Input a number \n";

	cin >> number;
	while (cin.fail())
	{
		cin.clear();
		cin.ignore();
		cout << "\nInvalid Input try again \n\nInput a number \n\n";
		cin >> number;
	}
	cout << " square-root: " << sqrt(number) << " cube-root: " << cbrt(number);
}
