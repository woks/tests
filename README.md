tests
=====

First repository

#include <iostream>

float metry;

float ile_cali(float m)
{
	return m*39.37;
}

float ile_jardow(float x)
{
	return x*1.0936;
}

void ile_mil(float m)
{
	cout << "na mile " << m*0.006231;
}

int main()
{
	using namespace std;

	cout << "Podaj metry\n";
	cin >> metry;
	cout << metry << "metry/ow to " << ile_cali(metry) << " cali";
	cout << "na jardy " << ile_jardow();
	ile_mil();
	
	cin.get();
	cin.get();
	return 0;


}
