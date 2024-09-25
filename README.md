using System;

namespace OceanCreatures
{
    class Program
    {
        static void Main(string[] args)
        {
            Octopus octopus = new Octopus("Inky");
            Console.WriteLine($"Meet {octopus.Name}, the octopus with {octopus.Legs} legs!");
        }
    }

    public class Octopus 
    {
        public readonly string Name;
        public readonly int Legs = 8;
        
        public Octopus (string name)
        {
            Name = name;
        }
    }
}

