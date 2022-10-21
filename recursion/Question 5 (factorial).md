# **print factorial of number n**
#### **n=5**

```java
class DSA {
  public static int printFactorial (int num) {
    if (num == 1 || num == 0) {
      return 1;
    }
    int fact_nm1 = printFactorial (num-1);
    int fact_n = num * fact_nm1;
    return fact_n;
  }
  public static void main (String args[]) {
    int num = 5;
   int ans = printFactorial (num);
   System.out.print (ans);
  }
}
```
