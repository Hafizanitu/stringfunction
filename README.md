public class Main {

    String s1 = "Nitu";
    String s2 = "Nipu";

    public void ReversString() {
        StringBuilder ab1 = new StringBuilder();
        ab1.append(s1);
        ab1.append(s2);
        System.out.println(ab1.toString());
        System.out.println(ab1.reverse());
    }

    public void InsertString() {
        StringBuilder ab2 = new StringBuilder();
        ab2.append(s1);
        ab2.insert(2, "name");
        System.out.println(ab2.toString());
    }

    public void DeleteString() {
        StringBuilder ab3 = new StringBuilder();
        ab3.append(s1);
        ab3.reverse();
        ab3.delete(1, 2);
    }



public static void main(String[] args) {
    Main m = new Main();
    System.out.println("Hello and welcome!");
    m.ReversString();
    m.InsertString();
    m.DeleteString();
}
}



///simple set and get function for private data

public class Main {

    private String name;
    private int age;

    public int getAge() {
        return this.age;
    }

    public void setAge(int age) {
        this.age = age;
    }

    public String getName() {
        return this.name;
    }

    public void getName(String name) {
        this.name = name;
    }

    public static void main(String[] args) {
        Main m = new Main();
        m.getName("John");
        System.out.println(m.getName());
        System.out.println("Hello and welcome!");
        for (int i = 1; i <= 5; i++) {
            System.out.println("i = " + i);
        }
    }
}
