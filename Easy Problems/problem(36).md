# problem(36)

**المستوى:** Easy Problems

هذا الكود يحسب عدد الأعداد الموجبة في مصفوفة عشوائية تحتوي على قيم بين -100 و100.  
يحل مشكلة الحاجة إلى تحليل التوزيع الإحصائي للقيم الموجبة في عينات البيانات العشوائية.  

السطر الأول يوضح وظيفة الكود في عد الأعداد الموجبة  
السطر الثاني يبين أهميته في التحليل المالي والعلمي للبيانات المختلطة

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
		arr1[i] = randNumber(-100, 100);
	}
}

int calculat_odd(int arr[], int num)
{
	int count = 0;
	for (int i = 0; i < num; i++)
	{
		if (arr[i] > 0)
		{
			count++;
		}
	}

	return count;
}

void print_array1(int arr1[], int num)
{
	cout << "array 1 elemnet :";
	for (int i = 0; i < num; i++)
	{
		cout << arr1[i] << " ";
	}

}

int main()
{
	srand((unsigned)time(NULL));
	int arr[100];
	int N = readNumber("please enter how element you want :");
	fill_array1(arr, N);
	print_array1(arr, N);

	cout << "\nthe coun of odd numbers :" << calculat_odd(arr, N) << endl;

	return 0;
}*/
```