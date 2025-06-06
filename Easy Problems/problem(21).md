# problem(21)

**المستوى:** Easy Problems

هذا الكود ينشئ مصفوفة بأعداد عشوائية ثم يستخرج الأعداد الأولية منها إلى مصفوفة ثانية.  
يحل مشكلة تصفية الأعداد الأولية من مجموعة بيانات عشوائية بسرعة وكفاءة.  

السطر الأول يشرح عملية إنشاء المصفوفة واستخلاص الأعداد الأولية  
السطر الثاني يبين فائدة الكود في تحليل البيانات العددية وعزل الخصائص الرياضية المحددة

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

void fillThePrimeNumbers(int arr1[], int arr2[] ,int num , int &count)
{
	count = 0;
	for (int i = 0; i < num; i++)
	{

		if (checkOfNumber(arr1[i]) == true)
		{
			arr2[count] = arr1[i];
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

bool print_array2(int arr2[], int count)
{
	cout << "\narray 2 elemnet :";
	if (count == 0)
	{
		cout << "no prime element \n";
		return true;
	}
	else
	{
		for (int i = 0; i < count ; i++)
		{	
			cout << arr2[i] << " ";
		}
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
	fillThePrimeNumbers(arr1, arr2, N , count);
	print_array1(arr1, N);
	print_array2(arr2, count);
	//cout << count << "\n";

	return 0;
}*/
```