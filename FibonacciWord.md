# Fibonacci Word
```java
String f0="a",f1="b";
for(int n=2;n<=10;n++){
 String fn=f1+f0;
 System.out.println("f("+n+")="+fn);
 f0=f1;f1=fn;
}
```