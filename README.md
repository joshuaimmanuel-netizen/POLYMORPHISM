

public class sample2 {
    String name;
    String job;
    int age;
    int weight;
    int height;

    public sample2(String name, String job, int age, int weight, int height) {
        this.name = name;
        this.job = job;
        this.age = age;
        this.weight = weight;
        this.height = height;
/*joshua immanuel in */    }

    public String getName() {
        return name;

    }

    public String getJob() {
        return job;
    }

    public int getAge() {
        return age;
    }

    public int getWeight() {
        return weight;
    }

    public int getHeight() {
        return height;
    }

    public String finale() {
        return (" MY NAME IS " + this.getName() + " MY JOB IS " + this.getJob() + " MY AGE IS " + this.getAge() + " MY WEIGHT IS " + this.getWeight() + " MY HEIGHT IS " + this.getHeight());
    }
    public static void main(String args[]){
        sample2 z = new sample2("Joshua Immannuel","Software Engineer",18,90,190);
        System.out.println(z.finale());
    }


}
