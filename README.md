# nu-odd-or-Even
 static void Main(string[] args)
        {

            Console.WriteLine("Enter A number");
          int number=Convert.ToInt32(  Console.ReadLine());
            
            if ( number % 2 == 0)
            {

                Console.Write("Even");
            }
            else
            {
                Console.Write("odd");
            }
            Console.ReadKey();
          
        }
