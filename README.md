# reversing-array
reverse an array in java programming languaga
package aditya;

public class reverse_array {
    public static void main(String[] args) {
        int reverse[] ={4,5,6,7,17};
        System.out.println("The Array is:");
        //for loop to print the original array element
        for (int i=0;i< reverse.length;i++){
            System.out.print(reverse[i]+ " ");
        }
        System.out.println("");
        //for loop to reverse the array element
        System.out.println("Reverse of Array is:");
        for (int i= reverse.length-1;i>=0;i--){

            System.out.print(reverse[i] + " ");
        }
    }
}
