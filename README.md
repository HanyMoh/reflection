This program shows you how to print out all information about a class. The program prompts you for the name of a class and writes out the signatures of all methods and constructors as well as the names of all instance fields of a class. For example, if you enter

    java.lang.Double

the program prints

Click here to view code image

  public final class java.lang.Double extends java.lang.Number
  {
  
  ---[Constructors]------------------------------
  public java.lang.Double(double);
  public java.lang.Double(java.lang.String);
  -----------------------------------------------

  ---[Methods]-----------------------------------
  public boolean equals(java.lang.Object);
  public static java.lang.String toString(double);
  public java.lang.String toString();
  public int hashCode();
  public static int hashCode(double);
  public static double min(double, double);
  public static double max(double, double);
  public static native long doubleToRawLongBits(double);
  public static long doubleToLongBits(double);
  public static native double longBitsToDouble(long);
  public volatile int compareTo(java.lang.Object);
  public int compareTo(java.lang.Double);
  public byte byteValue();
  public short shortValue();
  public int intValue();
  public long longValue();
  public float floatValue();
  public double doubleValue();
  public static java.lang.Double valueOf(java.lang.String);
  public static java.lang.Double valueOf(double);
  public static java.lang.String toHexString(double);
  public static int compare(double, double);
  public static boolean isNaN(double);
  public boolean isNaN();
  public static boolean isFinite(double);
  public static boolean isInfinite(double);
  public boolean isInfinite();
  public static double sum(double, double);
  public static double parseDouble(java.lang.String);
  ------------------------------------------------

  ---[Fields]-------------------------------------
  public static final double POSITIVE_INFINITY;
  public static final double NEGATIVE_INFINITY;
  public static final double NaN;
  public static final double MAX_VALUE;
  public static final double MIN_NORMAL;
  public static final double MIN_VALUE;
  public static final int MAX_EXPONENT;
  public static final int MIN_EXPONENT;
  public static final int SIZE;
  public static final int BYTES;
  public static final java.lang.Class TYPE;
  private final double value;
  private static final long serialVersionUID;
  ------------------------------------------------
} 
