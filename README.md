# InterviewCoder
import java.util.*;


public class ArraysSampleFunctions {

    private Scanner scanner;

    public ArraysSampleFunctions (Scanner scanner) {
        //Scanner is being shared across all classes, as multiple scanners are causing inputs to be missed errors.
        this.scanner = scanner;
    }

    public int find2ndMaximum(int[] arr, int arr_size) {
        int n= arr.length;
        int max1=max2=Integer.MIN_VALUE;
        for(inti=0;i<n;i++){
            if(max1<arr[i]){
                max2=max1;
                max1=arr[i];
            }
            else if(max2<arr[i]){
                max2=arr[i];
            }

        }
        //Write your code for find2ndMaximum here
        return max2;
    }

    public int find2ndMinimum(int[] arr, int arr_size) {


        //Write your code for find2ndMinimum here
        return 0;
    }

    public void changeToFactorialArray(int[] arr, int arr_size) {


        //Write your code for changeToFactorialArray here
        return ;
    }

    public void copyPrimeNumbers(int[] arr, int arr_size, int[] primes_arr, int primes_arr_size) {


        //Write your code for copyPrimeNumbers here
        return ;
    }


}
