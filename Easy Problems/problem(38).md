# problem(38)

**المستوى:** Easy Problems

هذا الكود ينشئ دالة لحساب القيمة المطلقة لعدد معين دون استخدام الدوال الجاهزة.  
يحل مشكلة الحاجة إلى تحويل الأعداد السالبة إلى موجبة في العمليات الحسابية المختلفة.  

السطر الأول يشرح كيفية عمل الدالة الرياضية المخصصة  
السطر الثاني يوضح فائدتها في تبسيط العمليات الحسابية التي تتطلب قيماً موجبة

/* int readNumber(string message)
{
	int num;

	do
	{
		cout << message << endl;
		cin >> num;

	} while (num == 0);

	return num;
}

int myAbs(int num)
{
	if (num > 0)
	{
		return num;
	}

	else
	{
		return num * -1;
	}
}

int main()
{
	int N = readNumber("please enter the number : ");

	cout << "my abs :" << myAbs(N) << endl;
	cout << "c++ abs :" << abs(N) << endl;
	
	return 0;
}*/

```cpp

```