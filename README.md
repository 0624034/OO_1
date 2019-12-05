```
0624034 翁敏婧
```
# 0624034 翁敏婧
>## 0624034 `翁敏婧`
>>### `0624034` 翁敏婧

>#### :smile: 0624034 翁敏婧
>##### :school: 0624034 翁敏婧
>###### :pig: 0624034 翁敏婧

* **Apple**
* *Bee*
* ~~Candy~~

***

[國立高雄科技大學](https://www.nkust.edu.tw/)

|AAA|BBB|CCC|
|:--|:-:|--:|
|1|2|3|
|4|5|6|


```java
public class Hello {
    public static int gvar;
    public static void say(String s) {
        int x = 10;
        System.out.print(s+x);
    }
    public static void main(String[] argv) {
        float y = 0;
        say("Hello, world\n");
    }
}
```
![Photo](photo.png "蠟筆小新")


[![Video](https://img.youtube.com/vi/LbgRJA-sIDs/0.jpg)](https://www.youtube.com/watch?v=LbgRJA-sIDs "我們這一家")

 * hw1121.java
```java
abstract class CShape
{
    protected String color;
    public void setColor(String str)
    {
        color = str;
    }
    public abstract void show();
}
class CTriangle extends CShape
{
    protected double a, b, c;
    public CTriangle(double l, double w, double h)
    {
        a = l;
        b = w;
        c = h;
    }
    public void show()
    {
        System.out.print("color="+color+", ");
        System.out.println("area="+a*b*0.5);
    }
}
public class hw1121{
    public static void main(String args[])
    {
        CTriangle ctriangle = new CTriangle(3, 4, 5);
        ctriangle.setColor("Red");
        ctriangle.show();
    }
}
```
 * 1128.java
```java
interface Shape{
    abstract double getArea();
}
class Rectangle implements Shape{
    private double length;
    private double width;
    public Rectangle(double l, double w){
        length = l;
        width = w;
    }
    public double getArea(){
        return length*width;
    }
    public String toString(){
        return "Rectangle area=" + getArea();
    }
}
class Triangle implements Shape{
    private double base;
    private double height;
    public Triangle(double b, double h){
        base = b;
        height = h;
    }
    public double getArea(){
        return base*height*0.5;
    }
     public String toString(){ 
        return "Triangle area=" + getArea();
    }  
}
public class 1128{
    public static void main(String args[]){
        Rectangle rec = new Rectangle(10,20);
        System.out.println(rec);
        Triangle tri = new Triangle(10,20);
        System.out.println(tri);
    }
}
```
 * 1205.java
```java

class Student {
    Course[] courses = new Course[10];
}
class Course {
}

```
