using System;

class Program
{
    static void Main(string[] args)
    {
        // Declare a variable to store the speed limit and initialize it to 110 kph
        int speedLimit = 110;

        // Declare a variable to store the car's speed
        int carSpeed;

        // Declare a variable to store the fine
        double fine = 0;

        // Prompt the user to enter the car's speed
        Console.WriteLine("Enter the car's speed in kph: ");

        // Read the user's input and convert it to an integer
        carSpeed = int.Parse(Console.ReadLine());

        // Check if the car's speed is equal to or less than the speed limit
        if (carSpeed <= speedLimit)
        {
            // If the car's speed is equal to or less than the speed limit, output "No fine"
            Console.WriteLine("Car's speed is within regulations (110 kph or below), there is no fine");
        }
        // Check if the car's speed is greater than the speed limit but not more than 50 kph over
        else if (carSpeed > speedLimit && carSpeed <= speedLimit + 50)
        {
            // Calculate the speed over the limit
            int speedOverLimit = carSpeed - speedLimit;

            // Check if the speed over the limit is 1 - 19 kph
            if (speedOverLimit >= 1 && speedOverLimit <= 19)
            {
                // Multiply the speed over the limit by $2.50
                fine = speedOverLimit * 2.5;
            }
            // Check if the speed over the limit is 20 - 29 kph
            else if (speedOverLimit >= 20 && speedOverLimit <= 29)
            {
                // Multiply the speed over the limit by $3.75
                fine = speedOverLimit * 3.75;
            }
            // Check if the speed over the limit is 30 - 49 kph
            else if (speedOverLimit >= 30 && speedOverLimit <= 49)
            {
                // Multiply the speed over the limit by $6.00
                fine = speedOverLimit * 6.0;
            }
            Console.WriteLine("The fine for speeding is: $" + fine);
        }
        // Check if the car's speed is greater than 50 kph over the speed limit
        else if (carSpeed > speedLimit + 50)
        {
            // If the car's speed is greater than 50 kph over the speed limit, print "NO"
            Console.WriteLine("No out of court settlement");
        }
    }
}

