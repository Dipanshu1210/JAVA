class Dog {
    void DogVoice() {
        System.out.println("!!Dog barks!!");
    }
}

class Cow extends Dog {
    void CowVoice() {
        System.out.println("!! Cow do mooooo!!");
        DogVoice();
    }
}

class Cat extends Cow {
    void CatVoice() {
        System.out.println("!! Cats do meoww!!");
        CowVoice();
    }
}

class Animals extends Cat {
    void Animals() {
        System.out.println("Voices of diffrent animals are ===> ");
        CatVoice();
    }
}

public class multipleInherit {
    public static void main(String args[]) {
        Animals d1 = new Animals();
        d1.Animals();

    }

}
