# Correct-It Small Mistake In it.

ckage com.company;

import java.util.Scanner;

public class Main {

    public static void main(String[] args) {
	// write your code here

        Scanner Sc = new Scanner(System.in);
        System.out.println("Enter Your First Side Of Triangle:");
        float a = Sc.nextFloat();
        System.out.println("Enter Your Second Side Of Triangle:");
        float b = Sc.nextFloat();
        System.out.println("Enter Your Third Side Of Your Triangle");
        float c = Sc.nextFloat();
        float s = (a+b+c)/2;
        System.out.println("This Is Your S:" + s);
        float r = (s*s-a*s-b*s-c)*0.5f;
        System.out.("This Is Your Heron's Formula Answer:" + r);

    }
}
