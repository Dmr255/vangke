# vangke
jujur karena saya melakukan ini sendiri (walaupun dibantu teman saya) saya akan memberi penjelasan se jelas mungkin sebisa saya

pertama cft atau Clash For Termux ya bisa cari tau sendiri di github ada itu wkwk

langsung ke intinya aja

download file .config.zip & cft di github ini
setelah download simpan filenya aja dulu

buka termux dan ketik

$ termux-setup-storage

lalu izinkan

kalau udh ketikan

$ mkdir -p $HOME/.config/clash (enter)

lalu install beberapa package pembantu seperti

$ pkg install unzip 
(buat unzip nanti)

$ pkg install micro 
(biat edit confignya kalau ini sih bebas mau install atau engga bisa pakai nano/mc)

setelah install tool pembantu ketikan

$ cd /sdcard/tempatdimanakamunyimpenfile

misalnya di file download jadi

$ cd /sdcard/Download
pertama pindahkan file bin clashnya

$ mv cft ~/

nah baru file zipnya tinggal ketik

$ mv config.zip ~/

kalau udh di move semua ketik

$ cd

nah lanjut ketik ls kalau muncul file cft artinya udh berhasil berpindah kalau belum ulangi cara di atas

lanjutkan ketikkan

$ unzip config.zip
tunggu sampe selesai

nah kalau udh
ubah perizinan cft biar 777 dengan cara ketik

$ chmod 777 cft (kalau gagal chat gw di t.me/Damzz25)

kalau udh ketik ls lagi, jika warna teks cft udh ijo artinya udh berhasil kalau warnanya masih putih artinya masih suci ehh belum keubah maksudnya ulangi cara di atas

kalau udh ketik

$ cd ~/.config/clash

nah disini kalian ketik

$ ls

kalau muncul berbagai isi dari config.zip artinya udh terpindah kalau belum ulangi lagi

tinggal ketik aja

$ cd
kalau udh selesai ketik 

$ rm -rf .config.zip
biar apa? biar lebih estetik
setelah itu ketik

$ cd

nah kalau udh semua

tinggal isi akun clash di proxy-provider
kalau install nano tinggal ketik

$ cd ~/.config/clash/proxy-provider

$ nano AKUN-VPN.yaml
isi aja tuh udh gw settingin bagian config.yaml ga usah di ubah ubah cukup isi akun aja btw ga support vless hanya bisa vmess & Trojan ya

setelah isi akun kalau pakai nano pencet di shortcut termux ctrl+x kemudian ketik y dan enter

nah kalau udh semua lanjut ke bagian apn buat apn baru dan isikan begini

nama : bebas

apn : bebas (bebas aja mau internet, aha, ngeue serah)

proxy: 127.0.0.1

port: 7893

nah kalau udh simpan apn dan langsung pake aja

kalah udh masuk lagi ke termux kemudian ketikkan  

$ ./cft

kalau muncul
INFO[0000] Start initial provider AKUN-VPN
INFO[0000] Start initial compatible provider DamarVPN

artinya berhasil kalau muncul eror silahkan perbaiki sendiri atau chat saya di t.me/Damzz25

terimakasih dan salam gretongan 
