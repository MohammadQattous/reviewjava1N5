/*
 * Program 5
 * Conversion Menu
 *
 * 1. Inches to Centimeters (CM)
 * 2. Centimeters (CM) to Inches
 * 3. Feet to Meters (M)
 * 4. Meters (M) to Feet
 * 5. Celsius to Fahrenheit
 * 6. Fahrenheit to Celsius
 * 7. Hektar to Dunum
 * 8. Dunum to Hektar
 */

package com.mycompany.reveiwjava1n5;

import java.util.Scanner;
public class Reveiwjava1N5 {


    public static void main(String[] args) {

        Scanner input = new Scanner(System.in);

        double number, result;
        int choice;

        System.out.print("Enter a number: ");
        number = input.nextDouble();

        System.out.println("\n===== CONVERSION MENU =====");
        System.out.println("1- Inch to CM");
        System.out.println("2- CM to Inch");
        System.out.println("3- Feet to Meter");
        System.out.println("4- Meter to Feet");
        System.out.println("5- Celsius to Fahrenheit");
        System.out.println("6- Fahrenheit to Celsius");
        System.out.println("7- Hektar to Dunum");
        System.out.println("8- Dunum to Hektar");

        System.out.print("Enter your choice: ");
        choice = input.nextInt();

        switch (choice) {

            case 1 -> {
                result = number * 2.54;
                System.out.println(number + " Inch = " + result + " CM");
            }

            case 2 -> {
                result = number / 2.54;
                System.out.println(number + " CM = " + result + " Inch");
            }

            case 3 -> {
                result = number / 3.28084;
                System.out.println(number + " Feet = " + result + " Meter");
            }

            case 4 -> {
                result = number * 3.28084;
                System.out.println(number + " Meter = " + result + " Feet");
            }

            case 5 -> {
                result = (number * 9 / 5) + 32;
                System.out.println(number + " Celsius = " + result + " Fahrenheit");
            }

            case 6 -> {
                result = (number - 32) * 5 / 9;
                System.out.println(number + " Fahrenheit = " + result + " Celsius");
            }

            case 7 -> {
                result = number * 10;
                System.out.println(number + " Hektar = " + result + " Dunum");
            }

            case 8 -> {
                result = number / 10;
                System.out.println(number + " Dunum = " + result + " Hektar");
            }

            default -> System.out.println("Invalid choice!");
        }
    }
}
    
