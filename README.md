interface A
{
	void display();
	void show();
}
class B implements A //error occurs here as show must be implemented
{
	public void display()
	{
		System.out.println("Hello im implemented");
	}
}
class Jala 
{
	public void show()
	{
		System.out.println("Im definition of abstact method");
	}
	public static void main(String[] args){ 
			 B b = new B();
			 b.display();
		
	}
}

