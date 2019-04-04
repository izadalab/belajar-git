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
- Mendownload/mengambil perubahan dari remote ke working folder
	`git pull nama-remote nama-branch`
- Menghapus perubahan di staging
	`git reset`
- Menghapus perubahan di staging dan working folder
	`git reset --hard`
- Melihat daftar branch
	`git branch -all`
- Membuat branch baru
	`git branch nama-branch`
- Pindah ke branch tertentu
	`git checkout nama-branch`
- Merge branch tertentu ke master
	`git checkout master`
	`git merge nama-branch`
- Menghapus branch tertentu di lokal
	`git branch -d nama-branch`
- Menghapus branch tertentu di remote
	`git push nama-remote :nama-branch`
