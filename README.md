# Goodmorning
using else if statement
#include<iostream>
using namespace std;
int main()
{
	int currentTime;    //declaring variable with datatype int
	cout << "Enter the time" << endl;   
	cin >> currentTime;
	if (currentTime <12) {  //if time is less than 12 then if block of statements will be executed
		cout << "GOOD MORNING!";
	}
	else if(currentTime<18){  //if time is less than 18 then goodafternoon will be displayed
		cout << "GOOD AFTERNOON!" << endl;
	}
	else if (currentTime < 21) {  //if time is less than 21 then good evening will be displayed
		cout << "GOOD EVENING!" << endl;
	}
	else if (currentTime < 24) {  //if time is less than 24 then goodnight will be displayed
		cout << "GOOD NIGHT!" << endl;
	}
	else {    //if time is greater than 24 then else block of statements will be exceuted
		cout << "Invalid time." << endl;
	}
	cin.get();
	return 0;
}
