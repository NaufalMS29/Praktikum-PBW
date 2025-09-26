<h1> Naufal Maulana Saputra 4523210083 </h1>

<h2>Laporan Instalasi GIT Pertemuan Pertama </h2>

<h3>1. Download GIT dari link berikut https://git-scm.com/download/win</h3>

<img width="1920" height="1032" alt="image" src="https://github.com/user-attachments/assets/d53c2da9-a88f-4591-ae4f-ade2477e4ec5" />

- jalankan file .exe

- biarkan pengaturan default lalu klik "next" sampai selesai

- buka Git Bash, cek versi git, "git --version"

<h3>2. Config Awal (Wajib)</h3>

masih di Git Bash, jalankan perintah berikut dengan username dan email sesuai dengan github masing-masing

git config --global user.name "Nama github"

git config --global user.email "emailgihub@gamil.com"

<img width="536" height="90" alt="image" src="https://github.com/user-attachments/assets/b9dcae95-80bd-4021-a737-8ae84fecc88c" />

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

<img width="575" height="758" alt="image" src="https://github.com/user-attachments/assets/4e056c15-3fd4-4b83-9bb3-2f3de3241154" />

<img width="576" height="567" alt="image" src="https://github.com/user-attachments/assets/964a1c3a-e212-4260-acc7-0b76abd3b557" />

<h3>4. Membuat Repository di Github, dan Hubungkan dengan Git</h3>

- git remote add origin https://github.com/NaufalMS29/prak-1-git.git <- ini dari link git repository masing masing

- git branch -M main

- git push -u origin main

<img width="576" height="111" alt="image" src="https://github.com/user-attachments/assets/a9cfbbbc-4be0-4125-aa53-a60bddc45fd7" />

<img width="576" height="194" alt="image" src="https://github.com/user-attachments/assets/195ecdde-374c-4938-b23a-9a609f9a6dcf" />

<img width="1920" height="1032" alt="image" src="https://github.com/user-attachments/assets/a233ab27-3772-4787-9cca-919190d8d36e" />
