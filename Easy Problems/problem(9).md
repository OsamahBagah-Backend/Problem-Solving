# problem(9)

**المستوى:** Easy Problems

هذا الكود يحاول كسر كلمة مرور مكونة من 3 أحرف إنجليزية كبيرة عن طريق تجربة كل التركيبات الممكنة. 
يحل مشكلة اختبار جميع الاحتمالات لإيجاد كلمة المرور الصحيحة بطريقة القوة الغاشمة (Brute Force).

/* string readTheBasoord(string meesage)
{
	string bassowrd;

	do
	{
		cout << meesage << endl;
		cin >> bassowrd;
	} while ((bassowrd[0] > char(90) || bassowrd[1] > char(90) || bassowrd[2] > char(90)) && bassowrd.length() ==2);

	return bassowrd;

}

bool printTheShape(string bassowrd)
{
	int sum = 0;
	string word = "";

	for (int i = 65; i <= 90; i++)
	{
	
		for (int j = 65; j <= 90; j++)
		{
			for (int k = 65; k <= 90; k++)
			{
				sum++;
				cout << "trial [" << sum << "] : " << char(i) << char(j) << char(k) << endl;
				word += char(i);
				word += char(j);
				word += char(k);
				
				if (bassowrd == word)
				{
					cout << "passowrd is " << bassowrd << endl;
					cout << "find after " << sum << " trials" << endl;
					return true;
				}

				word = "";
			}

		}
		
	}

	return false;
}

int main()
{
	printTheShape(readTheBasoord("please enter just three capital :"));

	return 0;

}*/

```cpp

```