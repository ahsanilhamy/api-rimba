# 🔥 Api Rimba

Simulasi kebakaran hutan interaktif bergaya kartun. Kamu pilot pesawat pemadam: api menyebar mengikuti arah angin, tugasmu menyelamatkan sebanyak mungkin hutan.

**Main sekarang:** https://ahsanilhamy.github.io/api-rimba/

## Cara main

- **Klik / ketuk** peta untuk menjatuhkan bom air dari pesawat (jeda isi ulang ±1,4 detik).
- Api menyebar **tiap detik**, paling cepat **searah angin**. Bidik di *depan* api, bukan tepat di atasnya.
- Tanah yang terkena air **kebal api ±14 detik**, jadikan sekat.
- Arah angin berubah tiap 12–20 detik. Pantau panah 💨 di bar atas.
- **Skor = hektar selamat.** Pohon bernilai 2 ha, rumah 4 ha. Rekor terbaik tersimpan di browser.
- Spasi atau tombol ⏸ untuk jeda.

## Teknis

Satu file `index.html`, tanpa library, build, atau aset luar. Kode JavaScript + Canvas 2D murni, responsif untuk desktop dan ponsel.

Untuk menjalankan lokal, buka `index.html` di browser.

Parameter gameplay (`BASE`, `COOLDOWN`, `BOMB_R`, `WET_TICKS`) ada di bagian atas script.
