Quest 1:calculate the average
class Main{
  public static void main(String[] args){
    int arr[] = {1,2,3,4,5};
    int sum = 0 ;
    for(int i=0;i<arr.length;i++){
      sum = sum + arr[i];
      
    }
   
    int avg = sum/arr.length;
    System.out.println("Average of array elements is " + avg);
  }
}

Quest 2:find the even and odd integer
class Main{
  public static void main(String[] args){
    int arr[] = {1,2,3,4,5,55};
    int even = 0;
    int odd = 0;
    for(int i=0;i<arr.length;i++){
      if(arr[i]%2==0){
        even++;
      }
      else{
      odd++;
      }
     
  }
    System.out.println("no.of even integer is " + even);
      System.out.println("no. of odd integer is " + odd);
    } 
}
Quest 3:find the index of an array
import java.util.*;
class Main{
  public static void main(String[] args){
    int arr[] = {1,20,3,4,5};
    Scanner sc = new Scanner(System.in);
    System.out.println("Enter the number to be searched");
    int num = sc.nextInt();
    for(int i=0;i<arr.length;i++){
      if(arr[i]==num){
        System.out.println("Number found at index " + i);
      }
      else{
       i++;
      }
    }
  }
}

Ques 4:maximum and minimum
class Main{
  public static void main(String[] args){
    int arr[] = {1,20,33,4,5};
    int max = arr[0];
    int min = arr[0];
    for(int i=0;i<arr.length;i++){
      if(arr[i]>max){
        max = arr[i];
      }
      else if(arr[i]<min){
        min = arr[i];
      }
    }
    System.out.println("Maximum number is " + max);
    System.out.println("Minimum number is " + min);
  }
}

