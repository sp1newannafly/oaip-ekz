1.	На биржевых торгах за 1 фунт стерлингов давали $1.487, за франк – $0.172, за немецкую марку – $0.584, а за японскую йену – $0.00955. 
Напишите программу, которая запрашивает денежную сумму в долларах, а затем выводит эквивалентные суммы в других валютах
#include <iostream>

using namespace std;

int main() {

	setlocale(0, "Russian");
	float dollar, funt, frank, germark, yen;
	
	cout << "\nВведите количество в Долларах:";
	cin >> dollar;
	funt = dollar * 1.487;
	frank = dollar * 0.172;
	germark = dollar * 0.584;
	yen = dollar * 0.00955;

		cout << "Эквалетная сумма в фунтах: " << funt << endl;
		cout << "Эквалетная сумма в франках: " << frank << endl;
		cout << "Эквалетная сумма в нем.марках: " << germark << endl;
		cout << "Эквалетная сумма в енах: " << yen << endl;

	return 0;
  
