# Constructor_overloading
class Test17
{
int x,z,k;
float y;
Test17(int a)
{
 x=a;
System.out.println("X:"+x);
}
Test17(float a)
{
y=a;
System.out.println("Y:"+y);
}
Test17(int a,int b)
{
 z=a;
 k=b;
System.out.print("Z:"+z);
System.out.print("K:"+k);
}
public static void main(String args[])
{
 Test17 obj=new Test17(15);
 Test17 obj1=new Test17(25.9f);
 Test17 obj2=new Test17(35,45);
}
}
