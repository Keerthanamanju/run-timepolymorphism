# run-timepolymorphism
package java .Application2;
class Animal {
    void sound() {
        System.out.println("Animal makes sound");
    }
}

class Cat extends Animal {
    void sound() {
        System.out.println("Cat Meows");
    }
}

class Dog extends Animal {
    void sound() {
        System.out.println("Dog Barks");
    }
}
class Cow extends Animal {
    void sound() {
        System.out.println("Cow Moos");
    }
}
/**
 *
 * @author 1BSCCSA47
 */
public class JavaApplication2 {

    /**
     * @param args the command line arguments
     */
    public static void main(String[] args) {
        // TODO code application logic here
          Animal a;  
      a = new Cat();  
        a.sound();    

        a = new Dog();
        a.sound();      

        a = new Cow();  
        a.sound();      
    }
}
    

