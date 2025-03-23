using System;

Console.WriteLine("Digite um número de 1 a 7 para converter em dia:");
string numero = Console.ReadLine();

if (int.TryParse(numero, out int numeroInt) && numeroInt >= 1 && numeroInt <= 7)
{

    switch(numeroInt)
    {
        case 1:
            Console.WriteLine("domingo");
            break;
        case 2:
            Console.WriteLine("segunda-feira");
            break;
        case 3:
            Console.WriteLine("terça-feira");
            break;
        case 4:
            Console.WriteLine("quarta-feira");
            break;
        case 5:
            Console.WriteLine("quinta-feira");
            break;
        case 6:
            Console.WriteLine("sexta-feira");
            break;
        case 7:
            Console.WriteLine("sábado");
            break;
    }
}
else
{
       Console.WriteLine("Dia da semana incorreto");
}
# numeros-em-dias
