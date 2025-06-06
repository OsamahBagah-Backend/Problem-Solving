# problem(19)

**المستوى:** Easy Problems

هذا الكود ينشئ مصفوفة بأرقام عشوائية ويحسب متوسط قيم عناصرها بناءً على عدد العناصر المحدد من المستخدم. 

يحل مشكلة حساب المتوسط الحسابي لمجموعة بيانات بشكل تلقائي دون الحاجة لإجراء العمليات الحسابية يدوياً.

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
	int average = 0;
	int count = 0;
	for (int i = 0; i < num; i++)
	{
		count += arr[i];
	}
	average = (count / num);
	return average;
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

	cout << "\nthe average of array is :" << sum_array(arr, N) << endl;
	return 0;
}*/

```cpp

```