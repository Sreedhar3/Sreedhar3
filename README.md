/*write a java program on data types using bufferedreader*/
import java.io.*;
class DataTypes
{
  public static void main(String[] args)throws IOException
  {
	byte a;
	short s;
	int i;
	long j;
	String city;
	float x;
	double y;
	boolean b1;
	char ch1; 
	BufferedReader br = new BufferedReader(new InputStreamReader(System.in));
	System.out.println("enter 9 input values-(byte,short,int,long,string,float,double,boolean, char)");
	a = Byte.parseByte(br.readLine());
	s = Short.parseShort(br.readLine());
	i = Integer.parseInt(br.readLine());
	j = Long.parseLong(br.readLine());
  city = br.readLine();
	x = Float.parseFloat(br.readLine());
  y = Double.parseDouble(br.readLine()); 
  b1 = Boolean.parseBoolean(br.readLine());
	ch1 = (char)br.read();
	System.out.println("a="+a);
	System.out.println("s="+s);
	System.out.println("i="+i);
	System.out.println("j="+j);
	System.out.println("x="+x);
	System.out.println("City="+city);
	System.out.println("y="+y);
	System.out.println("b1="+b1);
	System.out.println("ch1="+ch1);
	System.out.println(br);
	 
  }
}
