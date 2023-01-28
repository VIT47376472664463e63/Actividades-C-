# Actividades-C-
Menú con muchas funciones 

____________________________________________________________________CODIGO___________________________________________________________________________________________
#include <iostream>
using namespace std;
int opcion;

int main()
{
	string g;

	//Ingresa 3 numeros
	double a, b, n;
	//Numero mayor entre dos numeros 
	double c, d;
	// area de un triangulo 
	double u, j;
	// Bisiesto
	int t;

	// Semana
	int m;





	while (1 == 1)
	{

		cout << "------MENU------" << endl;
		cout << "1 Ingresa 3 numeros " << endl;
		cout << "2 Numero mayor entre dos numeros   " << endl;
		cout << "3 area de un triangulo   " << endl;
		cout << "4 Bisiesto " << endl;
		cout << "5 Semana" << endl;
		cout << "6 Salir" << endl;
		cout << "Eliga una opcion" << endl;
		cin >> opcion;
		cin.ignore();

		switch (opcion)
		{
		case 1:

			cout << "Ingresa tu primer numero" << endl;
			cin >> a;
			cout << "Ingresa tu segundo numero" << endl;
			cin >> b;
			cout << "Ingresa tu tercer numero" << endl;
			cin >> n;

			cout << "tu resultado es  " << a + b + n;
			cout << "\n" << endl;
			cin.ignore();
			break;

		case 2:
			cout << "Ingresa tu primer numero" << endl;
			cin >> c;
			cout << "Ingresa tu segundo numero" << endl;
			cin >> d;

			if (c > d) {
				cout << "el numero mayor es " << c;

			}

			if (d > c) {
				cout << "el numero mayor es " << d;

			}
			cout << "\n" << endl;
			break;

		case 3:

			cout << "Ingresa tu Base" << endl;
			cin >> u;
			cout << "Ingresa tu Altura" << endl;
			cin >> j;

			cout << "el resultado es " << u * j / 2;
			cout << "\n" << endl;
			break;

		case 4:
			cout << "Ingresa tu numero" << endl;
			cin >> t;
			if (t % 4== 0) {
				cout << "Este numero es bisiesto" << endl;
				cout << "\n" << endl;

			
			}
			else {
				cout << "Este numero no es bisiesto" << endl;
				cout << "\n" << endl;
			}

			break;

		case 5:
			cout << "Ingresa tu del 1 al 7" << endl;
			cin >> m;
			if (m > 7) {
				cout << "tienes que elegir un numero entre 1 y 7" << endl;
				cout << "\n" << endl;
			}
			if (m < 0) {
				cout << "tienes que elegir un numero entre 1 y 7" << endl;
				cout << "\n" << endl;
			}

			if (m == 1) {
				cout << "Lunes" << endl;
				cout << "\n" << endl;
			}

			if (m ==2 ) {
				cout << "Martes" << endl;
				cout << "\n" << endl;
			}

			if (m == 3) {
				cout << "Miercoles" << endl;
				cout << "\n" << endl;
			}

			if (m == 4) {
				cout << "Jueves" << endl;
				cout << "\n" << endl;
			}

			if (m == 5) {
				cout << "Viernes" << endl;
				cout << "\n" << endl;
			}

			if (m == 6) {
				cout << "Sabado" << endl;
				cout << "\n" << endl;
			}

			if (m == 7) {
				cout << "Domingo" << endl;
				cout << "\n" << endl;
			}
			break;

		
		case 56:
			exit(EXIT_SUCCESS);
			break;

		default:
			break;
		}


	}
	return 0;
}

