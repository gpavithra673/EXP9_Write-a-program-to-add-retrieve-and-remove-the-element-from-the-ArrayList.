# EXP9_Write-a-program-to-add-retrieve-and-remove-the-element-from-the-ArrayList.
## AIM:
### To create a program to add,retrieve and remove elements from arraylist.
## PROCEDURE:
### 1.Create the class and declare the main method so that the JVM will identify the main program to run.
### 2.Declare a variable to accept the arraylist input.
### 3.To accept the inputs from user import Scanner and get the input and store them.
### 4.To add elements to ARRAYLIST use add() to add elements to the list.
### 5.Print the output after accepting all the inputs.
### 6.The program will be executed after the compilation and results are printed.
## PROGRAM:
```
// NAME: PAVITHRA G
// ROLLNO: 212221240036

import java.util.ArrayList;
import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        ArrayList<Integer> arr1=new ArrayList<Integer>();
        Scanner sc=new Scanner(System.in);
        System.out.println("Enter the size of array: ");
        int n=sc.nextInt();
        for(int i=0;i<n;i++){
            arr1.add(sc.nextInt());
        }
        System.out.println("Array: ");
        System.out.println(arr1);
        System.out.println("Retrieving an element: "+ arr1.get(1));
        System.out.println("Removing an element: "+arr1.remove(2));
        System.out.println("After removing: "+arr1);
    }
}

```
## RESULT:
![image](https://github.com/gpavithra673/EXP9_Write-a-program-to-add-retrieve-and-remove-the-element-from-the-ArrayList./assets/93427264/7f08f3fb-b727-4ae7-a728-ee2d2a95f64c)


