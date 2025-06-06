# problem(23)

**المستوى:** Easy Problems

هذا الكود ينشئ مصفوفة بأرقام متسلسلة ثم يقوم بخلطها عشوائياً لإنشاء ترتيب جديد.

يحل مشكلة الحاجة إلى توليد تبديلات عشوائية لمجموعة من الأرقام المتسلسلة دون تكرار، وهو مفيد في تطبيقات مثل ألعاب الورق أو اختبارات العينات العشوائية.

```cpp
/* int readNumber(string message)
{
	int num;
	do
	{
		cout << message << endl;
		cin >> num;

	} while (num <= 0);

	return num;

}

int randNumber(int from, int to)
{

	int randomNum = rand() % (to - from + 1) + from;

	return randomNum;
}

void fill_array1(int arr1[], int num)
{
	for (int i = 0; i < num; i++)
	{
		arr1[i] = i+1;
	}
}

void print_array1(int arr[], int num)
{
	for (int i = 0; i < num; i++)
	{
		cout << arr[i] << " ";
	}

}

void shift(int arr2[], int num)
{
	int check;
	for (int i = 0; i < num; i++)
	{

		check = randNumber(1, num);
		arr2[i] = check;
		
		for (int j = 0; j < num; j++)
		{
			while (arr2[j] == check)
			{
				check = randNumber(1, num);
				j = 0;
			}
		}

		arr2[i] = check;

	}
}

void print_shift(int arr2[], int num)
{
	for (int i = 0; i < num; i++)
	{
		cout << arr2[i] << " ";
	}

	cout << endl;
}

int main()
{
	srand((unsigned)time(NULL));
	int N = readNumber("please enter how element :");
	int arr[100];
	int arr2[100];
	fill_array1(arr, N);

	cout << "\nthe array befor sheft : ";

	print_array1(arr, N);
	shift(arr2, N);

	cout << "\nthe array after shaeft : ";

	print_shift(arr2, N);
}*/
```