# Factorial-100
How to find factorial of 100 in JAVA

//How to find the factorial of 100
public class Main{
    public static void main(String[] args){
        
        double a=100;
        for(double i=1;i<100;i++)
        {
           a =a*i;
        }
        System.out.println("Factorial="+a);
    }
}
