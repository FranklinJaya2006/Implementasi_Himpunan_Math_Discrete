# Implementasi_Himpunan_Math_Discrete

Code proyek kali ini bertujuan untuk mengimplementasikan konsep konsep dasar himpunan dengan menggunakan bahasa Python

# Berikut ini Magic Method pada proyek kali ini : 
- __len__(self) : Mengembalikan jumlah elemen dalam himpunan (ukuran himpunan).
- __contains__(self, item) : Mengembalikan True jika suatu elemen ada dalam himpunan, dan False jika tidak ada.
- __eq__(self, other) : Mengecek apakah dua himpunan sama. Return Boolean
- __le__(self, other) : Mengecek apakah suatu himpunan merupakan subset dari himpunan lain. Return Boolean
- __lt__(self, other) : Mengecek apakah suatu himpunan merupakan proper subset dari himpunan lain. Return Boolean
- __ge__(self, other) : Mengecek apakah suatu himpunan merupakan superset dari himpunan lain. Return Boolean
- __floordiv__(self, other) : Mengecek apakah dua himpunan ekuivalen (memiliki elemen yang sama, meskipun urutannya berbeda). Return Boolean
- Gabungan (Union): Menggunakan operator + untuk menghitung gabungan antara dua himpunan.
- Selisih (Difference): Menggunakan operator - untuk menghitung selisih antara dua himpunan.
- Komplemen (Complement): Nama method komplement  untuk menghitung komplemen dari suatu himpunan dengan input himpunan Semester.
- Selisih Simetris (Symmetric Difference): Menggunakan operator * untuk menghitung selisih simetris antara dua himpunan.
- cartesian product : Menggunakan operator ** untuk menghitung hasil cartesian product dari dua himpunan
- Himpunan Kuasa (Power Set): Menggunakan abs() untuk menghitung himpunan kuasa (semua subset dari himpunan).
- Anggota Himpunan Kuasa: Nama method  ListKuasa Menampilkan list himpunan kuasa yang mungkin dibuat dari suatu himpunan.

# Syarat keberhasilan proyek ini : 
Tidak diperkenankan menggunakan additional packages dalam pembuatan kelas.

# Contoh/Hasil yang diinginkan : 
S = Himpunan(1,2,3,4,5,6,7,8,9)
h1 = Himpunan(1, 2, 3)
h2 = Himpunan(3, 4, 5)

print(len(h1))  # Output: 3
print(3 in h1)  # Output: True
print(h1 == h2)  # Output: False

h1 += 4  # Menambah elemen 4 ke h1
print(h1)  # Output: {1, 2, 3, 4}

h3 = h1 / h2  # Irisan
print(h3)  # Output: {3, 4}

h4 = h1 + h2  # Gabungan
print(h4)  # Output: {1, 2, 3, 4, 5}

h5 = h1 - h2  # Selisih
print(h5)  # Output: {1, 2]}

h6 = h1.Komplemen(S)  # Komplemen
print(h6)  # Output: {4,5,6,7,8,9}

print(abs(h1))  # 8

# Untuk menggunakan Library "himpunan-team3" :
lakukan instalasi dengan command berikut pada terminal (mac) / Command Prompt :

```command
pip install himpunan-team3==0.1.0
```

Jika hanya ingin import package dalam file : 

```python
from Himpunan import Himpunan
```

Link Pypi : https://pypi.org/project/himpunan-team3/0.1.0/

# Created By Team 3 Himpunan Math Discrete : 
- Franklin Jaya | 0806022310016
- Muh. Ryan Ardiansyah | 0806022310019
- Tiffany Tjandinegara | 0806022310027







