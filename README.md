# GITHUBVS2013
#include <iostream>
#include<math.h>
using namespace std;

int main()

{
	int i, n, t = 1;
	int choice;
	double suma = 0;
	double k = -1;
	double s = 1;
	double w = 0;
	double denom = 0;
	cout << "Enter from 1 to 10\n";
	switch (choice)

	{

	case 1:
	{

		cin >> n;

	}

		for (i = 1; i <= n; i++)

		{

			suma = suma + 1 / i;

		}

		cout << suma;
		system("pause");
		return 0;
		break;

	case 2:
	{
		cin >> n;
	}

		for (i = 2; i <= n*n; i = 2 * i)

		{
			suma = suma + i;

		}

		cout << suma;
		system("pause");
		return 0;
		break;

	case 3:

	{

		cin >> n;

	}

		for (i = 1; i <= n; i++)

		{

			i = i*i;
			suma = suma + (1 + (1 / i));

		}

		cout << suma;
		system("pause");
		return 0;
		break;

	case 4:
		cin >> n;

		for (i = 1; i <= n; i++)

		{

			suma = suma + t / (i*(i + 1));

			t = -t;

		}

		cout << suma;
		system("pause");
		return 0;
		break;

	case 5:


		cin >> n;



		for (i = 1; i <= n; i++)

		{

			i = i*i*i*i*i;
			suma = suma + 1 / i;

		}

		cout << suma;
		system("pause");
		return 0;

		break;

	case 6:
	{

		cin >> n;

	}

		for (i = 1; i <= n; i++)

		{

			i = (2 * i + 1)*(2 * i + 1);
			suma = suma + 1 / i;

		}

		cout << suma;
		system("pause");
		return 0;
		break;

	case 7:
	{

		cin >> n;

	}

		for (i = 1; i <= n; i++)

		{

			suma = suma + t / (i * 2 + 1);
			t = -t;

		}

		cout << suma;
		system("pause");
		return 0;
		break;

	case 8:
		cin >> n;

		for (i = 0; i <= n; i++)

		{

			s = s*i;
			w = w + 1 / i;
			suma = suma + s/ w ;

		}

		cout << suma;
		system("pause");
		return 0;
		break;

	case 9:
		cin >> n;

		for (i = 0; i <= n; i++)

		{

			suma = sqrt(2 + suma);

		}

		cout << suma;
		system("pause");
		return 0;
		break;

	case 10:
		cin >> n;

		for (i = 1; i <= n; i++)

		{

			denom = denom + sin(i);
			suma = suma + 1 / denom;
		}

		cout << suma;
		system("pause");
		return 0;
		break;
	}
}
