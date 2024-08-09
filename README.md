## Java Data Types and Comments Example

```java
public class Main {
    public static void main(String[] args) {

        // It's just a single line comment
        
        /* This is an example of multi-line comment.
         * This program prints "Hello and welcome" to the standard output. 
         */
        /* 
        System.out.println("Hello and welcome!");
        System.out.println("Hello and welcome!");
        System.out.println("Hello and welcome!"); 
        */

        // int speedlimit = 80;
        // float milk = 2.5;
        // char c = 'H';

        // System.out.println(speedlimit);

        /*
         * Primitive data types
         * 1. Boolean (true or false)
         * 2. byte  -128 to 127 (8-bit 2's compliment)
         * 3. short   -32768 to 32767
         * 4. int     -2^31 to 2^31-1   (32-bit 2's compliment)
         * 5. long     -2^63 to 2^63-1   (32-bit 2's compliment)
         * 6. double   64-bit floating type
         * 7. float    32-bit floating type
         * 8. char     16-bit Unicode character
         */

        // boolean flag = true;
        // flag = false;
        // System.out.println(flag);

        // byte range;
        // range = -128;
        // System.out.println(range);

        // short temperature = -200;
        // System.out.println(temperature);

        // int range = 1722928701;
        // System.out.println(range);

        // long range = 17229287019990L;
        // System.out.println(range);

        // double number = 42.66;
        // System.out.println(number);

        // float number = 42.68f;
        // System.out.println(number);

        // char letter = '\u0051';
        // System.out.println(letter);

        // char letter1 = '9';
        // System.out.println(letter1);
        // char letter2 = 65;
        // System.out.println(letter2);

        // String myString = "Java Programming";
        // System.out.println(myString);
    }
}











## Java Operators Example

```java
public class Main {
    public static void main(String[] args) {

        /*
        * 1. Arithmetic Operator (+,-,*,/,%)
        * 2. Assignment Operator  (assign values into variable) (=, +=, -=, *=, /=, %=)
        * 3. Relational Operator  (true / false return) (==, !=, >, <, >=, <=)
        * 4. Logical Operator (check whether expression is true or false) (&&-Logical AND, ||-Logical OR, !-Logical NOT)
        * 5. Unary Operator  incremental operator, decremental operator (+, - , ++,--,!)
        * 6. Bitwise Operator(~, <<. >>, >>>, &, ^)
        * */

        //Arithmetic operator
        /*
        int a = 12, b = 5;

        System.out.println("a + b = " + (a + b));
        System.out.println("a - b = " + (a - b));
        System.out.println("a * b = " + (a * b));
        System.out.println("a / b = " + (a / b));
        System.out.println("a % b = " + (a % b));
        */

        //assignment operator

        //creating variables
       /*
        int a = 4;
        int var;

        var = a;
        System.out.println("var is using =: " + var);

        var += a;
        System.out.println("var is using =: " + var);

        var -= a;
        System.out.println("var is using =: " + var);

        var *= a;
        System.out.println("var is using =: " + var);
        */

        // Relational operator

        //creating variables
       /*
        int a = 7, b = 10;

        System.out.println("a is " + a + " and b is " + b);

        System.out.println( a == b );
        System.out.println( a != b );
        System.out.println( a > b );
        System.out.println( a < b );
        System.out.println( a >= b );
        System.out.println( a <= b );
        */

        //logical operators

//        && operator
//        System.out.println((5>3) && (8>5));
//        System.out.println((5>3) && (8<5));
//
//        //        || operator
//        System.out.println((5<3) || (8>5));
//        System.out.println((5>3) || (8<5));
//        System.out.println((5<3) || (8<5));
//
//        //        ! operator
//        System.out.println(!(5==3));    !false = true
//        System.out.println(!(5>3));     true -> !true = false


        //unary operator
//        int num = 5;
//        ++num;
//
//        System.out.println(num);

    }
}
