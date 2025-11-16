# Standard Deviation
```java
double[] data={1,2,3,4,5};
double sum=0;
for(double x:data) sum+=x;
double avg=sum/data.length;
double sqsum=0;
for(double x:data) sqsum+=(x-avg)*(x-avg);
double std=Math.sqrt(sqsum/(data.length-1));
System.out.println(avg+","+std);
```