# problem(12)

**المستوى:** Easy Problems

هذا الكود يولد أحرفًا عشوائية من أنواع مختلفة (كبيرة، صغيرة، خاصة، أرقام) باستخدام نظام التعداد (enum)
. يحل مشكلة الحاجة إلى إنشاء محارف عشوائية متنوعة لأغراض مثل إنشاء كلمات مرور.

/* enum randey { litter = 1, capital = 2, special = 3, digit = 4 };

int randNumber(int from, int to)
{

	int randomNum = rand() % (to - from + 1) + from;

	return randomNum;
}

int print_the(randey chosse)
{
	switch (chosse)
	{
	case randey::capital:
		return (randNumber(65, 90)) ;

	case randey::litter:
		return (randNumber(97, 122)) ;

	case randey::special:
		return (randNumber(33, 47)) ;

	case randey::digit:
		return (randNumber(1, 10)) ;
	}
}

int main()
{
	srand((unsigned)time(NULL));
	//randey chosse;

	cout << char(print_the(randey::capital)) << endl;
	cout << char(print_the(randey::litter)) << endl;
	cout << char(print_the(randey::special)) << endl;
	cout << print_the(randey::digit) << endl;

	return 0;
}*/

```cpp

```