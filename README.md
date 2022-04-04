# For-Loop-ve-Break-Continue-Ifadeleri
//Döngüler
            // Ekrandan girilen sayıya kadar olan tek sayılarını ekrana yazdır.
            Console.WriteLine("Lütfen ekrana bir sayı giriniz:");
            int sayac = int.Parse(Console.ReadLine());

            for (int i = 1; i <= sayac; i++)// İ 0 dan başlıyor. Length i sayısının kaçta küçük olmasını istiyorsak onu yazıyoruz. İ yi bir artır.

            {
                // komutlar
                if (i % 2 == 1)
                {
                    Console.WriteLine("Tek sayılar:" + i);
                }
                Console.ReadLine();

            }
            // 1 ile 1000 arasındaki tek ve çift sayıların toplamını ekrana yazdır.
            int tekToplam = 0;
            int çiftToplam = 0;

            for (int i = 1; i <= 1000; i++)
            {
                if (i % 2 == 1)

                    tekToplam += i;// tekToplam= tekToplam + i;
                else
                    çiftToplam += i;//  çiftToplam= çiftToplam+i;

                

            }
            Console.WriteLine("Tek toplam="+tekToplam);
            Console.WriteLine("Çift Toplam" + çiftToplam);
            Console.ReadLine();
            // break, continue
            for (int i = 1; i <10; i++)
            {
                if (i == 4)
                    break;
                Console.WriteLine(i);
            }
            for (int i = 1; i < 10; i++)
            {
                if (i == 5)
                    continue;
                Console.WriteLine(i);
            }
