# Demo REMOTE REPO

Repo di local lewat perintah remote

git init itu buat inisialisasi file kita ke git repository atau folder yang tadi ada di hidden

git remote itu untuk repo dimana file atau folder yang kita buat di local dan akan ditaroh ke manapun misalnya di komputer server atau komputer kantor dengan media github kalo dalam kasus ini, jadi folder nya itu belum ada di github, baru ada di local kita doang
Caranya:
1. create new repository di button + yang ada di pojok kanan deket avatar profile
2. isi nama nya aja, terus langsung klik create repository
3. copy ssh terus ketik perintah git remote add origin si_ssh 
4. terus cek dengan ketik perintah git remote -v
5. git push -u origin master, -u fungsinya nanti buat mempermudah kita untuk shortcut perintha git push, jadi tanpa ketik origin master lagi
*branch master baru dibuat lewat perintah git push karena sebelumnya repo nya kosong, kalo kita kasih centang untuk nambahin file README.md nanti branch default nya itu main
6. nomor 5 itu create branch master, terus langkah buat sinkronisasi file itu sama seperti langkah nya clone:
- harus git add . atau git add nama_file dulu biar file nya ke track, biar bisa di commit
- lakuin commit
- lakuin push