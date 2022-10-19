# **Print numbers from 5 to 1.**

**1st method**

```java

class DSA {
  public static void printNum (int num) { //(int num) = parameter
    //base case
    if (num == 0) {
      return;
    }
    System.out.println (num); //print number
    printNum (num);  //recursion
  }
  public static void main (String args[]) { //args = arguments
    int num = 5; //initialize num variable with value 5
    printNum (num); //calling the function printNum
  }
}
```
**2nd method**
```java
class DSA {
  public static void printNum (int num) { //(int num) = parameter
    //base case
    if (num == 0) {
      return;
    }
    System.out.print (num + " "); //print number
    int i = num-1; 
    printNum (i);  //recursion
  }
  public static void main (String args[]) { //args = arguments
    int num = 5; //initialize num variable with value 5
    printNum (num);  //calling the function printNum
  }
}
```
