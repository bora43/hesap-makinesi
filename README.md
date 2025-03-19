ilkSayi = int(input("İlk sayıyı giriniz: "))
ikinciSayi = int(input("İkinci sayıyı giriniz: "))
islem = input("""Yapmak istediğiniz işlemi seçiniz
(Toplama:  +, çıkarma:  -, çarpma:  x, bölme:  /)
""")
if islem == "+":
  print("Sonuç: " + str(ilkSayi + ikinciSayi))
elif islem == "-":
  print("Sonuç: " + str(ilkSayi - ikinciSayi))
elif islem == "x":
  print("Sonuç: " + str(ilkSayi * ikinciSayi))
elif islem == "/":
  print("Sonuç: " + str(ilkSayi / ikinciSayi))
