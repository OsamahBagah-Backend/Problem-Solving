# problem(15)

**المستوى:** Easy Problems

هذا الكود ينشئ مصفوفة بأعداد عشوائية بين 1 و100 ويطبعها بناءً على حجم يحدده المستخدم.  
يحل مشكلة الحاجة لإنشاء مجموعات بيانات عشوائية سريعة لأغراض الاختبار أو المحاكاة.

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

	return 0;
}*/

```cpp

```