# linear_search
package june2019;
import java.math.BigInteger;
import java.util.Scanner;
import java.util.*;
public class HelloWorld {
	public static void main(String[] args) {

		int a[]= {1,2,3,4,5};
		
		int s=3;
		for(int i=0;i<a.length-1;i++) {
			if(a[i]==s) {
				System.out.println(i+1); //element found.
			}
      else{
      System.out.println("not found");// element not found.
		}
   }
}
