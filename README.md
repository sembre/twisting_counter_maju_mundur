# twisting_counter_maju_mundur

🔁 Twisting Counter Maju-Mundur (V1)
Twisting Counter Maju-Mundur adalah proyek berbasis Arduino yang mengontrol motor berputar maju (mode A) dan mundur (mode B) berdasarkan jumlah putaran yang ditentukan melalui keypad. Sistem ini dilengkapi dengan sensor IR untuk menghitung putaran dan LCD untuk menampilkan informasi secara real-time.

✨ Fitur Utama
✅ Input jumlah putaran untuk Mode A dan Mode B melalui Keypad 4x4

✅ Menampilkan status dan hasil pada LCD 16x2

✅ Mode A selalu dijalankan lebih dahulu, lalu otomatis lanjut ke Mode B

✅ Motor berhenti otomatis setelah masing-masing mode selesai

✅ Output pin (outputPin) hanya aktif di Mode A, mati di Mode B

✅ Tombol Start terpisah dan hanya aktif jika putaran telah dikunci dengan tombol #

✅ Reset pengaturan dengan tombol *

✅ Proteksi via switch darurat agar motor bisa dihentikan kapan saja

🧰 Hardware yang Dibutuhkan
Arduino Uno/Nano

LCD 16x2 (I2C optional)

Keypad 4x4

Sensor IR (untuk mendeteksi putaran)

Motor DC + Driver (sesuai kebutuhan)

Push button (tombol start)

Switch (untuk emergency stop)

Resistor, kabel jumper, dan breadboard

🚀 Cara Kerja Singkat
Masukkan jumlah putaran untuk mode A dan B.

Tekan tombol # untuk mengunci pengaturan.

Tekan tombol Start.

Motor menyala untuk Mode A sampai jumlah putaran terpenuhi.

Setelah itu otomatis lanjut ke Mode B.

Motor berhenti total setelah Mode B selesai.

Tekan * untuk reset dan input ulang.

📂 File Utama
Twisting_counter_maju_mundur_V1.ino: Program utama untuk Arduino.
