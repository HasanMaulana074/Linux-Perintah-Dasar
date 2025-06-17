# Linux-Perintah-Dasar
Perintah-perintah dasar dalam mengoprasikan OS Linux

Bagi temen-temen yang belum menginstall OS Linux, dipersilahkan untuk menginstall OS Linux terlebih dahulu
Atau temen-temen bisa menginstall OS Linux melalui virtual mesin seperti VIRTUALBOX dan VMWare

Berikut perintah-perintah dasar linux dan fungsinya
- su = meminta akses sebagai root
- su username = meminta akses sebagai user lain
- pdw = menampilkan path/direktori saat ini di mana kamu sedang berada
- sudo passwd = untuk menghapus/mereset password root
  sudo passwd hasan = menghapus/mereset password user yang bernama hasan
- touch = membuat file 
  touch file.txt = membuat file yang bernama file.txt
  touch Documents/file.txt = membuat file.txt di dalam direktori
- ls = untuk melihat isi direktori
  ls Documents = untuk melihat isi direktori Documents
  ls -l Documents = untuk melihat informasi ditail atas suatu file atau direktori
  ls -a Documents = untuk melihat semua file/direktori termasuk hidden file/direktori
  ls -la Documents = perintah gabungan dari dua perintah di atas
  ls -R Documents = untuk melihat isi direktori Documents dan melihat apa yang ada di dalamnya lagi
- mkdir = untuk membuat direktori
  mkdir data = membuat direktori dengan nama data
  mkdir -p data/dokumen/bulan-1 = (membuat direktori bersarang) membuat direktori di dalam direktori
- cp = untuk mencopy file/direktori
  cp file.txt Documents = mengcopy file.txt kedalam Documents
  cp *.txt Documents = mencopy semua file yang berbentuk .txt kedalam Documents
  cp Documents/file.txt Downloads/pendataan =  mengcopy file.txt yang berada di dalam direktori kedalam direktori yang lain
  cp -r Documents Downloads = untuk mengcopy direktori Documents ke dalam direktori Downloads
- mv = untuk memindakan atau merename file/direktori
  mv file1.txt file2.txt = merename nama file1 menjadi nama file
  mv file.txt Documents/ = memindahkan file.txt kedalam direktori Documents
  mv Documents Downloads = jika direktori Download belum ada/belum dibuat maka, perintah tersebut akan berfungsi sebagai rename dari Documents menjadi Downloads
  akan tetapi jika direktori Download sudah ada maka, fungsi perintah tersebut adalah memindahkan, direktori Documents di pindahkan kedalam direktori Downloads
  mv Documents/file.txt . = memindahkan file.txt di dalam direktori Documents ke Current direktori dengan menggunakan nama yang sama
- rm = untuk menghapus file
  rmdir = untuk menghapus direktori kosong
  rm -rf = untuk menghapus direktori berserta isinya
  
  
