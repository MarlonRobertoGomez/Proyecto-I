# Proyecto-I
Tarea de Programacion II
namespace PI_2025_I_P1_EJERCICIO2
{
    internal class Program
    {
        //Construir un programa donde capture dos numeros enteros e imprima el resultado de la suma
        Console.WriteLine("Ingrese el numero1: ");
        int numero1 = int.Parse(Console.ReadLine());
        Console.WriteLine("Ingrese el numero2: ");
        int numero2 = int.Parse(Console.ReadLine());
        int suma = numero1 + numero2;
        Console.WriteLine($"El numero 1: {numero1} + el numero 2: {numero2} es = {suma}.");
        Console.ReadLine();
    }
}
