# **Print sum of n natural number**
#### **n=5**


```java
class DSA {
  public static void printSum (int num, int n, int sum) {
    if (num == n) {
      sum += num;
      System.out.print (sum);
      return;
    }
    sum += num;
    printSum (num+1, n, sum);
  } 
  public static void main (String args[]) {
    printSum (1, 5, 0);
  }
}
```
