# Area-calulation-using c ++ function
#include<iostream>
using namespace std;
int area (int r)
{
	int z=2 * 3.14*r;
	return z;
}
void main()
{
	cout << "Area of given of circle : "<<	area(5)<<endl;
	system("pause");
}
