# Randomness-Debugging-Activity

Randomness Debugging Activity
Due No Due Date  Points 1  Submitting a website url
This program should generate 10 random integers from 1 to 6. Fix it so that it works...

import java.util.random;

public class RandomGenerator{
    public static void main(String[] args)
    {
        output("Generate 10 random integers between 0 and 6");
        Random rnd;
        
        for (int i = 1; i <= 12; ++i)
        {
          int randomInt = 1 + rnd.nextInt(0 to 6);
          output("Generated number: " + randomInt);
        }
    
        output("Done.");
    }
  
  private static void output(String aMessage)
  {
    System.out.println(aMessage);
  }
}
