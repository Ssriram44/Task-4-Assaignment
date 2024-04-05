public class Constructor {
	
	private String name;
	
	
	public Constructor() {           //constructor
		
		System.out.println("Constructor called");
		
		name="Sai";
	}
	
	public static void main(String[] args) {
		
		Constructor constr=new Constructor();         //creating an object of the constructor class 
		
		System.out.println(constr.name);              //constructor invoked while
	}
	

Output:-
Sai





---------------------------------------------------------------------------------------------------------------------------------


Class NestedIf
{
public static void main(String[] args) {
    int age = 22;
    boolean isEligible = false;
   if (age >= 18) {
        System.out.println("You are Adult");
        if (isEligible) {
            System.out.println("Eligible");
        } else {
            System.out.println("not Eligible");
        }
    } else {
        System.out.println("minor.");
    }
}
}




---------------------------------------------------------------------------------------------------

public class ClassA_Getter_Setter {
	
	private int rollno;
	private String name;
	
	public String getName() {
		return name;
	}
	
	public int getRollno() {
		return rollno;
	}
	
	public void setName(String n ) {
		name=n;
	}
    
	public void setRollno(int r) {
		rollno=r;
	}
}


  public class ClassB_Getter_Setter {

	public static void main(String[] args) {
		
		ClassA_Getter_Setter gs=new ClassA_Getter_Setter();
		gs.setName("Govind");
		gs.setRollno(17);
		
		System.out.println("Person Name is  :"+gs.getName());
		System.out.println("Person RollNum is :"+gs.getRollno());
	}

}
