public class PrimeNumbers {

    public static void main(String[] args) {

        System.out.println("Prime numbers between 0 and 500:");

        for (int number = 2; number <= 500; number++) {

            boolean isPrime = true;

            for (int i = 2; i < number; i++) {
                if (number % i == 0) {
                    isPrime = false;
                    break;
                }
            }

            if (isPrime) {
                System.out.print(number + " ");
            }
        }
    }
}
