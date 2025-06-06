# problem(3)

**المستوى:** Easy Problems

هذا الكود يتحقق مما إذا كان العدد المدخل **متناظرًا (Palindrome)** أي يقرأ بنفس الطريقة من اليمين لليسار والعكس (مثل 121). 
المشكلة التي يحلها هي تحديد إذا كان العدد يساوي قيمته المعكوسة أم لا.

```cpp
int readPositiveNumber(string meesage)
{
	int num;
	do
	{
		cout << meesage << endl;
		cin >> num;

	} while (num < 0);

	return num;
}

int gitTheRemaind(int num)
{
	int remaind = 0;
	int N = 0;
	while (num != 0)
	{
		remaind = num % 10;
		N += remaind;
		N *= 10;
		num /= 10;
	}

	return (N / 10);
}

void checkOfTheNumber(int num, int revers)
{
	if (num == revers)
	{
		cout << " its prosindeble number " << endl;
	}

	else
	{
		cout << " its not prosindeble number " << endl;
	}
}

int main()
{
	int N = readPositiveNumber("please enter positvie number :");

	checkOfTheNumber(N, gitTheRemaind(N));

	return 0;
}
```