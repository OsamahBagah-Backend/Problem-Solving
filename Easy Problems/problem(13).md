# problem(13)

**المستوى:** Easy Problems

هذا الكود يقوم بإنشاء مفاتيح عشوائية مكونة من أحرف كبيرة مفصولة بشرطات. يحل مشكلة توليد رموز أو أكواد فريدة يمكن استخدامها ككلمات مرور أو مفاتيح تنشيط.

(الكود يطبع سلسلة من المفاتيح العشوائية بحيث كل مفتاح يتكون من عدة أحرف كبيرة مفصولة بشرطات، مع تحديد عدد المفاتيح وطولها بناءً على المدخلات)

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

void print_spase(int i, int num)
{
	if (i == num - 1)
	{
		cout << generate_letter(num);
	}

	else
	{
		cout << generate_letter(num) << "-";
	}

}

void print_generate_key(int num)
{
	for (int i = 1; i <= num; i++)
	{
		cout << "key [" << i << "]:";
		for (int j = 1; j < num; j++)
		{
			print_spase(j, num);
		
		}

		cout << endl;
	}
}

int main()
{
	srand((unsigned)time(NULL));
	int N = readNumber("please enter the number :");

	print_generate_key(N);

	return 0;
}*/

```cpp

```