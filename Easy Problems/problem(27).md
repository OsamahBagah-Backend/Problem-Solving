# problem(27)

**المستوى:** Easy Problems

هذا الكود ينشئ مصفوفة بأرقام عشوائية ويبحث عن رقم محدد فيها لمعرفة وجوده من عدمه.  
يحل مشكلة التحقق من وجود عنصر معين في مجموعة بيانات كبيرة بسرعة وكفاءة دون بحث يدوي.  

السطر الأول يشرح وظيفة الكود الأساسية في البحث والتحقق  
السطر الثاني يوضح فائدته في تحليل البيانات وتوفير الوقت في عمليات البحث

```cpp
/* int readNumber(string message)
{
	int num;
	do
	{
		cout << message << endl;
		cin >> num;

	} while (num < 0);

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

void print_array1(int arr1[], int num)
{
	for (int i = 0; i < num; i++)
	{
		cout << arr1[i] << " ";
	}

	cout << endl;
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

void finish(int arr[], int search, int N)
{
	if (serch2(arr, search, N))
	{
		cout << "the number is fond \n";
	}

	else
	{
		cout << "the number its not fond :)" << endl;
	}
}

int main()
{
	srand((unsigned)time(NULL));
	int arr[100];
	int N = readNumber("please the number of element :");

	fill_array1(arr, N);
	cout << "\nthe array element\n";
	print_array1(arr, N);

	int search = readNumber("enetr the number to search :");

	cout << "the number you are locking for :" << search << endl;
	finish(arr, search, N);

	return 0;
}*/
```