# problem(31)

**المستوى:** Easy Problems

هذا الكود ينشئ مصفوفة عشوائية ثم يستخرج الأعداد الأولية منها إلى مصفوفة ثانية.  
يحل مشكلة تصفية الأعداد الأولية من مجموعة بيانات عشوائية بسرعة وكفاءة.

السطر الأول يوضح عملية الفحص الرياضي للأعداد الأولية  
السطر الثاني يبين فائدته في تحليل الخصائص العددية وتصنيف البيانات تلقائياً

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

void add_array(int arr[], int inde, int element)
{
	arr[inde] = element;
}

bool checkOfNumber(int num)
{
	//int c = 0;
	bool check = true;
	for (int i = 2; i < num; i++)
	{
		if (num % i == 0)
		{

			return false;
		}

		else
		{
			check = true;
		}
	}

	return check;
}


void fill_array2(int arr1[], int arr2[], int num, int& count)
{
	count = 0;
	for (int i = 0; i < num; i++)
	{
		if (checkOfNumber(arr1[i]) == true)
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