// Lanzar dos dados seguidos
using System;
public class Juego01e
{
    public static void Main()
    {
        Random dado = new Random();
        int aleatorio1 = dado.Next(1, 7);
        Console.WriteLine("El numero del 1º dado es {0}", aleatorio1);
    }
}
