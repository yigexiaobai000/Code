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

public class Lianxi008 {
public static void main(String[]args){
   int roujiamo = 1;
   Boolean roujiamoReHuDe = true;
   if (roujiamoReHuDe){
      roujiamo = roujiamo+2;
      System.out.println("肉夹馍是刚出炉的，买了" +roujiamo+ "个");
   }else {
      System.out.println("肉夹馍是热的，买了" +roujiamo+ "个");
     }
   }
} 

public class Lianxi009 {
    public static void main(String[] args) {
        int a = 89;
        int b = 2;
        if (a % b == 0) {
            System.out.println(a + "可以整除" + b + ",商是" +(a / b));
        }
        a++;
        if (a % b == 0) {
            System.out.println(a + "可以整除" + b + ",商是" +(a / b));
        }
        a++;
        if (a % b == 0) {
            System.out.println(a + "可以整除" + b + ",商是" +(a / b));
        }
        a++;
        if (a % b == 0) {
            System.out.println(a + "可以整除" + b + ",商是" +(a / b));
        }
        a++;
        if (a % b == 0) {
            System.out.println(a + "可以整除" + b + ",商是" +(a / b));
        }
        a++;
        if (a % b == 0) {
            System.out.println(a + "可以整除" + b + ",商是" +(a / b));
        }
        a++;
        if (a % b == 0) {
            System.out.println(a + "可以整除" + b + ",商是" +(a / b));
        }
        a++;
        if (a % b == 0) {
            System.out.println(a + "可以整除" + b + ",商是" +(a / b));
        }
        a++;
        if (a % b == 0) {
            System.out.println(a + "可以整除" + b + ",商是" +(a / b));
        }
        a++;
        if (a % b == 0) {
            System.out.println(a + "可以整除" + b + ",商是" +(a / b));
        }
        a++;
        if (a % b == 0) {
            System.out.println(a + "可以整除" + b + ",商是" +(a / b));
        }
        a++;
        if (a % b == 0) {
            System.out.println(a + "可以整除" + b + ",商是" +(a / b));
        }
        a++;
        if (a % b == 0) {
            System.out.println(a + "可以整除" + b + ",商是" +(a / b));
        }
        a++;
        if (a % b == 0) {
            System.out.println(a + "可以整除" + b + ",商是" +(a / b));
        }
        a++;

    }
}

public class Lianxi010 {
    public static void main(String[] agrs) {
        int a = 11;
        int b = 11;
        int c = 12;
        if (a == b && b == c) {
            System.out.println("a,b,c等大,值为" + a);
        } else if (a > b && a > c) {
            System.out.println("a的值最大，值为" + a);
        } else if (b > a && b > c) {
            System.out.println("b的值最大，值为" + b);
        } else if (c > a && c > b) {
            System.out.println("c的值最大，值为" + c);
        } else if (a == b && b > c) {
            System.out.println("a,b等大且值为" + a);
        } else if (a == c && a > b) {
            System.out.println("a,c等大且值为" + a);
        } else if (b == c && c > a) {
            System.out.println("b,c等大且值为" + b);
        }
    }
}

public class Lianxi011 {
    public static void main(String[] args) {
        char ch = 'A';
        int startNum = ch;
        for (int a = 0; a < 26; a++) {
            System.out.println((startNum + a) + "\t" + (char) (startNum + a));
        }
    }
}

public class Lianxi012 {
    public static void main(String[] args) {
        int divided = 100;
        int divisor = 3;
        for (int i = 0; i < 100 ; i++) {
            if (divided % divisor == 0) {
                System.out.println(divided + "可以整除" + divisor + "，的商是" + (divided / divisor));
                }
            divided++;
        }
    }
}

public class Lianxi013 {
    public static void main(String[] args) {
        int divided = 100;
        int divisor = 3;
        int found = 0;
        for (int i = 0; i < 100 && found<10; i++) {
            if (divided % divisor == 0) {
                System.out.println(divided + "可以整除" + divisor + "，的商是" + (divided / divisor));
                found++;
            }
            divided++;
        }
    }
}

public class Lianxi014 {
    public static void main(String[] args) {
        int divided = 100;
        int divisor = 3;
        int found = 0;
        int toBefound = 10;
        for (int i = 0; i < 100 ; i++) {
            if (divided % divisor == 0) {
                System.out.println(divided + "可以整除" + divisor + "，的商是" + (divided / divisor));
                found++;
            }
            if (found >= toBefound){
                System.out.println("程序已经找到"+toBefound+"个数，程序退出");
              break;
            }
            divided++;
        }
    }
}

public class Lianxi015 {
    public static void main(String[] args) {
        int divided = 1;
        int divisor = 7;
        int found = 0;
        int toBefound = 10;
        for (int i = 0; i < 100 ; i++) {
            if (divided<divisor ){
                System.out.println(divided+"小于"+divisor+"程序跳出");
                divided++;
            }
            if (divided % divisor == 0) {
                System.out.println(divided + "可以整除" + divisor + "，的商是" + (divided / divisor));
                found++;
            }
            if (found >= toBefound){
                System.out.println("程序已经找到"+toBefound+"个数，程序退出");break;
            }
            divided++;
        }
    }
}


public class Lianxi016 {
    public static void main(String[] args) {
        int outer = 100;
        {
            int inner = 10;
            System.out.println("outer的变量值是"+outer+"\t"+"inner的变量值是"+inner);
        }int a1 = 1;
        {
            int a2 =a1+1;
            {
                int a3 = a2+1;
                System.out.println("a3的值为"+a3);
            }
            {
                int a3 = a2+10;
                System.out.println("a3的值为"+a3);
            }
            System.out.println("a2的值为"+a2);
        }
    }
}


public class Lianxi017 {
    public static void main(String[] args) {
        for (int i = 1; i <= 9; i++) {
            String line = "";
            for (int j = 1; j <= 9; j++) {
                if (j > i) {
                    break;
                }
                line += i + "*" + j +"="+ i * j + "\t";
            }
            System.out.println(line);
        }
    }
}


public class Lianxi018 {
    public static void main(String[]agrs){
        int n =12;//找出12个符合的结果

        int dividend=100;
        int divisor=89;
        int found= 0;//第一次没找到
        while (found<n){
            if (dividend%divisor==0){
                found++;
                System.out.println(dividend+"可以整除"+divisor+"的，商为:"+(dividend/divisor));
            }
            dividend++;
        }
    }
}

public class Lianxi019 {
    public static void main(String[] agrs) {
        do {
            System.out.println("do-while会执行一次");
        } while (false);
        for (int i = 0; i > 4; i++) {
            System.out.println("for一次都不会执行");
        }
    }
}


public class Lianxi020 {
    public static void main(String[]agrs){
        int n =10;

        int dividend=125;
        int divisor=36;
        int found= 0;
        while (found<n){
            if (dividend%divisor==0){
                   //found++;
                System.out.println(dividend+"可以整除"+divisor+"的，商为:"+(dividend/divisor));
            }
            dividend++;
        }
    }
}


public class Lianxi021 {
    public static void main(String[]agrs){
        int n =5;

        int dividend=100;
        int divisor=2000000000;
        int found= 0;
        while (found<n){
            if (dividend%divisor==0){
                System.out.println(dividend+"可以整除"+divisor+"的，商为:"+(dividend/divisor));
            }
            dividend++;
        }
    }
}


public class Lianxi022 {
    public static void main(String[] agrs) {
        int n = 10;

        int dividend = 100;
        int divisor = 89;
        int found = 0;
        String start = "从" + dividend + "开始";
        while (found < n) {
            if (dividend < 0) {
                System.out.println("被除数溢出，计算结束。");
                break;
            }
            if (dividend % divisor == 0) {
                found++;
                System.out.println(dividend + "可以整除" + divisor + "的，商为:" + (dividend / divisor));
            }
            dividend++;
        }
        System.out.println(start + "共找到" + found + "个可以整除" + divisor + "的数。");
        System.out.println(dividend);
    }
}

public class Lianxi023 {
    public static void main(String[] args) {
        int n = 5;
        String str = n + "对应的中文数字是：";
        if (n == 1) {
            str += "壹";
        } else if (n == 2) {
            str += "贰";
        } else if (n == 3) {
            str += "叁";
        } else if (n == 4) {
            str += "肆";
        } else if (n == 5) {
            str += "伍";
        } else if (n == 6) {
            str += "陆";
        } else if (n == 7) {
            str += "柒";
        } else if (n == 8) {
            str += "捌";
        } else if (n == 9) {
            str += "玖";
        } else {
            System.out.println("数字应该是1到9之间的数，否则无效");
        }
        System.out.println(str);
    }
}

public class Lianxi024 {
    public static void main(String[] args) {
        int n = 5;
        String srt = n + "对应的中文数字是：";
        switch (n) {
            case 1:
                srt += "壹";
                break;
            case 2:
                srt += "贰";
                break;
            case 3:
                srt += "叁";
                break;
            case 4:
                srt += "肆";
                break;
            case 5:
                srt += "伍";
                break;
            case 6:
                srt += "陆";
                break;
            case 7:
                srt += "柒";
                break;
            case 8:
                srt += "捌";
                break;
            case 9:
                srt += "玖";
                break;
            default:
                System.out.println("错误的值" + n + ".值需要大于等于1，小于等于9。");
        }
        System.out.println(srt);
    }
}

public class Lianxi025 {
    public static void main(String[] args) {
        double randNum = 0;
        //要生成一大于0.5的随机数，只有随机数大于0.5，程序循环才会退出
        while (randNum < 0.5) {
            //使用java中的Math.random（），生成一个随机数
            randNum = Math.random();
            System.out.println(randNum);
        }
        System.out.println("生成的大于0.5的随机数是" + randNum);
        int rangeStart = 30;
        int rangeEed = 90;
        int mod = rangeEed - rangeStart;
        for (int i = 0; i < 50; i++) {
            int bigRandom = (int) (Math.random() * rangeEed * 100);
            int numberToGuess = (bigRandom % mod) + rangeStart;
            System.out.println("mod" + mod + ",numberToGuess=" + numberToGuess);
        }
    }
}

public class Lianxi025 {
    public static void main(String[] args) {
        double randNum = 0;
        //要生成一大于0.5的随机数，只有随机数大于0.5，程序循环才会退出
        while (randNum < 0.5) {
            //使用java中的Math.random（），生成一个随机数
            randNum = Math.random();
            System.out.println(randNum);
        }
        System.out.println("生成的大于0.5的随机数是" + randNum);
        int rangeStart = 30;
        int rangeEed = 90;
        int mod = rangeEed - rangeStart;
        if(rangeStart<0 || rangeEed<0){
            System.out.println("开始和结束必须是正数或者0");
        }
        if (mod<=1){
            System.out.println("非法的数字范围：（"+rangeStart+","+rangeEed+")");
        }
        for (int i = 0; i < 50; i++) {
            int bigRandom = (int) (Math.random() * rangeEed * 100);
            int numberToGuess = (bigRandom % mod) + rangeStart;
            if (numberToGuess<=rangeStart){
                numberToGuess=rangeStart+1;
            } else if (numberToGuess>rangeEed) {
                numberToGuess = rangeEed-1;
            }
            System.out.println("mod" + mod + ",numberToGuess=" + numberToGuess);
        }
    }
}


public class Lianxi026 {
   public static void main(String[]args){
       Scanner in =new Scanner(System.in);
       System.out.println("请问你的名字是？");
       String str = in.nextLine();
       System.out.println(str+",你好。");
       System.out.println("请问你几岁了?");
       int age= in.nextInt();
       System.out.println("好的，"+str+age+"岁了。");
   }
}


import java.util.Scanner;

public class Lianxi027 {
    public static void main(String[] args) {
        //创建Scanner来读取用户键盘输入
        Scanner in = new Scanner(System.in);
        //游戏的设置
        int rangeStart = 30;
        int rangeEnd = 50;
        int guessTotal = 5;
        //游戏统计
        int totalGameCount = 0;
        int correctGuessCoun = 0;
        //是否结束游戏
        boolean gameEnd = false;
        while (!gameEnd) {

            //生成指定范围内的随机数
            int mod = rangeEnd - rangeStart;
            if (rangeStart < 0 || rangeEnd < 0) {
                System.out.println("开始和结束必须是正数或者0");
            }
            if (mod <= 1) {
                System.out.println("非法的数字范围:(" + rangeStart + "," + rangeEnd + ")");
            }
            int bigRandom = (int) (Math.random() * rangeEnd * 100);
            int numberToGuess = (bigRandom % mod) + rangeStart;
            if (numberToGuess <= rangeStart) {
                numberToGuess = rangeStart + 1;
            } else if (numberToGuess > rangeEnd) {
                numberToGuess = rangeEnd - 1;
            }
            //剩余的猜测次数
            int leftToGuess = guessTotal;
            boolean currentGameCounted = false;
            boolean correctGuess = false;

            System.out.println("请输入猜测的数字，范围在（" + rangeStart + "," + rangeEnd + ").输入-1代表结束游戏：");
            while (leftToGuess > 0) {
                System.out.println("剩余猜测次数" + leftToGuess + ".请输入本次猜测的数字：");
                int guess = in.nextInt();
                if (guess < 0) {
                    gameEnd = true;
                    System.out.println("用户选择结束游戏。");
                    break;
                }
                if (!currentGameCounted) {
                    totalGameCount++;
                    currentGameCounted = true;
                }
                leftToGuess--;
                if (guess > numberToGuess) {
                    System.out.println("输入的数字比目标数字大");
                } else if (guess < numberToGuess) {
                    System.out.println("输入的数字比目标数字小");
                } else {
                    correctGuessCoun++;
                    correctGuess = true;
                    System.out.println("输入的数字正确！");
                    break;
                }
            }
            if (!correctGuess){
                System.out.println("本次的目标数字是："+numberToGuess);
            }
            System.out.println("共进行了" + totalGameCount + "次游戏，其中猜中的次数为" + correctGuessCoun);
        }
    }
}

public class Lianxi028 {
    public static void main(String[] args) {
        //每门成绩对应的索引
        int YuWen = 0;
        int ShuXue = 1;
        int WaiYu = 2;
        int WuLi = 3;
        int HuaXue = 4;
        int ShengWu = 5;

        int totalScoreCount = 6;
        double[] scores = new double[totalScoreCount];

        String[] scoreNames = new String[totalScoreCount];
        scoreNames[YuWen] = "语文";
        scoreNames[ShuXue] = "数学";
        scoreNames[WaiYu] = "外语";
        scoreNames[WuLi] = "物理";
        scoreNames[HuaXue] = "化学";
        scoreNames[ShengWu] = "生物";

        for (int i = 0; i < totalScoreCount; i++) {
            scores[i] = 80 + Math.random() * 20;
            System.out.println(scoreNames[i] + "的成绩是：" + scores[i]);
        }
        double maxScore = 0;
        int maxScoreIndxe = -1;

        for (int i = 0; i < totalScoreCount; i++) {
            if (scores[i] > maxScore) {
                maxScore = scores[i];
                maxScoreIndxe = i;

            }
        }
System.out.println("最好的成绩是"+scoreNames[maxScoreIndxe]+":"+maxScore);
    }
}


public class Lianxi029 {
 public static void main(String[]args){
     Scanner in =new Scanner(System.in);

     int a;
     System.out.println("创建了变量a，输入一个整数：");
     a=in.nextInt();
     System.out.println("给a赋值，a的值为"+a+",请再次输入一个整数；");

     a=in.nextInt();
     System.out.println("再次给赋值，现在a的值为"+a);
 }
}









