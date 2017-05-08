# HAHAH


/**
 * Created by Administrator on 2017/3/19.
 */
public class HumenTest {

    double height;
   boolean ismarried;
    String name;

    public HumenTest(double height, boolean ismarried, String name) {
        this.height = height;
        this.ismarried = ismarried;
        this.name = name;
    }

    public static void main(String[] args) {
       HumenTest d = new HumenTest(1.8, true,"sam");
//        System.out.println(d.height);
//        System.out.println(d.ismarried);
//        System.out.println(d.name);
        //或者
      System.out.println(d.height +"" + d.ismarried +""+ d.name);
    }

}
