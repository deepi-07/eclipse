class Student {
    String name;
    int age;
    int regno;

    void combination() {
        System.out.println("Student Name: " + name);
        System.out.println("Age: " + age);
        System.out.println("Register No: " + regno);
    }
}

public class Main1 {
    public static void main(String[] args) {
        Student deepi = new Student();
        deepi.name = "Deepika Chandrasekaran";
        deepi.age = 51;
        deepi.regno = 51;

        deepi.combination();
    }
}
