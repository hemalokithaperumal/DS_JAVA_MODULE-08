# Ex15 Value Existence Check in a TreeMap
## DATE:15.11.2025
## AIM:
To write a Java program that checks whether a given value exists in a TreeMap.

## Algorithm

Start the program.
Create a TreeMap containing key–value pairs.
Display the TreeMap elements.
Use the containsValue() method to check if a specific value exists in the map.
Display whether the value is found or not.
Stop the program.

## Program:
```
/*
Program to checks whether a given value exists in a TreeMap.
Developed by:HEMA LOKITHA P
RegisterNumber: 212223110014
*/
import java.util.*;

public class TreeMapValueCheck {
    public static void main(String[] args) {

        // Creating a TreeMap
        TreeMap<Integer, String> map = new TreeMap<Integer, String>();
        map.put(1, "Apple");
        map.put(2, "Banana");
        map.put(3, "Cherry");
        map.put(4, "Mango");

        // Display TreeMap
        System.out.println("TreeMap Elements: " + map);

        // Value to search
        String searchValue = "Mango";

        // Check value existence
        if (map.containsValue(searchValue)) {
            System.out.println("Value '" + searchValue + "' exists in the TreeMap.");
        } else {
            System.out.println("Value '" + searchValue + "' does NOT exist in the TreeMap.");
        }
    }
}

```

## Output:

<img width="490" height="354" alt="image" src="https://github.com/user-attachments/assets/730db54e-6c5a-426a-a4ed-1dd8047802b7" />


## Result:
Thus, the program successfully checks whether a specified value exists in a TreeMap using the containsValue() method.
