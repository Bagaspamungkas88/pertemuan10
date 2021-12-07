# pertemuan10 (latihan 1)

 ![IMG](gambar/soal1.png)

# jawab


    pertama

saya membuat data kontak awal

b={'ari':'085267888','dina':'087677776'}
    kedua

saya diberi soal untuk menampilkan kontak ari

print(b['ari'])
    ketiga

saya disuruh menambah kontak atas nama riko

b['riko']='087654544'
    keempat

ubah kontak dina
b['dina']='088999776'
    kelima

tampilkan semua nama

print(b.keys())
    keenam

tampilkan semua nomor

print(b.values())
    ketujuh

nenampilkan semua nama dan nomor
print(b)
menghapus kontak dina

del b['dina']

# tampilan pada visual studio code

![img](gambar/vscode1.png)


# output

![img](gambar/output1.png)



# PERTEMUAN 10 (TUGAS PRATIKUM)
pada tugas praktium saya diberi soal sebagai berikut

![img](gambar/soal2.png)

# flowchart

![img](gambar/flowchart.png)

# jawab
pertama saya membuat looping agar program terus berjalan

    while True:
        c = input("\n(L)ihat, (T)ambah, (U)bah, (H)apus, (C)ari, (K)eluar: ")                                

    lalu saya membuat format if untuk memasukan pilihan , sebagai contoh apabila memilih (t) akan menambah data

    if (c.lower() == 't'):                                               
        print('\nTambah Data Mahasiswa Baru')
        nama= input("Masukkan Nama\t\t: ")                                        
        nim= input("Masukkan NIM\t\t: ")                                         
        nilaiTugas= int(input("Masukkan Nilai Tugas\t: "))                              
        nilaiUts= int(input("Masukkan Nilai UTS\t: "))                                   
        nilaiUas= int(input("Masukkan Nilai UAS\t: "))                                    
        nilaiAkhir= (0.30 * nilaiTugas) + (0.35 * nilaiUts) + (0.35 * nilaiUas)              
        dataMhs[nama]= nim, nilaiTugas, nilaiUts, nilaiUas, nilaiAkhir                         
        print("\nData Berhasil Ditambahkan!")

    saya juga melakukan percabangan if (elif) untuk melaksanakan pilihan yang lain

    elif (c.lower() == 'u'):                                                                    
            print('\nMengedit Data Mahasiswa')
            nama = input("Masukkan Nama: ")                                                         
            if nama in dataMhs.keys():                              
                nim= input("Masukkan NIM Baru\t: ")                              
                nilaiTugas= int(input("Masukkan Nilai Tugas\t: "))                           
                nilaiUts= int(input("Masukkan Nilai UTS\t: "))                           
                nilaiUas= int(input("Masukkan Nilai UAS\t: "))                           
                nilaiAkhir= (0.30 * nilaiTugas) + (0.35 * nilaiUts) + (0.35 * nilaiUas)          
                dataMhs[nama] = nim, nilaiTugas, nilaiUts, nilaiUas, nilaiAkhir                      
                print("\nData Berhasil Di Update!")

    dan saya juga menggunakan else untuk apabila salah memasukan pilihan inputan

        else:
        print("Pilih menu yang tersedia: ")  

 # tampilan pada visual studio code  

 ![img](gambar/vscode2.png) 


# output 
ini adalah output apabila memilih tambah(t)
 
![img](gambar/outputTambah.png)


 ini adalah output apabilah memilih  diubah

![img](gambar/outputUbah.png)

ini adalah apabilah mencari output (c)

![img](gambar/outputCari.png)

ini adalah output apabila memilih untuk tambah lagi

![img](gambar/output/outputTambahlagi.png)

ini adalah output apabila memilih hapus(h) 

![img](gambar/outputHapus.png)

ini adalah output apabila memilih lihat (l)

![img](gambar/outputLihat.png)

ini adalah output apabila memilih keluar (k)

![img](gambar/outputk.png)






