# 🌐 OmniRoute Proxy Guide (Oʻzbekcha)

🌐 **Languages:** 🇺🇸 [English](../../../../ops/PROXY_GUIDE.md) · 🇪🇹 [am](../../../am/docs/ops/PROXY_GUIDE.md) · 🇸🇦 [ar](../../../ar/docs/ops/PROXY_GUIDE.md) · 🇦🇿 [az](../../../az/docs/ops/PROXY_GUIDE.md) · 🇧🇬 [bg](../../../bg/docs/ops/PROXY_GUIDE.md) · 🇧🇩 [bn](../../../bn/docs/ops/PROXY_GUIDE.md) · 🇧🇦 [bs](../../../bs/docs/ops/PROXY_GUIDE.md) · 🇨🇿 [cs](../../../cs/docs/ops/PROXY_GUIDE.md) · 🇩🇰 [da](../../../da/docs/ops/PROXY_GUIDE.md) · 🇩🇪 [de](../../../de/docs/ops/PROXY_GUIDE.md) · 🇬🇷 [el](../../../el/docs/ops/PROXY_GUIDE.md) · 🇪🇸 [es](../../../es/docs/ops/PROXY_GUIDE.md) · 🇪🇪 [et](../../../et/docs/ops/PROXY_GUIDE.md) · 🇮🇷 [fa](../../../fa/docs/ops/PROXY_GUIDE.md) · 🇫🇮 [fi](../../../fi/docs/ops/PROXY_GUIDE.md) · 🇫🇷 [fr](../../../fr/docs/ops/PROXY_GUIDE.md) · 🇮🇪 [ga](../../../ga/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [gu](../../../gu/docs/ops/PROXY_GUIDE.md) · 🇳🇬 [ha](../../../ha/docs/ops/PROXY_GUIDE.md) · 🇮🇱 [he](../../../he/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [hi](../../../hi/docs/ops/PROXY_GUIDE.md) · 🇭🇷 [hr](../../../hr/docs/ops/PROXY_GUIDE.md) · 🇭🇺 [hu](../../../hu/docs/ops/PROXY_GUIDE.md) · 🇦🇲 [hy](../../../hy/docs/ops/PROXY_GUIDE.md) · 🇮🇩 [id](../../../id/docs/ops/PROXY_GUIDE.md) · 🇳🇬 [ig](../../../ig/docs/ops/PROXY_GUIDE.md) · 🇮🇹 [it](../../../it/docs/ops/PROXY_GUIDE.md) · 🇯🇵 [ja](../../../ja/docs/ops/PROXY_GUIDE.md) · 🇬🇪 [ka](../../../ka/docs/ops/PROXY_GUIDE.md) · 🇰🇭 [km](../../../km/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [kn](../../../kn/docs/ops/PROXY_GUIDE.md) · 🇰🇷 [ko](../../../ko/docs/ops/PROXY_GUIDE.md) · 🇱🇹 [lt](../../../lt/docs/ops/PROXY_GUIDE.md) · 🇱🇻 [lv](../../../lv/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [ml](../../../ml/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [mr](../../../mr/docs/ops/PROXY_GUIDE.md) · 🇲🇾 [ms](../../../ms/docs/ops/PROXY_GUIDE.md) · 🇲🇹 [mt](../../../mt/docs/ops/PROXY_GUIDE.md) · 🇲🇲 [my](../../../my/docs/ops/PROXY_GUIDE.md) · 🇳🇵 [ne](../../../ne/docs/ops/PROXY_GUIDE.md) · 🇳🇱 [nl](../../../nl/docs/ops/PROXY_GUIDE.md) · 🇳🇴 [no](../../../no/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [or](../../../or/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [pa](../../../pa/docs/ops/PROXY_GUIDE.md) · 🇵🇭 [phi](../../../phi/docs/ops/PROXY_GUIDE.md) · 🇵🇱 [pl](../../../pl/docs/ops/PROXY_GUIDE.md) · 🇵🇹 [pt](../../../pt/docs/ops/PROXY_GUIDE.md) · 🇧🇷 [pt-BR](../../../pt-BR/docs/ops/PROXY_GUIDE.md) · 🇷🇴 [ro](../../../ro/docs/ops/PROXY_GUIDE.md) · 🇷🇺 [ru](../../../ru/docs/ops/PROXY_GUIDE.md) · 🇱🇰 [si](../../../si/docs/ops/PROXY_GUIDE.md) · 🇸🇰 [sk](../../../sk/docs/ops/PROXY_GUIDE.md) · 🇸🇮 [sl](../../../sl/docs/ops/PROXY_GUIDE.md) · 🇷🇸 [sr](../../../sr/docs/ops/PROXY_GUIDE.md) · 🇸🇪 [sv](../../../sv/docs/ops/PROXY_GUIDE.md) · 🇰🇪 [sw](../../../sw/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [ta](../../../ta/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [te](../../../te/docs/ops/PROXY_GUIDE.md) · 🇹🇭 [th](../../../th/docs/ops/PROXY_GUIDE.md) · 🇹🇷 [tr](../../../tr/docs/ops/PROXY_GUIDE.md) · 🇺🇦 [uk-UA](../../../uk-UA/docs/ops/PROXY_GUIDE.md) · 🇵🇰 [ur](../../../ur/docs/ops/PROXY_GUIDE.md) · 🇻🇳 [vi](../../../vi/docs/ops/PROXY_GUIDE.md) · 🇳🇬 [yo](../../../yo/docs/ops/PROXY_GUIDE.md) · 🇨🇳 [zh-CN](../../../zh-CN/docs/ops/PROXY_GUIDE.md) · 🇹🇼 [zh-TW](../../../zh-TW/docs/ops/PROXY_GUIDE.md)

---

> **Geografik bloklarni chetlab o'ting, shaxsingizni himoya qiling va konfiguratsiya murakkabligi nol bo'lgan istalgan proksi — orqali AI trafigini yo'naltiring.**

OmniRoute HTTP, HTTPS yoki SOCKS5 proksi-serverlari orqali yuqori oqim AI provayder trafigini yo'naltirish imkonini beruvchi to'liq xususiyatli proksi boshqaruv tizimini o'z ichiga oladi. Bloklangan hududda bo'lasizmi, IP aylantirish kerakmi yoki yashirin barmoq izlarini olishni xohlaysizmi — bu qo'llanma hamma narsani qamrab oladi.

---

## Mundarija

- [Nima uchun proksi-serverlardan foydalanish kerak?](#why-use-proxies)
- [Arxitekturaga umumiy nuqtai](#architecture-overview)
- [4 darajali proksi tizimi](#4-level-proxy-system)
- [Proksi registr (CRUD)](#proxy-registry-crud)
- [1 proksi bepul bozor](#1proxy-free-proxy-marketplace)
- [Proksi-serverni aylantirish](#proxy-rotation)
- [Anti-aniqlash va yashirin](#anti-detection--stealth)
- [Yuqori oqim proksi rejimlari](#upstream-proxy-modes)
- [Boshqaruv paneli UI](#dashboard-ui)
- [API havolasi](#api-reference)
- [Atrof-muhit o'zgaruvchilari](#environment-variables)
- [Muammolarni bartaraf qilish; nosozliklarni TUZATISH](#troubleshooting)

---

## Nima uchun proksi-serverlardan foydalanish kerak?

Ko'pgina AI provayderlari geografik mintaqa bo'yicha kirishni cheklaydi. Dasturchilar ichida** Rossiya, Xitoy, Eron, Kuba, Turkiya** , va boshqa mamlakatlar quyidagi kabi xatolarga duch keladi:

```
unsupported_country_region_territory
```

Hatto bloklangan hududlardan tashqarida ham proksi-serverlar quyidagilar uchun foydalidir:

| Foydalanish holati    | Tavsif                                                                  |
| --------------------- | ----------------------------------------------------------------------- |
| **Geografik aylanma** | Bloklangan mamlakatlardan OpenAI, Anthropic, Codex, Copilot ga kirish   |
| **IP aylanish**       | Tarifni cheklamaslik uchun so'rovlarni bir nechta IPs bo'ylab tarqating |
| **Maxfiylik**         | Yuqori oqim provayderlaridan haqiqiy IP yashiring                       |
| **Muvofiqlik**        | Muayyan yurisdiktsiyalar bo'ylab transportni yo'naltirish               |
| **Sinov**             | Turli mintaqalardan kelgan so'rovlarni taqlid qiling                    |

---

## Arxitekturaga umumiy nuqtai

```
┌───────────────────────────────────────────────────────────────┐
│                       OmniRoute Server                        │
│                                                               │
│  ┌─────────────┐    ┌──────────────┐    ┌──────────────────┐  │
│  │ Proxy       │    │ Proxy        │    │ Proxy            │  │
│  │ Registry    │───▶│ Dispatcher   │───▶│ Fetch (undici)   │  │
│  │ (SQLite)    │    │ (cached)     │    │                  │  │
│  └─────────────┘    └──────────────┘    └────────┬─────────┘  │
│         ▲                                        │            │
│         │                                        ▼            │
│  ┌──────┴──────┐                        ┌──────────────────┐  │
│  │ 1proxy Sync │                        │ Upstream         │  │
│  │ (free pool) │                        │ Provider API     │  │
│  └─────────────┘                        └──────────────────┘  │
└───────────────────────────────────────────────────────────────┘
```

### Asosiy komponentlar

| Komponent                | Fayl                                         | Rol                                                                |
| ------------------------ | -------------------------------------------- | ------------------------------------------------------------------ |
| **Proksi registr**       | `src/lib/db/proxies.ts`                      | proksi-server yozuvlari uchun CRUD + qamrovini belgilash           |
| **Proksi-dispetcher**    | `open-sse/utils/proxyDispatcher.ts`          | Keshlash bilan `undici` ProxyAgent/SOCKS dispetcherlarini yaratadi |
| **Proksi olish**         | `open-sse/utils/proxyFetch.ts`               | Proksi-dispetcher in'ektsiyasi bilan `fetch()` o'rab oladi         |
| **Marshrut sozlamalari** | `src/app/api/settings/proxy/route.ts`        | Eski proksi-server konfiguratsiyasi API (GET/PUT/DELETE)           |
| **Boshqaruv yo'nalishi** | `src/app/api/v1/management/proxies/route.ts` | Ro'yxatga olish kitobi CRUD API (GET/POST/PATCH/DELETE)            |
| **1 proksi DB**          | `src/lib/db/oneproxy.ts`                     | Bepul proksi-server bozorining doimiyligi                          |

---

## Yangi hisoblar uchun standart proksi holati

In** Sozlamalar → Proksi → Global konfiguratsiyasi** , foydalaning** Yangi ulanishlar uchun proksi-serverni sukut bo'yicha yoqing** yangi qo'shilgan provayder hisoblarining dastlabki proksi-server holatini tanlash.

Yangi sozlama yangi qoʻshilgan provayder hisoblarining dastlabki proksi-server holatini boshqaradi. U mavjud hisoblarni o'zgartirmaydi yoki global proksi-serverni almashtirmaydi. Uning boshlang'ich qiymati oldingi xatti-harakatni saqlaydi. Sukut bo'yicha proksi-server o'chirilgan holda kelajakdagi hisoblarni yaratish uchun uni bir marta o'chirib qo'ying.

Afzallik mavjud Sozlamalar API orqali `defaultNewConnectionProxyEnabled` sifatida saqlanadi. Hech qachon saqlanmasa, u sukut bo'yicha `true` bo'ladi. `false` saqlash keyingi yangi hisoblar uchun qayta ishga tushirilmasdan kuchga kiradi. `POST /api/providers` ixtiyoriy qat'iy mantiqiy `proxyEnabled` qabul qiladi; aniq `true` yoki `false` yaratish standartidan ustun turadi. Takroriy hisob qaydnomasi yoki OAuth qayta ulanishi o'tkazib yuborilsa, bu hisobning saqlangan holati saqlanib qoladi. Shaxsiy hisoblar keyin ham faollashtirilishi yoki o'chirilishi mumkin.

Tanlangan provayder o'tkazmalari yangi hisoblar uchun maqsadli o'rnatishning standartidan foydalanadi va mavjud hisoblarni almashtirishda maqsad siyosatini saqlaydi. Proksi-serverlar portativ uzatish maydonlari emas. To'liq zaxira nusxasini tiklash va tarixiy JSON/SQL migratsiyasi mavjud tiklash semantikasini, jumladan saqlangan hisob qiymatlari va eski sxema standartlarini saqlab qoladi; to'liq sozlamalarni tiklash ham ushbu afzallikni tiklashi mumkin.

Bu afzallik proksi-serverni tayinlamaydi yoki uning sog'lom yoki ishlatilayotganligini tasdiqlamaydi. Haqiqiy marshrut hali ham global proksi-serverga va tegishli proksi-server konfiguratsiyasiga bog'liq. Doimiy hisobsiz sintetik provayderlar, hisob yaratishdan oldin OAuth trafiki, environment/system proksi-serverlari va tashqi backendlar tarmog'i uning doirasidan tashqarida.

## 4 darajali proksi tizimi

OmniRoute proksi-server konfiguratsiyasini qo'llab-quvvatlaydi** to'rtta mustaqil doiralar** , ustuvor tartibda hal qilindi:

```
Priority Resolution Order (highest → lowest):

  1. 🔵 Account/Connection Proxy  →  per API key / OAuth connection
  2. 🟡 Provider Proxy            →  per provider (e.g., all OpenAI traffic)
  3. 🟠 Combo Proxy               →  per combo/routing configuration
  4. 🟢 Global Proxy              →  all traffic, all providers
```

### Rezolyutsiya qanday ishlaydi

OmniRoute yuqori oqim provayderiga so'rov yuborganda, u har bir darajani tartibda tekshiradigan `resolveProxyForConnectionFromRegistry()` chaqiradi:

1. **Hisob darajasi** — Ushbu maxsus ulanish ID uchun tayinlangan proksi-server bormi?
2. **Provayder darajasida** — Ushbu provayderga tayinlangan proksi-server bormi (masalan, `openai`)?
3. **Global darajada** — sozlangan global proksi-server bormi?
4. **Proksi yo'q** — Provayderga to'g'ridan-to'g'ri ulanish.

Birinchi o'yin g'alaba qozonadi. Bu shuni anglatadiki, siz global proksi-serverni zaxira sifatida o'rnatishingiz mumkin, lekin uni muayyan provayderlar yoki ulanishlar uchun bekor qilishingiz mumkin.

### Proksilangan narsa

| Trafik turi             | Proksilanganmi? | Eslatmalar                                                     |
| ----------------------- | --------------- | -------------------------------------------------------------- |
| Chat yakunlari          | ✅              | Barcha `/v1/chat/completions` so'rovlari                       |
| O'rnatishlar            | ✅              | `/v1/embeddings`                                               |
| Tasvir yaratish         | ✅              | `/v1/images/generations`                                       |
| Audio (TTS/STT)         | ✅              | `/v1/audio/*`                                                  |
| OAuth token almashinuvi | ✅              | `unsupported_country_region_territory` hal qiladi              |
| Ulanish sinovlari       | ✅              | "Ulanishni sinab ko'rish" tugmasi proksi-serverdan foydalanadi |
| Token yangilanishi      | ✅              | Fon OAuth yangilash                                            |
| Modelni sinxronlash     | ✅              | Model ro'yxati va kashfiyot                                    |

---

## Proksi registr (CRUD)

Proksi-server registri barcha proksi-serverlaringizni saqlaydigan SQLite jadvali (`proxy_registry`). Har bir proksi-server quyidagilarga ega:

| Maydon     | Turi      | Tavsif                                            |
| ---------- | --------- | ------------------------------------------------- |
| `id`       | UUID      | Noyob identifikator                               |
| `name`     | String    | Odam o'qiy oladigan yorliq                        |
| `type`     | String    | Protokol: `http`, `https`, `socks5`               |
| `host`     | String    | Proksi-server nomi yoki IP                        |
| `port`     | Butun son | Port raqami                                       |
| `username` | String    | Auth foydalanuvchi nomi (dam olishda shifrlangan) |
| `password` | String    | Auth paroli (dam olishda shifrlangan)             |
| `region`   | String    | Geografik mintaqa yorlig'i                        |
| `notes`    | String    | Erkin matnli eslatmalar                           |
| `status`   | String    | `active` yoki `inactive`                          |
| `source`   | String    | `manual` yoki `oneproxy`                          |

### Proksi yaratish

**Boshqaruv paneli orqali:**

1. ga boring** Proksi → sozlamalari**
2. bosing** Proksi qo'shing**
3. Tur, xost, port va ixtiyoriy autentifikatsiya ma'lumotlarini to'ldiring
4. Saqlash

**API orqali:**

```bash
curl -X POST http://localhost:20128/api/v1/management/proxies \
  -H "Content-Type: application/json" \
  -d '{
    "name": "US Proxy",
    "type": "http",
    "host": "proxy.example.com",
    "port": 8080,
    "username": "user",
    "password": "pass",
    "region": "US"
  }'
```

### Proksi-server yangilanmoqda

```bash
curl -X PATCH http://localhost:20128/api/v1/management/proxies \
  -H "Content-Type: application/json" \
  -d '{
    "id": "proxy-uuid-here",
    "host": "new-proxy.example.com",
    "port": 9090
  }'
```

> **Eslatma:** Agar siz bo'sh bo'lmagan almashtirishlarni aniq yubormasangiz, hisobga olish ma'lumotlari saqlanib qoladi. `username`/`password` uchun bo'sh satrlarni yuborish saqlangan qiymatlarni saqlab qoladi.

### Proksi-serverni o'chirish

```bash
# Fails if proxy is assigned to any scope
curl -X DELETE "http://localhost:20128/api/v1/management/proxies?id=proxy-uuid"

# Force delete (removes assignments too)
curl -X DELETE "http://localhost:20128/api/v1/management/proxies?id=proxy-uuid&force=1"
```

### Proksi-serverlarni ro'yxatga olish

```bash
curl "http://localhost:20128/api/v1/management/proxies?limit=50&offset=0"
```

### Scopelarga proksi-serverlarni tayinlash

```bash
# Assign to global scope
curl -X PUT http://localhost:20128/api/settings/proxy \
  -H "Content-Type: application/json" \
  -d '{"level": "global", "proxy": {"type":"http","host":"proxy.example.com","port":8080}}'

# Assign to a specific provider
curl -X PUT http://localhost:20128/api/settings/proxy \
  -H "Content-Type: application/json" \
  -d '{"level": "provider", "id": "openai", "proxy": {"type":"socks5","host":"socks.example.com","port":1080}}'

# Assign to a specific connection/key
curl -X PUT http://localhost:20128/api/settings/proxy \
  -H "Content-Type: application/json" \
  -d '{"level": "key", "id": "connection-uuid", "proxy": {"type":"http","host":"key-proxy.com","port":3128}}'
```

### Samarali proksi-serverni hal qilish

Berilgan ulanish uchun qaysi proksi-server ishlatilishini tekshiring:

```bash
curl "http://localhost:20128/api/settings/proxy?resolve=connection-uuid"
```

Yechilgan proksi-serverni darajasi (`account`, `provider` yoki `global`) va manbasi bilan qaytaradi.

### Ommaviy topshiriq

Bir vaqtning o'zida bir nechta provayderlar yoki ulanishlarga bitta proksi-server tayinlang:

```bash
curl -X POST http://localhost:20128/api/v1/management/proxies/bulk-assign \
  -H "Content-Type: application/json" \
  -d '{
    "scope": "provider",
    "scopeIds": ["openai", "anthropic", "codex"],
    "proxyId": "proxy-uuid"
  }'
```

### Import/Export

Proksi-serverlar tarkibiga kiritilgan**Backup/Restore** tizimi. OmniRoute konfiguratsiyasini eksport qilganingizda:

1. ga boring** Boshqaruv paneli → sozlamalari → Zaxiralash**
2. bosing** Eksport** — proksi registrlari va topshiriqlari kiritilgan
3. Qayta tiklash uchun bosing** Import** va zaxira faylni yuklang

Proksi registr ham qo'llab-quvvatlaydi** xost + porti orqali yuklang** — agar siz allaqachon mavjud bo'lgan proksi-serverni import qilsangiz (bir xil xost va port), u dublikat yaratish o'rniga yangilanadi.

### Eski migratsiya

Agar proksi-serverlarni eski versiyada (oldindan ro'yxatga olish) sozlagan bo'lsangiz, OmniRoute ularni avtomatik ravishda ko'chiradi:

```
Legacy key_value store → proxy_registry + proxy_assignments
```

Bu yangilanishdan keyin birinchi ishga tushirilganda bir marta sodir bo'ladi. Qayta ishga tushirish uchun `migrateLegacyProxyConfigToRegistry({ force: true })` foydalaning.

---

## 1 proksi bepul proksi bozori

> 🆕** [@oyi77](https://github.com/oyi77) hissa qo'shgan** — PR [#1847](https://github.com/diegosouzapw/OmniRoute/pull/1847) (ZQe [#1788](https://github.com/diegosouzapw/OmniRoute/issues/1788) )

OmniRoute bilan birlashadi** [1 proksi](https://1proxy-api.aitradepulse.com)** kirishni ta'minlash uchun jamoat platformasi** yuzlab bepul, tasdiqlangan proksi-serverlar** butun dunyodan. Bu proksi-server infratuzilmasiga ega bo'lmagan foydalanuvchilar uchun juda mos keladi.

### U qanday ishlaydi

```
┌─────────────┐     Sync      ┌─────────────────┐    Rotate     ┌──────────┐
│  1proxy API │ ────────────▶ │  proxy_registry  │ ────────────▶ │ Provider │
│  (external) │   up to 500   │  source=oneproxy │  by quality   │   API    │
└─────────────┘    proxies    └─────────────────┘               └──────────┘
```

1. **Sinxronlash** — OmniRoute 1proxy API dan tasdiqlangan proksi-serverlarni oladi
2. **Do'kon** — Proksi-serverlar `source = 'oneproxy'` bilan bir xil `proxy_registry` jadvalida saqlanadi
3. **Filtr** — Protokol, mamlakat, sifat ko‘rsatkichi bo‘yicha filtrlash
4. **Aylantirish** — Sifatli, tasodifiy yoki ketma-ket strategiyalardan foydalangan holda eng yaxshi proksi-serverni tanlang
5. **Avtomatik pasaytirish** — Muvaffaqiyatsiz proksi-serverlar sifat ko'rsatkichlarini pasaytiradi; → chegarasidan pastda faol emas deb belgilangan

### Proksi-serverlarni sinxronlash

**Boshqaruv paneli orqali:**

1. ga boring** Sozlamalar → 1proxy** tab
2. bosing** "Endi sinxronlash"**
3. Statistikani koʻrish: jami proksi-serverlar, faollar soni, oʻrtacha sifat, mamlakatlar boʻyicha taqsimot

**API orqali:**

```bash
# Trigger sync
curl -X POST http://localhost:20128/api/settings/oneproxy \
  -H "Content-Type: application/json" \
  -d '{}'

# Response:
# { "success": true, "added": 127, "updated": 45, "failed": 2, "total": 172 }
```

### Proksi-serverlarni filtrlash

```bash
# Filter by protocol
curl "http://localhost:20128/api/settings/oneproxy?protocol=socks5"

# Filter by country
curl "http://localhost:20128/api/settings/oneproxy?countryCode=US"

# Filter by minimum quality score
curl "http://localhost:20128/api/settings/oneproxy?minQuality=80"

# Combine filters
curl "http://localhost:20128/api/settings/oneproxy?protocol=http&countryCode=DE&minQuality=70"
```

### Proksi sifati ballari

Har bir proksi-server metadata bilan birga keladi:

| Maydon          | Tavsif                                                     |
| --------------- | ---------------------------------------------------------- |
| `qualityScore`  | 1 proksi tekshiruvidan 0-100 reyting                       |
| `latencyMs`     | O'lchangan tarmoq kechikishi                               |
| `anonymity`     | `transparent`, `anonymous` yoki `elite`                    |
| `googleAccess`  | Proksi-server Google xizmatlariga kira oladimi yoki yo'qmi |
| `countryCode`   | Ikki harfli ISO mamlakat kodi                              |
| `lastValidated` | Oxirgi tasdiqlash vaqt belgisi                             |

Sifat ko'rsatkichlari dinamik ravishda o'rnatiladi:

- **Muvaffaqiyatsiz so'rovlar** ballni 10 ballga qisqartirish
- **Bal ≤ 10 ga tushadi** → proksi `inactive` bilan belgilangan
- Nofaol proksi-serverlar aylanishdan chiqarib tashlanadi

### Rotatsiya strategiyalari

```bash
# Rotate by quality (best proxy first) — default
curl -X POST http://localhost:20128/api/settings/oneproxy/rotate \
  -H "Content-Type: application/json" \
  -d '{"strategy": "quality"}'

# Random rotation
curl -X POST http://localhost:20128/api/settings/oneproxy/rotate \
  -d '{"strategy": "random"}'

# Sequential (least recently validated first)
curl -X POST http://localhost:20128/api/settings/oneproxy/rotate \
  -d '{"strategy": "sequential"}'
```

### O'chirish to'xtatuvchisi

1proksi sinxronlashda o'rnatilgan o'chirgich mavjud:

- Keyin** 5 ta ketma-ket sinxronlash xatosi** , keyingi sinxronlash urinishlari bloklanadi
- Qayta tiklash: `resetOneproxyCircuitBreaker()` yoki serverni qayta ishga tushiring
- Sinxronizatsiya holati `GET /api/settings/oneproxy?action=status` da mavjud

### 1 proksi-serverni tozalash

```bash
# Delete a single 1proxy proxy
curl -X DELETE "http://localhost:20128/api/settings/oneproxy?id=proxy-uuid"

# Clear ALL 1proxy proxies (manual proxies are untouched)
curl -X DELETE "http://localhost:20128/api/settings/oneproxy?clearAll=1"
```

---

## Anti-aniqlash va yashirin

OmniRoute nafaqat proksi-server — orqali trafikni yo'naltiradi, balki trafikni qonuniy ko'rinishga olib keladi:

### TLS Barmoq izi spoofing

Brauzerga o'xshash TLS barmoq izlarini yaratish uchun `wreq-js` foydalanadi, bunda brauzerdan tashqari TLS qo'l siqishlarini belgilovchi botlarni aniqlash tizimlarini chetlab o'tadi.

### CLI Barmoq izini moslashtirish

The**CLI Barmoq izini almashtirish** (`Settings → Security`) HTTP sarlavhalari va JSON tana maydonlarini mahalliy CLI ikkilik fayllarining (Claude Code, Codex va boshqalar) aniq imzosiga mos kelishi uchun qayta tartiblaydi. Bu ishlaydi** tepasida** proksi:

```
Your IP (blocked) → Proxy IP (US) → Provider API
                    + TLS spoof
                    + CLI fingerprint
```

Ikkalasini ham olasiz**IP maskalash** va** haqiqiylikni talab qilish** bir vaqtning o'zida.

### Proksi IP saqlanishi

Boshqaruv panelidagi rangli kodli nishonlar qaysi proksi darajasi faol ekanligini ko‘rsatadi:

| Belgi | Daraja    | Ma'nosi                                                  |
| ----- | --------- | -------------------------------------------------------- |
| 🟢    | Global    | Barcha trafik ushbu proksi-server orqali o'tadi          |
| 🟡    | Provayder | Faqatgina ushbu provayderning trafigi proksilangan       |
| 🔵    | Ulanish   | Bu maxsus key/account ushbu proksi-serverdan foydalanadi |

Belgida tekshirish uchun hal qilingan proksi IP ham ko‘rsatilgan.

---

## Yuqori oqim proksi rejimlari

CLIProxyAPI namunasidan foydalanadigan provayderlar uchun OmniRoute uchta yuqori proksi-server rejimini qo'llab-quvvatlaydi:

| Rejim         | Tavsif                                                    |
| ------------- | --------------------------------------------------------- |
| `native`      | OmniRoute proksi-routingni bevosita boshqaradi (standart) |
| `cliproxyapi` | Tashqi CLIProxyAPI instansiyasiga delegatlar              |
| `fallback`    | Avval mahalliy tilda harakat qiladi, CLIProxyAPI qaytadi  |

Har bir provayderni sozlang:

```bash
curl -X PUT "http://localhost:20128/api/upstream-proxy/openai" \
  -H "Content-Type: application/json" \
  -d '{"mode": "native", "enabled": true}'
```

---

## Boshqaruv paneli UI

### Sozlamalar → Proksi-tab

- **Global proksi** konfiguratsiya (barcha trafik uchun bir marta o'rnatiladi)
- **Har bir provayder proksi** bekor qiladi
- **Har bir ulanish uchun proksi-server** topshiriqlar
- **Ulanish testi** sozlangan proksi orqali
- **Rangli nishonlar** faol proksi darajasini ko'rsatadi

### Sozlamalar → 1proxy Tab

- **Hozir sinxronlash** bepul proksi-serverlarni olish uchun tugma
- **Statistika kartalari** : Jami, Faol, Oʻrtacha sifat, Oxirgi sinxronlash
- **Filtrlar** : Protokol, Mamlakat kodi, Min Sifat
- **Proksi jadvali** xost, protokol, mamlakat, sifat ball, kechikish, anonimlik, Google kirish bilan
- **Sinxronlash holati** success/failure kuzatuvi va ketma-ket nosozliklar soni bilan panel
- **Hammasini tozalash** barcha 1 proksi yozuvlarini olib tashlash uchun

---

## API havolasi

### Proksi sozlamalari API

| Usul     | Yakuniy nuqta                                  | Tavsif                                        |
| -------- | ---------------------------------------------- | --------------------------------------------- |
| `GET`    | `/api/settings/proxy`                          | Toʻliq proksi-server konfiguratsiyasini oling |
| `GET`    | `/api/settings/proxy?level=global`             | Global proksi-serverni oling                  |
| `GET`    | `/api/settings/proxy?level=provider&id=openai` | Proksi-serverni oling                         |
| `GET`    | `/api/settings/proxy?resolve=connectionId`     | Samarali proksi-serverni hal qiling           |
| `PUT`    | `/api/settings/proxy`                          | Proksi-server konfiguratsiyasini yangilang    |
| `DELETE` | `/api/settings/proxy?level=provider&id=openai` | Proksini darajasida olib tashlang             |

### Proksi registr API

| Usul     | Yakuniy nuqta                                     | Tavsif                                |
| -------- | ------------------------------------------------- | ------------------------------------- |
| `GET`    | `/api/v1/management/proxies`                      | Barcha proksi-serverlarni ro'yxatlang |
| `GET`    | `/api/v1/management/proxies?id=uuid`              | ID orqali proksi-server oling         |
| `GET`    | `/api/v1/management/proxies?id=uuid&where_used=1` | Proksi-server topshiriqlarini oling   |
| `POST`   | `/api/v1/management/proxies`                      | Proksi yarating                       |
| `PATCH`  | `/api/v1/management/proxies`                      | Proksi-serverni yangilang             |
| `DELETE` | `/api/v1/management/proxies?id=uuid`              | Proksi-serverni o'chirish             |
| `DELETE` | `/api/v1/management/proxies?id=uuid&force=1`      | Majburiy o'chirish                    |
| `POST`   | `/api/v1/management/proxies/bulk-assign`          | Ommaviy tayinlash                     |
| `GET`    | `/api/v1/management/proxies/assignments`          | Topshiriqlar ro'yxati                 |
| `GET`    | `/api/v1/management/proxies/health`               | Proksi salomatligi statistikasi       |

### Tunnellar API

Proksi-server orqali chiqishni yo'naltirish o'rniga OmniRoute namunangizni umumiy internetga (Cloudflare/ngrok/Tailscale) chiqarish uchun [TUNNELS_GUIDE.md](./TUNNELS_GUIDE.md) ga qarang. Tunnel REST API `/api/tunnels/{cloudflared,ngrok,tailscale}/*` ostida yashaydi va yuqorida hujjatlashtirilgan chiquvchi proksi-server zanjiriga ortogonaldir.

### 1 proksi API

| Usul     | Yakuniy nuqta                          | Tavsif                               |
| -------- | -------------------------------------- | ------------------------------------ |
| `GET`    | `/api/settings/oneproxy`               | 1 proksi-server ro'yxati             |
| `GET`    | `/api/settings/oneproxy?action=stats`  | Stats + sinxronlash holatini oling   |
| `GET`    | `/api/settings/oneproxy?action=status` | Faqat sinxronizatsiya holatini oling |
| `POST`   | `/api/settings/oneproxy`               | Sinxronizatsiyani ishga tushirish    |
| `POST`   | `/api/settings/oneproxy/rotate`        | Keyingi proksi-serverga aylantiring  |
| `DELETE` | `/api/settings/oneproxy?id=uuid`       | Birini o'chirish                     |
| `DELETE` | `/api/settings/oneproxy?clearAll=1`    | Hammasini tozalang                   |

### Yuqori proksi API

| Usul     | Yakuniy nuqta                     | Tavsif                                              |
| -------- | --------------------------------- | --------------------------------------------------- |
| `GET`    | `/api/upstream-proxy/:providerId` | Yuqori oqim proksi konfiguratsiyasini oling         |
| `PUT`    | `/api/upstream-proxy/:providerId` | Yuqori oqim proksi rejimini o'rnating               |
| `DELETE` | `/api/upstream-proxy/:providerId` | Yuqori oqim proksi konfiguratsiyasini olib tashlang |

---

## Atrof-muhit o'zgaruvchilari

| Oʻzgaruvchan          | Standart | Tavsif                                                                |
| --------------------- | -------- | --------------------------------------------------------------------- |
| `ENABLE_SOCKS5_PROXY` | `true`   | SOCKS5 proksi-serverini yoqish ( `.env.example` da birlamchi `true` ) |

---

## Muammolarni bartaraf qilish; nosozliklarni TUZATISH

### "SOCKS5 proksi-server o'chirilgan"

`.env` faylingizga `ENABLE_SOCKS5_PROXY=true` o'rnating va qayta ishga tushiring.

### proksi-server orqali "soketni o'chirish" xatolari

Bo'sh ulanishlarni to'xtatadigan arzon proksi-serverlar bilan bu odatiy holdir. OmniRoute buni allaqachon boshqaradi:

- Proksi-ulanishlarda saqlashni o'chirish (`keepAliveTimeout: 1`)
- Quvurni o'chirish (`pipelining: 0`)
- Takroriy qo'l siqishlarini oldini olish uchun dispetcherlarni keshlash

Agar bu davom etsa, boshqa proksi-serverni sinab ko'ring yoki 1proksi aylantirish xususiyatidan foydalaning.

### OAuth vaqtida "qo'llab-quvvatlanmaydigan_mamlakat_mintaqa_territory"

Proksi-server sozlanganligiga ishonch hosil qiling** oldin** OAuth oqimini boshlash. OmniRoute konfiguratsiya qilingan proksi-server orqali OAuth token almashinuvini yo'naltiradi. Avval global yoki provayder darajasidagi proksi-serverni o'rnating, keyin ulaning.

### Proksi ishlatilmayapti

Rezolyutsiya tartibini tekshiring:

1. `GET /api/settings/proxy?resolve=your-connection-id` bilan tasdiqlang
2. Proksi `status` `active` ekanligini tekshiring ( `inactive` emas)
3. Proksi tayinlash doirasi ulanishingizga mos kelishiga ishonch hosil qiling

### 1 proksi sinxronlash muvaffaqiyatsiz tugadi

Sinxronizatsiya holatini tekshiring:

```bash
curl "http://localhost:20128/api/settings/oneproxy?action=status"
```

Agar `consecutiveFailures >= 5` bo'lsa, o'chirgich o'chirilgan. Qayta tiklash uchun serverni qayta ishga tushiring yoki qo'lda tiklashni kuting.

---

## Ma'lumotlar bazasi sxemasi

### `proxy_registry` jadvali

```sql
CREATE TABLE proxy_registry (
  id TEXT PRIMARY KEY,
  name TEXT NOT NULL,
  type TEXT NOT NULL DEFAULT 'http',
  host TEXT NOT NULL,
  port INTEGER NOT NULL,
  username TEXT DEFAULT '',
  password TEXT DEFAULT '',
  region TEXT,
  notes TEXT,
  status TEXT DEFAULT 'active',
  source TEXT NOT NULL DEFAULT 'manual',    -- 'manual' or 'oneproxy'
  quality_score INTEGER,                     -- 0-100 (1proxy only)
  latency_ms INTEGER,                        -- milliseconds (1proxy only)
  anonymity TEXT,                            -- transparent/anonymous/elite
  google_access INTEGER DEFAULT 0,           -- can access Google? (1proxy)
  last_validated TEXT,                       -- ISO timestamp (1proxy)
  country_code TEXT,                         -- ISO 2-letter code (1proxy)
  created_at TEXT NOT NULL,
  updated_at TEXT NOT NULL
);
```

### `proxy_assignments` jadvali

```sql
CREATE TABLE proxy_assignments (
  id INTEGER PRIMARY KEY AUTOINCREMENT,
  proxy_id TEXT NOT NULL REFERENCES proxy_registry(id),
  scope TEXT NOT NULL,        -- 'global', 'provider', 'account', 'combo'
  scope_id TEXT,              -- provider ID, connection ID, or combo ID
  created_at TEXT NOT NULL,
  updated_at TEXT NOT NULL,
  UNIQUE(scope, scope_id)
);
```

---

## Proksi salomatligini tekshirish (v3.8.16 +)

OmniRoute ning** proksi tez ishlamay qolishi** mexanizmi (`src/lib/proxyHealth.ts`) tezkor TCP ulanish tekshiruvi orqali < 2s da o'lik proksi-serverlarni aniqlaydi, keyin** natijani keshlaydi** har bir so'rov uchun qo'shimcha xarajatlardan qochish uchun.

### U qanday ishlaydi

```
Request ──▶ ProxyHealthCache.get(url)
             │
             ├─ Cache hit + fresh?  ──▶ return cached status
             │
             └─ Cache miss / stale?  ──▶ TCP connect to host:port
                                          (timeout: FAST_FAIL_TIMEOUT_MS)
                                          ──▶ cache for HEALTH_CACHE_TTL_MS
                                          ──▶ return result
```

Busiz, o'lik proksi to'liq `PROXY_TIMEOUT_MS` (standart 30s) uchun har bir so'rovni muvaffaqiyatsiz tugashidan oldin bloklaydi.

### Sozlanishi mumkin bo'lgan muhit o'zgaruvchilari

| Oʻzgaruvchan                 | Standart | Maqsad                                               |
| ---------------------------- | -------- | ---------------------------------------------------- |
| `PROXY_FAST_FAIL_TIMEOUT_MS` | `2000`   | sog'liqni tekshirish uchun TCP ulanish vaqti tugashi |
| `PROXY_HEALTH_CACHE_TTL_MS`  | `30000`  | Salomatlik natijasi qancha vaqt keshda saqlanadi     |

**Tavsiya etilgan qiymatlar:**

| Ssenariy                           | Tez ishlamay qolgan vaqt tugashi | Kesh TTL | Mulohaza yuritish                                                                     |
| ---------------------------------- | -------------------------------- | -------- | ------------------------------------------------------------------------------------- |
| Yuqori o'tkazuvchanlik API shlyuzi | 1500 ms                          | 60000ms  | Tekshiruvlarni kamaytirish uchun agressiv muvaffaqiyatsizlik, uzoqroq kesh            |
| Geo-tarqatilgan tugunlar           | 3000ms                           | 15000ms  | Sekinroq tarmoqlar ko'proq vaqt talab qiladi; tez uzilish uchun qisqaroq kesh         |
| Dev / sinov                        | 1000ms                           | 10000ms  | Mahalliy proksi-serverlarda tez takrorlash                                            |
| Yashirinlik / aniqlashga qarshi    | 2500 ms                          | 45000ms  | Tezlik chegaralarini keltirib chiqarishi mumkin bo'lgan tezkor tekshiruvdan saqlaning |

### Proksi salomatligini tekshirish

```ts
import { getAllProxyHealthStatuses, invalidateProxyHealth } from "omniroute/proxyHealth";

const statuses = getAllProxyHealthStatuses();
for (const s of statuses) {
  console.log(`${s.proxyUrl} → healthy=${s.healthy}, stale=${s.stale}`);
}

// Force re-check a specific proxy
invalidateProxyHealth("http://user:pass@203.0.113.7:8080");
```

Kesh yozuvi `HEALTH_CACHE_TTL_MS` dan oshib ketganda `stale` bayrog'i `true` bo'ladi va keyingi so'rov yangi tekshirishni boshlaydi.

### Har bir proksi turi standart sozlamalari

Salomatlik tekshiruvi URL sxemasiga asoslangan oqilona standartlardan foydalanadi:

| Sxema                      | Standart port |
| -------------------------- | ------------- |
| `http://`                  | 8080          |
| `https://`                 | 443           |
| `socks5://` / `socks5h://` | 1080          |

URL (`http://host:9999`) dagi maxsus portlar har doim standart sxemadan ustun turadi.

---

## Proksi tahlili va kuzatuvchanlik

OmniRoute har bir proksi-serverdan foydalanishni kuzatadi, bu operatorlarga marshrutlash naqshlari, kechikishlar va takroriy nosozliklarni tashxislashda yordam beradi.

### Nima kuzatilgan

Konfiguratsiya qilingan proksi-server orqali har bir so'rov uchun OmniRoute qayd qiladi:

| Metrik       | Tavsif                                                            |
| ------------ | ----------------------------------------------------------------- |
| `proxy_url`  | Toʻliq proksi-server URL (autlik maʼlumotlari niqoblangan)        |
| `provider`   | Yuqori oqim provayderi ID (ochiq, antropik va boshqalar)          |
| `latency_ms` | Proksi-server bilan qoʻl siqish, shu jumladan, umumiy safar vaqti |
| `connect_ms` | faqat TCP ulanish vaqti                                           |
| `status`     | yuqori oqimdan HTTP holat kodi                                    |
| `error`      | Agar so'rov bajarilmasa, xato klassi                              |
| `timestamp`  | ISO 8601 UTC                                                      |

### Ma'lumotlarga kirish

```bash
# Recent proxy events
curl -H "Authorization: Bearer $OMNIROUTE_KEY" \
  "http://localhost:20128/api/usage/proxy-logs?limit=100"
```

Haqiqiy yakuniy nuqta `/api/usage/proxy-logs` (qarang: `src/app/api/usage/proxy-logs/route.ts`). Ushbu oxirgi nuqta qo'llab-quvvatlaydi:

- `GET /api/usage/proxy-logs` — proksi jurnallarini olish
- `DELETE /api/usage/proxy-logs` — barcha proksi jurnallarini tozalang

Agar kerak bo'lsa, jami statistikani to'g'ridan-to'g'ri `proxy_logs` jadvalidan SQL orqali so'rash mumkin. Boshqaruv paneli UI umumiy ko'rinishlarni taklif qilishi mumkin.

### Umumiy naqshlar

**Proksi-serverni sindirish** ( success/failure o'rtasida almashinadi):

```sql
SELECT proxy_url,
       COUNT(*) AS total,
       SUM(CASE WHEN status >= 500 THEN 1 ELSE 0 END) AS errors,
       ROUND(100.0 * SUM(CASE WHEN status >= 500 THEN 1 ELSE 0 END) / COUNT(*), 1) AS error_pct
FROM proxy_logs
WHERE timestamp > datetime('now', '-1 hour')
GROUP BY proxy_url
HAVING error_pct > 5
ORDER BY error_pct DESC;
```

**Sekin proksi-serverlarni toping** (p95 kechikish > 2s):

```sql
WITH ranked AS (
  SELECT proxy_url, latency_ms,
         PERCENT_RANK() OVER (PARTITION BY proxy_url ORDER BY latency_ms) AS pct
  FROM proxy_logs
  WHERE timestamp > datetime('now', '-24 hour')
)
SELECT proxy_url, latency_ms
FROM ranked
WHERE pct >= 0.95
ORDER BY latency_ms DESC;
```

---

## Aylanish strategiyasi qaror daraxti

Bir nechta proksi-serverlar qamrovga tayinlanganda, OmniRoute a dan foydalanadi** aylanish strategiyasi** har bir so'rov uchun qaysi birini ishlatishni tanlash. Strategiya qamrov darajasida sozlangan (global, har bir provayder, har bir hisob, har bir kombinatsiya).

### Mavjud strategiyalar

| Strategiya           | Qachon foydalanish kerak                                | Sotib yuborish                                                                       |
| -------------------- | ------------------------------------------------------- | ------------------------------------------------------------------------------------ |
| `quality` (standart) | Aralash sifatli proksi-serverlar bilan ishlab chiqarish | Yuqori reytingli proksi-serverlarni afzal ko'radi; past baholilar och qolishi mumkin |
| `random`             | Yuk taqsimoti, maxfiylik                                | Bir tekis taqsimlash; sifat signallarini e'tiborsiz qoldiradi                        |
| `sequential`         | Nosozliklarni tuzatish, deterministik test              | Tartibda proksi-serverlar orqali aylanish; mulohaza yuritish oson                    |

### Qaror daraxti

```
                    Do you have quality scores for your proxies?
                    │
        ┌───────────┴───────────┐
        │                       │
       YES                     NO
        │                       │
   Are all proxies             │
   roughly equal                  │
   in quality?                   │
        │                       │
   ┌────┴────┐                  │
   │         │                  │
  YES       NO                Use
   │         │              `random`
   │         │              (even spread
   │         │              builds quality
   │         │              data over time)
   │         │
   │    Use `quality`
   │    (best for
   │    mixed quality)
   │
Use `random`
(spread load
evenly)
```

## O'z proksi-serverlaringiz uchun avtomatik nosozlikni istisno qilish

1proksi-server bozori allaqachon o'z-o'zidan muvaffaqiyatsiz proksi-serverlarni avtomatik ravishda pasaytiradi (qarang. [Proksi sifati ballari](#proxy-quality-scores) ). Proksi uchun** siz** ro'yxatga olish kitobiga qo'shilgan fon salomatligini rejalashtiruvchisi (`src/lib/proxyHealth/scheduler.ts`) hech narsani o'chirmasdan, xuddi shunday "o'lik a'zoni zanjirdan avtomatik ravishda chiqarib tashlash" xatti-harakatini ta'minlaydi:

```bash
# .env — soft-disable a proxy after 3 consecutive failed probes, re-enable it
# automatically once it starts answering probes again.
PROXY_AUTO_DISABLE=true
PROXY_AUTO_REMOVE_AFTER=3
```

Ko'p proksi zanjiriga qanday mos keladi:

1. Rejalashtiruvchi har bir ro'yxatdan o'tgan proksi-serverni har `PROXY_HEALTH_INTERVAL_MS` tekshiradi (standart 10 daqiqa; kamida 1 daqiqa).
2. `PROXY_AUTO_REMOVE_AFTER` dan keyin ketma-ket** yakuniy** nosozliklar (haqiqiy ulanish nosozligi — vaqt tugashi yoki probning o'z 5xx qiymati hech qachon hisobga olinmaydi, [Proksi salomatligini tekshirishga](#proxy-health-checking-v3816) qarang), proksi-serverning `status` `dead` ga o'rnatiladi.
3. `dead` pool/rotation rezolyutsiyasi tomonidan foydalaniladigan jonli holat filtri istisno qiladigan holatlardan biridir, shuning uchun ko‘lamning aylanishi (aylanma rejimda / tasodifiy / yopishqoq / kechikish — ga qarang. [Aylanish strategiyasi qaror daraxti](#rotation-strategy-decision-tree) ) bu proksi-serverni yangi so‘rovlarga topshirishni darhol to‘xtatadi. Hovuzdagi boshqa proksi-serverlar ta'sir qilmaydi va butun hovuz hech — jimgina [to'g'ridan](#4-level-proxy-system) -to'g'ri ulanishga qaytmaydi.
4. Rejalashtiruvchi `dead` proksi-serverlarini bir xil intervalda tekshirishda davom etadi. Keyingi muvaffaqiyatli zond `status` `active` -ga qaytaradi va u — aylanish jarayoniga qayta kiradi, qo'lda qayta qo'shish talab qilinmaydi.

Bu ataylab qilingan** qo'shilish va buzilmaydigan** : sukut bo'yicha rejalashtiruvchi faqat xatoliklarni hisoblaydi va qayd qiladi ( `decision.ts` dagi C siyosatiga qarang) va `PROXY_AUTO_DISABLE` hech qachon alohida, tajovuzkor `PROXY_AUTO_REMOVE` bayrog'i uchun mo'ljallangan — qatorini o'chirmaydi. Agar ikkalasi ham `true` ga o'rnatilgan bo'lsa, `PROXY_AUTO_REMOVE` g'alaba qozonadi (o'chirilishi kutilayotgan proksi-server o'rtasida yumshoq o'chirishdan foydalanmaydi). To'liq o'zgaruvchilar ro'yxati uchun [Environment Config](../reference/ENVIRONMENT.md) ma'lumotnomasiga qarang.

---

> 📖** Tegishli hujjatlar:**
>
> - [Foydalanuvchi uchun qoʻllanma](../guides/USER_GUIDE.md) — Umumiy sozlash va konfiguratsiya - [API Reference](../reference/API_REFERENCE.md) — Toʻliq API hujjatlari - [Environment Config](../reference/ENVIRONMENT.md) — Barcha muhit oʻzgaruvchilari
