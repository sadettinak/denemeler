# denemeler
denemeler

        System.out.println(num);
        System.out.println("basari");

        Scanner scan = new Scanner(System.in);
        System.out.println("Lutfen bir tam sayi girin");
        int sayi = scan.nextInt();
        if (  (sayi%10==0 )) {
            System.out.println("sayi cift ve 10'nun katidir");}
        if(sayi%2==0  && sayi%10!=0) System.out.println("sayi cift 10 un kati degildir");
        else if (sayi%2!=0 && sayi>0){
            System.out.println(" pozitif tek sayidir");}
        else  if(sayi%2!=0   ){
            System.out.println("negatif tek sayidir");}
Scanner scan = new Scanner(System.in);
        System.out.println("Matematiksel isleme sokmak icin 2 tane tamsayi giriniz : ");

        int a = scan.nextInt();
        int b = scan.nextInt();

        System.out.println("Islem turunu seciniz : \n\t1 : Toplama\n\t2 : Cikarma\n\t3 : Carpma\n\t4 : Bolme");

        int islem = scan.nextInt();

        System.out.println("****************** IF Cozumu ********************");

        if (islem==1) System.out.println(a+b);
        else if (islem==2) System.out.println(a-b);
        else if (islem==3) System.out.println(a*b);
        else if (islem==4) {
            if(b==0) System.out.println("0'a bolum tanimsizdir");
            else System.out.println(a/b);
        }
        else System.out.println("Yanlis giris yaptiniz, lutfen tekrar deneyiniz");

        System.out.println("****************** Switch Case Cozumu 1 ********************");

        switch (islem) {
            case 1:
                System.out.println(a + " + " + b + " = " + (a + b));
                break;

            case 2:
                System.out.println(a + " - " + b + " = " + (a - b));
                break;

            case 3:
                System.out.println(a + " * " + b + " = " + (a * b));
                break;

            case 4:
                if (b == 0) System.out.println("0'a bolum tanimsizdir");
                else System.out.println(a + " / " + b + " = " + (a / b));
                break;

            default:
                System.out.println("Yanlis giris yaptiniz, lutfen tekrar deneyiniz");
        }

            System.out.println("****************** Switch Case Cozumu 2 ********************");

                System.out.println("Islem turunu seciniz : \n\t+ : Toplama\n\t- : Cikarma\n\t* : Carpma\n\t/ : Bolme");


                char isaret = scan.next().charAt(0);

            switch (isaret){
                case '+' : System.out.println(a + " + " + b +" = " + (a+b)); break;

                case '-' : System.out.println(a + " - " + b +" = " + (a-b)); break;

                case '*' : System.out.println(a + " * " + b +" = " + (a*b)); break;

                case '/' : if(b==0) System.out.println("0'a bolum tanimsizdir");
                else System.out.println(a + " / " + b +" = " + (a/b)); break;

                default: System.out.println("Yanlis giris yaptiniz, lutfen tekrar deneyiniz");
String mesaj= "Bugün hava cok güzel";
System.out.println(mesaj);
        System.out.println("Eleman sayisi: "+mesaj.length());
        System.out.println("5.eleman:"+mesaj.charAt(4));

    }
}
