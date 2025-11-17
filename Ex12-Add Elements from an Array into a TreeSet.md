# Ex12 Add Elements from an Array into a TreeSet
## DATE:15.11.2025
## AIM:
To write a Java program that adds elements from an array into a TreeSet and displays the elements in sorted order.
## Algorithm
1. Start the program.
2. Create an array containing integer elements.
3. Create a TreeSet object.
4. Add all elements of the array to the TreeSet using a loop or Collections method.
5. Display the elements of the TreeSet.
6. Stop the program. 

## Program:
```
/*
Program that adds elements from an array into a TreeSet and displays the elements in sorted order.
Developed by: HEMA LOKITHA P
RegisterNumber: 212223110014
*/
import java.util.*;

public class ArrayToTreeSet
 {
    public static void main(String[] args)
{

        int[] arr = {40, 10, 50, 30, 20};
        TreeSet<Integer> set = new TreeSet<Integer>();
        for (int num : arr) {
            set.add(num);
        }
        System.out.println("Elements in TreeSet (Sorted Order): " + set);
    }
}

```

## Output:

<img width="622" height="153" alt="image" src="https://github.com/user-attachments/assets/4565660b-83b6-4b23-be16-5407b24aa1c6" />


## Result:
The program successfully adds elements from an array into a TreeSet.
