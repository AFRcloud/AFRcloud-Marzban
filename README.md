

# Instalasi
  ```html
 apt-get update && apt-get upgrade -y && apt dist-upgrade -y && update-grub && apt install wget && reboot
 ```
Pastikan anda sudah login sebagai root sebelum menjalankan perintah dibawah
 ```html
 wget https://raw.githubusercontent.com/AFRcloud/AFRcloud-Marzban/main/mar.sh && chmod +x mar.sh && ./mar.sh
 ```

Buka panel Marzban dengan mengunjungi https://domainmu/dashboard <br>

Jika ingin mengubah konfigurasi env variable 
```html
marzban edit-env
 ```
Perintah Restart service Marzban 
```html
marzban restart
 ```
Perintah Cek Logs service Marzban 
```html
marzban logs
 ```
Perintah ganti Core Xray marzban
```html
marzban core-update
 ```
Perintah untuk sett backup marzban
```html
 marzban backup-service
 ```
Perintah Cek update service Marzban
```html
marzban update
 ```
Perintah untuk ke Menu Warp
```html
warp
 ```
atau selebih nya bisa cek 
```html
warp --help
 ```
