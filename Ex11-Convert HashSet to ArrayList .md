# Ex11 Convert HashSet to ArrayList in Java
## DATE:
## AIM:
To convert a collection of distinct integers stored in a HashSet into an ArrayList and display its contents.
## Algorithm
1. Start the program.
2. Create a HashSet of integers and add elements into it.
3. Create an ArrayList by passing the HashSet as a parameter to the ArrayList constructor.
4. Display the HashSet elements and the converted ArrayList.
5. Stop the program.
6. 
## Program:
```
/*
Program to To convert a collection of distinct integers stored in a HashSet into an ArrayList and display its contents.
Developed by: HEMA LOKITHA P
RegisterNumber:212223110014 
*/
import java.util.*;

public class HashSetToArrayList {
    public static void main(String[] args) {

        // Creating a HashSet
        HashSet<Integer> numbers = new HashSet<Integer>();
        numbers.add(10);
        numbers.add(20);
        numbers.add(30);
        numbers.add(40);
        numbers.add(50);

        // Converting HashSet to ArrayList
        ArrayList<Integer> list = new ArrayList<Integer>(numbers);

        // Displaying contents
        System.out.println("HashSet elements: " + numbers);
        System.out.println("ArrayList elements: " + list);
    }
}
```

## Output:

<img width="445" height="182" alt="image" src="https://github.com/user-attachments/assets/96686415-4b40-403d-905e-cd03213627da" />


## Result:
The program successfully converts a collection of distinct integers stored in a HashSet into an ArrayList
