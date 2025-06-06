# problem(20)

**المستوى:** Easy Problems

هذا الكود ينشئ مصفوفتين ويقوم بنسخ محتويات المصفوفة الأولى إلى المصفوفة الثانية.  
يحل مشكلة الحاجة إلى تكرار أو نسخ مجموعات البيانات لمقارنتها أو معالجتها بشكل منفصل.  

السطر الأول يوضح عملية إنشاء المصفوفتين ونسخ المحتوى بينهما  
السطر الثاني يبين فائدة الكود في التعامل مع نسخ البيانات للعمليات المختلفة

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


void fill_array2(int arr1[],int arr2[], int num)
{
	for (int i = 0; i < num; i++)
	{
		arr2[i] = arr1[i];
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
	cout << "\n array 2 elemnet :";
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
	int N = readNumber("please enetr the element :");
	fill_array1(arr1, N);
	fill_array2(arr1,arr2, N);
	print_array1(arr1, N);
	print_array2(arr2, N);
	
	return 0;
}*/
```