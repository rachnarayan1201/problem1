# check equality of arrays
import java.util.Arrays; 
  
public class ArrayEqualDemo  
{ 
    public static void main(String[] args)  
    { 
        // Let us create different integers arrays 
        int[] arra = new int [] {1, 2, 3, 4}; 
        int[] arrb = new int [] {1, 2, 3, 4}; 
          
        System.out.println("is arr1 equals to arr2 : " + 
                                Arrays.equals(arra, arrb)); 
        System.out.println("is arr1 equals to arr3 : " + 
                                Arrays.equals(arra, arrb)); 
    } 
} 
