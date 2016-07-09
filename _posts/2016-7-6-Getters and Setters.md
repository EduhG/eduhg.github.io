### Getter and Setter Methods in Java

Introduction

Getters and setters allow control over the values passed to a class. They provide a mechanism for encapsulation.

A getter method gets the value (of a member variable), while a setter method sets the value (of a member variable).

The reason to use getter and setter methods rather than just making the member variables public is because of the principle of information hiding (encapsulation) - classes should not reveal their innards to the outside world, because that tightly couples the implementation of the class to whatever is in the outside world. That's bad, because if you tightly couple lots of classes together in a larger program, the program will become a big, entangled mess that's hard to maintain.

An Example implementing the getter and setter methods is shown below:

```java

package moringaschool;

/**
 *
 * @author EduhG
 */
public class Student {
    private int id;
    private String first_name;
    private String middle_name;
    private String last_name;
    private String form;
    private double fees_balance;

    public int getId() {
        return id;
    }

    public void setId(int id) {
        this.id = id;
    }

    public String getFirst_name() {
        return first_name;
    }

    public void setFirst_name(String first_name) {
        this.first_name = first_name;
    }

    public String getMiddle_name() {
        return middle_name;
    }

    public void setMiddle_name(String middle_name) {
        this.middle_name = middle_name;
    }

    public String getLast_name() {
        return last_name;
    }

    public void setLast_name(String last_name) {
        this.last_name = last_name;
    }

    public String getForm() {
        return form;
    }

    public void setForm(String form) {
        this.form = form;
    }

    public double getFees_balance() {
        return fees_balance;
    }

    public void setFees_balance(double fees_balance) {
        this.fees_balance = fees_balance;
    }  
}
```

To access the varibles in class Student. We instantiate the class and call the indivivual get and set methods as needed. For Example:

```java

package moringaschool;

/**
 *
 * @author EduhG
 */
public class Register {
    Student student = new Student();
    
    int id = 0;
    String first_name = "";
    String middle_name = "";
    String last_name = "";
    String form = "";
    double fees_balance = 0;
    
    public void setDetails() {
        student.setId(0);
        student.setFirst_name("Edwin");
        student.setMiddle_name("M");
        student.setLast_name("Nyangena");
        student.setForm("Form 3");
        student.setFees_balance(2000.00);
    }
    
    public void getDetails() {
        System.out.println(student.getId());
        System.out.println(student.getFirst_name());
        System.out.println(student.getMiddle_name());
        System.out.println(student.getLast_name());
        System.out.println(student.getForm());
        System.out.println(student.getFees_balance());
    }
    
}

```

