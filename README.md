


public class Mustela {

    public static void main(String[] args) {
        Person animal1 = new Person();
        animal1.setColor ("я коричневого кольору " + "("+ "brown" +")" );
        animal1.setName("Привіт я " + "Ведмідь бурий");

    
    System.out.println(animal1.getName());
    System.out.println(animal1.getColor());
    }

}



class Person{
       private String name;
       private String color;

    void sayHello(){
        
    }

    public String getName() {
        return name;
    }

    public void setName(String name) {
        this.name = name;
    }

    public String getColor() {
        return color;
    }

    public void setColor(String color) {
        this.color = color;
    }






       }



