import java.util.*;
import java.lang.*;
import java.io.*;

// Please name your class Main
class Main {
	public static void main (String[] args) throws java.lang.Exception {
	    Scanner in = new Scanner(System.in);
    	try{
                int K = in.nextInt();
                int J = in.nextInt();
    		    int phrase=0;
                while(K+J>=3 && K>0 && J>0){
    		    if(K<J){
    		        K--;
    		        J=J-2;
    		    }else{
    		        J--;
    		        K=K-2;
    		    }
    		    phrase++;
    		}
    		    System.out.print(phrase);
            }catch (Exception e){
                System.out.println(0);
        }
    }
}
