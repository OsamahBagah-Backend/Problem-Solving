# problem(33)

**المستوى:** Easy Problems

هذا الكود يتحقق مما إذا كانت المصفوفة المدخلة متناظرة (تقرأ بنفس الترتيب من البداية والنهاية).  
يحل مشكلة تحديد إذا ما كانت البيانات تشكل متوالية متناظرة (Palindrome) في المصفوفات أحادية البعد.

السطر الأول يشرح عملية التحقق من التناظر في عناصر المصفوفة  
السطر الثاني يوضح تطبيقاته في تحليل التسلسلات الرقمية واللغوية المتناظرة

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
 
bool check_of_array(int arr[], int num)
{
	bool check = false;
	int count = num;
	for (int i = 0; i < num; i++)
	{
		if (arr[i] == arr[count - 1])
		{
			check = true;
		}

		else
		{
			return false;
		}

		count--;
	}

	return check;
}

void print_array1(int arr1[], int num)
{
	cout << "array 1 elemnet :";
	for (int i = 0; i < num; i++)
	{
		cout << arr1[i] << " ";
	}

}

void print(int arr[], int num)
{
	if (check_of_array(arr, num))
	{
		cout << "\nthe array is polynomeil \n";
	}

	else
	{
		cout << "\nthe array is not polynomeial \n";
	}
}

int main()
{
	srand((unsigned)time(NULL));
	int arr1[100];
	int N = readNumber("please enetr the element :");
	fill_array1(arr1, N);
	print_array1(arr1, N);
	print(arr1, N);

	return 0;
}*/
```