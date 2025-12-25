// First interface
interface Father {
    void fatherProperty();
}

// Second interface
interface Mother {
    void motherProperty();
}

// Child class implementing multiple interfaces
class Child implements Father, Mother {

    public void fatherProperty() {
        System.out.println("Father's property");
    }

    public void motherProperty() {
        System.out.println("Mother's property");
    }
}

public class Main {
    public static void main(String[] args) {
        Child obj = new Child();
        obj.fatherProperty();
        obj.motherProperty();
    }
}
