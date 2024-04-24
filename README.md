# vangke
jujur karena saya melakukan ini sendiri (walaupun dibantu teman saya) saya akan memberi penjelasan se jelas mungkin sebisa saya

pertama cft atau Clash For Termux ya bisa cari tau sendiri di github ada itu wkwk

langsung ke intinya aja

download file .config.zip di github ini
setelah download simpan filenya aja dulu

buka termux dan ketik
termux-setup-storage
lalu izinkan

kalau udh ketikan
mkdir -p $HOME/.config/clash (enter)

lalu install beberapa package pembantu seperti
pkg install unzip (buat unzip nanti)
pkg install micro (biat edit confignya kalau ini sih bebas mau install atau engga bisa pakai nano/mc)

setelah install tool pembantu ketikan
cd /sdcard/tempatdimanakamunyimpenfile

misalnya di file download jadi
cd /sdcard/Download

nah tinggal ketik
mv .config.zip ~/.config/clash

nah kalau udh di pindah
tinggal unzip aja pakai command
unzip .config.zip
tunggu sampe selesai

kalau udh coba test dulu pakai command
