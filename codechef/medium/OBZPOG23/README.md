# OBZPOG23

![Difficulty](https://img.shields.io/badge/Difficulty-Medium-yellow)

## Problem

### Format a Movie Quote

In this example, we demonstrate how escape sequences can be used in Java to format text output within a structured program.

The `System.out.println` function is used to display a famous movie quote with proper formatting using escape sequences.

When executed, the code will produce an output that includes newline (`\n`), tab (`\t`), and quotes (`\"` and `\'`) for better readability.

```
Here's Johnny!"
    - The Shining

```

## Solution

**Language:** Java  
**Runtime:** N/A  
**Memory:** N/A  
**Submitted:** 2026-08-14T05:51:40.524Z  

```java
class Codechef {
    public static void main(String[] args) {
        // Prints the famous movie quote using escape sequences
        // \' is used to include a single quote within the string
        // \" is used to include a double quote within the string
        // \n is used to add a new line
        // \t is used to add a tab space before "- The Shining"
        System.out.println("Here\'s Johnny!\"\n\t- The Shining");
        
    }
}

```

---

[View on CodeChef](https://www.codechef.com/problems/OBZPOG23)