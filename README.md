<img width="1918" height="1077" alt="Screenshot 2025-11-03 164503" src="https://github.com/user-attachments/assets/29d74ecd-d5f5-460b-9bda-33247978e95e" />
Program ngecek dulu, kalau angka yang dimasukin kurang dari 0,
maka muncul tulisan:

Bilangan harus positif!


dan program langsung berhenti (pakai return).

Kalau angkanya positif, baru program lanjut ke proses ngitung faktorial.
Di sini rumusnya pakai perulangan:

for (int i = 1; i <= n; i++) {
    hasil *= i;
}


Artinya:

Kalau n = 2 → hasil = 1 × 2 = 2

Kalau n = 4 → hasil = 1 × 2 × 3 × 4 = 24

Setelah selesai, program nampilin hasilnya:

Faktorial dari 2 adalah: 2


atau

Faktorial dari 4 adalah: 24


Kesimpulan:
Program ini buat ngitung faktorial dari bilangan positif.
Kalau kamu masukin angka negatif, program langsung bilang “Bilangan harus positif!” dan nggak lanjut ngitung.
