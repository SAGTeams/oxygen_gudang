# oxygen_gudang

##UPDATE *oxygen_gudang* UNTUK OX_INVENTORY

+ Update fungsi CreateCallback pada oxygen_gudang untuk ox_inventory
+ Menghapus fungsi qb-inventory `TriggerEvent("inventory:client:SetCurrentStash", data.storagename)` karena sudah menggnakan export ox_inventory
+ Mengubah fungsi `SetStashMaxWeight` ke `RegisterStash` fungsi ox_inventoy 
+ Menambahkan Fungsi untuk registrasi ulang semua stash saat resource start

untuk default penyimpanan gudang anda bisa setting di config `oxygen_gudang`

note : Tidak perlu mengubah database gudang yang sudah anda punya dari serverpack oxygen 4.0 ini

#GAMABR
> Gambar 1 gudang yang sudah di upgrade kapasitasnya
> Gambar 2 gudang yang belum sama sekali di upgrade / masih perawan

![Screenshot 2025-06-10 042150](https://github.com/user-attachments/assets/a30359d4-7067-45f6-a071-bb2ca1a1e855)
![Screenshot 2025-06-10 042248](https://github.com/user-attachments/assets/17de45ad-5a30-4a0f-9759-5d652970327a)
![Screenshot 2025-06-10 043139](https://github.com/user-attachments/assets/a5df1a9f-8538-4f6b-a555-4f6b4051c5e9)
