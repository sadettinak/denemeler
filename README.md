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

String mesaj= "Bugün hava cok güzel";
System.out.println(mesaj);
        System.out.println("Eleman sayisi: "+mesaj.length());
        System.out.println("5.eleman:"+mesaj.charAt(4));

    }
}
