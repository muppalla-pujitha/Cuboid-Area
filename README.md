# Cuboid-Area
import java.util.Scanner;
class cuboid
{
public static void main(String[] args)
{
int length,breadth,height;
int totalarea,volume;
Scanner sc=new Scanner(System.in);
System.out.println("enter length,breadth and height");
length=sc.nextInt();
breadth=sc.nextInt();
height=sc.nextInt();
totalarea=2*(length*breadth+length*height+breadth*height);
volume=length*breadth*height;
System.out.println("Total area "+totalarea);
System.out.println("volume is "+volume);
}
}

