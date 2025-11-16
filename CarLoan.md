# Car Loan Payments
```java
double P=10000,R=5,Y=3;
double n=12*Y;
double r=(R/100)/12;
double payment=P*r/(1-Math.pow(1+r,-n));
System.out.println(payment);
```