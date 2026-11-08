# Compression Engines (Bahasa Indonesia)

🌐 **Languages:** 🇺🇸 [English](../../../../compression/COMPRESSION_ENGINES.md) · 🇪🇹 [am](../../../am/docs/compression/COMPRESSION_ENGINES.md) · 🇸🇦 [ar](../../../ar/docs/compression/COMPRESSION_ENGINES.md) · 🇦🇿 [az](../../../az/docs/compression/COMPRESSION_ENGINES.md) · 🇧🇬 [bg](../../../bg/docs/compression/COMPRESSION_ENGINES.md) · 🇧🇩 [bn](../../../bn/docs/compression/COMPRESSION_ENGINES.md) · 🇧🇦 [bs](../../../bs/docs/compression/COMPRESSION_ENGINES.md) · 🇨🇿 [cs](../../../cs/docs/compression/COMPRESSION_ENGINES.md) · 🇩🇰 [da](../../../da/docs/compression/COMPRESSION_ENGINES.md) · 🇩🇪 [de](../../../de/docs/compression/COMPRESSION_ENGINES.md) · 🇬🇷 [el](../../../el/docs/compression/COMPRESSION_ENGINES.md) · 🇪🇸 [es](../../../es/docs/compression/COMPRESSION_ENGINES.md) · 🇪🇪 [et](../../../et/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇷 [fa](../../../fa/docs/compression/COMPRESSION_ENGINES.md) · 🇫🇮 [fi](../../../fi/docs/compression/COMPRESSION_ENGINES.md) · 🇫🇷 [fr](../../../fr/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇪 [ga](../../../ga/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [gu](../../../gu/docs/compression/COMPRESSION_ENGINES.md) · 🇳🇬 [ha](../../../ha/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇱 [he](../../../he/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [hi](../../../hi/docs/compression/COMPRESSION_ENGINES.md) · 🇭🇷 [hr](../../../hr/docs/compression/COMPRESSION_ENGINES.md) · 🇭🇺 [hu](../../../hu/docs/compression/COMPRESSION_ENGINES.md) · 🇦🇲 [hy](../../../hy/docs/compression/COMPRESSION_ENGINES.md) · 🇳🇬 [ig](../../../ig/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇹 [it](../../../it/docs/compression/COMPRESSION_ENGINES.md) · 🇯🇵 [ja](../../../ja/docs/compression/COMPRESSION_ENGINES.md) · 🇬🇪 [ka](../../../ka/docs/compression/COMPRESSION_ENGINES.md) · 🇰🇭 [km](../../../km/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [kn](../../../kn/docs/compression/COMPRESSION_ENGINES.md) · 🇰🇷 [ko](../../../ko/docs/compression/COMPRESSION_ENGINES.md) · 🇱🇹 [lt](../../../lt/docs/compression/COMPRESSION_ENGINES.md) · 🇱🇻 [lv](../../../lv/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [ml](../../../ml/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [mr](../../../mr/docs/compression/COMPRESSION_ENGINES.md) · 🇲🇾 [ms](../../../ms/docs/compression/COMPRESSION_ENGINES.md) · 🇲🇹 [mt](../../../mt/docs/compression/COMPRESSION_ENGINES.md) · 🇲🇲 [my](../../../my/docs/compression/COMPRESSION_ENGINES.md) · 🇳🇵 [ne](../../../ne/docs/compression/COMPRESSION_ENGINES.md) · 🇳🇱 [nl](../../../nl/docs/compression/COMPRESSION_ENGINES.md) · 🇳🇴 [no](../../../no/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [or](../../../or/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [pa](../../../pa/docs/compression/COMPRESSION_ENGINES.md) · 🇵🇭 [phi](../../../phi/docs/compression/COMPRESSION_ENGINES.md) · 🇵🇱 [pl](../../../pl/docs/compression/COMPRESSION_ENGINES.md) · 🇵🇹 [pt](../../../pt/docs/compression/COMPRESSION_ENGINES.md) · 🇧🇷 [pt-BR](../../../pt-BR/docs/compression/COMPRESSION_ENGINES.md) · 🇷🇴 [ro](../../../ro/docs/compression/COMPRESSION_ENGINES.md) · 🇷🇺 [ru](../../../ru/docs/compression/COMPRESSION_ENGINES.md) · 🇱🇰 [si](../../../si/docs/compression/COMPRESSION_ENGINES.md) · 🇸🇰 [sk](../../../sk/docs/compression/COMPRESSION_ENGINES.md) · 🇸🇮 [sl](../../../sl/docs/compression/COMPRESSION_ENGINES.md) · 🇷🇸 [sr](../../../sr/docs/compression/COMPRESSION_ENGINES.md) · 🇸🇪 [sv](../../../sv/docs/compression/COMPRESSION_ENGINES.md) · 🇰🇪 [sw](../../../sw/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [ta](../../../ta/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [te](../../../te/docs/compression/COMPRESSION_ENGINES.md) · 🇹🇭 [th](../../../th/docs/compression/COMPRESSION_ENGINES.md) · 🇹🇷 [tr](../../../tr/docs/compression/COMPRESSION_ENGINES.md) · 🇺🇦 [uk-UA](../../../uk-UA/docs/compression/COMPRESSION_ENGINES.md) · 🇵🇰 [ur](../../../ur/docs/compression/COMPRESSION_ENGINES.md) · 🇺🇿 [uz](../../../uz/docs/compression/COMPRESSION_ENGINES.md) · 🇻🇳 [vi](../../../vi/docs/compression/COMPRESSION_ENGINES.md) · 🇳🇬 [yo](../../../yo/docs/compression/COMPRESSION_ENGINES.md) · 🇨🇳 [zh-CN](../../../zh-CN/docs/compression/COMPRESSION_ENGINES.md) · 🇹🇼 [zh-TW](../../../zh-TW/docs/compression/COMPRESSION_ENGINES.md)

---

kompresi OmniRoute dibangun berdasarkan kontrak mesin. Sebuah mode dapat menjalankan satu mesin secara langsung (`caveman` atau `rtk`) atau pipeline bertumpuk deterministik yang mengeksekusi beberapa mesin secara berurutan.

## Mode

| Mode         | Jalur mesin                                                                                      | Masukan yang dimaksudkan                          |
| ------------ | ------------------------------------------------------------------------------------------------ | ------------------------------------------------- |
| `off`        | tidak ada                                                                                        | Pelestarian cepat yang tepat                      |
| `lite`       | Pembantu ringan manusia gua                                                                      | Pembersihan selalu berisiko rendah                |
| `standard`   | Manusia gua                                                                                      | Kondensasi cepat dalam bahasa alami               |
| `aggressive` | Ringkasan manusia + history/tool                                                                 | Sesi obrolan panjang                              |
| `ultra`      | Pembantu pemangkasan + manusia gua                                                               | Pemulihan batas konteks                           |
| `rtk`        | RTK                                                                                              | Terminal, shell, build, test, dan keluaran git    |
| `omniglyph`  | OmniGlyph                                                                                        | Konteks-sebagai-gambar pada kabel penyedia asli   |
| `stacked`    | Saluran pipa. Default permintaannya adalah `session-dedup -> lite`. `rtk -> caveman` ikut serta. | Log alat campuran dan prosa, penghematan maksimal |

### profil kompresi OmniGlyph

Mesin `omniglyph` (paket `omniglyph`, 1.4.0 +) menerima profil semantik bernama, diatur secara global melalui `omniglyph.profile` dalam pengaturan kompresi atau per langkah melalui konfigurasi langkah pipa bertumpuk:

| Profil        | Batas                                                                                                   |
| ------------- | ------------------------------------------------------------------------------------------------------- |
| `aggressive`  | Bawaan. Kebijakan penerimaan yang diterbitkan mengukur sistem gambar —, dokumen alat, dan riwayat padat |
| `balanced`    | Mempertahankan status asli, melindungi 8 putaran terakhir, meruntuhkan riwayat tertutup yang lebih lama |
| `coding-safe` | Menjaga otoritas, skema alat, dan keluaran alat langsung tetap asli, melindungi 12 putaran terakhir     |
| `passthrough` | Rute tanpa transformasi; mesin dilewati                                                                 |

Profilnya adalah a** langit-langit, bukan lantai** : `mergeCompressionProfileOptions` dalam paket menolak untuk membiarkan penelepon menimpa membuka kembali jalur lossy profil ditutup, sehingga `preserveSystemPrompt: false` per langkah tidak dapat mengaktifkan kembali kompresi sistem di bawah `coding-safe`.

Diukur pada basis kode ini: `coding-safe` dan `balanced` menaikkan `minCompressChars` ke maksimum dan menjaga sistem, skema alat, dan hasil alat tetap asli, sehingga sesi yang belum mengumpulkan riwayat berhenti di `below_min_chars` dan mesin tidak mengubah apa pun. Itu sebabnya defaultnya adalah `aggressive` daripada profil teraman.

Paket ini menyelesaikan cakupan model dan profilnya sendiri dari konfigurasi lingkungannya. OmniRoute tidak pernah mendelegasikan keputusan: adaptor menyematkan gerbang model ke cakupan paket yang paling ketat, sehingga pengaturan lingkungan host hanya dapat mempersempit daftar yang diizinkan, tidak pernah memperluasnya melebihi penerimaan terukur OmniRoute.

## Registri Mesin

Registri tinggal di `open-sse/services/compression/engines/registry.ts`. Mesin memaparkan kontrak bersama:

- `id`: id mesin stabil seperti `caveman` atau `rtk`
- `apply(text, config)`: jalur eksekusi lama yang digunakan oleh saluran pipa bertumpuk
- `compress(input, config)`: jalur eksekusi utama yang mengembalikan teks statistik +
- `getConfigSchema()`: mengembalikan bentuk konfigurasi valid seperti Skema JSON
- `validateConfig(config)`: mengembalikan `{ valid, errors[] }`

Pendaftaran menggunakan `registerCompressionEngine(engine)` (atau `registerEngine` untuk kasus tingkat lanjut), yang memanggil `assertValidEngine()` dan `validateConfig(defaultConfig)` sebelum menerima. Gunakan `unregisterCompressionEngine(id)` untuk melepas mesin saat runtime.

`strategySelector.ts` mendaftarkan mesin bawaan sebelum kompresi dijalankan. Hal ini memungkinkan pratinjau, kompresi waktu proses, mode bertumpuk, pengujian, dan mesin masa depan menggunakan jalur eksekusi yang sama.

### kompresi deskripsi MCP (terkait)

Registri terpisah memampatkan metadata deskripsi alat MCP di tingkat registri — lihat `open-sse/mcp-server/descriptionCompressor.ts` dan [MCP-SERVER.md](../frameworks/MCP-SERVER.md). Ini menggunakan kembali aturan Caveman tetapi beroperasi pada metadata alat, bukan muatan permintaan.

### Mesin bawaan tambahan

Di luar Caveman, RTK, dan LLMLingua-2, registri mengirimkan beberapa mesin lossless/struktural khusus (digunakan oleh saluran pipa bertumpuk, taman bermain, dan pengujian):

| Mesin        | Pengenal        | Apa fungsinya                                                                                                                                                                                             |
| ------------ | --------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| CCR          | `ccr`           | Content-Compress-Retrieve (H4): menggantikan blok teks besar yang bersebelahan dengan referensi yang ditujukan pada konten, sehingga blok repeated/large dikirim satu kali dan direferensikan setelahnya. |
| ruang kepala | `headroom`      | SmartCrusher (H3 + N5): pemadatan tabel lossless dari muatan array JSON homogen ke dalam bentuk `[N rows]` kolom.                                                                                         |
| pengion      | `ionizer`       | pengambilan sampel baris Head/middle/tail untuk blok homogen yang sangat besar, menyimpan bagian tengah yang tereliminasi sebagai referensi alamat konten CCR.                                            |
| sesi-dedup   | `session-dedup` | Deduplikasi lintas putaran yang ditujukan pada konten (terinspirasi oleh TokenMizer): menghilangkan teks yang sudah terlihat di putaran sebelumnya pada sesi yang sama.                                   |

**instruksi protokol pengambilan CCR (#8033):** pertama kali CCR menggantikan blok ≥ 1 dalam permintaan, mesin menambahkan satu pesan `system` idempoten (dimulai dengan penjaga `[CCR protocol]` ) mengajarkan kepada pemanggil kontrak alat penanda → : apa arti penanda `[CCR retrieve hash=<24hex> chars=N]`, bahwa hash harus disalin kata demi kata (semua 24 karakter hex hash — yang salah disalin kemungkinan besar menyebabkan kesalahan "blok tidak ditemukan"), dan bahwa penanda `[dedup:ref sha=...]` berarti "lihat kembali ke dalam history", bukan "panggil alat". Catatan itu disuntikkan** hanya jika `tools[]` yang diiklankan penelepon membuktikan bahwa ia benar-benar dapat mencapai `omniroute_ccr_retrieve`** (`callerSupportsCcrRetrieve()` in `open-sse/services/compression/engines/ccr/protocolInstruction.ts`) — penelepon biasa yang kompatibel dengan OpenAI tanpa alat itu tidak akan pernah menerima instruksi untuk memanggil sesuatu yang tidak dapat dijangkau. Idempotensi diterapkan dengan memindai riwayat pesan untuk sentinel sebelum melakukan injeksi, sehingga permintaan multi-turn (yang memutar ulang pesan sebelumnya) tidak menumpuk catatan satu kali per giliran.

## Manusia gua

Mode manusia gua berfokus pada kondensasi semantik dari prosa normal:

- mempertahankan blok kode, URLs, JSON, jalur, dan data terstruktur
- menghilangkan pengisi, lindung nilai, konteks berulang, dan frasa penghubung verbose
- mendukung paket aturan file yang sadar bahasa di `open-sse/services/compression/rules/`
- tetap tersedia melalui mode `standard`, `aggressive`, dan `ultra` lama

Permukaan dasbornya `Dashboard -> Context & Cache -> Caveman`.

Laporan hulu Caveman `~75%` lebih sedikit token keluaran, penghematan keluaran rata-rata `65%` dalam tolok ukur dengan rentang `22-87%`, dan alat kompresi masukan `~46%`. OmniRoute menggunakan nomor sisi input Caveman saat mendokumentasikan tumpukan simpanan prompt/context ; Mode keluaran manusia gua tetap menjadi fitur perilaku respons yang terpisah.

## RTK

mode RTK berfokus pada keluaran perintah dan alat:

- mendeteksi kelas keluaran seperti `git status`, `git branch`, `git diff`, Vitest/Jest/Pytest, Cargo/Go tes, TypeScript/Vite/Webpack build, ESLint, npm audit/installs, Docker logs, shell `find`/`grep`, stack trace, dan generic logs
- menerapkan 49 filter JSON dari `open-sse/services/compression/engines/rtk/filters/`
- mendukung pipeline deklaratif gaya RTK: ANSI stripping, replace, match-output short-circle, strip/keep line, per-line truncation, head/tail/max-line truncation, dan on-empty fallback
- mendukung filter proyek yang terjaga keamanannya di `.rtk/filters.json` dan filter global di `DATA_DIR/rtk/filters.json`
- menghapus urutan ANSI, kebisingan kemajuan, garis berulang, dan boilerplate yang tidak membantu
- mempertahankan kegagalan, peringatan, ringkasan, file yang diubah, dan konteks ekor yang dapat ditindaklanjuti
- secara opsional dapat mempertahankan keluaran mentah yang telah disunting untuk recovery/debugging melalui rute manajemen yang diautentikasi

Permukaan dasbornya `Dashboard -> Context & Cache -> RTK`.

Detail operasional untuk filter khusus, kepercayaan, verifikasi, dan pemulihan keluaran mentah ada di [`RTK_COMPRESSION.md`](./RTK_COMPRESSION.md).

RTK upstream melaporkan penghematan `60-90%` untuk kompresi keluaran perintah. Contoh README -nya menunjukkan sesi Kode Claude selama 30 menit yang beralih dari token `~118,000` ke `~23,900`, atau `79.7%` disimpan.

## LLMLingua-2 (Pemangkasan Semantik)

mode LLMLingua-2 berfungsi** pemangkasan token semantik** pada prosa menggunakan pengklasifikasi token ONNX kecil, melengkapi mesin Caveman dan RTK berbasis aturan:

- mengompresi prosa hanya dalam pesan non-sistem; blok kode berpagar dan konstruksi lain yang diawetkan tidak pernah diubah
- menjalankan backend `@atjsh/llmlingua-2` (ONNX via `@huggingface/transformers`) di thread pekerja, sehingga inferensi model tidak pernah memblokir loop peristiwa permintaan
- adalah** dapat ditumpuk** (`stackPriority` 35): dalam pipa bertumpuk, ini berjalan setelah mesin struktural (CCR, session-dedup, headroom, Caveman) tetapi sebelum `ultra`, karena pemangkasan semantik paling efektif pada teks yang sudah dikompresi secara struktural — misalnya `rtk -> caveman -> llmlingua`
- **gagal-terbuka pada kesalahan apa pun** (tidak ada deps opsional, kemunculan pekerja, pemuatan model, inferensi, atau batas waktu) → teks asli dikembalikan tidak berubah, tidak pernah ada kesalahan

Lokasi mesin: `open-sse/services/compression/engines/llmlingua/`. Permukaan dasbornya `Dashboard -> Context & Cache -> LLMLingua`.

### Model

Model defaultnya adalah**TinyBERT** (`atjsh/llmlingua-2-js-tinybert-meetingbank`, ~ 57 MB, cepat). Akurasi yang lebih tinggi** Basis BERT** model (`Arcoldd/llmlingua4j-bert-base-onnx`, ~ 710 MB) tersedia melalui bidang konfigurasi mesin `model`. `@huggingface/transformers` mengunduh model yang dipilih dengan malas dari HuggingFace Hub ke `${DATA_DIR}/models/llmlingua` pada panggilan pertama (`modelStore.ts`); penggantian konfigurasi `modelPath` mengarahkannya ke salinan lokal (pemasangan offline/pemasangan udara).

### Ketergantungan opsional & pemasangan sesuai permintaan

Tumpukan peer runtime LLMLingua yang dapat dipangkas adalah** opsional** . Dua paket dideklarasikan sebagai `optionalDependencies` di `package.json` dan disimpan** luar** oleh build produksi (`scripts/build/prepublish.ts` tidak menggabungkannya):

| Kemasan              | Versi (pin) | Catatan                                         |
| -------------------- | ----------- | ----------------------------------------------- |
| `@atjsh/llmlingua-2` | `2.0.5`     | Paket masuk; menyatakan yang lain sebagai rekan |
| `js-tiktoken`        | `^1.0.20`   | Tokenizer                                       |

`@huggingface/transformers` disematkan di `^4.2.0` (dibagi dengan jalur penyematan lokal dan juga ditelusuri ke dalam bundel mandiri); `@atjsh/llmlingua-2@2.0.5` melakukan rekanan dengan `"^3.5.2 || ^4.0.0"`, sehingga Transformers.js v3 dan v4 didukung. Sejak 2.0.4, `@atjsh/llmlingua-2` tidak lagi memerlukan `@tensorflow/tfjs`, yang menghapus kontributor tunggal terbesar (TensorFlow.js) dari tumpukan SLM. Hanya dua paket di atas yang merupakan rekan SLM yang dapat dipangkas. `npm install` (dev) standar menginstal tumpukan opsional secara otomatis kecuali dependensi opsional dihilangkan.

**Mengapa sesuai permintaan:** paket yang diterbitkan npm, paket mandiri, dan pengiriman gambar Docker** tanpa** deps ini untuk tetap langsing. Ketika mereka tidak ada, gerbang ketergantungan pekerja (probe penyelesaian `@atjsh/llmlingua-2` di `worker.ts`) gagal dan mesin** gagal-terbuka secara diam-diam** — memilih LLMLingua menjadi larangan operasi (teks dikembalikan tidak berubah, tidak ada kesalahan yang tercatat). Untuk mengaktifkannya di lingkungan yang dipangkas, instal tumpukan opsional:

```bash
# pin to the versions declared in package.json optionalDependencies
npm install @atjsh/llmlingua-2@2.0.5 js-tiktoken
```

Penghapusan `@tensorflow/tfjs` (2.0.4 +) menghilangkan kontributor ~ 800 MB yang sebelumnya dominan — jejak yang tersisa adalah runtime transformers.js + onnxruntime-node, ditambah model TinyBERT (~ 57 MB) yang diunduh pada penggunaan pertama (bukan melalui npm).

Per lingkungan:

- **Dev / `npm install`** — diinstal secara otomatis kecuali Anda melewati `--omit=optional` (atau `--no-optional`). Tidak diperlukan tindakan.
- **Npm global (`npm i -g omniroute`) / mandiri** — jalankan perintah install di atas di dalam direktori paket yang diinstal, atau instal ulang tanpa menghilangkan deps opsional.
- **Docker** — menambahkan perintah install di lapisan gambar turunan; gambar yang dipublikasikan dikirimkan dengan desain yang ramping.
- **VPS (PM2)** — install ke `node_modules` aplikasi, lalu mulai ulang prosesnya sehingga pekerja memeriksa ulang gerbangnya.
- **Mentah Berikutnya mandiri (`npm run build` → `.build/next/standalone/server.js`)** — jejak mandiri mengirimkan NEITHER pekerja maupun deps opsional, sehingga mesin gagal terbuka secara diam-diam. `scripts/build/colocate-standalone.mjs` menerapkan kembali keduanya (pekerja esbuild + penutupan opsional-dep ke pohon mandiri); ini berjalan secara otomatis melalui hook `postbuild` npm setelah setiap build. Idempoten, lunak ketika deps tidak ada.

**Pastikan itu aktif:** dengan LLMLingua dipilih, prosa sebenarnya sebenarnya menyusut (mesin berhenti gagal membuka), dan permintaan pertama memicu pengunduhan model ke `${DATA_DIR}/models/llmlingua`. Gerbang dengan sengaja hanya menyelidiki `@atjsh/llmlingua-2` — rekan-rekan lainnya hanya untuk ESM dan `require.resolve` melemparkannya bahkan ketika ada — sehingga pekerja masih gagal membuka jika ada rekan yang benar-benar hilang pada waktu `import()`.

## Pipa Bertumpuk

Mode bertumpuk menjalankan langkah-langkah alur secara berurutan. Standarnya adalah:

```txt
rtk -> caveman
```

Gunakan ini untuk sesi agen pengkodean di mana prompt menggabungkan output perintah dengan prosa manusia atau asisten. RTK mengurangi log alat yang berisik terlebih dahulu, lalu Caveman mengompresi bahasa alami yang tersisa.

Langkah-langkah pipeline dikonfigurasikan dengan `stackedPipeline` dalam pengaturan kompresi atau melalui kombo kompresi.

Ketika kedua mesin mengurangi muatan yang memenuhi syarat yang sama, penghematan bertambah:

```txt
combined = 1 - (1 - RTK savings) * (1 - Caveman input savings)
average  = 1 - (1 - 0.80) * (1 - 0.46) = 89.2%
range    = 1 - (1 - 0.60..0.90) * (1 - 0.46) = 78.4-94.6%
```

## MCP Filter Pohon Aksesibilitas

Filter pintar pohon aksesibilitas MCP adalah lapisan kompresi pasca-eksekusi yang berjalan di MCP** hasil alat** , bukan berdasarkan perintah atau konteks. Ini menargetkan pohon aksesibilitas verbose dan payload snapshot browser yang dikembalikan oleh alat seperti Playwright, penggunaan komputer, dan server MCP otomatisasi browser.

### Apa fungsinya

1. **Penghilangan kebisingan** — menghapus entri generic/text yang kosong (`- generic:`, `- text: ""`)
2. **Keruntuhan saudara kandung** — ketika ≥ `collapseThreshold` (default 30) baris berturut-turut adalah pengulangan struktural, gabungkan menjadi baris `collapseKeepHead` (default 10) pertama + ringkasan hitungan + baris `collapseKeepTail` terakhir (default 5)
3. **Pelestarian referensi** — `[ref=eXX]` jangkar yang dibutuhkan oleh Playwright/computer-use tidak pernah disentuh
4. **Pemotongan yang sulit** — jika teks setelah diciutkan masih melebihi `maxTextChars` (default 50.000), terpotong dengan petunjuk navigasi sehingga agen dapat terus bekerja

### Lokasi mesin

```txt
open-sse/services/compression/engines/mcpAccessibility/
  index.ts            ← smartFilterText() entry point
  collapseRepeated.ts ← sibling-collapse algorithm
  constants.ts        ← DEFAULT_MCP_ACCESSIBILITY_CONFIG
```

### Konfigurasi

Dikendalikan oleh `compression.mcpAccessibility` dalam pengaturan global (migrasi 056). Konfigurasi bawaan:

```json
{
  "enabled": true,
  "maxTextChars": 50000,
  "collapseThreshold": 30,
  "collapseKeepHead": 10,
  "collapseKeepTail": 5,
  "minLengthToProcess": 2000
}
```

Filter ini hanya diterapkan pada muatan hasil pahat yang `type` adalah `"text"` dan panjangnya melebihi `minLengthToProcess`. Ini tidak mempengaruhi kompresi cepat atau muatan permintaan.

### Penghematan yang diharapkan

60–80% pada hasil alat snapshot browser, bergantung pada kompleksitas halaman. Algoritme penciutan adalah O(n) dalam jumlah baris dan menambahkan latensi yang dapat diabaikan.

### Filter ini vs mesin kompresi di atas

| Aspek             | Manusia gua / RTK / Ditumpuk | filter aksesibilitas MCP               |
| ----------------- | ---------------------------- | -------------------------------------- |
| Target            | Permintaan petunjuk/konteks  | hasil alat MCP                         |
| Pemicu            | Pengaturan mode kompresi     | `compression.mcpAccessibility.enabled` |
| Cakupan           | Semua pesan SSE              | Hasil alat saja                        |
| Jangkar referensi | N/A                          | Diawetkan tanpa syarat                 |

---

## Kombo Kompresi

Kombo kompresi diberi nama profil kompresi yang dapat ditetapkan ke kombo perutean:

- `compression_combos`: menyimpan mode, pipeline, konfigurasi RTK, konfigurasi bahasa, dan penanda default
- `compression_combo_assignments`: memetakan kombo kompresi ke kombo perutean
- integrasi runtime menyelesaikan kombo kompresi yang ditetapkan sebelum kombo umum diganti
- analitik termasuk `compression_combo_id` dan `engine`

Permukaan dasbor: `Dashboard -> Context & Cache -> Compression Combos`.

## Prasyarat / panduan operator (CCR & sesi-dedup)

CCR (`ccr`) dan `session-dedup` ganti atau hilangkan teks dan tinggalkan a** penanda** di belakang. Bagian ini adalah referensi operator untuk menghubungkan klien, membaca dua penanda, dan mengambil atau mendiagnosis konten yang dihilangkan. Mekanika masing-masing mesin dibahas di atas; ini adalah lapisan "bagaimana cara menjalankannya".

### Transportasi & titik akhir

Server MCP yang mengekspos alat CCR dapat dijangkau dengan tiga cara. Basis default URL adalah `http://localhost:20128` (`OMNIROUTE_BASE_URL`):

| Mengangkut                                          | URL / perintah                          | Catatan                                                                                                                                                    |
| --------------------------------------------------- | --------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------- |
| HTTP yang dapat dialirkan (klien, direkomendasikan) | `http://localhost:20128/api/mcp/stream` | Titik akhir yang diajak bicara oleh klien MCP saat ini.                                                                                                    |
| SSE singleton lawas                                 | `http://localhost:20128/api/mcp/sse`    | Transportasi tunggal yang lebih tua. Dia** menutup** sesi yang dapat dialirkan; gunakan klien `streamable-http` melawan `/api/mcp/stream`, bukan yang ini. |
| stdio                                               | `omniroute --mcp`                       | Untuk konfigurasi IDE MCP yang memunculkan proses. Tidak ada bendera `--dev` ; `omniroute --mcp` adalah titik masuk stdio.                                 |

### Tingkat penyimpanan (yang bertahan jika dimulai ulang)

CCR adalah a** dua tingkat** simpan, bukan hanya di memori:

- **Tingkat dalam memori yang panas** — per blok tutup 2 MiB, per kepala sekolah 16 MiB, global 64 MiB. Entri default ke TTL 24 jam (maksimum 7 hari). Pengambilan MCP penuh dari memori dibatasi pada 256 KiB; apa pun yang lebih besar masih dapat dijangkau melalui mode jarak jauh/grep.
- **Tingkat SQLite yang tahan lama** (`ccr_blocks`, `COMPRESSION_CCR_DURABLE_STORE`, aktif secara default) — mendukung tingkat dalam memori sehingga sebuah blok bertahan dari penggusuran LRU, restart, atau pengambilan kembali di instance lain. Baris tersebut mempertahankan TTL blok, sehingga blok yang melewati TTL hilang dari kedua tingkatan.

Tiga penjaga menjaga tingkat tahan lama yang dibatasi — sebuah blok tetap hanya untuk memori ketika:

1. blok sudah berakhir** 512 KB** (`MAX_DURABLE_BLOCK_BYTES`);
2. runtime adalah runtime cloud (tidak ada disk lokal);
3. `COMPRESSION_CCR_DURABLE_STORE=false`.

Jadi "blok menghilang" bukanlah cerita restart menyeluruh: blok sub-512 KB pada runtime non-cloud lokal akan bertahan jika restart melalui tingkat tahan lama sampai TTL -nya habis. Lihat [Referensi lingkungan](../reference/ENVIRONMENT.md) untuk variabel.

### Kedua penanda itu

| Penanda                               | Arti                                                                                                                                                                                     | Apa yang harus dilakukan oleh model tersebut                                                                                                                                                                                                         |
| ------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| `[CCR retrieve hash=<24hex> chars=N]` | Sebuah blok besar disimpan dengan alamat konten.                                                                                                                                         | Hubungi `omniroute_ccr_retrieve` dengan** Hash 24-hex disalin kata demi kata** untuk mendapatkan teks aslinya kembali.                                                                                                                               |
| `[dedup:ref sha=…]`                   | `session-dedup` teks yang dihilangkan sudah dikirim pada giliran sebelumnya di sesi yang sama. Ini adalah sebuah** melihat ke belakang dengan sengaja** , bukan kerugian atau kesalahan. | Melakukan** bukan** panggil alat apa pun dan lakukan** bukan** cobalah untuk "merekonstruksinya". Kemunculan pertama teks tersebut adalah salinan kanonik; giliran saat ini tidak pernah ditulis ulang, melainkan dikurangi pada giliran berikutnya. |

`[dedup:ref]` melihat kembali adalah keputusan protokol yang disengaja — tidak ada rekonstruksi sebelum pengiriman. Anggap saja sebagai "teks persis seperti ini sudah disampaikan pada awal sesi ini."

### Prasyarat klien

- **Kunci (stdio):** penelepon stdio tidak membawa identitas per permintaan, sehingga diautentikasi dengan `OMNIROUTE_API_KEY` (diatur dalam `env` server MCP ). Tanpanya, penelepon bersifat anonim dan alat yang memerlukan prinsipal dapat menurun.
- **`tools[]` adalah prasyarat injeksi.** Instruksi protokol pengambilan CCR (#8033) disuntikkan** hanya** ketika permintaan yang diiklankan `tools[]` membuktikan bahwa klien benar-benar dapat mencapai `omniroute_ccr_retrieve`. Pencocokannya adalah pencocokan segmen tambahan yang dibatasi oleh pemisah (`__`, `.`, `/`, `:`) — tidak pernah berupa substring kosong — sehingga nama dengan namespace seperti `mcp__gateway__omniroute_ccr_retrieve` tetap dihitung. `tools[]` yang tidak ada atau tidak cocok berarti instruksinya _tidak_ disuntikkan, sesuai desain.
- **`codemode:false` (klien OpenCode ).** OpenCode defaultnya adalah Mode Kode, yang hanya mengiklankan alat aslinya ke model dan** tidak** letakkan alat MCP di daftar `tools[]` asli. Setel `codemode: false` pada entri server MCP sehingga alat `omniroute_ccr_*` diiklankan. Ini adalah sebuah** klien** pengaturan, bukan yang OmniRoute. Itu belum memasukkan instruksi CCR : OpenCode memberi nama alat `<server>_<tool>`, sehingga server bernama `omniroute` mengekspos `omniroute_omniroute_ccr_retrieve`, dan `_` bukan salah satu pemisah yang cocok.
- **Kepala Sekolah.** Penyimpanan dan pengambilan diisolasi per prinsipal yang diautentikasi (per kunci API ). Sebuah kunci hanya melihat bloknya sendiri.

### Cakupan per alat

Penegakan cakupan selalu aktif untuk penelepon HTTP/SSE dengan cakupan sempit. Alat `omniroute_` CCR memerlukan:

| Alat                     | Cakupan             |
| ------------------------ | ------------------- |
| `omniroute_ccr_store`    | `write:compression` |
| `omniroute_ccr_delete`   | `write:compression` |
| `omniroute_ccr_retrieve` | `read:compression`  |
| `omniroute_ccr_inspect`  | `read:compression`  |
| `omniroute_ccr_list`     | `read:compression`  |
| `omniroute_ccr_stats`    | `read:compression`  |

Cakupan yang hilang mengembalikan sebuah** hasil kesalahan alat MCP** (`isError: true`, bukan HTTP 403 — `403 LOCAL_ONLY` adalah auth penjaga rute loopback yang terpisah): `Error: Insufficient MCP scopes for <tool>. Missing: <scope>.` Kunci jarak jauh minimal dapat menampung `mcp:connect` (mengotorisasi `/api/mcp/` ukiran lokal saja) ditambah cakupan read/write spesifik yang dibutuhkannya.

### Matriks klien

| Klien                    | Mengangkut                                                | Konfigurasi yang akan digunakan                                                                                                                                                                                                                           | `tools[]` diiklankan? (instruksi → CCR disuntikkan)                                                                                                                                                 |
| ------------------------ | --------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Kode Claude              | dapat dialirkan-http                                      | `claude mcp add --transport http omniroute http://localhost:20128/api/mcp/stream`                                                                                                                                                                         | Ya — berkemampuan MCP; disuntikkan.                                                                                                                                                                 |
| Cursor / Cline           | `stdio`** atau** `streamable-http`                        | stdio: `omniroute --mcp` dengan `OMNIROUTE_API_KEY` di `env`; atau entri MCP jarak jauh yang menunjuk ke `http://localhost:20128/api/mcp/stream` (lihat [Panduan Pengaturan → MCP Konfigurasi Klien](../guides/SETUP_GUIDE.md#mcp-client-configuration) ) | Ya — mengiklankan alat `omniroute_ccr_*`.                                                                                                                                                           |
| OpenCode                 | dapat dialirkan-http                                      | `opencode mcp add omniroute --url http://localhost:20128/api/mcp/stream`, ditambah `codemode: false`                                                                                                                                                      | Alat yang diiklankan hanya dengan `codemode: false`; instruksinya masih belum disuntikkan, karena `omniroute_omniroute_ccr_retrieve` tidak cocok (lihat [Prasyarat klien](#client-prerequisites) ). |
| Kompatibel dengan OpenAI | HTTP yang kompatibel dengan OpenAI (penyelesaian obrolan) | klien penyelesaian obrolan standar terhadap titik akhir yang kompatibel dengan OpenAI                                                                                                                                                                     | **Tidak pernah** — penelepon biasa yang kompatibel dengan OpenAI tidak pernah diminta untuk memanggil alat tersebut, dan instruksinya tidak dimasukkan.                                             |

### Batas pengambilan & penomoran halaman

hasil teks alat MCP terpotong di sekitar `mcpAccessibility.maxTextChars` (default `50000`). Pengambilan `full` suatu blok dibatasi pada 256 KiB —** tidak ada pengambilan penuh tanpa batas** . Ketika `chars=N` suatu blok besar, halamankanlah blok tersebut alih-alih menarik semuanya:

- Aturan praktisnya:**`chars > 40000` → gunakan `mode`** , tidak pernah penuh.
- `mode:"grep"` — regex `pattern` mencocokkan baris demi baris, hingga 1.000 baris yang cocok (`unique: true` tetes berulang), termurah untuk "temukan satu baris yang saya perlukan."
- `mode:"lines"` — rentang garis 1 yang diindeks; membutuhkan `start` dan `end`.
- garis `mode:"head"` / `mode:"tail"` — first/last `n`.
- `mode:"stats"` — jumlah baris, karakter, dan byte tanpa isi.

Gunakan `mode:"lines"` dengan `start`/`end` untuk berjalan dalam satu blok panjang di halaman daripada meminta semuanya sekaligus.

### Penamaan alat

Alat pengambilan saat ini bernama `omniroute_ccr_retrieve` (awalan `omniroute_` adalah solusi tertanggal untuk tabrakan nama lintas server). Nama alat akhiran terbatas yang lebih bersih dan perbaikan untuk hasil MCP JSON terpotong di tengah string dilacak sebagai tindak lanjut hulu; halaman ini hanya mendokumentasikan perilaku yang dikirimkan saat ini.

### Siklus hidup sesi

Sesi HTTP yang dapat dialirkan tidak aktif dan server mengambilnya; jendela idle adalah konstanta `MCP_SESSION_IDLE_MS` (direferensikan berdasarkan nama, bukan nilai hardcode, sehingga halaman ini tidak melayang saat diubah). Gejala sesi yang menganggur adalah HTTP 404 dengan `Unknown Mcp-Session-Id` — solusinya adalah menyambungkan kembali atau memulai kembali sesi,** bukan** untuk memutar kunci, mengubah cakupan, atau mengganti nama alat.

## API Permukaan

| Rute                                   | Tujuan                                                                |
| -------------------------------------- | --------------------------------------------------------------------- |
| `/api/settings/compression`            | Pengaturan kompresi global (termasuk konfigurasi `mcpAccessibility` ) |
| `/api/compression/preview`             | Pratinjau mode kompresi apa pun                                       |
| `/api/compression/language-packs`      | Daftar paket bahasa Caveman yang tersedia                             |
| `/api/context/caveman/config`          | Alias pengaturan manusia gua                                          |
| `/api/context/rtk/config`              | RTK default dan pengaturan                                            |
| `/api/context/rtk/filters`             | katalog filter RTK                                                    |
| `/api/context/rtk/test`                | titik akhir RTK preview/test                                          |
| `/api/context/rtk/raw-output/[id]`     | Pemulihan keluaran mentah yang diautentikasi dan disunting            |
| `/api/context/combos`                  | Kombo kompresi CRUD                                                   |
| `/api/context/combos/[id]/assignments` | Penugasan kombo perutean CRUD                                         |
| `/api/context/analytics`               | Alias analitik kompresi                                               |

Rute manajemen memerlukan autentikasi manajemen atau pemeriksaan kebijakan kunci API.

## alat MCP

Kompresi memperlihatkan lima alat MCP :

| Alat                                | Cakupan             | Tujuan                                |
| ----------------------------------- | ------------------- | ------------------------------------- |
| `omniroute_compression_status`      | `read:compression`  | Pengaturan, analitik, statistik cache |
| `omniroute_compression_configure`   | `write:compression` | Perbarui pengaturan global            |
| `omniroute_set_compression_engine`  | `write:compression` | Atur mode dan alur opsional           |
| `omniroute_list_compression_combos` | `read:compression`  | Daftar kombo kompresi                 |
| `omniroute_compression_combo_stats` | `read:compression`  | Baca analitik combo/engine            |

## Cakupan & pengecualian

**Embeddings tidak pernah dikompresi.** `open-sse/handlers/embeddings.ts` tidak pernah memanggil mesin kompresi apa pun — badan request/response meneruskan langsung ke pelaksana tanpa disentuh. Ini bersifat struktural saat ini (penyelesaian penyematan dan penyelesaian obrolan adalah penangan terpisah), bukan pemeriksaan waktu proses, namun ini berarti masalah distorsi vektor di #8034 tidak memiliki permukaan paparan di jalur penyematan.

**filter pengecualian Per-model/endpoint (#8034).** Untuk penyelesaian obrolan, operator dapat memberi nama id model / target `provider/model` yang tidak boleh dikompresi — pagar pembatas yang berguna jika kompresi dihubungkan lebih dekat ke jalur yang berdekatan dengan penyematan nanti, dan umumnya berguna untuk model apa pun yang prompt byte-untuk-byte yang tepat penting (eval deterministik, awalan sensitif cache, dll.).

- Bidang pengaturan: `exclusions?: string[]` pada konfigurasi kompresi global (`GET`/`PUT /api/settings/compression`), dipertahankan melalui namespace kompresi `key_value` yang ada (`src/lib/db/compression.ts`) — tidak ada tabel baru.
- Tab dasbor:** Pengecualian Dashboard → Kompresi →** (`/dashboard/compression/exclusions`).
- Sintaks pola: `*` adalah satu-satunya karakter pengganti. Setiap metakarakter regex lainnya dalam suatu pola di-escape sebelum dicocokkan, jadi `gpt-5.6` hanya cocok dengan string literal, tidak pernah `gpt-5x6` (aman untuk ReDoS, dibatasi, tidak ada bilangan bersarang). Pola mencocokkan huruf besar-kecil dengan id model kosong dan komposit `provider/model` — `gpt-5-6`, `openai/gpt-5-6`, dan `openai/*` semuanya berfungsi, dan `*` sendiri mengecualikan setiap model.
- Pencocokan: `isCompressionExcluded()` / `normalizeCompressionExclusions()` di `open-sse/services/compression/exclusions.ts`. `chatCore.ts` memeriksa target yang dikecualikan tepat setelah menyelesaikan pengaturan kompresi,** sebelum mesin apa pun hidup** , dan memperlakukan kecocokan persis seperti kompresi yang dinonaktifkan secara global — isi permintaan terbukti identik dengan byte. Lompatan tersebut dicatat melalui `writeCompressionSkip(..., "excluded")` untuk visibilitas analitik.
- Default ( daftar empty/absent ): identik dengan perilaku sebelum #8034 — tidak ada yang dikecualikan.

## Keterbatasan yang diketahui

- **LLMLingua-2 (SLM) memerlukan deps opsional yang berlokasi bersama.** Pekerja hanya berjalan di build produksi ketika rekan `@atjsh/llmlingua-2` + ditempatkan bersama di `dist/node_modules` (lihat `scripts/build/colocateOptionals.mjs`, #4286). Tanpa mereka, mesin akan gagal terbuka (mengembalikan teks asli). Resolusi pekerja tidak lagi bergantung pada `import.meta.url` (ia mati dalam bundel mandiri) — ia berlabuh pada runtime cwd / `argv[1]`.
- **Paket bahasa manusia gua `de` / `fr` / `ja` bersifat parsial.** Mereka mengirimkan aturan `context` + `filler` + `structural` tetapi tidak ada paket `dedup` / `ultra`, jadi intensitas `ultra` tidak lebih kuat dari `full` untuk bahasa-bahasa tersebut (mereka hanya menggunakan aturan mereka sendiri — tidak ada kemunduran diam-diam ke aturan `dedup`/`ultra` bahasa Inggris, yang akan memotong teks asing). `en` / `es` / `id` / `pt-BR` selesai. Kontribusi `dedup.json` + `ultra.json` untuk sebagian paket dipersilakan.
- **Telemetri bertumpuk hanya mencantumkan mesin yang dikompresi.** Langkah pipa bertumpuk yang mesinnya berjalan tetapi menghasilkan penghematan 0 % menghasilkan `stats:null` sehingga tidak muncul di `engineBreakdown` — dan tidak dapat dibedakan dari langkah yang dilewati. Membedakan "berjalan, 0%" dari "dilewati" memerlukan perubahan model perincian dan ditunda.

## Validasi

Gerbang fokus untuk area ini adalah:

```bash
node --import tsx/esm --test tests/unit/compression/rtk-*.test.ts tests/unit/compression/pipeline-integration.test.ts tests/unit/compression/context-compression-api.test.ts
node --import tsx/esm --test tests/unit/compression/*.test.ts tests/golden-set/*.test.ts tests/integration/compression-pipeline.test.ts tests/unit/api/compression/compression-api.test.ts
node --import tsx/esm --test tests/unit/compression/mcpAccessibility*.test.ts
npm run typecheck:core
```
