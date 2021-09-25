# test1


#include <iostream>
#include <string>
using namespace std;
int main()
{
  cout << "Hello World!\n";
  double radius;
  cout << "Enter the radius to find the area of a circle \n";
  cin >> radius;
  double area = (22 / 7) * radius * radius;
  double cirm = (22 / 7) * 2 * radius;
  cout << "\n The area of the circle is: " << area << " \n The circumference of the circle is: " << cirm;

  cout << "\n Enter the length \n";
  double length, width;
  cin >> length;
  cout << "Enter the width \n";
  cin >> width;

  cout << "\n The area of the rectangle is:  " << (length * width) << " \n The area of square is: " << length * length << " \n The area of triangle is:  " << (1 / 2) * length * width;

}
