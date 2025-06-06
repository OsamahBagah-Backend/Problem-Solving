# problem(1)

**المستوى:** Easy Problems

هذا الكود يحسب ويطبع تكرار كل رقم من 0 إلى 9 في العدد المدخل من قبل المستخدم. المشكلة التي يحلها هي تحديد عدد مرات ظهور كل رقم في العدد المعطى، 
مثل حساب تكرار الرقم 5 في العدد 1553 (وهو 2 في هذه الحالة).

```cpp
int readTheNumber(string message)
{
	int num;

	cout << message << endl;
	cin >> num;

	return num;
}

int frecuincy(int num , int frec)
{
	//int N = readTheNumber("please enter the number that you want his frecwency : ");
	int remaind = 0, sum = 0;
	int H = remaind;
	do {
		remaind = num % 10;
		num /= 10;
		if (remaind == frec)
		{
			sum++;
		}
	} while (num != 0 );

	return sum;
}

void printTheResult(int num)
{
	int N;
	for (int i = 0; i < 10; i++)
	{
		N = frecuincy(num, i);
		if (N > 0)
		{
			cout << "the number " << i << " his frecuncy is : " << N << endl;
		}
	}
	
	
}

int main()
{
	int a = readTheNumber("please enter number :");
	
	
	printTheResult(a);
	//string numbe = to_string(N);
	

	
	return 0;
}
```