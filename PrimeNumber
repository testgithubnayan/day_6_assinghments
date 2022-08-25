package com.bridgelabz.logical;

import java.util.Scanner;

public class PrimeNumber {

    public static void main(String[] args) {

        Scanner scr = new Scanner(System.in);
        System.out.println("Enter the Number to check prime or not:");
        int n = scr.nextInt();
        int flag = 0;

        if (n == 0 || n == 1) {
            System.out.println(n + " is not prime number");
        }
        else {
            for (int i = 2; i <= n / 2; i++) {
                if (n % i == 0) {
                    System.out.println(n + " is not prime number");
                    flag = 1;
                    break;
                }
            }
            if (flag == 0) {
                System.out.println(n + " is prime number");
            }
        }
    }
}
