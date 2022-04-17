import java.util.Scanner;
public class Calculator {
    public static void main(String[] args) {
        CalculatorDemo();
    }
    static double Calculator(double n1, double n2, String operator){
        switch(operator){
            case("+"):
                return n1+n2;
            case("-"):
                return n1-n2;
            case("*"):
                return n1*n2;
            case("/"):
                return n1/n2;
            case("avg"):
                return (n1+n2)/2;
            case("max"):
                return Math.max(n1, n2);
            case("min"):
                return Math.min(n1, n2);
            default:
                return Double.NaN;
        }
    }
    static void CalculatorDemo(){
        Scanner input = new Scanner(System.in);
        System .out.print("Give first number: ");
        double n1 = input.nextDouble();
        System .out.print("Give second number: ");
        double n2 = input.nextDouble();
        System .out.print("Give a function: ");
        String operator = input.next();
        do {
            System .out.print("Give a function: ");
        }
        while(operator != "avg" || operator != "max"
                || operator != "+" || operator != "min"
                || operator != "*" || operator != "-" || operator != "/");

        System.out.println(+Calculator(n1,n2,operator));
    }
}
