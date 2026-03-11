# 🌐 ikhwanulhakim.site

🌐 _[Read in English](README.md)_

> Website pribadi yang harusnya jadi project weekend. Sekarang jadi satu file HTML 1900+ baris tanpa penyesalan.

<p align="center">
  <a href="https://ikhwanulhakim.site">
    <img src="https://img.shields.io/badge/👉_LIHAT_WEBSITE-ikhwanulhakim.site-00d4ff?style=for-the-badge&labelColor=0a192f" alt="Kunjungi Website"/>
  </a>
</p>

[![Self Hosted](https://img.shields.io/badge/Di_Host_Di-Laptop_Bekas_🏠-orange?style=flat-square)](#-fakta-menarik)

<p align="center">
  <img src="preview.png" alt="Preview" width="600"/>
</p>

---

## 📖 Ceritanya

Awalnya ini mau jadi project portfolio keren. Tau kan, yang tiap developer pasti janji ke diri sendiri mau bikin.

Rencananya _ambisius_:

```
✓ Halaman intro keren       (selesai! akhirnya ada yang jadi)
✓ Showcase project          (10 kartu portfolio, pamer secara bertanggung jawab)
✓ Timeline pengalaman kerja (ada entry "pengangguran produktif", iya beneran)
✓ Project pribadi           (ada tombol "Google it" buat dominasi SEO)
✓ Bagian about              (bukti pizza, foto kucing, dan video homeserver)
○ Bagian blog               (wkwk)
```

Plot twist: Keburu keterima kerja sebelum selesai. Terus diselesaiin juga pas nganggur 2 bulan karena punya "energi kreatif" (baca: kebanyakan waktu luang dan adonan pizza).

Bakal nambah blog? Mungkin. Kapan? Setelah kehabisan hal buat di-self-host.

---

## 💡 Fakta Menarik

Website ini jalan di **laptop Infinix InBook X1 bekas di kamar**. Intel i3-1005G1, 8GB RAM, 256GB NVMe. Pake Proxmox karena ngapain pake cloud provider kalau bisa cek `/var/log` sambil anxiety jam 2 pagi?

Ga pake AWS, ga pake Vercel, ga ada biaya langganan. Cuma vibes dan laptop yang nolak pensiun. Satu-satunya pengeluaran? Domain murah.

Self-hosted gang rise up. 🏠

---

## ⚙️ Tech Stack

| Layer        | Tech                                       |
| ------------ | ------------------------------------------ |
| Frontend     | HTML5, CSS3, Vanilla JS                    |
| CMS          | WordPress + Elementor (HTML block)         |
| Arsitektur   | Satu file. Itu aja. Itu stack-nya.         |
| Server       | Laptop bekas pake Proxmox                  |
| Uptime       | _tergantung tagihan listrik_               |
| CI/CD        | Ctrl+C, Ctrl+V ke WordPress                |

---

## 🎯 Fitur

- 🌙 Dark/Light mode dengan `localStorage` persistence
- 📱 Layout responsif pake `clamp()` di mana-mana
- ✨ Animasi CSS yang smooth (keyframes go brrr)
- 🔗 Social links (WhatsApp, Instagram, LinkedIn)
- 💼 Timeline pengalaman kerja dengan elemen `<time>` semantik
- 📂 Showcase portfolio (10 kartu, beberapa confidential karena NDA)
- 🚀 Project pribadi dengan link live dan tombol "Google it" buat flexing SEO
- 🍕 Bagian about dengan lightbox modal foto/video
- 🎥 Support video player di modal (buat tur homeserver)
- ♿ ARIA tab roles lengkap karena aksesibilitas itu flex, bukan beban
- 📊 JSON-LD structured data yang kaya (crawler Google kirim email terima kasih)
- 🔍 SEO yang thoroughnya kayak surat cinta buat search engine

---

## 📂 Struktur Repository

```
ikhwanulhakim.site/
├── elementor-embed.html  ← 1900+ baris tekad murni
├── linkedin_projects.txt ← sumber data portfolio (kitab suci)
├── PLAN.md               ← rencana yang entah gimana beneran diikutin
├── README.md             ← versi Inggris
└── README.id.md          ← kamu disini, selamat
```

---

## 🚀 Proses "Deployment"

```
1. Edit elementor-embed.html
2. Ctrl+A → Ctrl+C
3. Paste ke HTML block Elementor
4. Klik Save
5. Berdoa
6. Cek laptop masih hidup apa nggak
```

Ga ada CI/CD. Ga ada pipeline. Ga ada Docker. Cuma vibes dan Ctrl+V.

---

<p align="center">
  <b>© 2025 – 2026 Ikhwanul Hakim</b><br>
  <sub>Dibuat dengan prokrastinasi massal, pizza buatan sendiri, dan CSS custom properties yang kebanyakan</sub>
</p>
