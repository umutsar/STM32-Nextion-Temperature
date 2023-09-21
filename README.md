# STM32-Nextion-Temperature

# Analog ölçtüğümüz sıcaklık değerini nextion ekranına yazdırma kodu.
•STM32f103C8T6 kartı ile test edilip onaylanmıştır diğer stm32 kartlari ile de ufak değişiklikler ile çalışacaktır.

•Nextion ekranında Nextion Editor programı ile t3 ismine sahip bir text oluşturduk ardından hafıza kartına atıp nextion ekranına hafıza kartını taktık ve programladık. Hemen ardından STM32CubeIDE programından oluşturduğumuz kodların içerisinde dışarıdan aldığımız fonksiyon ile bu t3 adlı metnin içerisine sıcaklık verisini yazdık.

•t3 bir text parçası olduğu için direkt olarak integer(tamsayı) bir değer atamazsınız. Onun için sensörden aldığımız integer veriyi önce sprintf ile string değere çevirip o şekilde nextiona gönderiyoruz.




# Kaynakça:
•ControllersTech isimli youtube kanalından nextion fonksiyonu alınmıştır.
