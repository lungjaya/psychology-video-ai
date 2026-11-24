# Visual Style Bible

Tujuan: semua scene di semua video terlihat dari "dunia" yang sama.

## Karakter utama

- Manusia minimalis, kepala bulat hitam pekat, tanpa rambut detail
- Dua mata putih kecil yang ekspresif, tanpa hidung, mulut sangat sederhana (atau tanpa mulut)
- Badan ramping, lengan dan kaki tipis, pakaian polos (sweater krem atau kaos abu-abu)
- Ekspresi lewat bahasa tubuh: bahu turun, kepala menunduk, tangan di kepala

## Lingkungan

- Ruang minimalis: kamar, meja kerja dengan satu monitor, jendela geometris besar, jalan kota yang sepi
- Furnitur sederhana bentuk dasar, tanpa tekstur rumit
- Untuk TRADING: monitor menampilkan grafik candlestick yang disederhanakan (tanpa angka/teks terbaca)

## Palet warna

| Peran | Warna | Hex |
|---|---|---|
| Latar gelap / malam | Deep navy | #1E2A44 |
| Emosi sedih / tegang | Dark purple | #3D2B56 |
| Kehangatan / harapan | Warm cream | #F2E6D0 |
| Aksen emosi | Soft pink | #E8A6B0 |
| Aksen trading (untung/rugi) | Muted green / muted red | #6FA58A / #C46A6A |

Awal video cenderung navy/ungu, akhir video lebih krem/hangat.

## Pencahayaan & kamera

- Soft cinematic lighting, satu sumber cahaya utama (jendela, lampu meja, layar monitor)
- Kamera: slow push-in, slow pull-out, static, atau pan pelan. Tidak ada gerakan cepat.
- Komposisi 9:16, karakter di sepertiga tengah/bawah, area atas kosong untuk teks.

## BLOK GAYA TETAP (tempel di awal SETIAP prompt gambar)

```
Minimalist 2D animation style, flat vector illustration, simple faceless character with a round solid black head and small white expressive eyes, thin limbs, plain cream sweater, clean minimalist environment, soft cinematic lighting, limited color palette of deep navy, dark purple, warm cream and soft pink, subtle grain texture, vertical 9:16 composition, no text, no watermark
```

## Rumus prompt gambar

```
[BLOK GAYA TETAP], [lokasi], [aksi karakter + pose], [objek/metafora], [mood & warna dominan], [sudut kamera]
```

Contoh:
```
[BLOK GAYA TETAP], small dark bedroom at night, character sitting on the edge of the bed holding a phone, the phone light illuminates the face, a large shadow on the wall shaped like another person, melancholic mood dominated by deep navy and purple, medium shot from slightly below
```

## Rumus prompt animasi (image-to-video)

Singkat, 1 gerakan utama + 1 gerakan kamera:
```
[gerakan karakter], [gerakan objek/lingkungan], [gerakan kamera], slow and subtle motion, keep character design consistent
```

Contoh:
```
character slowly lowers the phone and looks at the shadow, the shadow grows slightly larger, slow camera push-in, slow and subtle motion, keep character design consistent
```

## Hindari

- Wajah realistis, rambut detail, jari kompleks
- Teks di dalam gambar (teks ditambahkan di CapCut)
- Lebih dari 2 karakter dalam satu frame
- Latar ramai, logo, merek
