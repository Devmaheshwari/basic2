import java.util.Scanner;
class vowel_consonant
{
	public static void main(String[] args)
	{
		char a;
		Scanner obj=new Scanner(System.in);
		System.out.println("Enter any character");
		a=obj.next().charAt(0);
		switch(a)
		{
			case 'a':
			case 'e':
			case 'i':
			case 'o':
			case 'u':System.out.println(a+ " is vowel");
			break;
			default:System.out.println(a+ " is consonant");
		}
	}
}
