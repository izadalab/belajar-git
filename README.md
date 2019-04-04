## Belajar Git



### Perintah Dasar Git

- Membuat Repository Baru
 	`git init`
- Melihat status wolking folder
	`git status`
- Menambahkan perubahan ke staging area
	`git add nama-file` -> untuk menambahkan file tertentu
	`git add .` -> untuk menambahkan semua file.
- Menyimpan perubahan ke local repo
	`git commit -m "pesan/keterangan commit"`
- Mendaftarkan remote repo
	`git remote add nama-remote url-remote`
	`git remote add github https://github.com/izadalab/belajar-git.git`
- Mengupload repo lokal ke remote
	`git push -u nama-remote nama-branch`
