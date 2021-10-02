import java.util.*;

public class ykp {  
    public static void main(String[] args) { 
        
        int n;  
        Scanner sc=new Scanner(System.in);    
        //reading the number of elements from the that we want to enter  
        n=sc.nextInt();  
        //creates an array in the memory of length 10  
        int[] array = new int[n];  
        for(int i=0; i<n; i++)  
        {  
        //reading array elements from the user   
        array[i]=sc.nextInt();  
        }   
        //Initialize array   
        int sum = 0;  
        //Loop through the array to calculate sum of elements  
        for (int i = 0; i < array.length; i++) {  
           sum = sum + array[i];  
        }  
        System.out.println(sum);  
    }  
}  
