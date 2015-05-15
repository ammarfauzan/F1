# Hello F1
echo Hello F1

import java.util.Scanner;
	class Fakto{
	
		static int faktorial(int i){
			if(i==1){
				return i;
			}else{
				return i * faktorial(i-1);
			}	
		}
	public static void main(String[] args){
	Scanner input = new Scanner(System.in);
			int a;
		System.out.print("Masukan Faktorial ke : ");
			a = input.nextInt();
			int fa = faktorial(a);
		System.out.println("Faktorial dari " + a +" adalah "+fa);
	}
	} 
	
