# YekSoalSade.sln

- **Link:** [Quera Problem #2885](https://quera.org/problemset/2885)
- **Description:** Given an integer **n**, print the sentence `man khoshghlab hastam` exactly **n** times, each on a new line.
- **Solution:** Implemented in C#.

namespace yekSoalSade
{
    internal class Program
    {
        static void Main(string[] args)
        {
            //Console.WriteLine("Enter a numbere:");
            int n = Convert.ToInt32(Console.ReadLine());
            for(int i = 1; i <= n; i++)
            {
                Console.WriteLine("man khoshghlab hastam");
            }
        }
    }
}
