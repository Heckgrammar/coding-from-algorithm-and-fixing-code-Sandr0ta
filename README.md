![image](https://github.com/MrAStone/StartEndCodeFixingTask/assets/60425249/d34dad5e-a403-4d6e-863f-2d3ebcd4b873)

In your notes copy the table and complete it.

![image](https://github.com/MrAStone/StartEndCodeFixingTask/assets/60425249/2c96d63f-1681-4b62-b50b-48fb68eba186)

Do the coding task in C#
 static void Main()
    {
        bool validChoice = false;
        int difference = -1;
        int startYear, endYear;

        while (!validChoice)
        {
            Console.Write("Enter a start year: ");
              startYear = Convert.ToInt32((Console.ReadLine());
            
            Console.Write("Enter an end year: ");
              endYear = Convert.ToInt32((Console.ReadLine());

            if (startYear >= endYear)
            {
                Console.WriteLine("Start year must be before end year");
            }
            else if (startYear > 2000)
            {
                Console.WriteLine("Start year must be before 2000");
            }
            else
            {
                validChoice = true;
            }
        }

        difference = endYear - startYear;
        Console.WriteLine("Difference: " + difference);
