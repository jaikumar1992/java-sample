# java-sample

package com.java.Programs;

import java.util.Scanner;

public class ReverseNo {
	
	public void reverse(){
		Scanner scan=new Scanner(System.in);
		System.out.println("Please enter your number");
		int a=scan.nextInt();
		do{
			int b=a%10;
			System.out.print(b);
			a=a/10;
		}while(a>0);
		
		}
	
	public static void main(String[] args) {
		// TODO Auto-generated method stub
     //	ReverseString rs=new ReverseString();
		//		rs.reverse();
				ReverseNo rn=new ReverseNo();
				rn.reverse();
			}

		

	}


