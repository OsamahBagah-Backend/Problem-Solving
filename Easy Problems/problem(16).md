# problem(16)

**المستوى:** Easy Problems

هذا الكود ينشئ مصفوفة بأعداد عشوائية ويحدد أكبر قيمة فيها بناءً على حجم يحدده المستخدم.  
يحل مشكلة الحاجة لتحديد القيمة القصوى في مجموعة بيانات عشوائية بسرعة وكفاءة.  

السطر الأول يشرح الوظيفة الأساسية للكود (إنشاء مصفوفة عشوائية وإيجاد القيمة العظمى)  
السطر الثاني يوضح الغرض من الكود (تلبية حاجة سريعة لتحديد القيم القصوى في البيانات العشوائية)

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

int Max_number(int arr[], int count)
{
	int first = arr[0];
	int max = 0;

	for (int i = 0; i < count; i++)
	{
		if (first > arr[i])
		{
			max = first;
		}

		else
		{
			first = arr[i];
			max = first;
		}
	}

	return max;
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

	cout << "\nthe max number in array :" << Max_number(arr, N) << endl;
	return 0;
}*/

```cpp

```