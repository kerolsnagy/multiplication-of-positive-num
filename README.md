# multiplication-of-positive-num
package com.company;

import jdk.swing.interop.SwingInterOpUtils;

import java.util.Scanner;

public class Main
{
    public static void main (String args[])
    {
        Scanner k =new Scanner(System.in);
        int num;
        System.out.println("Enter positive number");
        num= k.nextInt();
        for (int i = 1; i <= 10; i++)
        {
            System.out.println(num + " * " + i + " = " + (num*i));
        }
    }
}
