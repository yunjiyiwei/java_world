# java_world
A new warehouse
public class QianZhiZhuangHuan1{
    public static void main(String[]args){
        int qi=123;                        //定义一个int类型
        byte w1=(byte)qi;                   //强制类型转换为byte
        System.out.println("int 强制类型转换 byte 后值等于"+w1);
    }
}

public class QianZhiZhuangHuan2{
    public static void main(String[]agrs){
        int  yi=128;                      //定义一个 int 类型
        byte ui=(byte)yi;                 //强制类型转换为 byte
        System.out.println("int 强制类型转换 byte 后值等于"+ui);
        double r1=123.456;                //定义一个 double 类型
        int    e1=(int)r1;                //强制类型转换为 int
        System.out.println("double 强制类型转换 int 后值等于"+e1);

    }
}

public class QianZhiZhuangHuan3{
    public static void main(String[]args){
        char i1='A';
        int  io=i1+0;
        char i9=(char)io;
        System.out.println(i9);
    }
}
