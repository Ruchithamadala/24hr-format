# 24hr-format


import java.util.*;
public class Main{
      public static void main (String[] args){
      Scanner sc = new Scanner(System.in);
      int a = sc.nextInt();
      if(a<12)
      {
        System.out.println("Good Morning");
      }
      else if(a>=12 && a<=16)
      {
        System.out.println("Good Afternoon");
      }
      else if(a>16 && a<=20)
      {
        System.out.println("Good Evening");
      }
      else
      {
        System.out.println("Good night");
      }
