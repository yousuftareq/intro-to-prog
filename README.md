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
  
  /////   Circles  //////

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
	
//////   Biography  ////////////////
	
#include <iostream>
#include <string>
using namespace std;
int main()
{
double x;
double y;
cout << "Enter the temperature in Fahrenheit to be converted into celcius\n";
cin >> x;
y = (x - 32) * 0.5556;
cout << "The temperature in Celcius is: " << y << endl;
}
	
////////   Temperature  1 //////////
	
#include <iostream>
#include <string>
using namespace std;
int main()
{
double x,y;
cout << "Enter the temperature in celcius to be converted into Fahrenheit \n";
cin >> x;
y = (x *1.8) +32;
cout << "The temperature in Fahrenheit is: " << y << endl;
}
	
	
//////  Temperature 2 //////////
	

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
  
  // calculating the area of Rectangle, Triangle and Square ///////////
  
  
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
        cout << "Sorry later";
    }

}
	
  // whether or not they are eligible to vote //////////
	

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
	
          /////// Check whether it's even or odd ///////

	
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
		
	////////// To see whether its positive, negative or zero /////////////

		
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
			
	///////////// Whether profit or loss ////////////////	

		
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
			
	////////// shape from its number of sides /////////////	
			
		
#include<iostream>
using namespace std;
int main()
{
	cout << "Enter the time in 24 hour pattern to see whether it Morning, Afternoon, Evening or Night\n";
	double time;
	cin >> time;
	if (time < 12)
	{
		cout << "Good Morning";
	}
	else if (time >= 12 && time < 18)
	{
		cout << "Good Afternoon";
		}
	else if (time >=18 && time < 21)
	{
		cout << "Good Evening";
	}
	else if (time >=21 && time <24)
	{
		cout << "Good Night";
	}
	else
	{
		cout << "wrong input";
	}
}

/////////// Good Morning ////////////			
			
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

/////////////    Coding Test   ///////////
	

#include <iostream>
using namespace std;
int main()
{
    cout << "What is the capital of France?\n";
    string capital;
    cin >> capital;
   
    if (capital == "Paris" || capital == "paris" || capital == "PARIS")
    {
        cout << "You enter the correct answer";
    }
    else 
    {
        cout << "Sorry wrong answer";
    }
    
    return 0;
}
	
	/////////  What is the capital of France ///////
	
#include <iostream>
using namespace std;

int main()
{
	cout << "Enter a letter to see whether its a vowel or consonant\n";
	char c;
	cin >> c;
	//isalpha is a built in function to check for alphabet values in c++
	if (!isalpha(c))
	{
		cout << "you entered an incorrect value";
	}
	else if (c == 'a' || c == 'e' || c == 'i' || c == 'o' || c == 'u' || c == 'A' || c == 'E' || c == 'I' || c == 'O' || c == 'U')
	{
		cout << "you entered a vowel";

	}


	else
	{
		cout << "you entered a consonant";
	}
}
	
//////// Letter Checker //////////
	
#include <iostream>
using namespace std;

int main()
{
	
	char l;
	int count1, count2; // variable for isalpha
	
	cout << "Enter a letter to check whether its a vowel or a consonant: ";
	cin >> l;
	if (l == 'a' || l == 'e' || l == 'i' || l == 'o' || l == 'u'|| l == 'A' || l == 'E' || l == 'I' || l == 'O' || l == 'U') // Checking if the entered character is a vowel
	{
		cout << "The input is a vowel." << endl;
	}
	count1 = isalpha(char(l)); // Using isalpha built-in function for alphabets
	count2 = isdigit(char(l)); // Using isdigit built-in function for digits
	if (count1 == 0 && count2 != 4) // Checking if the entered character is a special character, converting the special character into their ASCII code
	{
		cout << "The input is a special character." << endl;
	}
	else if (count1 != 2 && count2 == 4) // Checking if the entered character is a digit
	{
		cout << "The input is a digit." << endl;
	}
	else if (count1 != 0 && count2 != 4 && l != 'a' && l != 'e' && l != 'i' && l != 'o' && l != 'u' && l != 'A' && l != 'E' && l != 'I' && l != 'O' && l != 'U') // Checking if the entered character is a consonant
	{
		cout << "The input is a consonant." << endl;
	}
	else
	{
		cout << "The input is incorrect.";
			}
	return 0;
}
	
////////// Letter Checker 2 ///////////
	
#include <iostream>
using namespace std;

int main()
{
   cout << "Enter the marks from 1-100 to see the grade, 0 input is not accepted\n";
   double m;
   cin >> m;
   if (m>70)
   {
  cout << "You have a A Grade";
   }
   else if (m >= 60 && m < 70)
   {
  cout << "You have a B Grade";
   }
   else if (m >= 50 && m < 60)
   {
  cout << "You have a C Grade";
   }
   else if (m>40 && m<50)
   {
  cout << "You have a D Grade";
   }
   else if (m == 40 )
   {
  cout << "You have a JUST PASSED Grade";
   }
   else if(m<40 && m!=0)
   {
  cout << "You have a Fail Grade";
   }
   else 
   {
  cout << "Wrong input";
   }
}
	
////////// Mark my Words ///////////
	
#include<iostream>
#include<string>
using namespace std;
int main()
{
	bool musician;
	string reply;
	string instrument;
	cout << "Do you play any musical instrument? \n type 'y' for yes \n and 'n' for no \n ";
	cin >> reply;
	if (reply == "y" || reply == "Y")
	{
		musician = true;
		if (musician == true)
		{
			cout << "What kind of insturment you can play \n type d if you're a drummer \n type g if you're a guitarist\n type o for other\n" << endl;
			cin >> instrument;
			if (instrument == "g" || instrument == "G")
			{
				cout << "That's great! I really needed a guitarist." << endl;
			}
			else if (instrument == "d" || instrument == "D")
			{
				cout << "That's great! I really needed a drummer." << endl;
			}
			else if(instrument =="o" || instrument == "O")
			{
				cout << "Ah I see, actually I'm looking for guitarist or a drummer.\n Let me know if you someone who plays them\n Thank you :)" << endl;
			}
			else
			{
				cout << "Incorrect input" << endl;
			}

		}
	}
		else if (reply == "N" || reply == "n")
		{
			musician = false;
			cout << "Oh! so you don't know how to play any instrument\n it's alright, let me know if you know someone who does \n Thanks" << endl;
		}
		else
		{

			cout << "Incorrect input" << endl;
		}

	
		return 0;
	}
	
	
/////////////   Starting a Band //////////
	
#include<iostream>
using namespace std;
int main()
{
	int t, m;
	cout << "Until what time your friend will come? (Enter the time in minutes)\n";
	cin >> t;
	if (t >= 15)
	{
		cout << "Your friend will take more or equal to 15 minutes to come,\n enter the money amount to see if you can drink something";
		cin >> m;
		if (m > 5)
		{
			cout << "You have more than 5 AED, now you will buy a drink and wait for him" << endl;
		}
		else
		{
			cout << "You don't have enough money,\n Let's just walk around";
		}
	}
	else
	{
		cout << "Your friend will be here within 15 minutes, \n so you're just going to wait for him." << endl;
	}
	return 0;
}

/////////  KillingTime  ////////////
	
#include<iostream>
using namespace std;
int main()
{
	double mag;
	cout << "please enter the mangitude of the earthquake in numbers 0 input is not accepted : ";
	cin >> mag;

	

		if (mag < 2.0 && mag >0) {
			cout << " earthquake is considered to be a micro earthquake.";
		}
		else if (mag >= 2.0 && mag < 3)
		{
			cout << mag << " earthquake is considered to be a very minor earthquake.";
		}
		else if (mag >= 3.0 && mag < 4)
		{
			cout << mag << " earthquake is considered to be a minor earthquake.";
		}
		else if (mag >= 4.0 && mag < 5.0)
		{
			cout << mag << " earthquake is considered to be a light earthquake.";
		}
		else if (mag >= 5.0 && mag < 6.0)
		{
			cout << mag << " earthquake is considered to be a moderate earthquake." << endl;
		}
		else if (mag >= 6.0 && mag < 7)
		{
			cout << mag << " earthquake is considered to be a strong earthquake." << endl;
		}
		else if (mag >= 7.0 && mag < 8)
		{
			cout << mag << " earthquake is considered to be a major earthquake." << endl;
		}
		else if (mag >= 8.0 && mag <= 10)
		{
			cout << mag << " earthquake is considered to be a great earthquake." << endl;
		}
		else if (mag > 10.0)
		{
			cout << mag << " earthquake is considered to be a meteoric earthquake." << endl;
		}
	
		else {
			cout << "You entered an invalid value" << endl;
		}
		return 0;
		}
	
///////////   Earthquake /////////////
	
#include <iostream>
using namespace std;
int main()
{

	cout << "Kindly select the option number for the month you want to see the days of:\n";

	cout << " 1. January\n 2. February\n 3. March\n 4. April\n 5. May \n 6. June \n 7. July \n 8. August\n 9. September\n 10. October\n 11. November\n 12. December\n";
	int a;
	cin >> a;


	switch (a)
	{
	case 1:
	{
		cout << "The month of January have  days 31";
		break;
	}
	case 2:
	{
		cout << "The month of February have  days 28 if there is a leap year than 29";
		break;
	}
	case 3:
	{
		cout << "The month of March have  days 31";
		break;
	}
	case 4:
	{
		cout << "The month of April have  days 30";
		break;
	}
	case 5:
	{
		cout << "The month of May have  days 31";
		break;
	}
	case 6:
	{
		cout << "The month of June have  days 30";
		break;
	}
	case 7:
	{
		cout << "The month of July have  days 31";
		break;
	}
	case 8:
	{
		cout << "The month of August have  days 31";
		break;
	}
	case 9:
	{
		cout << "The month of September have  days 30 ";
		break;
	}
	case 10:
	{
		cout << "The month of October have  days 31";
		break;
	}
	case 11:
	{
		cout << "The month of November have  days 30";
		break;
	}
	case 12:
	{
		cout << "The month of December have  days 31";
		break;
	}

	default:
	{
		cout << "Invalid Input" << endl;
		break;
	}
	}

}
	
/////////////  Days of the Month ///////////////////
	
#include <iostream>
using namespace std;
int main()
{
    cout << "Kindly enter how many litres you want to fill up your car\n";
    int lit;
    cin >> lit;
    if (lit != 0)
    {
        cout << "You have selected " << lit << " litres\n";
        cout << "Kindly select the fuel type you want for your car\n";
        cout << "Enter 'p' for Petrol\n 'd' for Diesel\n";
        char fuel;
        cin >> fuel;
        switch (fuel)
        {
        case 'P':
        case 'p':
        {

            cout << "You have selected Petrol for filling up your car\n "; 
            int c;
            c = lit * 0.8;
            cout << "\nThe price per litres is 0.8 now the total is " << c;
            break;
        }
        case 'd':
        case 'D':
        {
            cout << "You have selected Diesel for filling up your car ";
            int c;
            c = lit * 0.5;
            cout << "\nThe price per litres is 0.5 now the total is " << c;
            break;

            break;
        }

        default:
        {
            cout << "Incorrect command"; break;
        }
        }
    }
    else
    {
        cout << "Incorrect command\n ";
    }
    

}
	
///////////  Fuel me up /////////////
	
#include <iostream>

using namespace std;
int main()
{

	cout << "Kindly select what type of temperature conversion you're interested in" << endl;
	cout << "Type 'c' for conversion from celcius into fahrenheit" << endl;
	cout << "Type 'f' for conversion from fahrenheit into celcius" << endl;
	
	char select;
	int temp;
	cin >> select;
	switch (select)
	{
		case 'c':
		case 'C':

	{
		cout << "\nKindly enter the temperature in celcius to be converted into fahrenheit\n";
		cin >> temp;
		temp = (temp * 1.8) +32;
		cout << "\n The temperature after converison is " << temp;
		break;
	}
		case 'f':
		case 'F':
		{
			cout << "\nKindly enter the temperature in fahrenheit to be converted into celcius\n";
			cin >> temp;
			temp = (temp - 32) * 0.5556;
			cout << "\n The temperature after converison is " << temp;
			break;
		}
		
		default:
	{
		cout << "Incorrect command";
		break;
	}

	}

	
	cin.get(); //keeps console window open in Visual Studio
	return 0;
}
	
/////////// Switching Temperature //////////////
	
#include <iostream>
#include <exception>
#include <string>

using namespace std;
int main()
{


    

    cout << "Enter your full name" << endl;
    string name;
  // cin cannot read spaces, that is why we can use the getline code to read the input untill the next line
    getline(cin, name);
    

    cout << "\nEnter The Marks Between 0 To 100 to check your grade:";

    cout << "\nEnter The Mark: ";
    int marks;

    std::cin >> marks;
    //Using the cin.fail function (when user enters alphabet instead of numbers)
    if (std::cin.fail())
    {
        std::cin.clear();
        std::cin.ignore(std::numeric_limits<std::streamsize>::max(), '\n');
        std::cout << "Incorrect command\n: ";
    }

    else if (marks > 100)

    {

        /* Marks greater than 100 */

        cout << "\nKindly input your Marks Between Limit\n";
    }

    else

    {

        switch (marks / 10)

        {

        case 10:

        case 9:
        case 8:

        {
            /* Marks between 80-100 */


            cout << name <<" Your Grade Is: A Excellent";


            break;
        }
        case 7:

        {    /* Marks between 70-79 */


            cout << name << " Your Grade Is: B Very Good";


            break;
        }
        case 6:
        {
            /* Marks between 60-69 */


            cout << name << " Your Grade Is: C Fair";

            break;
        }
        case 5:
        {
            /* Marks between 50-59 */

            cout << name << " Your Grade Is: D Need more practice";


            break;
        }
        case 4:
        {
            /* Marks between 40-49 */



            cout << name << " Your Grade Is: E Need more practice";



            break;
        }
        default:
        {
            /* Marks less than 40 */


            cout << name << " You Grade Is: F or Fail\n";


        }
        }
    }
}
	
/////////  Bonus Exercise: SwitchGrade Calculator ///////////////
	
#include <iostream>
using namespace std;

int main()
{
	
	double myNum=20;
	
	while (myNum>0) {
		myNum = myNum - 0.5;
		cout << myNum << endl;
	}
	
}
	
////////////  REMAIN POSITIVE /////////////
	
	
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
	
//////////////// Reverse 9 /////////////
	

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
	
/////////////  The Pointless box ///////////
	
	
#include <iostream> 
using namespace std; 
int main() {

char input;  
do {
	cout << "Would you like to Quit (Y/N)?" << endl;
	cin >> input;
	
} 
while ((input != 'Y') && (input != 'y') );

return 0;
}
	
////////////  Input improvement ///////////////////
	
#include <iostream>
using namespace std;
int main()
{
	string password = "246"; 
	string userInput;
	


	while (userInput != password)
	{
		cout << "Enter the pass code for the safe" << endl;
		cin >> userInput;

	}
	//to print the ran out of message only if the password was not found within 5 attempts
	cout << "You found the code";
}
	
//////////// Brute-Force Attack //////////////
	
#include <iostream>
using namespace std;
int main()
{
	string password = "246";
	string userInput;
	int x = 5;
	cout << "You will only have 5 attempts" << endl;


	while (x > 0)
	{
		cout << "Enter the pass code for the safe" << endl;
		cin >> userInput;
		if (userInput == password)
		{
			cout << "You have finally unlocked the safe" << endl;

			break;
		}
		else
			x--;
	}
	//to print the ran out of message only if the password was not found within 5 attempts
	if (x == 0)
	{
		cout << "You ran out of attempts" << endl;
	}
}
	
////////////  Brute-Force Attack II /////////////////

#include <iostream>  
using namespace std; 
int main() {

	int myInt = 0, counter;
	cout << "Enter a number\n";
	cin >> counter;
	do
	{
		cout << myInt << endl;
		myInt++;

	} while (myInt<=counter);

}
				 
//////////  Loopy ////////////

#include <iostream>
#include <string>
using namespace std;
int main()
{
cout << " **********A program that counts up from 0 to 50 in increments of 1**********\n";
for (int x=0; x<51; x++)
{
	cout << x << endl;
}
cout << endl;
cout << " **********A program that counts down from 50 to 0 in decrements of 1**********\n";
for (int x = 50; x >= 0; x--)
{
	cout << x << endl;
}
cout << endl;
cout << " **********A program that counts up from 30 to 50 in increments of 1**********\n";
for (int x = 30; x < 51; x++)
{
	cout << x << endl;
}

cout << " **********A program that counts down from 50 to 10 in decrements of 2**********\n";
for (int x = 50; x > 11; x=x-2)
{
	cout << x << endl;
}

cout << " **********A program that counts up from 100 to 200 in increments of 5**********\n";
for (int x = 100; x < 201; x = x + 5)
{
	cout << x << endl;
}
}
			 
////////////  Some counting ///////////
			 
#include <iostream>
#include <string>
using namespace std;
int main()
{
	for (int x = 20; x <= 24; x++)
	{
		if (x %2==0)
			cout << x << " - even" << "\n";
		else
			cout << x << " - odd" << "\n";
	}

}
						 
///////////  Odd or Even  //////////////
				
#include <iostream>
#include <string>
using namespace std;
int main()
{
	for (int x = 0; x < 4; x++)
	{
		string myWord = "ARSH";
		cout << myWord.at(x) << endl;
	}

}
					    
////////////  Iterate through a word  ////////////
					    
#include <iostream>
#include <string>
using namespace std;
int main()
{
	for (int i = 0; i < 7; i++)
	{ 
		for (int j = 0; j < 7; j++)
		{
			cout << "*";
		}
		cout << endl;
	}


}
	
/////////////  Seven Stars, Seven Lines //////////////
	
#include <iostream>
#include <string>
using namespace std;
int main()
{
	for (int i = 1; i <= 5; i++)
	{ 
		for (int j = 1; j <= i; j++)
		{
			cout << "*";
		}
		cout << endl; 
	}


}
	
//////////  Descending Stars, Seven Lines /////////////
	
#include <iostream>
#include <string>
using namespace std;
int main()
{
	for (int i = 1; i <= 5; i++)
	{
		for (int j = 1; j <= i; j++)
		{
			cout << "*";
		}
		cout << endl;
	}


}
	
/////////// Rising Stars, Five Lines /////////////
	
#include <iostream>
#include <string>
using namespace std;
int main()
{
	for (int i = 1; i <= 5; i++)
	{ 
		for (int j = 1; j <= i; j++)
		{
			cout << "*"; 
		}
		cout << endl; 
	}


	for (int i = 1; i <= 5; i++) {
		for (int j = i; j <= 5; j++) {
			cout << "*";
		}
		cout << endl;
	}


}
	
//////// Rising and Falling Stars ///////////
	
#include <iostream>
#include <string>
using namespace std;
int main()
{
	int r;
	cout << "Enter a number to find the cube" << endl;
	cin >> r;
	for (int x = 1; x <= r; x++)
	{
		cout << "\nNumber is " << x << " the cube is ";
		int y = x;
		y = y * y * y;
		cout << y;
	}

}
			 
/////////// Cubes ////////////
			 
#include <iostream>
#include <string>
using namespace std;
int main()
{
	int sum = 0;
	
	for (int x = 100; x <= 200; x++)
	{
		if (x % 9 == 0)
		{
			cout << "\nNumber is " << x << endl;
					
			sum = sum + x;
		
					}
		
		
	}
	cout << "The sum is " << sum << endl;
}
					    
////////////  9s ////////////////
					    
#include <iostream>
#include <string>
using namespace std;
int main()
{
	int i = 1, j = 1;
	while (i <= 5)
	{
		j = 1;
		while (j <= i)
		{
			cout << "*";
			j++;
		}
		cout << endl;
		i++;
	}

}
	
/////////  Rising Star's ////////
	
#include <iostream>
#include <string>
using namespace std;
int main()
{
	int i = 1, j = 1;
	while (i <= 5)
	{
		j = i;
		while (j <= 5)
		{
			cout << "*";
			j++;
		}
		cout << endl;
		i++;
	}

}
	
///////// Falling Star's//////////
	
#include <iostream>
#include <string>
using namespace std;
int main()
{
    cout << "Enter the number for factorial\n";
    double x, fact=1;
    cin >> x;
    for (int y = x; y > 0; y--)
    {
       fact = y*fact;
    }
    cout << "The factorial is: " << fact;
}
//////////// Factorial ///////////
	
#include <iostream>
#include <string>
using namespace std;
int main()
{
	int x=100, sum = 0;
	do
	{
	
		if (x % 9 == 0)
		{
			cout << "\nNumber is " << x << endl;

			sum = sum + x;

		}
		x++;

	} while (x <= 200);

	cout << "The sum is " << sum << endl;
}
					    
/////////// 9s ////////////
					    
#include <iostream>
#include <string>
using namespace std;
int main()
{
	int y;
	cout << "Enter a number you want the table of: " << endl;
	cin >> y;
	while (cin.fail())
	{
		cout << "Invalid command enter the numbers again: " << endl;
		cin.clear();
		cin.ignore(1000, '\n');
		cin >> y;
	}
	for (int x=0; x<= 10; x++)
	{
		cout << y << " x " << x << " = " << y * x << endl;
		
	}

}

/////////   For Loop Table ///////////
								 
#include <iostream>
#include <string>
using namespace std;
int main()
{
	int y, x = 0;
	cout << "Enter a number you want the table of: " << endl;
	cin >> y;
	while (cin.fail())
	{
		cout << "Invalid command enter the number again: " << endl;
		cin.clear();
		cin.ignore(1000, '\n');
		cin >> y;
	}
	while (x <= 10)
	{
		cout << y << " x " << x << " = " << y * x << endl;
		x++;
	}

}
								 
///////////   while loop Table //////////
								 
#include <iostream>
#include <string>
using namespace std;
int main()
{
	int x;
	cout << "Enter a number you want the table of:" << endl;
	cin >> x;
	while (cin.fail())
	{
		cout << "Invalid command enter the numbers again: " << endl;
		cin.clear();
		cin.ignore(1000, '\n');
		cin >> x;
	}
	int y;
	cout << "Enter a number till which number you want it to be printed example 10 etc.: " << endl;
	cin >> y;
	while (cin.fail())
	{
		cout << "Invalid command enter the numbers again: " << endl;
		cin.clear();
		cin.ignore(1000, '\n');
		cin >> y;
	}
	for (int z=0; z<=y; z++)
	{
		cout << x << " x " << z << " = " << x * z << endl;
		
	}

}

////////////// For Loop Table ////////////
								 
								 
#include <iostream>
#include <string>
using namespace std;
int main()
{
    string months[12] = { "January", "February", "March","April","May","June","July","August","September","October","November","December" };

    for (int i = 0; i < 12; i++)
    {
        cout << months[i] << endl;
    }
}
				 
////////// Months ////////////
				 
#include <array>
#include <string>
#include <algorithm>
using namespace std;
#include <iostream>

int main()
{
    cout << "Hello User!\nEnter marks for five subjects";
    int marks[5];
    int sum = 0;
    for (int i = 0; i < 5; i++)
    {
        cout << "\nInput the subject marks" << endl;
        cin >> marks[i];
        while (cin.fail() || marks[i] > 100 || marks[i] < 0) {
            cout << "invalid command, enter the marks again\n";
            cin.clear();
            cin.ignore();
            cin >> marks[i];
        }

        sum = sum + marks[i];
    }
    cout << "\nYour average is: " << sum / 5 << endl;
}
	
//////////  Marks  ////////////
	
#include <iostream>
#include <string>
using namespace std;
int main()
{
	string snacks[5][5] = {
		{"_","_","_","_","_"},
	{"_", "O", "_", "O", "_"},
	{"_", "@", "@", "@", "_"},
	{"_", "^", "^", "^", "_"},
	{"_", "V", "V", "V","_" }
	};

	for (int x = 0; x < 5; x++)
	{
		cout << endl;
		for (int y = 0; y < 5; y++)
			cout << snacks[x][y];
	}
	cout << endl;
}
	
/////////// ArrayArt ///////////
	
#include <iostream>
#include <string>
using namespace std;
int main()
{
    int courses[5];

    for (int i = 0; i < 5; i++) {
        cout << "Input the " << i + 1 << " number" << endl;
        cin >> courses[i];
        while (cin.fail()) {
            cout << "invalid command, enter the number again\n";
            cin.clear();
            cin.ignore();
            cin >> courses[i];
        }
    }
    cout << "the numbers are: \n";
    for (auto course : courses) {
        cout << course << endl;
    }


}

///////////  Input / OutputArray /////////////
	
#include <iostream>
#include <string>
#include <algorithm>
#include <exception>
#include <array>
#include <random>
using namespace std;

int main()
{
	int sum = 0;
	
	srand(7);
	array<int, 1000> randomArry;
	for (int i = 0; i < 1000; i++)
	{

		randomArry[i] = rand() % 50;
		cout << randomArry[i] << ",";
		if (randomArry[i] == 6)
			sum++;
	}
	cout << "The number 6 appeared: " << sum << " times" << endl;
}
					
////////////////  random numbers ////////////////
								    
#include <iostream>
#include <array>
#include <algorithm>
#include <string>
using namespace std;

int main()
{
    int i;
    double x = 0, arr[10];
    cout << "Enter total number of elements(1 to 10): \n";
    for (i = 0; i < 10; i++)
    {
        cout << "Enter Number " << i + 1 << " : ";
        cin >> arr[i];

        while (cin.fail())
        {
            cout << "Incorrect command, kindly enter the number again ";
            cin.clear();
            cin.ignore(1000, '\n');
            cin >> arr[i];
        }
    }
    for (i = 0; i < 10; ++i)
    {

        if (x < arr[i])
            x = arr[i];
    }
    cout << "Largest element = " << x;

    return 0;
}
	
//////////// Largest NO. //////////////
	
#include <iostream>
#include <array>
#include <algorithm>
#include <string>
using namespace std;

int main()
{
    int i;
    double x = 0, arr[10];
    cout << "Enter total number of elements(1 to 10): \n";
    for (i = 0; i < 10; ++i)
    {
        cout << "Enter Number " << i + 1 << " : ";
        cin >> arr[i];

        while (cin.fail())
        {
            cout << "Incorrect command, kindly enter the number again ";
            cin.clear();
            cin.ignore(1000, '\n');
            cin >> arr[i];
        }
    }
    x = arr[0];
    for (i = 0; i < 10; i++)
    {

        if (x > arr[i])
            x = arr[i];
    }
    cout << "Smallest element = " << x;

    return 0;
}
	
//////////   smallest NO. ///////////
	
#include <iostream>
#include <string>
#include <math.h>
using namespace std;
int main()
{
	cout << "Enter a number you want the square root and cube root of" << endl;
	int x;
	cin >> x;
	while (cin.fail())
	{
		cout << "Invalid command enter the numbers again: " << endl;
		cin.clear();
		cin.ignore(1000, '\n');
		cin >> x;
	}

	cout << "The square-root of "<<x <<" is " << sqrt(x) << endl;
	cout << "The cube-root of " << x << " is " << cbrt(x) << endl;
	//cout << "The cube-root of "<< x << " is " << pow(x, 0.333333333333333) << endl;
	//cout << "The square-root of "<< x << " is " << pow(x, 0.5) << endl;
	return 0;
}
	
/////////// Square and Cube root  //////////////
	

#include <iostream>
#include <string>
#include <array>
#include <algorithm>
using namespace std;

void welcome();
void bye();

int main()
{
    welcome();
    bye();
    return 0;
}


void welcome()
{
    cout << "Hello there\n";
}

void bye()
{
    cout << "See you later\n";
}
	
//////// Function 1 //////////
	
#include <iostream>
#include <string>
#include <math.h>
#include <cmath>
using namespace std;

string message(double num)
{

	cout << "\n\nThe rooth from 1-10 is: " << endl;
	double y = 1;
	do
	{
		cout << y << " root value for " << num << " is: ";
		double x = 1 / y;
		double r = pow(num, x);
		cout << r << endl;
		y++;
	} while (y != 11);

	return "********END OF THE CODE*******";
}

int main()
{

	int num, fact = 1;

	cout << "Enter a number you want the root value from 1-10: " << endl;
	cin >> num;

	while (cin.fail())
	{
		cout << "Invalid command enter the numbers again: " << endl;
		cin.clear();
		cin.ignore(1000, '\n');
		cin >> num;
	}


	cout << message(num) << endl;

	return 0;

}
	
//////////// Exercise function Root ////////////
	
#include <iostream>
#include <string>
#include <math.h>
#include <cmath>
using namespace std;

string message(double num)
{

	cout << "\n\nThe exponent from 1-10 is: " << endl;
	double y = 1;
	do
	{
		cout << y << " exponent value for " << num << " is: ";

		cout << pow(num, y) << endl;
		y++;
	} while (y != 11);

	return "********END OF THE CODE*******";
}

int main()
{

	int num, fact = 1;

	cout << "Enter a number you want the exponent value from 1-10: " << endl;
	cin >> num;

	while (cin.fail())
	{
		cout << "Invalid command enter the numbers again: " << endl;
		cin.clear();
		cin.ignore(1000, '\n');
		cin >> num;
	}


	cout << message(num) << endl;

	return 0;

}
	
/////////// Exercise function exponent value ///////////

	
	
#include<iostream>
#include<iomanip>
using namespace std;
void CoffeeMenu();
void TeaMenu();
int main()
{
    int Option, Amount, ReadyMoney = 0;
    char Answer;
    string Sugar;
    cout << "What drink you are thinking to drink today?\n1. Coffee\n2. Tea\n=> ";
    cin >> Option;
    while (cin.fail() || (Option != 1 && Option != 2))
    {
        cin.clear();
        cin.ignore(1000, '\n');
        cout << "kindly try again to help better, please.\nOnly 1 or 2: ";
        cin >> Option;
    }
    if (Option == 1)
    {
        CoffeeMenu();
    }
    else
    {
        TeaMenu();
    }
    cout << "Enter 'I' for Ice, 'M' for Milk, and 'B' for Black: ";
    cin >> Answer;
    while (cin.fail() || (Answer != 'I' && Answer != 'M' && Answer != 'B' && Answer != 'i' && Answer != 'm' && Answer != 'b'))
    {
        cin.clear();
        cin.ignore(1000, '\n');
        cout << "kindly try again to help better, please.\nOnly I, M, or B: ";
        cin >> Answer;
    }
    cout << "Kindly enter the amount over here please: ";
    cin >> Amount;
    while (cin.fail() || Amount < 1)
    {
        cin.clear();
        cin.ignore(1000, '\n');
        cout << "kindly try again to help better, please.\nTry again: ";
        cin >> Amount;
    }
    ReadyMoney = Amount;
    switch (Answer)
    {
    case 'i':
    case 'I':
    {
        Amount -= 3;
        break;
    }
    case 'm':
    case 'M':
    {
        Amount -= 2;
        break;
    }
    case 'b':
    case 'B':
    {
        Amount -= 1;
        break;
    }
    default:
    {
        break;
    }
    }
    if (Amount >= 0)
    {
        cout << "Do you like to add some sugar to the drink that you will drink? (Yes/No): ";
        cin >> Sugar;
        do
        {
            for (int i = 0; i < Sugar.length(); i++)
            {
                Sugar[i] = tolower(Sugar[i]);
            }
            while (Sugar != "yes" && Sugar != "no")
            {
                cin.clear();
                cin.ignore(1000, '\n');
                cout << "kindly try again to help better, please.\nTry again: ";
                cin >> Sugar;
            }
        } while (Sugar != "yes" && Sugar != "no");
        cout << "Here's your change of your drink for the drink that you prefer for your Goodtoday: " << Amount << " DHS" << endl;
    }
    else
    {
        cout << "Sorry seem that you don't have enough money\nHere's your money: " << ReadyMoney << " DHS" << endl;
    }
    return 0;
}
void CoffeeMenu()
{
    string Coffee[6] = { "Ice Coffee","3 DHS","Milk Coffee","2 DHS","Black Coffee","1 DHS" };
    for (int i = 0; i < 6; i += 2)
    {
        cout << setw(5) << Coffee[i] << setw(9) << Coffee[i + 1] << endl;
    }
}
void TeaMenu()
{
    string Tea[6] = { "Ice Tea","3 DHS","Milk Tea","2 DHS","Black Tea","1 DHS" };
    for (int i = 0; i < 6; i += 2)
    {
        cout << setw(5) << Tea[i] << setw(9) << Tea[i + 1] << endl;
    }
}
	
//////////////////  S3 Final Submission Code ////////////////////
