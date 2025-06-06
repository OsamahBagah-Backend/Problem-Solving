# problem(14)

**المستوى:** Easy Problems

هذا الكود يحسب عدد تكرارات رقم معين في مصفوفة من الأعداد التي يدخلها المستخدم. يحل مشكلة معرفة عدد مرات ظهور قيمة محددة في مجموعة من البيانات المدخلة.

(الكود يطلب من المستخدم إدخال عناصر المصفوفة ثم يبحث عن عدد تكرارات رقم معين فيها ويعرض النتيجة)

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

void fill_array(int arr[],int length)
{
	
	cout << "enter element array \n";
	for (int i = 0; i < length; i++)
	{
		cout << "element [" << i << "] :";
		cin >> arr[i];
		//cout << endl;
	}

}

int raplete(int arr[] , int num, int number)
{
	//arry arr;
	int count = 0;
	for (int i = 0; i < number; i++)
	{
		if (arr[i] == num)
		{
			count++;
		}
	}

	return count;
}

void print(int arr[],int num)
{
	//arry arr;
	cout << "the general array :";
	for (int i = 0; i < num; i++)
	{
		cout << arr[i] << ",";
	}

	cout << endl;
	int B = readNumber("eneter the number how is repeat :\n");
	cout << "the number :" << B << " his repeat " << raplete(arr, B,num) << " time\n";
}

int main()
{
	int arr[100];
	int N1 = readNumber("please enter how element you want :");
	fill_array(arr, N1);
	print(arr,N1);

	return 0;
}*/

```cpp

```