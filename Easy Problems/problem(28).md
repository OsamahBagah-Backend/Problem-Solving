# problem(28)

**المستوى:** Easy Problems

هذا الكود يسمح للمستخدم بإدخال عناصر مصفوفة يدويًا مع تحديد متى يتوقف عن الإدخال.  
يحل مشكلة الحاجة إلى إنشاء مصفوفات مخصصة بحجم ديناميكي حسب احتياجات المستخدم المباشرة.  

السطر الأول يشرح آلية إدخال العناصر بشكل تفاعلي مع المستخدم  
السطر الثاني يبين فائدته في إنشاء هياكل بيانات مرنة بدون تحديد حجم مسبق

```cpp
/* void add_array(int arr[], int inde, int element)
{
	arr[inde] = element;
}

void fill_array(int arr[] , int &count)
{
	int element;
	int chosse;
	count = 0;
	do
	{
		cout << "please enter the element :";
		cin >> element;
		cout << "did you will add more element yes =1 , no =0 :";
		cin >> chosse;
		add_array(arr, count, element);
		count++;

	} while (chosse == 1);
}

void print_aray(int arr[], int count)
{
	for (int i = 0; i < count; i++)
	{
		cout << arr[i] << " ";
	}

	cout << endl;
}

int main()
{
	int arr[100];
	int count = 0;

	fill_array(arr, count);
	 
	cout << "\nthe array leangh is :" << count << endl;
	cout << "the array element : ";

	print_aray(arr, count);


	return 0;
}*/
```