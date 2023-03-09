# Code

public class lianxi001 {
    public static void main(String[] args) {
        System.out.println(10+15);
        System.out.println(10-15);
        System.out.println(10*15);
        System.out.println(10/15.0);
        System.out.println((1+2+3)*4/5.0);
        System.out.println(2*5+2*5*5+3*5*5*5);

        int a = 3;
        int b = 5;
        int c = 7;

        int x = 9;
        int y = a*x + b*x*x +c*x*x*x;
        System.out.println(y);

    }
}


public class lianxi002 {
    public static void main(String[] args) {
        System.out.println(1<2);
        System.out.println(1>2);
        System.out.println("A B C");
        System.out.println('b');

        byte byteVar = 99;
        System.out.println(byteVar);
        short shortVar = -32500;
        System.out.println(shortVar);
        int intVar = -2133333333;
        System.out.println(intVar);
        long longVar = 99;
        long bigLongVar = 99999999999L;
        System.out.println(bigLongVar);

        float floatVar = 100.2222222222F;
        System.out.println(floatVar);
        double doubleVar = 100.2222222222;
        System.out.println(doubleVar);
        boolean condition = true;
        boolean fcondotion = false;
        System.out.println(condition);
        char ch = 'A';
        System.out.println(ch);
    }
}


public class lianxi003 {
    public static void main (String[]args){
        int a = 2;
        System.out.println(a + 5);
        System.out.println(a);
        a = a + 7;
        System.out.println(a);

        int num = 10;
        System.out.println(num % 2);
        System.out.println(num % -3);
        System.out.println(num % 4);
        System.out.println(num % 5);
        System.out.println(num % -6);

        int b = 10;
        int c = 3;
        System.out.println(b / c);
        double e = 3.0;
        System.out.println(b / e);

        int f = 10;
        int g = 15;
        int h = 10;
        System.out.println(f > g);
        System.out.println(f >= g);
        System.out.println(f < g);
        System.out.println(f <= g);
        System.out.println(f != g);

        System.out.println(f != h);
        System.out.println(f >= h);
        System.out.println(f <= h);
        System.out.println(f == g);
        System.out.println(f == h);

        boolean i = true;
        boolean j = false;
        System.out.println(i && j);
        System.out.println(i & j);
        System.out.println(i || j);
        System.out.println(i | j);

        int k = 12;
        int l = 10;
        boolean m = ((k+l) * k - 9 * (k+l)) == 3 * (k+l);
        System.out.println(m);
    }
}


public class lianxi004 {
    public static void main(String[] arag){
        int a = 05;
        int b = 011;
        int c = 0xf;
        int d = 0x11;
        System.out.println(a);
        System.out.println(b);
        System.out.println(c);
        System.out.println(d);

        int e = 0xF8;
        int f = 0xF4;
        int g = 0xFF;
        System.out.println(e & f);
        System.out.println(e | f);
        System.out.println(e ^ f);
        System.out.println(~g);

        int h = 0x400;
        System.out.println(h);
        System.out.println(h >> 1);
        System.out.println(h >> 2);
        System.out.println(h << 1);
        System.out.println(h << 2);
        int i = -0x400;
        System.out.println(i);
        System.out.println(i >> 1);
        System.out.println(i >> 2);
        System.out.println(i << 1);
        System.out.println(i << 2);
        System.out.println(i >>> 1);
        System.out.println(i >>> 2);

        int base = 1;
        int is_student_mask = base;//0001
        int is_programmer_mask = base << 1;//0010
        int is_driver_mask = base << 2;//0100
        int is_painter_mask = base << 3;//1000
        int data = 5;//二进制是0101
        boolean isStudent = (data & is_student_mask) !=0;//0101 & 0001 = 1
        System.out.println(isStudent);
        boolean isProgrammer = (data & is_programmer_mask) !=0;//0101 & 0010 = 0
        System.out.println(isProgrammer);
        boolean isDriver = (data & is_driver_mask) !=0;//0101 & 0100 = 0100
        System.out.println(isDriver);
        boolean isPainter = (data & is_painter_mask) !=0;//0101 & 1000 = 0
        System.out.println(isPainter);
    }
}


public class Lianxi005 {
    public static void main(String[] args) {
        String content = "a\tb\tcc\n\tee\t";
        String align = "1111222233334444";
        System.out.println(content);
        System.out.println(align);

        int a = 65;
        char cha = (char) a;
        char zhu = '\u6731';//朱
        char peng = '\u9e4f';//鹏
        char  kai = '\u51ef';//凯
        System.out.println(cha);
        System.out.println(zhu);
        System.out.println(peng);
        System.out.println(kai);

       int a = 10;
       int b = 20;
       int c = a + b;
       System.out.println("a + b=" + c);
       boolean aBiggerThanB = a > b;
       System.out.println("a > b 是"+ aBiggerThanB + "的");
       System.out.println("a + b =" + a + b);
       System.out.println("a + b ="+ (a+b));
       System.out.println("a * b =" + a * b);

       int a = 10;
       String str = "a的值是";
       System.out.println(str);
       String s2 = "a的值是";
       System.out.println(s2+a);
       System.out.println(s2);
       
       int a = 10;
       System.out.println("a++=" + a++);
       System.out.println("a++=" + a);
       System.out.println("++a=" + ++a);
       System.out.println("++a=" + a);
    }
}

public class Lianxi006 {
    public static void main(String[] args) {
      char ch = 'A';
      int num = ch;
        System.out.println(num+"\t"+((char)(num++)));
        System.out.println(num+"\t"+((char)(num++)));
        System.out.println(num+"\t"+((char)(num++)));
        System.out.println(num+"\t"+((char)(num++)));
        System.out.println(num+"\t"+((char)(num++)));
        System.out.println(num+"\t"+((char)(num++)));
        System.out.println(num+"\t"+((char)(num++)));
        System.out.println(num+"\t"+((char)(num++)));
        System.out.println(num+"\t"+((char)(num++)));
        System.out.println(num+"\t"+((char)(num++)));
        System.out.println(num+"\t"+((char)(num++)));
        System.out.println(num+"\t"+((char)(num++)));
        System.out.println(num+"\t"+((char)(num++)));
        System.out.println(num+"\t"+((char)(num++)));
        System.out.println(num+"\t"+((char)(num++)));
        System.out.println(num+"\t"+((char)(num++)));
        System.out.println(num+"\t"+((char)(num++)));
        System.out.println(num+"\t"+((char)(num++)));
        System.out.println(num+"\t"+((char)(num++)));
        System.out.println(num+"\t"+((char)(num++)));
        System.out.println(num+"\t"+((char)(num++)));
        System.out.println(num+"\t"+((char)(num++)));
        System.out.println(num+"\t"+((char)(num++)));
        System.out.println(num+"\t"+((char)(num++)));
        System.out.println(num+"\t"+((char)(num++)));
        System.out.println(num+"\t"+((char)(num++)));
    }
}

public class Lianxi007 {
public static void main(String[]args){
    int div = 77;
    int divsor = 9;
    System.out.println(div+"可以整除"+divsor+"吗？"+(div++%divsor == 0));
    System.out.println(div+"可以整除"+divsor+"吗？"+(div++%divsor == 0));
    System.out.println(div+"可以整除"+divsor+"吗？"+(div++%divsor == 0));
    System.out.println(div+"可以整除"+divsor+"吗？"+(div++%divsor == 0));
    System.out.println(div+"可以整除"+divsor+"吗？"+(div++%divsor == 0));
    System.out.println(div+"可以整除"+divsor+"吗？"+(div++%divsor == 0));
    System.out.println(div+"可以整除"+divsor+"吗？"+(div++%divsor == 0));
    System.out.println(div+"可以整除"+divsor+"吗？"+(div++%divsor == 0));
    System.out.println(div+"可以整除"+divsor+"吗？"+(div++%divsor == 0));
    System.out.println(div+"可以整除"+divsor+"吗？"+(div++%divsor == 0));
    System.out.println(div+"可以整除"+divsor+"吗？"+(div++%divsor == 0));
    System.out.println(div+"可以整除"+divsor+"吗？"+(div++%divsor == 0));
    System.out.println(div+"可以整除"+divsor+"吗？"+(div++%divsor == 0));
    System.out.println(div+"可以整除"+divsor+"吗？"+(div++%divsor == 0));
    System.out.println(div+"可以整除"+divsor+"吗？"+(div++%divsor == 0));
    System.out.println(div+"可以整除"+divsor+"吗？"+(div++%divsor == 0));
    System.out.println(div+"可以整除"+divsor+"吗？"+(div++%divsor == 0));
    System.out.println(div+"可以整除"+divsor+"吗？"+(div++%divsor == 0));
    System.out.println(div+"可以整除"+divsor+"吗？"+(div++%divsor == 0));
    System.out.println(div+"可以整除"+divsor+"吗？"+(div++%divsor == 0));
    System.out.println(div+"可以整除"+divsor+"吗？"+(div++%divsor == 0));
    System.out.println(div+"可以整除"+divsor+"吗？"+(div++%divsor == 0));
    System.out.println(div+"可以整除"+divsor+"吗？"+(div++%divsor == 0));
    System.out.println(div+"可以整除"+divsor+"吗？"+(div++%divsor == 0));
    System.out.println(div+"可以整除"+divsor+"吗？"+(div++%divsor == 0));
    System.out.println(div+"可以整除"+divsor+"吗？"+(div++%divsor == 0));
    System.out.println(div+"可以整除"+divsor+"吗？"+(div++%divsor == 0));
    System.out.println(div+"可以整除"+divsor+"吗？"+(div++%divsor == 0));
    System.out.println(div+"可以整除"+divsor+"吗？"+(div++%divsor == 0));
    System.out.println(div+"可以整除"+divsor+"吗？"+(div++%divsor == 0));
    System.out.println(div+"可以整除"+divsor+"吗？"+(div++%divsor == 0));
    System.out.println(div+"可以整除"+divsor+"吗？"+(div++%divsor == 0));
    System.out.println(div+"可以整除"+divsor+"吗？"+(div++%divsor == 0));
    System.out.println(div+"可以整除"+divsor+"吗？"+(div++%divsor == 0));
    System.out.println(div+"可以整除"+divsor+"吗？"+(div++%divsor == 0));
    System.out.println(div+"可以整除"+divsor+"吗？"+(div++%divsor == 0));
    System.out.println(div+"可以整除"+divsor+"吗？"+(div++%divsor == 0));
    System.out.println(div+"可以整除"+divsor+"吗？"+(div++%divsor == 0));
    System.out.println(div+"可以整除"+divsor+"吗？"+(div++%divsor == 0));
    System.out.println(div+"可以整除"+divsor+"吗？"+(div++%divsor == 0));
    System.out.println(div+"可以整除"+divsor+"吗？"+(div++%divsor == 0));
    System.out.println(div+"可以整除"+divsor+"吗？"+(div++%divsor == 0));
    System.out.println(div+"可以整除"+divsor+"吗？"+(div++%divsor == 0));
    System.out.println(div+"可以整除"+divsor+"吗？"+(div++%divsor == 0));
    System.out.println(div+"可以整除"+divsor+"吗？"+(div++%divsor == 0));
    System.out.println(div+"可以整除"+divsor+"吗？"+(div++%divsor == 0));
    System.out.println(div+"可以整除"+divsor+"吗？"+(div++%divsor == 0));
    System.out.println(div+"可以整除"+divsor+"吗？"+(div++%divsor == 0));
    System.out.println(div+"可以整除"+divsor+"吗？"+(div++%divsor == 0));
    System.out.println(div+"可以整除"+divsor+"吗？"+(div++%divsor == 0));
    System.out.println(div+"可以整除"+divsor+"吗？"+(div++%divsor == 0));
    System.out.println(div+"可以整除"+divsor+"吗？"+(div++%divsor == 0));
    System.out.println(div+"可以整除"+divsor+"吗？"+(div++%divsor == 0));
    System.out.println(div+"可以整除"+divsor+"吗？"+(div++%divsor == 0));
    System.out.println(div+"可以整除"+divsor+"吗？"+(div++%divsor == 0));
    System.out.println(div+"可以整除"+divsor+"吗？"+(div++%divsor == 0));
    System.out.println(div+"可以整除"+divsor+"吗？"+(div++%divsor == 0));
    System.out.println(div+"可以整除"+divsor+"吗？"+(div++%divsor == 0));
    System.out.println(div+"可以整除"+divsor+"吗？"+(div++%divsor == 0));
    System.out.println(div+"可以整除"+divsor+"吗？"+(div++%divsor == 0));
    System.out.println(div+"可以整除"+divsor+"吗？"+(div++%divsor == 0));
    System.out.println(div+"可以整除"+divsor+"吗？"+(div++%divsor == 0));
    System.out.println(div+"可以整除"+divsor+"吗？"+(div++%divsor == 0));
    System.out.println(div+"可以整除"+divsor+"吗？"+(div++%divsor == 0));
    System.out.println(div+"可以整除"+divsor+"吗？"+(div++%divsor == 0));
    System.out.println(div+"可以整除"+divsor+"吗？"+(div++%divsor == 0));
    System.out.println(div+"可以整除"+divsor+"吗？"+(div++%divsor == 0));
    System.out.println(div+"可以整除"+divsor+"吗？"+(div++%divsor == 0));
    System.out.println(div+"可以整除"+divsor+"吗？"+(div++%divsor == 0));
    System.out.println(div+"可以整除"+divsor+"吗？"+(div++%divsor == 0));
    System.out.println(div+"可以整除"+divsor+"吗？"+(div++%divsor == 0));
    System.out.println(div+"可以整除"+divsor+"吗？"+(div++%divsor == 0));
    System.out.println(div+"可以整除"+divsor+"吗？"+(div++%divsor == 0));
    System.out.println(div+"可以整除"+divsor+"吗？"+(div++%divsor == 0));
    System.out.println(div+"可以整除"+divsor+"吗？"+(div++%divsor == 0));
    System.out.println(div+"可以整除"+divsor+"吗？"+(div++%divsor == 0));
    System.out.println(div+"可以整除"+divsor+"吗？"+(div++%divsor == 0));
    System.out.println(div+"可以整除"+divsor+"吗？"+(div++%divsor == 0));
    System.out.println(div+"可以整除"+divsor+"吗？"+(div++%divsor == 0));
    System.out.println(div+"可以整除"+divsor+"吗？"+(div++%divsor == 0));
    System.out.println(div+"可以整除"+divsor+"吗？"+(div++%divsor == 0));
    System.out.println(div+"可以整除"+divsor+"吗？"+(div++%divsor == 0));
    System.out.println(div+"可以整除"+divsor+"吗？"+(div++%divsor == 0));
    System.out.println(div+"可以整除"+divsor+"吗？"+(div++%divsor == 0));
    System.out.println(div+"可以整除"+divsor+"吗？"+(div++%divsor == 0));
    System.out.println(div+"可以整除"+divsor+"吗？"+(div++%divsor == 0));
    System.out.println(div+"可以整除"+divsor+"吗？"+(div++%divsor == 0));
    System.out.println(div+"可以整除"+divsor+"吗？"+(div++%divsor == 0));
    System.out.println(div+"可以整除"+divsor+"吗？"+(div++%divsor == 0));
    System.out.println(div+"可以整除"+divsor+"吗？"+(div++%divsor == 0));
    System.out.println(div+"可以整除"+divsor+"吗？"+(div++%divsor == 0));
    System.out.println(div+"可以整除"+divsor+"吗？"+(div++%divsor == 0));
    System.out.println(div+"可以整除"+divsor+"吗？"+(div++%divsor == 0));
    System.out.println(div+"可以整除"+divsor+"吗？"+(div++%divsor == 0));
    System.out.println(div+"可以整除"+divsor+"吗？"+(div++%divsor == 0));
    System.out.println(div+"可以整除"+divsor+"吗？"+(div++%divsor == 0));
    System.out.println(div+"可以整除"+divsor+"吗？"+(div++%divsor == 0));
    System.out.println(div+"可以整除"+divsor+"吗？"+(div++%divsor == 0));
    System.out.println(div+"可以整除"+divsor+"吗？"+(div++%divsor == 0));
    System.out.println(div+"可以整除"+divsor+"吗？"+(div++%divsor == 0));
   }
} 








