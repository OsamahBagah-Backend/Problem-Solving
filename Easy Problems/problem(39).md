# problem(39)

**المستوى:** Easy Problems

هذا الكود ينشئ دالة تقريب أعداد عشرية مع دقة في التعامل مع الأعداد الموجبة والسالبة.  
يحل مشكلة الحاجة إلى تقريب الأعداد بشكل صحيح في التطبيقات الحسابية دون استخدام الدوال الجاهزة.  

السطر الأول يوضح آلية التقريب المخصصة للأعداد العشرية  
السطر الثاني يبين أهميته في العمليات المالية والعلمية التي تتطلب دقة في التقريب

```cpp
/* float readNumber(string message)
{
	float num;
	cout << message << endl;
	cin >> num;

	return num;
}

int myRound(float num)
{
	float numm = num;
	float num3 = int(num) * 1.05;
	if (num > 0)
	{
		if (num3 <= num)
		{
			return int(num) + 1;
		}

		else
		{
			return int(num);
		}
	}

	else
	{
		if (num3 >= num)
		{
			return int(num) - 1;
		}

		else
		{
			return int(num);
		}
	}
}

int main()
{
	float N = readNumber("please enter the number :");

	cout << "my round :" << myRound(N) << endl;
	cout << "c++ round :" << round(N) << endl;
	
	return 0;
}*/
```