# Java-learning-examples
Andreev-soft-train-2016


/* package whatever; // don't place package name! */

import java.util.*;
import java.lang.*;
import java.io.*;
import Math;


/* Name of the class has to be "Main" only if the class is public. */
class Ideone
{
	public static void main (String[] args) throws java.lang.Exception
	{
		// your code goes here
	System.out.println("рассчет длины дуги по длине хорды");
	Scanner scanner1=new Scanner(System.in);
	System.out.println("введите диаметр окружности");
	double d = scanner1.nextDouble();
	System.out.println("введите длину хорды");
	double l = scanner1.nextDouble();
	double pi = 3.1415;
	double alpha = l/d;
	double result = Math.arcsyn(alpha)*pi*d/180;
	System.out.println("длина дуги составляет: " + result);
	}
}
