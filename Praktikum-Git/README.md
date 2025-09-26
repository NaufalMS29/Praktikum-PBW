<h1> Naufal Maulana Saputra 4523210083 </h1>

<h2>Laporan Instalasi GIT Pertemuan Pertama </h2>

<h3>1. Download GIT dari link berikut https://git-scm.com/download/win</h3>

<img width="1920" height="1032" alt="image" src="https://github.com/user-attachments/assets/7cbcb8a4-f0bd-4679-a213-cc6800a069ff" />

- jalankan file .exe

- biarkan pengaturan default lalu klik "next" sampai selesai

- buka Git Bash, cek versi git, "git --version"

<h3>2. Config Awal (Wajib)</h3>

masih di Git Bash, jalankan perintah berikut dengan username dan email sesuai dengan github masing-masing

git config --global user.name "Nama github"

git config --global user.email "emailgihub@gamil.com"

<img width="536" height="90" alt="image" src="https://github.com/user-attachments/assets/a487912c-e145-40fe-a205-c5319f20c802" />

<h3>3. Membuat Folder Local di Git Bash</h3>

- masuk ke folder dimana folder praktikum ingin dibuat, berpindah folder di Git Bash menggunakan cd

- kemudian membuat folder, mkdir proyek-web

- masuk ke dalam folder proyek-web, cd proyek-web

- git init, untuk inisialisasi git agar terhubung ke folder tersebut

- buat beberapa file, contohnya index.html dan style.css

- git add .

- git commit -m "pesan commit"

- git checkout -b fitur-kontak, untuk bikin branch baru

- setiap ada perubahan, lakukan git add . dan git commit -m "pesan commit"

- git checkout master, balik ke branch utama yaitu master

- git merge fitur-kontak, untuk menyatukan kedua branch

<img width="753" height="837" alt="image" src="https://github.com/user-attachments/assets/15f020f7-f67f-42a4-a836-c75e368fcaef" />

<img width="739" height="692" alt="image" src="https://github.com/user-attachments/assets/7376c322-2278-4c07-9148-4220bfaf2929" />

<h3>4. Membuat Repository di Github, dan Hubungkan dengan Git</h3>

- git remote add origin https://github.com/NaufalMS29/Praktikum-PBW.git <- ini dari link git repository masing masing

- git branch -M main

- git push -u origin main

<img width="672" height="323" alt="image" src="https://github.com/user-attachments/assets/aaad6fa4-d24e-4150-b4f6-2e165a4ea12d" />
