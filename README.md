#include <iostream>
#include <string>
using namespace std;
int main()

{
	int minutes;
	float change;
	cout << "Enter the number of minutes: ";
	cin >> minutes;

	if (minutes >= 15)
	{
		cout << "Enter how much money do you have ?: ";
		cin >> change;
		if (change >= 5) 
		{
			cout << "Go buy a coffee\n";
		}
		else {
			cout << "Go for a walk around the town\n";
		}
	}
	else {
		cout << "Sit in the food zone and wait\n";
	}
	cin >> change;
	return 0;


}
