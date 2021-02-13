# Practica-3

•	Crear un programa que pida números positivos al usuario, y vaya calculando
la suma de todos ellos (terminará cuando se teclea un número negativo o cero).

using System;

namespace Practica_3
{
    class Program
    {
        static void Main(string[] args)
        {
            int suma, cant, valor, promedio;
            string linea;
            suma = 0;
            cant = 0;
            do
            {
                Console.Write("Ingrese un valor (0 para finalizar):");
                linea = Console.ReadLine();
                valor = int.Parse(linea);
                if (valor != 0)
                {
                    suma = suma + valor;
                    cant++;
                }
            } while (valor != 0);
            if (cant != 0)
            {
                promedio = suma;
                Console.Write("La suma de los valores ingresados es:");
                Console.Write(promedio);
            }
            else
            {
                Console.Write("No se ingresaron valores.");
            }
            Console.ReadLine();
        }
    }
}
     










•	Crea un programa que escriba en pantalla los números del 1 al 10, usando "do..while".

using System;

namespace Practica_3_do_while
{
    class Program
    {
        static void Main(string[] args)
        {
            int num = 0;
            int cant;
            int x = 0;

           
            Console.Write("Introduzca un numero: ");
           
            cant = Convert.ToInt32(Console.ReadLine());
            

            
            do
            {
                Console.WriteLine(x);
                x++;
                
                     
                

            }
            while (x<=10);
            





                Console.ReadKey();
        } 

    }

}













•	Crear un programa que muestre los primeros 10 números pares a partir del producto de (10 x 1

using System;

namespace _10x10
{
    class Program
    {
        static void Main(string[] args)
        {
            int num = 0;
            int cant = 0;
            int x = 100;


            Console.Write("Introduzca un numero: ");

            cant = Convert.ToInt32(Console.ReadLine());



            do
            {
                Console.WriteLine(x);
                x += 10; 




            }
            while (x <= 200);




            Console.ReadKey();
        }

    }

}
