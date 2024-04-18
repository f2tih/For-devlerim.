namespace Project
{
    public class Uygulama1
    {
        public void AppRun()
        {
            Console.Write("bir sayı giriniz");
            int x = Convert.ToInt32(Console.ReadLine());

            for(int i = 0; i <=10; i++) 
            {
                Console.Write(x + "+" + "=" + x * i); 
            }
        }
        
    }
}




{
    public class Uygulama2
    {
        public void AppRun()                
        {
            Console.Write("Bir sayı girin: ");
            int x = Convert.ToInt32(Console.ReadLine());

            Console.Write("Kare genişliğini girin: ");
            int width = Convert.ToInt32(Console.ReadLine());

            for (int i = 0; i < width; i++)
            {
                for (int j = 0; j < width; j++)
                {
                    Console.Write(x);
                }
                Console.WriteLine();
                
            }
        }
    }







namespace Project
{
    public class Uygulama3
    {
        public void AppRun()
        {
            Console.Write("Bir sayı giriniz: ");
            int x = Convert.ToInt32(Console.ReadLine());

            for (int i = 0; i < 5; i++)
            {
                Console.WriteLine(x + "" + x + "" + x);
            }
        }
    }
}















namespace Project
{
    public class Uygulama4
    {
        public void AppRun()
        {
            Console.Write("Bir sembol girin: ");
            int symbol = Convert.ToInt32(Console.ReadLine());

            Console.Write("Üçgenin genişliğini girin: ");
            int width = Convert.ToInt32(Console.ReadLine());

            for (int i = 1; i <= width; i++)
            {
                for (int j = 1; j <= i; j++)
                {
                    Console.Write(symbol + " ");
                }
                Console.WriteLine();
            }
        }
    }
}






















namespace Project
{
    public class Uygulama5
    {
        public void AppRun()
        {
            Console.Write("Üçgenin genişliğini girin: ");
            int width = Convert.ToInt32(Console.ReadLine());

            for (int i = 0; i < width; i++)
            {
                for (int j = 0; j < width; j++)
                {
                    if (j >= i)
                    {
                        Console.Write("*");
                    }
                    else
                    {
                        Console.Write(" ");
                    }
                }
                Console.WriteLine();
            }
        }
    }






















        public class Uygulama6
    {
        public void AppRun()
        {
            Console.Write("Bir isim giriniz: ");
            string name = Console.ReadLine();

            for (int i = 1; i <= name.Length; i++)
            {
                for (int j = 0; j < i; j++)
                {
                    Console.Write(name[j]);
                }
                Console.WriteLine();
            }
        }
    }
}


















namespace Project
{
    public class Uygulama7
    {
        public void AppRun()
        {
            Console.Write("başlangıç değerini girin: ");
            int start = Convert.ToInt32(Console.ReadLine());
            Console.Write("bitiş değerini girin: ");
            int finish = Convert.ToInt32(Console.ReadLine());

            for (int x = start; x <= finish; x++)
            {
                int y = (x - 4) * (x - 4);
                for (int i = 0; i < y; i++)
                {
                    Console.Write("*");
                }
                Console.WriteLine();
            }
        }
    }
}













namespace Project
{
    public class Uygulama8
    {
        public void AppRun()
        {
            Console.Write("Ad giriniz: ");
            string name = Console.ReadLine();

            for (int i = 0; i <= name.Length; i++)
            {
                for (int j = 1; j <= name.Length - i; j++)
                {
                    Console.Write(" ");
                }

                for (int n = 0; n <= 2 * i - 1; n++)
                {
                    Console.Write(name[n]);

                }
                Console.WriteLine();
            }
        }
    }
}















    
}
