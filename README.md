# Nickitar2
package hw;

public class lesson2 {
        public static void main(String[] args) {
                System.out.println(номер1(1, 9));
                номер2(10);
                System.out.println(номер3(-25));
                номер4("Ivan", 5);
                System.out.println(номер5(1900));
        }
        public static boolean номер1(int a, int b) {
                int sum = a + b;
                if (sum >= 10 && sum <=20) {
                        return true;
                }
                return false;
        }

        public static void номер2(int x) {
                if (x >= 0) {
                        System.out.println("Положительное");
                }
                else {
                        System.out.println("Отприцательное");
                }
        }

        public static boolean номер3(int x) {
                if (x >= 0) {
                        return true;
                }
                else {
                        return false;
                }
        }

        public static void номер4(String str, int n) {
                for (int i = 1; i <= n; i++) {
                        System.out.println("[" + i + "]" + " " + str);
                }
        }

        public static boolean номер5(int year) {
                if ((year % 4 == 0 && year % 100 != 0) || year % 400 == 0) {
                        return true;
                }
                else {
                        return false;
                }
        }
}
