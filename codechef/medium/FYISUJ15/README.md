# FYISUJ15

![Difficulty](https://img.shields.io/badge/Difficulty-Medium-yellow)

## Problem

### Earthquake Intensity Tracker

Seismologists record earthquake intensity using the `short` data type for its wider range than byte. In this task, you'll declare three variables for intensity across different locations within the short range (`-32,768 to 32,767`).

 **Steps to Complete** 

- Declare a variable named regionOneIntensity using short and assign a positive intensity value 12000.
- Declare another variable named regionTwoIntensity using short and assign a negative intensity value -5000.
- Declare a third variable named regionThreeIntensity using byte and assign a zero intensity value 0.
- Print all three values to confirm they are correctly stored.

Run your code and verify the output. Click "Submit" when you're ready!

 **Expected Output** 
If stored and printed correctly, your output should look something like:

```
Region One Intensity: 12000  
Region Two Intensity: -5000  
Region Three Intensity: 0  

```

Feel free to adjust the intensity values to observe how different earthquake readings affect the results.

## Solution

**Language:** Java  
**Runtime:** N/A  
**Memory:** N/A  
**Submitted:** 2026-08-14T06:19:54.906Z  

```java
class Codechef {
    public static void main(String[] args) {
        //  Declare and assign earthquake intensity readings

        short regionIntensity = 12000;
        short regionTwoIntensity = -5000;
        byte regionThreeIntensity = 0;


        //  Print the intensity values

        System.out.println("Region one Intensity: "+ regionIntensity);
        System.out.println("Region Two Intensity: "+ regionTwoIntensity);
        System.out.println("Region Three Intensity: "+ regionThreeIntensity);

    }
}

```

---

[View on CodeChef](https://www.codechef.com/problems/FYISUJ15)