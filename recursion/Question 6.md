# **Print x^n (with stack height = n)**
#### **x=2, n=5**

```java
class DSA {
  public static int calPower (int x, int n) {
    if (n == 0) {
      return 1;
    }
    if (x == 0) {
      return 0;
    }
    int xpownm1 = calPower (x, n-1);
    int xpown = x * xpownm1;
    return xpown ;
  }
  public static void main (String args[]) {
     int x = 2, n = 5;
     int ans = calPower (x, n);
     System.out.println (ans);
  } 
}
```
