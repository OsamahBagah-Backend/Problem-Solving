# problem(18)

**المستوى:** Easy Problems

هذا الكود ينشئ مصفوفة بأعداد عشوائية ويحسب مجموع قيم عناصرها بناءً على حجم يحدده المستخدم.  
يحل مشكلة حساب المجموع الكلي لمجموعة بيانات عشوائية بشكل سريع ودقيق دون حسابات يدوية.

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

int sum_array(int arr[], int num)
{
	int count = 0;
	for (int i = 0; i < num; i++)
	{
		count += arr[i];
	}

	return count;
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

	cout << "\nthe sum of array is :" << sum_array(arr, N) << endl;
	return 0;
}*/

```cpp

```