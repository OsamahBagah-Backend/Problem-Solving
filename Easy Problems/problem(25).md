# problem(25)

**المستوى:** Easy Problems

هذا الكود يقوم بإنشاء مجموعة من المفاتيح العشوائية المكونة من أحرف كبيرة مفصولة بشرطات. يحل مشكلة الحاجة إلى توليد أكواد أو مفاتيح فريدة يمكن استخدامها في أنظمة التسجيل أو التوثيق.  

السطر الأول يشرح آلية عمل الكود في توليد المفاتيح العشوائية  
السطر الثاني يوضح التطبيق العملي له في إنشاء معرّفات فريدة لأنظمة الحسابات أو التنشيط

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

string generate_letter(int num)
{
	string word = "";

	for (int i = 1; i < num; i++)
	{
		word += char(randNumber(65, 90));
	}

	return word;

}

string void_key(int num)
{
	string key = "";

	key += generate_letter(num) + "-";
	key += generate_letter(num) + "-";
	key += generate_letter(num) + "-";
	key += generate_letter(num);

	return key;
}

void fill_array(int num , string arr[])
{
	for (int i = 0; i < num; i++)
	{
		arr[i] = void_key(num);
	}
}

void print_2(int num , string arr[])
{
	for (int i = 0; i < num; i++)
	{
		cout << "array[" << i <<  "] :" << arr[i] << endl;
	}

	cout << endl;
}

int main()
{
	srand((unsigned)time(NULL));
	int N = readNumber("please enter how number you want :");
	string arr[100];
	
	fill_array(N, arr);
	print_2(N, arr);

	return 0;
}*/
```