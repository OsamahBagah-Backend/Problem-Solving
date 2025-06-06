# problem(22)

**المستوى:** Easy Problems

هذا الكود ينشئ ثلاث مصفوفات عشوائية ويجمع عناصر المصفوفتين الأولى والثانية في المصفوفة الثالثة.

يحل مشكلة الحاجة إلى إجراء عمليات حسابية على عناصر متعددة من مصفوفات مختلفة وتخزين النتائج في مصفوفة جديدة.

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
		arr1[i] = randNumber(1, 100);
	}
}

void fill_array2(int arr2[], int num)
{
	for (int i = 0; i < num; i++)
	{
		arr2[i] = randNumber(1, 100);
	}
}

void fill_array3(int arr1[],int arr2[] ,int arr3[], int num)
{
	for (int i = 0; i < num; i++)
	{
		arr3[i] = arr1[i] + arr2[i];
	}
}

void print_array1(int arr1[], int num)
{
	cout << "array 1 elemnet :";
	for (int i = 0; i < num; i++)
	{
		cout << arr1[i] << " ";
	}

}

void print_array_2(int arr2[], int num)
{
	cout << "\narray 1 elemnet :";
	for (int i = 0; i < num; i++)
	{
		cout << arr2[i] << " ";
	}

}

void print_array3(int arr3[], int num)
{
	cout << "\narray 1 elemnet :";
	for (int i = 0; i < num; i++)
	{
		cout << arr3[i] << " ";
	}
	cout << "\n";
}

int main()
{
	srand((unsigned)time(NULL));
	int arr1[100];
	int arr2[100];
	int arr3[100];
	int N = readNumber("please enetr the element :");
	fill_array1(arr1, N);
	fill_array2(arr2, N);
	fill_array3(arr1, arr2, arr3, N);
	print_array1(arr1, N);
	print_array_2(arr2, N);
	print_array3(arr3, N);
	

	return 0;
}*/
```