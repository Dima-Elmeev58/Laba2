Console.WriteLine("Введите значение координаты x");
double x = Convert.ToDouble(Console.ReadLine());
Console.WriteLine("Введите значение координаты у");
double y = Convert.ToDouble(Console.ReadLine());
if (y == 0 && x == 0)
{
    Console.WriteLine("Начало координат");
}
else if (y != 0 && x == 0)
{
    Console.WriteLine("На оси X");
}
else if (x != 0 && y == 0)
{
    Console.WriteLine("На оси Y");
}
else if (x > 0 && y > 0)
{
    Console.WriteLine("В первой четверти");
}
else if (x > 0 && y < 0)
{
    Console.WriteLine("В второй четверти");
}
else if (x < 0 && y < 0)
{
    Console.WriteLine("В третьей четверти");
}
else if (x < 0 && y > 0)
{
    Console.WriteLine("В четвертой четверти");
}
