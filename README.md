# 27.SINGLE-INHERITANCE
package singleinheritance;

/**
 *
 * @author 1BSCCSA04
 */
class Parent{
    void display(){
        System.out.println("This is parent class");
    }
}
class Child extends Parent{
    void show(){
        System.out.println("This is Child class");
    }
}
public class SingleInheritance {

    /**
     * @param args the command line arguments
     */
    public static void main(String[] args) {
        // TODO code application logic here
        Child k=new Child ();
        k.display();
        k.show();
    }
    
}

O/P:
This is parent class
This is Child class
