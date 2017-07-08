# Rectangle2D
Define the Rectangle2D class that contains:
■ Two double data fields named x and y that specify the center of the rectangle with constant get functions and set functions. 
(Assume that the rectangle sides are parallel to x- or y-axes.) 
■ The double data fields width and height with constant get functions and set functions. 
■ A no-arg constructor that creates a default rectangle with (0, 0) for (x, y) and 1 for both width and height. 
■ A constructor that creates a rectangle with the specified x, y, width, and height.
■ A constant function getArea() that returns the area of the rectangle. 
■ A constant function getPerimeter() that returns the perimeter of the rectangle.
■ A constant function contains(double x, double y) that returns true if the specified point (x, y) is inside this rectangle. 
■ A constant function contains(const Rectangle2D &r) that returns true if the specified rectangle is inside this rectangle. 
■ A constant function overlaps(const Rectangle2D &r) that returns true if the specified rectangle overlaps with this rectangle. 

A bounding rectangle is the minimum rectangle that encloses a set of points in a two-dimensional plane. 
Write a function that returns a bounding rectangle for a set of points in a two-dimensional plane, 
as follows: const int SIZE = 2; Rectangle2D getRectangle(const double points[][SIZE]); 
The Rectangle2D class is defined in Programming Exercise 11.9. 
Write a test program that prompts the user to enter five points and displays the bounding rectangle’s center, width, and height.

