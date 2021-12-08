#include <iostream>
#include <string>
using namespace std;
int main()
{
string age, address, name;
cout << "Enter your name: \n";
cin >> name;
cout << "\nEnter your age: \n";
cin >> age;
cout << "\n Enter your address:\n" << address;
cin >> address;
cout << "\nYour name is: \n" << name;
cout << "\nYour age is: \n" << age;
cout << "\n Your address is: \n" << address;
}
  
  // enter name, age and address //
  
#include <iostream>
#include <string>
using namespace std;
int main()
{
double r,a,c;
cout << "Enter the radius to calculate the area and circumference of the circle \n";
cin >> r;
a = 3.14 * r * r;
c = 2 * 3.14 * r;
cout << "The area of the circle is: \n " << a << endl;
cout << "The circumference of the circle is: \n " << c << endl;
}
  
  // calculate of the radius //
  
  #include <iostream>
#include <string>
using namespace std;

int main()
{
	double length, width, rect, tri, sq;
	cout << "\n calculating the area of Rectangle, Triangle and Square shapes\n";
	cout << "enter the length:\n";
	cin >> length;
	cout << "/n enter the width : \n";
	cin >> width;

	rect = length * width;
	tri = (length * width) * 0.5;
	sq = length * length;
	cout << "\nThe area of rectangle : \n" << rect;
	cout << "\nThe area of triangle: \n" << tri;
	cout << "\nThe area of square: \n" << sq;
}
  
  // calculating the area of Rectangle, Triangle and Square //
  
  
#include <iostream>
using namespace std;

int main()
{
    cout << "Kindly enter your age to see whether you can vote or not!\n";
    int age;
    cin >> age;
    if (age >= 18)
    {
        cout << "You can vote";

    }
    else
    {
        cout << "Sorry not today";
    }

}
	
  // whether or not they are eligible to vote //
	

#include <iostream>
using namespace std;
bool checkEvenOdd(int num);

int main() {
    int num;
    bool isEven;
    cout << "Enter any number: ";
    cin >> num;
    isEven = checkEvenOdd(num);
    if (isEven)
        cout << num << " is an even number";
    else
        cout << num << " is an odd number";

    return 0;
}

bool checkEvenOdd(int num) {
    bool b;
    if (num % 2 == 0)
        b = true;
    else
        b = false;

    return b;
}
	
	// Check whether it's even or odd //

	
#include <iostream>
using namespace std;

int main()
{
    cout << "Enter the number to see whether its positive, negative or zero\n";
    double number;
    cin >> number;
    if (number == 0)
    {
        cout << "The number you entered is zero";
    }

    else  if (number > 0)
    {
        cout << "The number you entered is positive";
    }
    else  if (number < 0)
    {
        cout << "The number you entered is negative";
    }
    else
    {
        cout << "Incorrect input";
    }
}
		
		// To see whether its positive, negative or zero //

		
#include<iostream>
using namespace std;
int main()
{
	double Purchase, sale, x;
	cout << "Enter the purchase price: \n";
	cin >> Purchase;
	cout << "\nEnter the sale price: ";
	cin >> sale;
	x = sale - Purchase; 
	if (x > 0) 
	{
		cout << "You have a Profit of " << x << endl;
	}
	else if (x < 0) // For loss
	{
		cout << "You had a Loss of " << x << endl;
	}
	else if(x==0)
	{
		cout << "No loss no profit." << endl;
	}
	else
	{
		cout << "Incorrect input";
	}
	return 0;
}
			
		// Whether profit or loss //	

		
#include<iostream>
using namespace std;
int main()
{
	double side;
	cout << "Enter the sides number to see the shape name (minimum 3 sides, maximum 10) \n";
	cin >> side;
	
	if (side <= 2)
	{
		cout << "You enter 2 as side, which is incorrect input";
	}
	else if (side==3) 
	{
		cout << "Triangle  has " << side << " sides" << endl;
	}
	else if (side == 4)
	{
		cout << "Square | Rectangle has " << side << " sides" << endl;
	}
	else if (side == 5)
	{
		cout << "Pentagon has " << side << " sides" << endl;
	}
	else if (side == 6)
	{
		cout << "Hexagon have " << side << " sides" << endl;

	}
	else if (side == 7)
	{
		cout << "Hepaton have " << side << " sides" << endl;

	}
	else if (side == 8)
	{
		cout << "Octagon have " << side << " sides" << endl;

	}

	else if (side == 9)
	{
		cout << "Nonagon have " << side << " sides" << endl;

	}
	else if (side == 10)
	{
		cout << "Decagon have " << side << " sides" << endl;

	}
	else 
	{
		cout << "Incorrect";

	}

	return 0;
}
			
		// shape from its number of sides //	

			
			
#include<iostream>
using namespace std;
int main()
{
	string myname;
	int myage;
	int mylocation;
	cout << "enter your name" << endl;
	cin >> name;
	cout << "enter your age" << endl;
	sin >> age;
	cout << "select the locatiion you want to go\n1.Abu dhabi charges aed 100\n2.Sharjah charges aed 500\n3.Ajmen charjes and 390\n4.Dubai charges aed 650\n5.RAK charges aed 250\n6.umm al quwain charges aed 300\n7.Fujairh charges aed 300\n8. al ain charges aed 1000\n9.other no transportion available\n" << endl;
	cin >> ion;
	switch (loaction)
	{
	case 1:
		cout << "aub dhabi charges aed 1000" << endl;
		break;
	case 2:
		cout << "sharjah charges aed 500" << endl;
		break;
	case 3:
		cout << "Ajman charges aed 390" << endl;
		break;
	case 4:
		cout << "Dubai charges aed 650" << endl;
		break;
	case 5:
		cout << "Rak charges aed 250" << endly;
		break;
	case 5:
		cout << "UMM al quwain charges aed 300" << endly
			break;
	case 6:
		cout << "Fujairah charges aed 300" << endl;
		break;
	case 7:
		cout << "Al ain charges aed 1000" << endly;
	case 9:
		cout << "other no transportaion available" << endl;
		break;
	default:
		cout << "invalid loaction" << endl;
		break;
	}
	cout << "t to avail transportation" << endl;
	cout << "if nothen type n and if yes then type n" << endl;
	char check;
	cin >> check;
	if (check)
	{
		switch (check)
		{
		case 'A':
		case "b":
			cout << "transportation has been booked" << endl;
			break;
		case 'O':
		case "p":
			cout << "transportation has been cancelled" << endl;
			break;
		default:
			cout << "invalid error" << endly;
			break;
		}
	}

	//    Coding Test   //
	
	
#include <iostream>
using namespace std;
int main()
{
	int num = 108;
	while (num >= 9) //while conditional check
	{
		//code to output then decrease number
		cout << num << endl;
		num = num - 9;

	}

	cin.get(); //keeps console window open in visual studo
	return 0;

}
	
	// Reverse 9 //
	

#include <iostream>
using namespace std;
int main()
{
	cout << "enter a number either 1 or 2 \n";
	int x;
	cin >> x;
	while (x != 0 && x <= 2 && !cin.fail())
	{
		if (x == 1)
		{
			cout << "you have entered the number 1 \n";
		}
		else
		{
			cout << "you have entered the number 2\n";
		}
		cout << "enter a number either 1 or 2\n";
		cin >> x;
	}
	cout << "You did not enter the number 1 or 2";

}
	
	//  The Pointless box //
	
	
	
	#include<iostream>
#include<math.h>
#include<string>
using namespace std;
int main()
{
	int Num, Fact = 1, Counter = 10;
	string Name;
	cout << "Enter your name: ";
	getline(cin, Name);
	cout << "Enter a number: ";
	cin >> Num;
	while (cin.fail())
	{
		cin.clear();
		cin.ignore(1000, '\n');
		cout << "Invalid number\nTry again: ";
		cin >> Num;
	}
	for (int i = Num; i > 0; i--)
	{
		Fact *= i;
	}
	cout << "Factorial is: " << Fact << endl;
	do
	{
		cout << Num << " x " << Counter << " = " << Num * Counter << endl;
		Counter--;
	} while (Counter > 0);
	for (int i = 10; i > 4; i--)
	{
		cout << Num << " with exponent of " << i << " = " << pow(Num, i) << endl;
	}
	return 0;
}
	// Coding test 2 ///
