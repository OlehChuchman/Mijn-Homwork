package Lesson5;

public class SpaceX {
    public int year;
    public int maxSpeed;

    public SpaceX(int year, int maxSpeed) {
        this.year = year;
        this.maxSpeed = maxSpeed;

    }

}
package Lesson5;

public class SpaceXN2 extends SpaceX {
    public boolean isDiving = true;
    public int quantityofoxigen;

    public SpaceXN2(int year, int maxSpeed, boolean isDiving, int quantityofoxigen) {
        super(year, maxSpeed);
        this.isDiving = isDiving;
        this.quantityofoxigen = quantityofoxigen;

    }
}
package Lesson5;

public class SpaceXN3 extends SpaceXN2 {
    public boolean isDrivingoffroad = true;


    public SpaceXN3(int year, int maxSpeed, boolean isDiving, int quantityofoxigen, boolean isDrivingoffroad) {
        super(year, maxSpeed, isDiving, quantityofoxigen);
        this.isDrivingoffroad = isDrivingoffroad;

    }
}


package Lesson5;

public class Lesson5Main {

    public static void main(String[] args) {

        SpaceXN3 spaceXN3 = new SpaceXN3(2018, 200, true, 30, true);
        System.out.println(spaceXN3.maxSpeed);
        System.out.println(spaceXN3.year);
        System.out.println(spaceXN3.isDiving);
        System.out.println(spaceXN3.quantityofoxigen);
        System.out.println(spaceXN3.isDrivingoffroad);


    }
}
