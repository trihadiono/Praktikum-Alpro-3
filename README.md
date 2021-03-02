# Praktikum-Alpro-3
Modular Programming (Fungsi)
#Nama: Tri Hadiono
#NIM: 71200536
#Group: D
#Universitas Kristen Duta Wacana
#Referensi: Modul dan www.dosenit.com

print("================== DAFTAR MENU ==================")
print("============== MAKANAN DAN MINUMAN ==============")
print("Menu Makanan: ")
print("1. Ayam Goreng + Nasi")
print("2. Nasi Goreng Spesial")
print("3. Pecel Lele")
print("4. Sate Ayam + Nasi")
print("5. Nasi Rames")
print("====================================================")
print("Menu Minuman: ")
print("a. Es Teh Manis/Teh Manis")
print("b. Es Teh Tawar/Teh Tawar")
print("c. Es Jeruk")
print("d. Jeruk Hangar")
print("e. Kopi")
makan=int(input("Pilih Makanan Sesuai di Menu: "))
porsi=int(input("Jumlah Porsi: "))
minum=str(input('Pilih Minuman Sesuai di Menu: '))
porsi2=int(input("Jumlah Minuman: "))

def ayamgoreng(n):
    harga= n*18000
    return harga
def nasigorenf(n):
    harga= n*15000
    return harga
def pecellele(n):
    harga= n*12000
    return harga
def sateayam(n):
    harga= n*15000
    return harga
def nasirames(n):
    harga= n*8000
    return harga
def tehmanis(a):
    harga= a*3000
    return harga
def tehtawar(a):
    harga= a*2500
    return harga
def esjeruk(a):
    harga= a*4000
    return harga
def jerukhangat(a):
    harga= a*3500
    return harga
def kopihitam(a):
    harga= a*2500
    return harga

if makan==1:
    if minum=='a':
        print(porsi, "Ayam Goreng +", porsi2, "Es/Teh Manis")
        print("Total Yang Harus Dibayar: Rp.", ayamgoreng(porsi) + tehmanis(porsi2))
    elif minum=='b':
        print(porsi, "Ayam Goreng +", porsi2, "Es/Teh Tawar")
        print("Total Yang Harus Dibayar: Rp. ", ayamgoreng(porsi) + tehtawar(porsi2))
    elif minum=='c':
        print(porsi, "Ayam Goreng +", porsi2, "Es Jeruk")
        print("Total Yang Harus Dibayar: Rp. ", ayamgoreng(porsi) + esjeruk(porsi2))    
    elif minum=='d':
        print(porsi, "Ayam Goreng +", porsi2, "Jeruk Hangat")
        print("Total Yang Harus Dibayar: Rp. ", ayamgoreng(porsi) + jerukhangat(porsi2))  
    elif minum=='e':
        print(porsi, "Ayam Goreng +", porsi2, "Kopi")
        print("Total Yang Harus Dibayar: Rp. ", ayamgoreng(porsi) + kopi(porsi2))
    else:
        print(porsi, "Ayam Goreng")
        print("Total Yang Harus Dibayar: Rp.", ayamgoreng(porsi))
elif makan==2:
    if minum=='a':
        print(porsi, "Nasi Goreng Spesial +", porsi2, "Es/Teh Manis")
        print("Total Yang Harus Dibayar: Rp.", nasigoreng(porsi) + tehmanis(porsi2))
    elif minum=='b':
        print(porsi, "Nasi Goreng Spesial +", porsi2, "Es/Teh Tawar")
        print("Total Yang Harus Dibayar: Rp. ", nasigoreng(porsi) + tehtawar(porsi2))
    elif minum=='c':
        print(porsi, "Nasi Goreng Spesial +", porsi2, "Es Jeruk")
        print("Total Yang Harus Dibayar: Rp. ", nasigoreng(porsi) + esjeruk(porsi2))    
    elif minum=='d':
        print(porsi, "Nasi Goreng Spesial +", porsi2, "Jeruk Hangat")
        print("Total Yang Harus Dibayar: Rp. ", nasigoreng(porsi) + jerukhangat(porsi2))  
    elif minum=='e':
        print(porsi, "Nasi Goreng Spesial +", porsi2, "Kopi")
        print("Total Yang Harus Dibayar: Rp. ", nasigoreng(porsi) + kopi(porsi2))
    else:
        print(porsi, "Nasi Goreng Spesial")
        print("Total Yang Harus Dibayar: Rp.", nasigoreng(porsi))
elif makan==3:
    if minum=='a':
        print(porsi, "Pecel Lele +", porsi2, "Teh Manis")
        print('Total yang harus dibayar: Rp',pecellele(porsi)+tehmanis(porsi2))
    elif minum=='b':
        print(porsi, "Pecel Lele +", porsi2, "Teh Tawar")
        print('Total yang harus dibayar: Rp',pecellele(porsi)+tehtawar(porsi2))
    elif minum=='c':
        print(porsi, "Pecel Lele +", porsi2, "Es Jeruk")
        print('Total yang harus dibayar: Rp',pecellele(porsi)+esjeruk(porsi2))
    elif minum=='d':
        print(porsi, "Pecel Lele +", porsi2, "Jeruk Hangat")
        print('Total yang harus dibayar: Rp',pecellele(porsi)+jerukhangat(porsi2))
    elif minum=='e':
        print(porsi, "Pecel Lele +", porsi2, "Kopi Hitam")
        print('Total yang harus dibayar: Rp',pecellele(porsi)+kopihitam(porsi2))
    else:
        print(porsi, "Pecel Lele")
        print('Total yang harus dibayar: Rp',pecellele(porsi))

elif makan==4:
    if minum=='a':
        print(porsi, "Sate Ayam +", porsi2, "Teh Manis")
        print('Total yang harus dibayar: Rp',sateayam(porsi)+tehmanis(porsi2))
    elif minum=='b':
        print(porsi, "Sate Ayam +", porsi2, "Teh Tawar")
        print('Total yang harus dibayar: Rp',sateayam(porsi)+tehtawar(porsi2))
    elif minum=='c':
        print(porsi, "Sate Ayam +", porsi2, "Es Jeruk")
        print('Total yang harus dibayar: Rp',sateayam(porsi)+esjeruk(porsi2))
    elif minum=='d':
        print(porsi, "Sate Ayam +", porsi2, "Jeruk Hangat")
        print('Total yang harus dibayar: Rp',sateayam(porsi)+jerukhangat(porsi2))
    elif minum=='e':
        print(porsi, "Sate Ayam +", porsi2, "Kopi Hitam")
        print('Total yang harus dibayar: Rp',sateayam(porsi)+kopihitam(porsi2))
    else:
        print(porsi, "Sate Ayam")
        print('Total yang harus dibayar: Rp',sateayam(porsi))

elif makan==5:
    if minum=='a':
        print(porsi, "Nasi Rames +", porsi2, "Teh Manis")
        print('Total yang harus dibayar: Rp',nasirames(porsi)+tehmanis(porsi2))
    elif minum=='b':
        print(porsi, "Nasi Rames +", porsi2, "Teh Tawar")
        print('Total yang harus dibayar: Rp',nasirames(porsi)+tehtawar(porsi2))
    elif minum=='c':
        print(porsi, "Nasi Rames +", porsi2, "Es Jeruk")
        print('Total yang harus dibayar: Rp',nasirames(porsi)+esjeruk(porsi2))
    elif minum=='d':
        print(porsi, "Nasi Rames +", porsi2, "Jeruk Hangat")
        print('Total yang harus dibayar: Rp',nasirames(porsi)+jerukhangat(porsi2))
    elif minum=='e':
        print(porsi, "Nasi Rames +", porsi2, "Kopi Hitam")
        print('Total yang harus dibayar: Rp',nasirames(porsi)+kopihitam(porsi2))
    else:
        print(porsi, "Nasi Rames")
        print('Total yang harus dibayar: Rp',nasirames(porsi))
