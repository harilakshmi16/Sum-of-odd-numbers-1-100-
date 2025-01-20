# Sum-of-odd-numbers-1-100-
Sum of Odd Numbers (1-100)

public class SumOfOddNumbers {
    public static void main(String[] args) {
        int sum = 0;
        for (int i = 1; i <= 100; i += 2) {
            sum += i;
        }
        System.out.println("Sum of odd numbers between 1 and 100: " + sum);
    }
}

Output

Sum of odd numbers between 1 and 100: 2500
