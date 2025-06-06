# problem(40)

**المستوى:** Easy Problems

هذا الكود ينشئ دالة تقريب عشري لأعلى (Ceil) تعمل على تقريب الأعداد إلى أقرب عدد صحيح أكبر.  
يحل مشكلة الحاجة إلى تقريب القيم لأعلى في التطبيقات المالية والرياضية دون استخدام الدوال الجاهزة.  

السطر الأول يوضح آلية التقريب التصاعدي للأعداد العشرية  
السطر الثاني يبين أهميته في حسابات الأسعار والكميات التي تتطلب تقريباً تصاعدياً

```cpp
/* float readNumber(string message)
{
	float num;
	cout << message << endl;
	cin >> num;

	return num;
}

int myceil(float num)
{
	if (num > 0)
	{
		return int(num) + 1;
	}
	
	else
	{
		return int(num);
	}
}

int main()
{
	float N = readNumber("please enter the number :");

	cout << "my round :" << myceil(N) << endl;
	cout << "c++ round :" << ceil(N) << endl;

	return 0;
}*/
```