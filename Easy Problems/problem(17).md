# problem(17)

**المستوى:** Easy Problems

هذا الكود ينشئ مصفوفة بأعداد عشوائية ثم يبحث عن أصغر قيمة فيها بناءً على حجم المدخلات.
يحل مشكلة تحديد القيمة الصغرى في مجموعة بيانات عشوائية بكفاءة لأغراض التحليل السريع.

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

void fill_array(int arr[], int num)
{
	for (int i = 0; i < num; i++)
	{
		arr[i] = randNumber(1, 100);
	}
}

int Min_number(int arr[], int count)
{
	int first = arr[0];
	int min = 0;

	for (int i = 0; i < count; i++)
	{
		if (first < arr[i])
		{
			min = first;
		}

		else
		{
			first = arr[i];
			min = first;
		}
	}

	return min;
}

void print_array(int arr[], int num)
{
	cout << "array elemnet :";
	for (int i = 0; i < num; i++)
	{
		cout << arr[i] << " ";
	}

}

int main()
{
	srand((unsigned)time(NULL));
	int arr[100];
	int N = readNumber("please enetr the element :");
	fill_array(arr, N);
	print_array(arr, N);

	cout << "\nthe mini number in array :" << Min_number(arr, N) << endl;
	return 0;
}*/

```cpp

```