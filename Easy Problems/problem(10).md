# problem(10)

**المستوى:** Easy Problems

هذا الكود يقوم بتشفير وفك تشفير نص باستخدام خوارزمية بسيطة (إزاحة كل حرفين للأمام في الأبجدية). 
يحل مشكلة الحاجة إلى تشفير أساسي للنصوص مع إمكانية استعادتها بسهولة.

/* string readTheWord(string meesage)
{
	string word;
	cout << meesage << endl;
	cin >> word;

	return word;
}

string encryptTheWord(string word)
{
	string encrypt = "";
	int capital = 90;
	int litter = 122;

	for (int i = 0; i < word.length(); i++)
	{
		for (int j = 0; j < 26; j++)
		{
			if (word[i] == char(capital) || word[i] == char(capital-1))
			{
				encrypt += char(capital-2);
				break;
			}
			
			else if (word[i] == char(litter) || word[i] == char(litter-1))
			{
				encrypt += char(litter-2);
				break;
			}

			else if (word[i] == char(j + 97) && (word[i] != char(122) || word[i] != char(121)))
			{
				encrypt += char(j + 97 + 2);
			}

			else if (word[i] == char(j + 65) && (word[i] != char(90) || word[i] != char(89)))
			{
				encrypt += char(j + 65 + 2);
			}

		}
		
	}

	return encrypt;

}

int main()
{
	string descryption = readTheWord("please enter the text you want encrypt :");

	cout << "\nthe text befour decseprtion :" << descryption << endl;
	cout << "the text after Encryption :" << encryptTheWord(descryption) << endl;
	cout << "the text after unEncryption :" << descryption << endl;

	return 0;
}*/

```cpp

```