Console.WriteLine("Введите x");
double x = Convert.ToDouble(Console.ReadLine());
Console.WriteLine("Введите y");
double y = Convert.ToDouble(Console.ReadLine());
int i = Math.Sign(x) + 1;
int k = Math.Sign(y) + 1;
string[] arr = new string[] {
    "III квадрант", "Ось X (-)", "II квадрант", "Ось Y (-)", "ось Y (+)", "IV квадрант", " ось X (+)", "I квадрант",
    }
Console.WriteLine([arr [i + 3 * k]);
