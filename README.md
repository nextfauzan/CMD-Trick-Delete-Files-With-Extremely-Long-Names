# CMD-Trick-Delete-Files-With-Extremely-Long-Names

````markdown
Kadang Windows tidak dapat menghapus file yang memiliki nama atau path yang sangat panjang.  
Keterbatasan ini bisa diatasi dengan menggunakan **extended path prefix** pada Windows yaitu `\\?\`.

## Command

```cmd
del "\\?\C:\Users\Lenovo\Downloads\ACFrOgDnwfAVrhjWUlyKnbT1zd60OPW8J1XuC314PwRTgfb3ifZc9d0DIJyY3_G8KHyjLOnqO9mGssd23i84sVciF-343olAY6Ddtinyak8OUvDiI8TwzNTWdM8mZnk_P5eftt6De0eRRUNAYad8V9Wu1YBTIsDaaT6C5kjrnWdt2lwrnoRDJboefut6Y8114lWbJiV4Gv0GOyJOU0VAdI99e_3FXA3leXtW_iopypgAr2JGcRbp742dH7M.pdf"
````

## Penjelasan

* `\\?\` → Mengaktifkan dukungan **path panjang (extended-length paths)** di Windows
* `del` → Perintah untuk menghapus file
* Berguna ketika file **tidak bisa dihapus melalui Windows Explorer atau CMD biasa**

```

Kalau mau, saya juga bisa buatkan **judul README yang lebih menarik seperti repositori GitHub populer** (misalnya: *“Windows Trick: Delete Undeletable Files”*) supaya terlihat lebih profesional.
```
