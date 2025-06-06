# problem(30)

**المستوى:** Easy Problems

هذا الكود ينشئ مصفوفة عشوائية ثم يستخرج الأعداد الفردية منها إلى مصفوفة ثانية.  
يحل مشكلة تصفية الأعداد الفردية من مجموعة بيانات عشوائية بسرعة ودقة.

السطر الأول يوضح عملية التصفية التلقائية للأعداد الفردية  
السطر الثاني يبين فائدته في تحليل البيانات العددية وعزل الخصائص الرياضية

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


void fill_array2(int arr1[], int arr2[], int num , int &count)
{
	count = 0;
	for (int i = 0; i < num; i++)
	{
		if (arr1[i] % 2 != 0)
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
	cout << "\narray 2 elemnet Odd:";
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
	fill_array2(arr1, arr2, N,count);
	print_array1(arr1, N);
	print_array2(arr2, count);

	return 0;
}*/
```