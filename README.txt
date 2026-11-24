PORTFOLIO REZA — versi dashboard + efek musim (statis, tanpa admin)

Isi: index.html (semua teks + CSS + JS ada di sini), assets/ (foto + CV), wrangler.jsonc.
Ubah teks : edit index.html langsung.
Ganti foto/CV : timpa file di assets/ dengan nama yang sama.
Upload : timpa isi repo dengan file-file ini (index.html di root). "name" di wrangler.jsonc harus sama dengan nama Worker di Cloudflare.

Musim (tombol ikon di topbar): Autumn, Rain, Snow, Night sky. Pilihan tersimpan di browser pengunjung.
- Warna tiap musim: cari  html[data-season=...]  di bagian TOKENS pada <style>.
- Jumlah partikel: fungsi leaf / rain / snow / stars di <script> (angka n).
- Efek otomatis mati kalau pengunjung memakai "reduce motion"; ada juga saklar "Weather effects" di sidebar.
- Efek mesin ketik: tambahkan atribut data-tw pada elemen teks pendek (judul/kalimat).
- Highlight: <mark> (stabilo), <mark class="bx"> (kotak), <b>, <i>, <u class="wv"> (garis bergelombang), <s> (coret), <span class="rd"> (disensor).
Font: Special Elite + Courier Prime (Google Fonts, butuh internet; fallback Courier New).
