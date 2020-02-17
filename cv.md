# Nikita Slizhuk Aleksandrovich

I’m 17 years old student of the third course College business and law and RS School.
## Contact:  
[Vk.com](https://vk.com/sabotage_mm)  
[Github](https://github.com/nikson1707)
### Purpose : To beсome a frontend developer.
### Skils:
* C#
* C++
* HTML5
* CSS
```C
using System;
using System.IO;
namespace Файлы_практика
{
    class Program
    {
        static void Main(string[] args)
        {
            using (StreamWriter s = new StreamWriter(@"D:\\zad_1.txt"))
            {
                for (int i = 1; i != 10; ++i)
                {
                    s.WriteLine(Math.Pow(3, i));
                }
            }
            using (StreamReader sr = new StreamReader(@"D:\\zad_1.txt"))
            {
                while(!sr.EndOfStream)
                {
                    string str = sr.ReadLine();
                    str = sr.ReadLine();
                    Console.WriteLine(str);
                }
            }
            using (StreamWriter s = new StreamWriter(@"D:\\zad_2.txt"))
            {
                for (int i = 1; i != 10; ++i)
                {
                    s.WriteLine(Console.ReadLine());
                }
            }
            using (StreamReader sr = new StreamReader(@"D:\\zad_2.txt"))
            {
                string str = sr.ReadLine();
                int l = 0;
                while (str != null) 
                {
                    if (str[0] == 1 && str[str.Length - 1] == 1) ++l;
                    str = sr.ReadLine();
                    Console.WriteLine(str);
                }
                sr.Close;
            }
    }
}
```
### Experience:

I dont have experience in web programming.Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam.

### Education: 

11 years of school, two years of studying C++ and C#.

### English
A2

