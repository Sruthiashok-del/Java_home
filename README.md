pse
# Java_home
Its a commands

package codedecoder;
// Overloading constructor
public class Car {    
	int model;
	String color;
	
	public Car() {        //default constructor
        color = "Unknown";
        model = 123;
    }
/*** public Car(int ct,String cc){    //  parameterized constructor
	  model = ct;
	  color = cc;
  }
	 ***/ 
public void display() {
		  System.out.println("model: " + model + ", color: " + color);
	 return;
  }
public static void main(String args[]) {
	Car c = new Car();
	//Car c1 = new Car(123,"blue");
	//Car c2 = new Car();
	c.display();
	//c1.display();
	
}
	
}
	
