# problem(11)

**المستوى:** Easy Problems

هذا الكود يولد أرقامًا عشوائية بين مدى معين (من 1 إلى 10 في المثال). يحل مشكلة الحاجة إلى قيم عشوائية في البرامج باستخدام دالة `rand()` مع تهيئة البذور بواسطة الوقت.

/* int randomNumber(int from, int to)
{

	int randNum = rand() % (to - from + 1) + from;
	return randNum;
}

int main()
{
	srand((unsigned)time(NULL));

	cout << randomNumber(1, 10) << endl;
	cout << randomNumber(1, 10) << endl;
	cout << randomNumber(1, 10) << endl;

	return 0;
}*/

```cpp

```