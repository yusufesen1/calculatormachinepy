def toplama (a,b):
    return a+b
def cikarma (a,b):
    return a-b
def carpma (a,b):
    return a*b
def bolme (a,b):
    if (a==0):
        return "0 ile bolme islemi yapilamaz"
    return a/b

print ("Dort islem:")
print ("""1. Toplama
2. Cikarma
3. Carpma
4. Bolme""")

islem=int(input("Lutfen dort islemden birini seciniz: "))
sayi1=int(input("Birinci sayiyi giriniz: "))
sayi2=int(input("İkinci sayiyi giriniz: "))

if (islem==1):
    print(f"Sonuc: {(toplama(sayi1, sayi2))}")
elif (islem==2):
    print(f"Sonuc: {(cikarma(sayi1, sayi2))}")
elif (islem==3):
    print(f"Sonuc: {(carpma(sayi1, sayi2))}")
elif (islem==4):
    print(f"Sonuc: {(bolme(sayi1, sayi2))}")
else:
    print("Gecersiz islem yaptiniz!")
