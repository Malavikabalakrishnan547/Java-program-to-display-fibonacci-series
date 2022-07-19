// Java-program-to-display-fibonacci-series
public class fibinocci {

    public static void main(String args[]) {
        int p, c, n, i, j;
        p = 0;
        c = 1;

        for (i = 0; i <= 10; i++) {
            n = p + c;

            System.out.print(" " + p);
            p = c;
            c = n;

        }
    }
}
