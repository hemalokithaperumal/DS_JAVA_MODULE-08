# Ex14 Tracking the First Unique Number in a Stream using LinkedHashMap
## DATE:15.11.2025
## AIM:
To implement a program that tracks the first unique (non-repeating) number in a stream of integers using a LinkedHashMap.

## Algorithm
1.Start the program.
2.Declare an integer array with a fixed size.
3.Use Arrays.fill() to fill the first 10 positions of the array with a constant value .
4.Display all elements of the array.
5.Stop the program.

## Program:
```
/*
Program to tracks the first unique (non-repeating) number in a stream of integers using a LinkedHashMap.
Developed by: Abinaya A
RegisterNumber:212223040003
*/
import java.util.*;

public class FirstUniqueNumber {
    public static void main(String[] args) {

        int[] stream = {4, 5, 4, 5, 3, 2, 3, 6};

        LinkedHashMap<Integer, Integer> map = new LinkedHashMap<>();
        for (int num : stream) {
            map.put(num, map.getOrDefault(num, 0) + 1);

            System.out.print("Current First Unique Number: ");
            boolean found = false;

            for (Map.Entry<Integer, Integer> entry : map.entrySet()) {
                if (entry.getValue() == 1) {
                    System.out.println(entry.getKey());
                    found = true;
                    break;
                }
            }

            if (!found) {
                System.out.println("No Unique Number");
            }
        }
    }
}

```

## Output:

<img width="490" height="354" alt="image" src="https://github.com/user-attachments/assets/56e00910-7a32-4301-a0f4-38eaf7d09b16" />


## Result:
The program successfully tracks and returns the first unique number at any point in the integer stream using a LinkedHashMap.
