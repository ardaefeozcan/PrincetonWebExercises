# RGB to YIQ Color Converter
```java
int r=255, g=100, b=50;
double Y=0.299*r+0.587*g+0.114*b;
double I=0.596*r-0.274*g-0.322*b;
double Q=0.211*r-0.523*g+0.312*b;
System.out.println(Y+","+I+","+Q);
```