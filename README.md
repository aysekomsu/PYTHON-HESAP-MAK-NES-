# PYTHON-HESAP-MAK-NES-
#ALICIDAN ALINAN İKİ SAYININ,ALICININ İSTEDİĞİ İŞLEMİNİ YAPMA:

sayı1 = float(input("ilk sayıyı giriniz : "))

sayı2 = float(input("ikinci sayıyı giriniz : "))



print("Giriş Ekranı\n1. Toplama\n2. Çıkarma\n3. Çarpma\n4. Bölme\n")



secenek = 1



while secenek == 1:

    soru = input("Yapmak istediğiniz işlemin numarasını giriniz : ")



    if soru == "1":

        print(sayı1, "+", sayı2, "=", sayı1 + sayı2)



    elif soru == "2":\

        print(sayı1, "-", sayı2, "=", sayı1 - sayı2)



    elif soru == "3":

        print(sayı1, "*", sayı2, "=", sayı1 * sayı2)



    elif soru >= "5":

        print("hatalı giriş yaptınız,tekrar deneyiniz.")



    elif soru == "4" and sayı2 != 0:

        print(sayı1, "/", sayı2, "=", sayı1 / sayı2)

    else :

        print("hatalı giriş yaptınız,tekrar deneyiniz.")



    cevap = input("Devam etmek istiyor musunuz? (e/h) ")

    if cevap == 'h' :

        print("hesap makinesi kapandı.")

        break

    else :

        continue
