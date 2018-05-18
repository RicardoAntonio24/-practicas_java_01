# -practicas_java_01
public class variable {
    public static void main(String[] args) {
        byte b = Byte.MAX_VALUE;
        short s = Short.MAX_VALUE;
        int i = Integer.MAX_VALUE;
        long l = Long.MAX_VALUE;
        float f = Float.MAX_VALUE;
        double d = Double.MAX_VALUE;

        System.out.println("byte Max "+b);
        System.out.println("short Max "+s);
        System.out.println("int Max "+i);
        System.out.println("long Max "+l);
        System.out.println("float Max "+f);
        System.out.println("double Max "+d);

        b = Byte.MIN_VALUE;
        s = Short.MIN_VALUE;
        i = Integer.MIN_VALUE;
        l = Long.MIN_VALUE;
        f = Float.MIN_VALUE;
        d = Double.MIN_VALUE;

        System.out.println("byte Min "+b);
        System.out.println("short Min "+s);
        System.out.println("int Min "+i);
        System.out.println("long Min "+l);
        System.out.println("float Min "+f);
        System.out.println("double Min "+d);
    }
}
