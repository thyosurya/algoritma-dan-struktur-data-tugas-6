# Tugas Algoritma dan Struktur Data

## Biodata
- **Nama**: Moh. Radithyo Surya Martuah
- **NIM**: 531424113
- **Mata Kuliah**: Algoritma dan Struktur Data
- **Dosen Pengampu**: Alfian Zakaria, ST., M.T., MCE

## Deskripsi Tugas
Program ini berisi fungsi untuk menghitung nilai faktorial dari sebuah bilangan. Faktorial adalah hasil perkalian dari sebuah bilangan dengan bilangan-bilangan bulat positif di bawahnya. Sebagai contoh, faktorial dari 5 (5!) adalah 120.

## Kode Program
Program ini menggunakan fungsi rekursif dalam bahasa C++ untuk menghitung faktorial. Berikut adalah contoh kodenya:

```cpp
#include <iostream>
using namespace std;

int faktorial(int n) {
    if (n <= 1)
        return 1;
    else
        return n * faktorial(n - 1);
}

int main() {
    int angka = 5;
    cout << "Faktorial dari " << angka << " adalah: " << faktorial(angka) << endl;
    return 0;
}
