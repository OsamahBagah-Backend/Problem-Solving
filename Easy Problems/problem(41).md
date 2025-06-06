# problem(41)

**المستوى:** Easy Problems

هذا الكود ينشئ دالة تقريب عشري لأعلى (Ceil) تعمل على تقريب الأعداد إلى أقرب عدد صحيح أكبر.  
يحل مشكلة الحاجة إلى تقريب القيم لأعلى في التطبيقات المالية والرياضية دون استخدام الدوال الجاهزة.  

السطر الأول يوضح آلية التقريب التصاعدي للأعداد العشرية  
السطر الثاني يبين أهميته في حسابات الأسعار والكميات التي تتطلب تقريباً تصاعدياً

```cpp
float readNumber(string message)
{
	float num;
	cout << message << endl;
	cin >> num;

	return num;
}

float mysqrt(float num)
{
	for (float i = 0.0; i < num; i += 0.1)
	{

		if (round(i * i) == int(num))
		{
			return i ;
		
		}

	}
}

int main()
{
	float N = readNumber("please enter the number :");

	cout << "my round :" << mysqrt(N) << endl;
	cout << "c++ round :" << sqrt(N) << endl;
	
	return 0;
}
```