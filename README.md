# Class de Ichiban Kawaii Gal o Ezuke Shiteiru Hanashi

> Sakura Kouzuki, seorang gyaru populer di kelas yang juga bekerja sebagai model majalah, dan Houri Kazami, yang duduk di pojok kelas sambil asyik membicarakan hal-hal otaku bersama teman-temannya.Meskipun tampaknya berasal dari dunia yang benar-benar berbeda, keduanya sebenarnya adalah kakak-adik tiri dan pasangan kekasih yang tinggal serumah.Dan tidak ada satu pun teman sekelas mereka yang mengetahui fakta itu.Meski Sakura tampil bersinar dan ceria di sekolah, begitu sampai di rumah, ia langsung santai dan tergila-gila dengan masakan Houri.Dan Houri yang bertanggung jawab atas urusan makan pun sebenarnya sangat menikmati itu――.Sebuah kisah manis tentang memberi makan dan menikmati kehidupan ganda bersama gyaru imut di sekolah dan di rumah!

---

## Info

| | |
|---|---|
| Judul | Class de Ichiban Kawaii Gal o Ezuke Shiteiru Hanashi |
| Judul Alternatif | クラスで一番かわいいギャルを餌付けしている話 |
| Author | Tomo Shirano |
| Artist | Ryou Miyazaki |
| Tipe | Manga (Hitam Putih) |
| Status | Ongoing |
| Genre | Shounen · Cooking · Gyaru · Comedy · Romance · School Life · Slice of Life |
| Chapter | 25 chapter (1 locked) |

## Link

- [MangaDex](https://mangadex.org/title/acfd6902-b39c-4b7d-91a8-9825dda4ede8/class-de-ichiban-kawaii-gal-o-ezuke-shiteiru-hanashi)
- [Raw](https://www.manga-up.com/titles/1540)

---

## Struktur

```
KawaiiGal/
├── manga-config.json     # Metadata manga
├── manga.json            # Data chapter (auto-generated)
├── manga-automation.js   # Script automation
├── encrypt-manifest.js   # Script enkripsi manifest
├── daily-views.json      # Data views harian
└── <chapter>/
    └── manifest.json     # Daftar halaman (encrypted)
```

## Automation

Semua proses berjalan otomatis via GitHub Actions:

1. Push chapter baru (folder + manifest.json)
2. `encrypt-manifest.yml` — enkripsi manifest
3. `manga-automation.yml` — regenerate manga.json
4. Trigger rebuild ke website utama
5. `sync-cover.yml` — sinkronisasi cover dari website

---

Bagian dari [Nurananto Scanlation](https://nuranantoscans.my.id)