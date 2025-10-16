AD-SOYAD:EMİRE ŞEKER
ÖĞRENCİ NO:250541041
BAŞLA

1. Ekranda “Kartınızı takınız” yazısını göster.
2. Kullanıcı kartı takana kadar bekle.
3. Kart takıldığında kart bilgilerini oku.
4. “PIN (şifre) giriniz” yazısını göster.
5. Kullanıcıdan PIN numarasını al.
6. PIN numarasını banka veritabanındaki bilgilerle karşılaştır.

7. EĞER PIN doğruysa:
      7.1. Ekranda “Hoş geldiniz” mesajı göster.
      7.2. İşlem menüsünü göster:
           - Para çekme
           - Bakiye sorgulama
           - Para yatırma
           - Kart iade
      7.3. Kullanıcının seçim yapmasını bekle.

      7.4. EĞER kullanıcı “Para çekme”yi seçerse:
              7.4.1. “Çekmek istediğiniz miktarı giriniz” mesajı göster.
              7.4.2. Kullanıcıdan tutar bilgisini al.
              7.4.3. EĞER kullanıcının bakiyesi tutardan büyük veya eşitse:
                        7.4.3.1. Banka hesabından tutarı düş.
                        7.4.3.2. ATM’den parayı çıkar.
                        7.4.3.3. “Lütfen paranızı alınız.” mesajı göster.
                        7.4.3.4. EĞER kullanıcı isterse makbuz yazdır.
                        7.4.3.5. İşlem tamamlandığında menüye dön.
                     DEĞİLSE:
                        7.4.3.6. “Yetersiz bakiye!” mesajı göster.
                        7.4.3.7. Menüye geri dön.

      7.5. EĞER kullanıcı “Bakiye sorgulama”yı seçerse:
              7.5.1. Kullanıcının mevcut bakiyesini ekranda göster.
              7.5.2. Menüye geri dön.

      7.6. EĞER kullanıcı “Para yatırma”yı seçerse:
              7.6.1. “Yatırmak istediğiniz tutarı giriniz” mesajı göster.
              7.6.2. Tutarı al ve bakiyeye ekle.
              7.6.3. “Para başarıyla yatırıldı.” mesajı göster.
              7.6.4. Menüye geri dön.

      7.7. EĞER kullanıcı “Kart iade”yi seçerse:
              7.7.1. Kartı çıkart.
              7.7.2. “Kartınızı alınız. İyi günler!” mesajı göster.
              7.7.3. SİSTEMİ SONLANDIR.

8. DEĞİLSE (PIN yanlışsa):
      8.1. “Hatalı PIN girdiniz!” mesajı göster.
      8.2. Deneme sayısını 1 artır.
      8.3. EĞER deneme sayısı 3 olduysa:
              8.3.1. “Kartınız bloke edildi.” mesajı göster.
              8.3.2. Kartı yut ve SİSTEMİ SONLANDIR.
           DEĞİLSE:
              8.3.3. Tekrar PIN girilmesini iste ve 5. adıma dön.

BİTİR
