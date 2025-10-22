class Sum {
    // Method 1: Two integers
    public int add(int a, int b) {
        return a + b;
    }

    // Method 2: Two floats
    public float add(float a, float b) {
        return a + b;
    }

    // Method 3: Three integers
    public int add(int a, int b, int c) {
        return a + b + c;
    }
}

public class Main {
    public static void main(String[] args) {
        Sum obj = new Sum();

        System.out.println(obj.add(5, 6));           // Output: 11
        System.out.println(obj.add(5.7f, 6.2f));      // Output: 11.9
        System.out.println(obj.add(5, 6, 7));         // Output: 18
    }
}
# MAIN-JAVA
