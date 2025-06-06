# problem(4)

**المستوى:** Easy Problems

هذا الكود يطبع شكلًا تنازليًا من الأرقام حيث كل صف يحتوي على رقم معين مكررًا بعدد الصف (مثل ٣٣٣ لصف رقم ٣).
 المشكلة التي يحلها هي إنشاء نمط مرئي تنازلي بناءً على العدد المدخل.

```cpp
int readPositiveNumber(string meesage)
{
	int num;
	do
	{
		cout << meesage << endl;
		cin >> num;

	} while (num < 0);

	return num;
}

void printTheShape(int num)
{
	for (int i = num; i > 0; i--)
	{
		for (int j = 0; j < i; j++)
		{
			cout << i;
		}

		cout << endl;
	}

}

int main()
{
	printTheShape(readPositiveNumber("please enter psitive number :"));

	return 0;
}
```