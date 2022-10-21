# **Print n natural numbers with its sum**
#### **n=5**


```java
class DSA {
  public static void printSum (int num, int n, int sum) {
    if (num == n) {
      sum += num;
      System.out.println (sum);
      System.out.println (num);
      return;
    }
    sum += num;
    printSum (num+1, n, sum);
    System.out.println (num);
  } 
  public static void main (String args[]) {
    printSum (1, 5, 0);
  }
}
```
