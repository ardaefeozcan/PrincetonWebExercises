# CMYK to RGB Converter
```java
double C=0.1,M=0.2,Y=0.3,K=0.1;
int R=(int)(255*(1-C)*(1-K));
int G=(int)(255*(1-M)*(1-K));
int B=(int)(255*(1-Y)*(1-K));
System.out.println(R+","+G+","+B);
```