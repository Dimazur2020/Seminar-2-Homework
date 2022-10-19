//Задача 2: Напишите программу, которая на вход принимает два числа и выдаёт, какое число большее, а какое меньшее.
           
 /*          
 Console.WriteLine("Введите первое число: ");
 int num1 = Convert.ToInt32(Console.ReadLine());
 Console.WriteLine("Введите второе число: ");
 int num2 = Convert.ToInt32(Console.ReadLine());
 
   if(num1 > num2)

        {
             Console.WriteLine("Первое число больше второго");
        }
        else if (num1 < num2)
        {
            Console.WriteLine("Первое число меньше второго");
        }
        else
        {
            Console.WriteLine("Оба числа равны");
        }
        
        
           */

           //Задача 4: Напишите программу, которая принимает на вход три числа и выдаёт максимальное из этих чисел

/*

Console.WriteLine("Введите первое число: ");
 int num1 = Convert.ToInt32(Console.ReadLine());
 Console.WriteLine("Введите второе число: ");
 int num2 = Convert.ToInt32(Console.ReadLine());
 Console.WriteLine("Введите третье число: ");
 int num3 = Convert.ToInt32(Console.ReadLine());

 int max=num1;
if (num2>max)max=num2;
if (num3>max)max=num3;

Console.WriteLine($"Число {max} является максимальным");

*/

//Напишите программу, которая на вход принимает число и выдаёт, является ли число чётным (делится ли оно на два без остатка).

/*
Console.WriteLine("Введите число: ");
 int num1 = Convert.ToInt32(Console.ReadLine());

if (num1 % 2 == 0)
  {
    Console.WriteLine($"Число {num1} является чётным");
  }
  else
  {
    {
    Console.WriteLine($"Число {num1} не является чётным");
    }
  }
*/
  //Напишите программу, которая на вход принимает число (N), а на выходе показывает все чётные числа от 1 до N.

  Console.WriteLine("Введите число: ");
 int N = Convert.ToInt32(Console.ReadLine());

  
for (int x = 2; x < N; x++)       
if (x % 2 == 0)        
Console.WriteLine(x);

