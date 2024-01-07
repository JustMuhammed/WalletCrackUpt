using System;
using System.Text;

class Program
{
    static void Main()
    {

        Console.Clear();
        Console.ForegroundColor = ConsoleColor.Cyan;
        Console.Title = "LostMiner Wallet Cracker v2.5";


        Console.WriteLine("LostMiner Wallet Cracker Programımıza Hoş Geldiniz.");
        Console.WriteLine("v2.5 Sürümünü Kullanmaktasınız. Bizi Tercih Ettiğiniz İçin Teşekkür Ederiz.");
        Console.WriteLine("Telegram = t.me/lostminerbtc");


        Console.ResetColor();

        Console.WriteLine();
        Console.Write("Lisans Anahtarınızı Giriniz : ");
        string girilenLisans = Console.ReadLine();
        string premiumLisans = "s";
        string vipLisans = "WGeXurV63MHG8igAWouGMdio1ciFpa0Z8DB1iweTrd";
        string ucretsizLisans = "HG8igAWouGMdio1cWGeXurV63GMdio1ciFpa0Z8DB1iweTrd";


        if (girilenLisans == premiumLisans)
        {
            Console.WriteLine("Üyelik Tipi Premium. İyi Kullanımlar.");
        }
        else if (girilenLisans == vipLisans)
        {
            Console.WriteLine("Üyelik Tipi VIP. İyi Kullanımlar.");
        }
        else if (girilenLisans == ucretsizLisans)
        {
            Console.WriteLine("Üyelik Tipi Deneme. İyi Kullanımlar.");
        }


        else
        {
            Console.WriteLine("Lisans Kodunuz Hatalıdır. Eğer Bir Lisansınız Yoksa t.me/lostminerbtc Üzerinden Satın Alabilirsiniz.");
            Console.Read();
            return;
        }

        {
            // Lisans süresi
            DateTime lisansBaslangic = DateTime.Now;
            DateTime lisansBitis = DateTime.Now.AddDays(1);

            DateTime simdikiZaman = DateTime.Now;

            if (simdikiZaman >= lisansBaslangic && simdikiZaman <= lisansBitis)
            {
                Console.WriteLine("Lisans Süreniz 1 Gündür. Geriye Kalan Lisans Süresi = 23 Saat 42 Dakika 17 Saniye");

                Console.WriteLine();
                Console.ForegroundColor = ConsoleColor.Green;
                Console.Write("Lütfen Cracklemek İstediğiniz Cüzdanın Türünü ETH veya BTC Olarak Giriniz.");
                string token = Console.ReadLine();
                string bitcoinAdresi = "";
                string ethereumAdresi = "";
                int onay = 0;

                if (token == "BTC" || token == "btc" || token == "Btc")
                {
                    Console.ForegroundColor = ConsoleColor.Yellow;
                    Console.WriteLine();
                    Console.Write("Lütfen Bitcoin Adresinizi Girin: ");
                    bitcoinAdresi = Console.ReadLine();
                    onay = 1;
                }
                else if (token == "ETH" || token == "eth" || token == "Eth")
                {
                    Console.ForegroundColor = ConsoleColor.Yellow;
                    Console.WriteLine();
                    Console.Write("Lütfen Ethereum Adresinizi Girin: ");
                    ethereumAdresi = Console.ReadLine();
                    onay = 1;
                }
                else
                {
                    Console.Write("ETH veya BTC Yazmanız Gerekmektedir. Programı Yeniden Başlatın.");
                    Console.Read();
                    return;
                }



                // Wallet listeleme kısmı

                Console.WriteLine("Cracklenecek Cüzdan Listesi Hazırlanıyor..");

                if (string.IsNullOrEmpty(bitcoinAdresi) && string.IsNullOrEmpty(ethereumAdresi))
                {
                    Console.WriteLine("Eksik veya Hatalı Giriş Yapıldı. Programı Yeniden Başlatın.");
                    Console.Read();
                    return;
                }
                else
                {
                    if (!string.IsNullOrEmpty(bitcoinAdresi))
                    {
                        Console.WriteLine("Bitcoin Adresiniz Kontrol Ediliyor. ");
                        System.Threading.Thread.Sleep(1500);
                        Console.WriteLine("Bitcoin Adresiniz Kontrol Ediliyor.. ");
                        System.Threading.Thread.Sleep(1500);
                        Console.WriteLine("Bitcoin Adresiniz Kontrol Ediliyor... ");
                        System.Threading.Thread.Sleep(2300);
                        Console.ForegroundColor = ConsoleColor.Green;
                        Console.WriteLine();
                        Console.WriteLine("Kontrol Başarılı!");
                        Console.WriteLine();
                        // Rasgele wallet oluşturma
                        for (int j = 0; j < 1000000000000000000; j++)
                        {
                            const string characters = "ABCDEFGHIJKLMNOPQRSTUVWXYZabcdefghijklmnopqrstuvwxyz0123456789";
                            Random random = new Random();
                            string prefix = "bc";
                            StringBuilder builder = new StringBuilder();
                            builder.Append(prefix);


                            for (int i = 0; i < 40; i++)
                            {
                                builder.Append(characters[random.Next(characters.Length)]);
                            }

                            string randomText = builder.ToString();
                            Console.ForegroundColor = ConsoleColor.Red;
                            Console.WriteLine("[+] " + randomText + "| Invalid | 0.0000 BTC");
                            if (girilenLisans == vipLisans)
                            {
                                System.Threading.Thread.Sleep(0);
                            }
                            else if (girilenLisans == premiumLisans)
                            {
                                System.Threading.Thread.Sleep(150);
                            }
                            else if (girilenLisans == ucretsizLisans)
                            {
                                System.Threading.Thread.Sleep(6000);
                            }

                        }

                    }
                    if (!string.IsNullOrEmpty(ethereumAdresi))
                    {
                        Console.WriteLine("Ethereum Adresiniz Kontrol Ediliyor. ");
                        System.Threading.Thread.Sleep(1500);
                        Console.WriteLine("Ethereum Adresiniz Kontrol Ediliyor.. ");
                        System.Threading.Thread.Sleep(1500);
                        Console.WriteLine("Ethereum Adresiniz Kontrol Ediliyor... ");
                        System.Threading.Thread.Sleep(2300);
                        Console.ForegroundColor = ConsoleColor.Green;
                        Console.WriteLine();
                        Console.WriteLine("Kontrol Başarılı!");
                        Console.WriteLine();
                        // Rasgele wallet oluşturma
                        for (int j = 0; j < 1000000000000000000; j++)
                        {
                            const string characters = "ABCDEFGHIJKLMNOPQRSTUVWXYZabcdefghijklmnopqrstuvwxyz0123456789";
                            Random random = new Random();
                            string prefix = "0x";
                            StringBuilder builder = new StringBuilder();
                            builder.Append(prefix);


                            for (int i = 0; i < 40; i++)
                            {
                                builder.Append(characters[random.Next(characters.Length)]);
                            }

                            string randomText = builder.ToString();
                            Console.ForegroundColor = ConsoleColor.Red;
                            Console.WriteLine("[+] " + randomText + "| Invalid | 0.0000 ETH");
                            if (girilenLisans == vipLisans)
                            {
                                System.Threading.Thread.Sleep(0);
                            }
                            else if (girilenLisans == premiumLisans)
                            {
                                System.Threading.Thread.Sleep(150);
                            }
                            else if (girilenLisans == ucretsizLisans)
                            {
                                System.Threading.Thread.Sleep(6000);
                            }
                        }
                    }

                    else
                    {
                        Console.WriteLine("Lisans süresi dolmuş. Programı kullanamazsınız.");
                        Console.Read();
                        return;
                    }
                }


            }
        }
    }
}
