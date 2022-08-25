package com.bridgelabz.logical;

import java.util.Scanner;

public class CouponNumber {

    static void coupon(int n){
        char[] chars = "abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ0123456789".toCharArray();
        int max = 1000000000;

        for (int i = 0; i<n; i++){
            int random = (int) (Math.random() * max );
            StringBuilder sb = new StringBuilder();
            while (random > 0) {
                sb.append(chars[random % chars.length]);
                random /= chars.length;
            }

            String couponCode = sb.toString();
            System.out.println("Coupon Code: " + couponCode);
        }


    }
    public static void main(String[] args) {

        Scanner scr = new Scanner(System.in);
        System.out.println("Enter the number of coupons to be generated:");
        int n = scr.nextInt();
        coupon(n);
    }
}
