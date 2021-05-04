# task_2.7

public class Main {

    public static void main(String[] args) {
        double a = 31;

        for (int i = 1; i <= a; i++) {
            if (a%i == 0) {
                System.out.println("true - " + i);
            } else {
                System.out.println("false - " + i);
            }
        }
    }
}
