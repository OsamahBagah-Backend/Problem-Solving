# problem(2)

**المستوى:** Easy Problems

هذا الكود يقوم بعكس أرقام العدد المدخل من قبل المستخدم ثم طباعتها بشكل منفصل. 
المشكلة التي يحلها هي عرض أرقام العدد بترتيب معكوس، مثل تحويل العدد 1234 إلى 4 3 2 1.

```cpp
int readPositiveNumber(string meesage)
{
	int num;
	do
	{
		cout << meesage << endl;
		cin >> num;

	} while (num <0);

	return num;
}

int gitTheRemaind(int num)
{
	int remaind = 0;
	int N =0;
	while (num !=0)
	{
		remaind = num % 10;
		N += remaind;
		N *= 10;
		num /= 10;
	}

	return (N/10);
}

void reversTheNumber(int num)
{
	int remaind2;
	while (num !=0)
	{
		remaind2 = num % 10;

		cout << remaind2 << endl;

		num /= 10;
	}
}

int main()
{
	int number = readPositiveNumber("please enter a bositive number :");

	reversTheNumber(gitTheRemaind(number));

	return 0;
}
```