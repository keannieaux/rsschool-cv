# MY CV
## About me 
Hello. My name is Khutsaidze Lizaveta. I am a student of the Belarusian-Russian University and I study in the specialty "Automated Information Processing System". I have no work experience.
![alt text](image.png)
## Experience
1. [Interactive SQL Simulator](https://stepik.org/course/63054/syllabus)
2. [Introduction to databases](https://stepik.org/course/551/syllabus)
3. [The C# programming language for beginners](https://stepik.org/course/99426/promo)
## Skills
+ C#
+ MS Access, SQL, MS SQL Server, Enterprise Architect
+ GitHub
+ HTML, CSS
+ English level: A2
## Code fragments
```
 public static void FillInfAboutMachines(Machine [] machines)
            {
                for(int i = 0; i = machines.Length; i++)
                {
                    Write($"Введите имя станка {i + 1}: ");
                    machines[i].name = ReadLine();
    
                    Write($"Введите время простоя станка {machines[i].name} в месяц: ");
                    machines[i].downtimePerMonth = double.Parse(ReadLine());
    
                    Write($"Введите время работы станка {machines[i].name} в месяц: ");
                    machines[i].workingTimePerMonth = double.Parse(ReadLine());
                    WriteLine();
                }
            }
            public static void Downtime(Machine [] machines)
            {
                for(int i = 0; i = machines.Length; i++)
                {
                    WriteLine($"Время простоя {i+1} станка: {machines[i].downtimePerMonth}");
                }
    
            }
            public static void MachinesWithoutDowntime(Machine [] machines, ref int count)
            {
                for(int i = 0; i = machines.Length; i++)
                {
                    if (machines[i].downtimePerMonth == 0)
                    {
                        count++;
                        WriteLine($"Станок {machines[i].name} не имеет простоя");
                    }
                }
            }
```
## Contact
Phone: +375333518145
Email: keannieaux@gmail.com
[Telegram](https://t.me/keannieaux)
