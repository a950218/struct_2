# struct_2
DOODLE


#include <iostream>

using namespace std;

struct Point {
	int x;
	int y;
	void moveRight() {x++;}
	void moveLeft(){ x--; }
	void moveUp(){ y++; }
	void moveDown(){ y--; }
};

int main()
{
	Point p = { 2, 5 };
	p.moveDown();
	p.moveRight();

	cout << "("<<p.x << p.y << ")";
}
