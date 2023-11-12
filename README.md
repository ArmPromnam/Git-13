import java.util.Random;

public class RandomNumber {

    public static void main(String[] args) {
        // Declare and initialize a Random object
        Random random = new Random();

        // Generate a random number from 1 to 1000
        int number = random.nextInt(1000) + 1;

        // Print the random number
        System.out.println(number);
    }
}
