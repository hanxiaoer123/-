App.java
package com;

public class APP {

	public APP() {
		Animal animal1;
		
		animal1=new Dog();
		animal1.move();
		
		
		animal1=new Fish();
		animal1.move();
		
	}

	public static void main(String[] args) {
		new APP();

	}

}
