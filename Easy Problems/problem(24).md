# problem(24)

**المستوى:** Easy Problems

هذا الكود ينشئ مصفوفة عشوائية ثم ينشئ مصفوفة ثانية تحتوي على عناصر المصفوفة الأولى بترتيب عكسي.

يحل مشكلة الحاجة لعكس ترتيب عناصر المصفوفة، وهو أمر مفيد في معالجة البيانات والخوارزميات التي تتطلب التكرار العكسي.

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
		arr1[i] = randNumber(1, num);
	}
}

void fill_array_2(int arr1[], int arr2[], int num)
{
	int a = 0;
	for (int i = num; i >= 0; i--)
	{
		arr2[a] = arr1[i-1];
		a += 1;
	}
}

void print_array1(int arr1[], int num)
{
	for (int i = 0; i < num; i++)
	{
		cout << arr1[i] << " ";
	}

}

void print_array2(int arr2[], int num)
{
	for (int i = 0; i < num; i++)
	{
		cout << arr2[i] << " ";
	}

}

int main()
{
	srand((unsigned)time(NULL));

	int arr1[100];
	int arr2[100];
	int N = readNumber("please enter the element number :");

	fill_array1(arr1, N);
	fill_array_2(arr1,arr2 ,N);

	cout << "\n the array elemnt \n";
	print_array1(arr1, N);

	cout << "\n\nthe array elemnt after his copy in revers order \n";
	print_array2(arr2, N);

	return 0;
}*/
```