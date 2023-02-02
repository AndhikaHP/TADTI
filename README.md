# TADTI
Ini adalah tugas akhir Dasar Teknologi dan informasi, dimana kita disuruh membuat star pattern menggunskan stambuk mahasiswa dan huruf pertama dari nama.
Didalam program coding , saya menggunakan nested for atau for didalam for ,catatan dimana i =  jumlah baris/tinggi karakter j = jumlah colome/lebar karakter.<br />
for(int i=1;i<=5;i++)<br />
perulangan ini menenjukkan tinggi kararkter adalah lima baris bingtang.<br />
for(int j=1;j<=5;j++){ => codingan ini menunjukkan lebar karakter adalah 5 colome bingtang , perulangan ini digunakan untuk membuat karakter angka nol.<br />
                if(i==1 || i==5 )<br />
                System.out.print("* ");<br />
                =>Decision ini digunakan untuk membuat 2 kaki kiri dan kanan angka nol.<br />
                else if(j==1 || j==5)<br />
                System.out.print("* ");<br />
                =>Decision ini digunakan membuat garis atas dan bawah angka no.<br />
                else<br />
                System.out.print("  ");<br />
            }<br />
            System.out.print(" "); => digunakan untuk menjaga jara antar karakter.<br />
for(int j=1;j<=4;j++){=> Perulangan ini digunakan untuk membuat karakter angka tiga dengan lebar 4 colome bingtang.<br />
                if(i==1||i==3||i==5)<br />
                    System.out.print("* ");<br />
                =>Decision ini digunakan untuk membuat tiga jari-jari pada karakter angka tiga.<br />
                else if(j==4)<br />
                    System.out.print("* ");<br />
                =>Decision ini digunakan untuk membuat badan dari karakter angka tiga.<br />
                else<br />
                    System.out.print("  ");<br />
            } <br />
System.out.print(" "); => digunakan untuk menjaga jara antar karakter.<br />
for(int j=1;j<=5;j++){=>Perulangan ini digunakan untuk membuat karakter huruf a dengan lebar 5 colome bintang.<br />
                if(i==1||i==3)<br />
                System.out.print("* ");<br />
                =>Decision ini digunakan untuk membuat kaki dari karakter huruf a.<br />
                else if(j==1||j==5)<br />
                System.out.print("* ");<br />
                =>Decision ini digunakan untuk membuat badan dari karakter huruf a.<br />
                else<br />
                System.out.print("  "); <br />
            }   System.out.println();=>Digunakan untuk membuat baris baru/digunakan membuat tinggi karakter sesuai dengan besar i.<br />
