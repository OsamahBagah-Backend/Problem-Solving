# problem(32)

**المستوى:** Easy Problems

هذا الكود ينشئ مصفوفتين ويقوم بإزالة التكرارات من المصفوفة الأولى لحفظ القيم الفريدة في المصفوفة الثانية.  
يحل مشكلة تنقية البيانات من القيم المكررة للحصول على مجموعة عناصر فريدة.

السطر الأول يوضح آلية تصفية العناصر المكررة  
السطر الثاني يبين أهميته في تحسين جودة البيانات وإزالة التكرارات غير المرغوب فيها

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

bool serch2(int arr[], int num, int num2)
{

	for (int i = 0; i < num2; i++)
	{
		if (arr[i] == num)
		{
			return true;
		}


	}

	return false;
}

void fill_array1(int arr1[], int num)
{
	int element;
	for (int i = 0; i < num; i++)
	{
		cout << "enter the element :";
		cin >> element;
		arr1[i] = element;
	}
}

void add_array(int arr[], int inde, int element)
{
	arr[inde] = element;
}

void fill_array2(int arr1[], int arr2[], int num, int& count)
{
	
	for (int i = 0; i < num; i++)
	{
		if (serch2(arr2, arr1[i], count))
		{
			continue;
		}

		else
		{
			add_array(arr2, count, arr1[i]);
			count++;
		}
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

void print_array2(int arr2[], int num)
{
	cout << "\narray 2 elemnet Prime:";
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
	int count = 0;
	int N = readNumber("please enetr the element :");
	fill_array1(arr1, N);
	fill_array2(arr1, arr2, N, count);
	print_array1(arr1, N);
	print_array2(arr2, count);

	return 0;
}*/
```