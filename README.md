public class Area
{
	public static double area(double radius){
		return Math.PI * Math.pow (radius,2); 	
	}

	public static double area(int length, int width){
	return length * width;
}
	public static double area(double base1, double base2, double height){
		return (base1 + base2) * height/2;
	}
	
	public static void main(String[] args)
{

		System.out.printf("%2.2f\n",
				area(3.0));

    // Area of a rectangle
    System.out.printf("%1.1f\n",
            	area(2, 4));

    // Area of cylinder
    System.out.printf("%2.1f\n",
            	area(3.3, 4.495, 4.49));}
}
