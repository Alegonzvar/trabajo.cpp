Programa que indique si el numero es primo
*/

#include<istream>
using namespace std;
int main () {
	int num;
	int a=1;
	cout<<"ingrese un numero:\n";
	cin>>num;
	while (a<=num)
		if(num%a==0)
			cout<<"El numero es primo\n";
		else
			cout<<"El numero es primo\n";
		if (num==0)
	return 0;
}


/*
Programa...0 al 500
*/

#include<istream>
using namespace std;
int main () {
	int num;
	int a=1;
	cout<<"ingrese un numero:\n";
	cin>>num;
	if(num>50 and num <500)
		cout<<"Ganaste :)\n";
	else
		cout<<"Perdiste :()\n";
	return 0;
}
