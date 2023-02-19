
    Console.WriteLine("Введите число от 1 до 7: ");
    int number = Convert.ToInt32(Console.ReadLine());
    return number;

    if (number >= 1 && number <= 7)
    {
      if (number == 7 || number == 6) 
        Console.WriteLine("Под цифрой "+number+" - Да");
      else
        Console.WriteLine("Под цифрой "+number+" - Нет ");
    }
    else
        Console.WriteLine("Не верное число: ");