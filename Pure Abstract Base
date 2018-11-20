# Brian1030
//Using Header Files
///////////////////////////////////////////////////main.h///////////////////////////////////////////////////
#include<iostream>
#include "BasicShape.h"
#include "Circle.h"
#include "Rectangle.h"
using namespace std;

int main()
{
	double cordinateX;
	double cordinateY;
	double rad;
	
	//get the width, length, and height of the circle form user
	
	
// Get the X coor, Y coor, and Radius of
   // the circle from the user.
   cout << "\nEnter the dimensions of a Circle:\n";
   cout << "Enter X corrdinate Circle center: ";
   cin >> cordinateX;
   cout << "Enter Y corrdinate Circle center: ";
   cin >> cordinateY;
   cout << "Enter Radius: ";
   cin >> rad;

   // Define a Circle object and use the dimensions
   // entered by the user.
   circle circ(cordinateX, cordinateY, rad);

   // Display the Circle's object's properties.
   cout << "\nHere are the Circles's properties:\n";
   cout << "Circle area is: " << circ.calcArea() << endl;

//  Rectangle input

   double rectangleWidth;   // To hold the rectangle's width
   double rectangleLength;  // To hold the rectangle's length

   // Get the width, length, of the
   // the rectangle from the user.
   cout << "\nEnter the dimensions of a Rectangle:\n";
   cout << "Enter Width: ";
   cin >> rectangleWidth;
   cout << "Enter Length: ";
   cin >> rectangleLength;
   
   // Define a Rectangle object and use the dimensions
   // entered by the user.
   rectangle myRectangle(rectangleWidth, rectangleLength );
   // Display the Rectangles object's properties.
   cout << "\nHere are the Rectangles's properties:\n";
   cout << "Width is: " << myRectangle.getWidth() << endl;
   cout << "Length is: " << myRectangle.getLength() << endl;
   cout << "Retangle area is: " << myRectangle.getArea() << endl; 
   

cout << "\nEnd of program." << endl;
//system ("pause");
cin.get();
cin.get();
   return 0;
}//end of main*

/////////////////////////////////////////////////////////////Rectangle.h////////////////////////////////////////////////////////////////
#ifndef Rectangle
#define Rectangle

class rectangle
{
	private:
		double width;
		double length;
	public:
		//default constructor
		rectangle()
		{ width = 0.0;
		  length = 0.0;}
		  
		  //constructor
		  rectangle(double w, double len)
		  {width = w;
		  length = len; }
		  
		  double getWidth()const
		  {return width; }
		  
		  double getLength()const
		  {return length;}
		  
		  double getArea() const
		  {return width * length; }
		  	  
};
#endif
////////////////////////////////////////////////////////////////Circle.h////////////////////////////////////////////////////////////
#ifndef Circle
#define Circle
using namespace std;

class circle
{
private:
	long circleX;
	long circleY;
	double radius;
	
	public:
		circle(long cordinateX, long cordinateY, double rad)
		{
			circleX = cordinateX;
			circleY = cordinateY;
			radius = rad;
		}
		
		double calcArea()
		{
			return 3.14159 * radius * radius;
		}
		
};
#endif
/////////////////////////////////////////////////////////BasicShape.h///////////////////////////////////////////////////////////////
#ifndef BasicShape
#define BasicShape
#include <iostream>
#include <string>
using namespace std;


class Basicshape
{
	private:
	    double area; 
	    double calcArea;
	
	public:
	getArea()
	{ area = 0.0;
	calcArea = 0.0;}
	
	//constructor 
	Basicshape(double a, double c)
	{ area = a;
	calcArea = c;}
	
	double getarea()const
	{return area; }
	
	double getcalc()const
	{return calcArea; }
	
	double getArea()const
	{return area * calcArea;}
};
#endif
