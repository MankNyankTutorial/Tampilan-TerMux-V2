# Tampilan TerMux V2
Ubah tampilan termux Mank Nyank Tutorial V2

# Cara Pasang Script:
$ pkg update && pkg upgrade
$ pkg install ruby cowsay toilet figlet
$ pkg install nano
$ gem install lolcat

# NEW SESSION 
*Ini digunakan untuk menghilangkan tulisan "Welcome blablabla" bawaan termux
$ cd ../
$ cd usr
$ cd etc
$ rm -rf motd
# NEW SESSION
$ termux-setup-storage
$ nano .bashrc

#Paste Script (nano .bashrc)
*Pastikan script berwarna warni, kalau masih serba putih, ikuti langkah-langkah sesuai urutan sebelumnya... Pastikan juga di setiap akhir baris tulisan ada jeda berwarna hijau, jika tidak ada, bisa ditambahkan sendiri dengan memberikan "spasi"
   #Save (CTRL+X)
   
# NEW SESSION
$ cd ../
$ cd usr
$ cd etc
$ nano bash.bashrc

#Paste Script (nano bash.bashrc)
*Hapus tulisan yang ada kecuali tulisan yang pertama (baris satu memanjang atau bisa juga ke bawah, intinya satu kalimat ini jangan dihapus). Ini kalimat yang menunjukkan lokasi penyimpanan
   #Save (CTRL+X)

##########DONE##########
