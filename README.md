# Operators
Javascripts

public class Operators {
    public static void main(String[] args) {

        //Assignment operators
        int x = 5;
        System.out.println("x = " + x);

        //Addition assignment
        int y = 10;
        y += 5;
        //y=y+5 bunun yerine kisaca y+=5 yazilir
        System.out.println("y = " + y);

       //subtractors assignment
        int z = 10;
        z -= 5;
        System.out.println("z = " + z);

        //multiplication assignment
        int e = 10;
        e *= 5;
        System.out.println("e = " + e);


        //division assignment
        int t = 100;
        t /= 10;
        System.out.println("t = " + t);


        //Task assignment  10 ata, _ ekle, ikiye bol, 7 ile carp
        int assignment = 10;
        assignment += 8;
        System.out.println("assignment= " + assignment);
        assignment /= 2;
        System.out.println("assignment= " + assignment);
        assignment *= 7;
        System.out.println("assignment= " + assignment);

        //remairing assignment
        int m = 11;
        m %= 2;
        System.out.println("m=" + m);
        int number = 112;
        number %= 10;
        System.out.println("number= " + number);

        //example
        int vv = 789;
        vv %= 6;
        System.out.println("vv= " + vv);


        //Comparison OPerators esit (equal)
        int xx = 5;
        int yy = 5;
        int zz = 6;
        System.out.println(xx == yy);
        System.out.println(xx == zz);


        //esit degil != not equal

        System.out.println(xx != yy);
        System.out.println(xx != zz);

        //greater daha buyuk

        System.out.println(xx > yy);
        System.out.println(zz > xx);

        //leasten daha kucuk

        System.out.println(xx < yy);
        System.out.println(xx < zz);


        // >=
        System.out.println(xx >= yy);
        System.out.println(xx >= zz);


        // <=

        System.out.println(xx <= yy);
        System.out.println(zz <= yy);

        //LOgical operators

         //logical &&

        boolean xy = true;
        boolean ab = true;
        boolean cd = false;

        System.out.println(xx == yy && xx >= yy);
        System.out.println(xx > yy && zz <= yy);
        System.out.println(xy && ab);

        //logical veya: OR:(||)
        int xxx = 5;
        int yyy = 5;
        int zzz = 6;

        System.out.println(xxx > yyy || yyy > yyy);  // false
        System.out.println(xxx < yyy || zzz > yyy);

        //logical not
        boolean statu_1 = true;
        boolean statu_2 = false;
        System.out.println(!(statu_1));     // false
        System.out.println(!(statu_2));

        int b = 2;
        int r = 2;
        int j = 3;

        System.out.println(!(b == r));

        //UNARY operators
        //increment
        //pre incerement


        int pi = 10;
        System.out.println(++pi);         //11

        //post-increment
        int nk = 10;
        System.out.println(nk++);    //10 
        System.out.println(nk);       //11


        // decrement operators
        //pre-decrement
        int nn = 10;
        System.out.println(--nn);  

        // post-decrement
        int kl = 10;
        System.out.println(kl--);    //10
        System.out.println(kl);      //9


    }

