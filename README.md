This program shows you how to print out all information about a class. The program prompts you for the name of a class and writes out the signatures of all methods and constructors as well as the names of all instance fields of a class. For example, if you enter

    java.lang.Double

the program prints

Click here to view code image

shows you how to print out all information about a class. The program prompts you for the name of a class and writes out the signatures of all methods and constructors as well as the names of all instance fields of a class. For example, if you enter

    java.lang.Double

the program prints

Click here to view code image

    public class java.lang.Double extends java.lang.Number
    {
       public java.lang.Double(java.lang.String);
       public java.lang.Double(double);

       public int hashCode();
       public int compareTo(java.lang.Object);
       public int compareTo(java.lang.Double);
       public boolean equals(java.lang.Object);
       public java.lang.String toString();
       public static java.lang.String toString(double);
       public static java.lang.Double valueOf(java.lang.String);
       public static boolean isNaN(double);
       public boolean isNaN();
       public static boolean isInfinite(double);
       public boolean isInfinite();
       public byte byteValue();
       public short shortValue();
       public int intValue();
       public long longValue();
       public float floatValue();
       public double doubleValue();
       public static double parseDouble(java.lang.String);
       public static native long doubleToLongBits(double);
       public static native long doubleToRawLongBits(double);
       public static native double longBitsToDouble(long);

       public static final double POSITIVE_INFINITY;
       public static final double NEGATIVE_INFINITY;
       public static final double NaN;
       public static final double MAX_VALUE;
       public static final double MIN_VALUE;
       public static final java.lang.Class TYPE;
       private double value;
       private static final long serialVersionUID;
    }
