# FYISUJ25

![Difficulty](https://img.shields.io/badge/Difficulty-Medium-yellow)

## Problem

### Global Financial Transactions Tracker

Banks process billions of transactions daily, storing large transaction IDs and branch codes for tracking.
Use  **`long`**  for  **transaction IDs**  due to their size and  **`short`**  for  **branch codes**  as they are smaller values.

```
transactionID = 5_123_456_789_000L;  
branchCode = 3052;  

```

 **Expected Output:** 

```
Transaction ID: 5123456789000  
Branch Code: 3052  

```

## Solution

**Language:** Java  
**Runtime:** N/A  
**Memory:** N/A  
**Submitted:** 2026-08-14T06:35:42.211Z  

```java
 class Codechef{
    public static void main(String[] args){
        long transactionID = 512345678900l;
        short branchCode = 3052;
        
    System.out.println("Tranaction ID: "+ transactionID);
    System.out.print("Branch Code"+ branchCode);
    }
}
```

---

[View on CodeChef](https://www.codechef.com/problems/FYISUJ25)