# Equatorial to Horizontal Coordinates
```java
double phi=30,delta=45,H=60;
double alt=Math.asin(Math.sin(Math.toRadians(phi))*Math.sin(Math.toRadians(delta))+Math.cos(Math.toRadians(phi))*Math.cos(Math.toRadians(delta))*Math.cos(Math.toRadians(H)));
double az=Math.acos((Math.cos(Math.toRadians(phi))*Math.sin(Math.toRadians(delta))-Math.sin(Math.toRadians(phi))*Math.cos(Math.toRadians(delta))*Math.cos(Math.toRadians(H)))/Math.cos(alt));
System.out.println(Math.toDegrees(alt)+","+Math.toDegrees(az));
```