#include<iostream>
#include<conio.h>
using namespace std;
int Gcd(int,int);
int main()
{
	int a,b,total;
	cout << "Enter  number  : ";
	cin >> a;
	cin >> b;
	total= Gcd(a,b);
	cout << total;
	_getch();

}int Gcd(int a,int b) {
	
	if (b == 0) {
		return a;
	} 
	else if (b != 0) {
	

		return Gcd(b, a%b);
	}
	


}
