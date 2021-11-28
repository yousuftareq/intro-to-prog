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
