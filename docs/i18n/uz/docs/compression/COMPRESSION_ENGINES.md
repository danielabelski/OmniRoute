# Compression Engines (Oʻzbekcha)

🌐 **Languages:** 🇺🇸 [English](../../../../compression/COMPRESSION_ENGINES.md) · 🇪🇹 [am](../../../am/docs/compression/COMPRESSION_ENGINES.md) · 🇸🇦 [ar](../../../ar/docs/compression/COMPRESSION_ENGINES.md) · 🇦🇿 [az](../../../az/docs/compression/COMPRESSION_ENGINES.md) · 🇧🇬 [bg](../../../bg/docs/compression/COMPRESSION_ENGINES.md) · 🇧🇩 [bn](../../../bn/docs/compression/COMPRESSION_ENGINES.md) · 🇧🇦 [bs](../../../bs/docs/compression/COMPRESSION_ENGINES.md) · 🇨🇿 [cs](../../../cs/docs/compression/COMPRESSION_ENGINES.md) · 🇩🇰 [da](../../../da/docs/compression/COMPRESSION_ENGINES.md) · 🇩🇪 [de](../../../de/docs/compression/COMPRESSION_ENGINES.md) · 🇬🇷 [el](../../../el/docs/compression/COMPRESSION_ENGINES.md) · 🇪🇸 [es](../../../es/docs/compression/COMPRESSION_ENGINES.md) · 🇪🇪 [et](../../../et/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇷 [fa](../../../fa/docs/compression/COMPRESSION_ENGINES.md) · 🇫🇮 [fi](../../../fi/docs/compression/COMPRESSION_ENGINES.md) · 🇫🇷 [fr](../../../fr/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇪 [ga](../../../ga/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [gu](../../../gu/docs/compression/COMPRESSION_ENGINES.md) · 🇳🇬 [ha](../../../ha/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇱 [he](../../../he/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [hi](../../../hi/docs/compression/COMPRESSION_ENGINES.md) · 🇭🇷 [hr](../../../hr/docs/compression/COMPRESSION_ENGINES.md) · 🇭🇺 [hu](../../../hu/docs/compression/COMPRESSION_ENGINES.md) · 🇦🇲 [hy](../../../hy/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇩 [id](../../../id/docs/compression/COMPRESSION_ENGINES.md) · 🇳🇬 [ig](../../../ig/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇹 [it](../../../it/docs/compression/COMPRESSION_ENGINES.md) · 🇯🇵 [ja](../../../ja/docs/compression/COMPRESSION_ENGINES.md) · 🇬🇪 [ka](../../../ka/docs/compression/COMPRESSION_ENGINES.md) · 🇰🇭 [km](../../../km/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [kn](../../../kn/docs/compression/COMPRESSION_ENGINES.md) · 🇰🇷 [ko](../../../ko/docs/compression/COMPRESSION_ENGINES.md) · 🇱🇹 [lt](../../../lt/docs/compression/COMPRESSION_ENGINES.md) · 🇱🇻 [lv](../../../lv/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [ml](../../../ml/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [mr](../../../mr/docs/compression/COMPRESSION_ENGINES.md) · 🇲🇾 [ms](../../../ms/docs/compression/COMPRESSION_ENGINES.md) · 🇲🇹 [mt](../../../mt/docs/compression/COMPRESSION_ENGINES.md) · 🇲🇲 [my](../../../my/docs/compression/COMPRESSION_ENGINES.md) · 🇳🇵 [ne](../../../ne/docs/compression/COMPRESSION_ENGINES.md) · 🇳🇱 [nl](../../../nl/docs/compression/COMPRESSION_ENGINES.md) · 🇳🇴 [no](../../../no/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [or](../../../or/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [pa](../../../pa/docs/compression/COMPRESSION_ENGINES.md) · 🇵🇭 [phi](../../../phi/docs/compression/COMPRESSION_ENGINES.md) · 🇵🇱 [pl](../../../pl/docs/compression/COMPRESSION_ENGINES.md) · 🇵🇹 [pt](../../../pt/docs/compression/COMPRESSION_ENGINES.md) · 🇧🇷 [pt-BR](../../../pt-BR/docs/compression/COMPRESSION_ENGINES.md) · 🇷🇴 [ro](../../../ro/docs/compression/COMPRESSION_ENGINES.md) · 🇷🇺 [ru](../../../ru/docs/compression/COMPRESSION_ENGINES.md) · 🇱🇰 [si](../../../si/docs/compression/COMPRESSION_ENGINES.md) · 🇸🇰 [sk](../../../sk/docs/compression/COMPRESSION_ENGINES.md) · 🇸🇮 [sl](../../../sl/docs/compression/COMPRESSION_ENGINES.md) · 🇷🇸 [sr](../../../sr/docs/compression/COMPRESSION_ENGINES.md) · 🇸🇪 [sv](../../../sv/docs/compression/COMPRESSION_ENGINES.md) · 🇰🇪 [sw](../../../sw/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [ta](../../../ta/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [te](../../../te/docs/compression/COMPRESSION_ENGINES.md) · 🇹🇭 [th](../../../th/docs/compression/COMPRESSION_ENGINES.md) · 🇹🇷 [tr](../../../tr/docs/compression/COMPRESSION_ENGINES.md) · 🇺🇦 [uk-UA](../../../uk-UA/docs/compression/COMPRESSION_ENGINES.md) · 🇵🇰 [ur](../../../ur/docs/compression/COMPRESSION_ENGINES.md) · 🇻🇳 [vi](../../../vi/docs/compression/COMPRESSION_ENGINES.md) · 🇳🇬 [yo](../../../yo/docs/compression/COMPRESSION_ENGINES.md) · 🇨🇳 [zh-CN](../../../zh-CN/docs/compression/COMPRESSION_ENGINES.md) · 🇹🇼 [zh-TW](../../../zh-TW/docs/compression/COMPRESSION_ENGINES.md)

---

OmniRoute siqish vosita shartnomalari atrofida qurilgan. Bir rejim to'g'ridan-to'g'ri bitta dvigatelni (`caveman` yoki `rtk`) yoki bir nechta dvigatellarni tartibda bajaradigan deterministik stacked quvur liniyasini ishga tushirishi mumkin.

## Tartiblar

| Rejim        | Dvigatel yo'li                                                                                             | Maqsadli kiritish                                    |
| ------------ | ---------------------------------------------------------------------------------------------------------- | ---------------------------------------------------- |
| `off`        | yo'q                                                                                                       | Aniq tezkor saqlash                                  |
| `lite`       | Caveman Lite yordamchilari                                                                                 | Har doim ochiq tozalash xavfi past                   |
| `standard`   | G'or odami                                                                                                 | Tabiiy tilda tez kondensatsiya                       |
| `aggressive` | Caveman + history/tool xulosalari                                                                          | Uzoq suhbatlar                                       |
| `ultra`      | Caveman + Azizillo yordamchilari                                                                           | Kontekst chegarasini tiklash                         |
| `rtk`        | RTK                                                                                                        | Terminal, qobiq, qurish, test va git chiqishi        |
| `omniglyph`  | OmniGlyph                                                                                                  | Mahalliy provayder simida tasvir sifatida kontekst   |
| `stacked`    | Quvur liniyasi. Standart so'rov `session-dedup -> lite` hisoblanadi. `rtk -> caveman` - ro'yxatdan o'tgan. | Aralash asboblar jurnallari va nasr, maksimal tejash |

### OmniGlyph siqish profillari

`omniglyph` dvigateli (paket `omniglyph`, 1.4.0 +) siqish sozlamalarida `omniglyph.profile` orqali global miqyosda yoki stacked quvur liniyasining qadam konfiguratsiyasi orqali har bir qadamda o‘rnatiladigan nomli semantik profilni qabul qiladi:

| Profil        | Chegara                                                                                                              |
| ------------- | -------------------------------------------------------------------------------------------------------------------- |
| `aggressive`  | Standart. Nashr qilingan tushumlar siyosati — tasvirlar tizimi, asboblar hujjatlari va zich tarixni o'lchadi         |
| `balanced`    | Jonli shtatni asl holatida saqlaydi, oxirgi 8 burilishni himoya qiladi, eski yopiq tarixni buzadi                    |
| `coding-safe` | Avtoritet, asboblar sxemalari va jonli asboblar chiqishini asl holatida saqlaydi, oxirgi 12 burilishni himoya qiladi |
| `passthrough` | O'zgartirilmagan marshrutlar; dvigatel o'tkazib yuborilgan                                                           |

Profil a** ship, pol emas** : paketdagi `mergeCompressionProfileOptions` qo'ng'iroq qiluvchiga yo'qolgan yo'lni yopilgan profilni qayta ochishga ruxsat berishni rad etadi, shuning uchun har bir qadam `preserveSystemPrompt: false` `coding-safe` ostida tizimni siqishni qayta faollashtira olmaydi.

Ushbu kod bazasida o'lchanadi: `coding-safe` va `balanced` `minCompressChars` maksimal darajaga ko'taradi va tizim, asboblar sxemalari va asboblar natijalarini asl holatda saqlaydi, shuning uchun hali tarix to'planmagan seans `below_min_chars` da to'xtaydi va vosita hech narsani o'zgartirmaydi. Shuning uchun sukut bo'yicha eng xavfsiz profil emas, balki `aggressive` hisoblanadi.

Paket o'zining atrof-muhit konfiguratsiyasidan o'zining model doirasi va profilini hal qiladi. OmniRoute hech qachon qarorni topshirmaydi: adapter model eshigini paketning eng cheklovchi doirasiga o'rnatadi, shuning uchun xost muhiti sozlamalari ruxsat etilgan ro'yxatni faqat toraytirishi mumkin, uni hech qachon OmniRoute o'lchangan tushumlaridan keyin kengaytirmaydi.

## Dvigatel reestri

Ro'yxatga olish kitobi `open-sse/services/compression/engines/registry.ts` yashaydi. Dvigatellar umumiy shartnomani ochib beradi:

- `id`: `caveman` yoki `rtk` kabi barqaror vosita identifikatori
- `apply(text, config)`: yig'ilgan quvurlar tomonidan ishlatiladigan eski ijro yo'li
- `compress(input, config)`: matn + statistikasini qaytaruvchi asosiy ijro yo‘li
- `getConfigSchema()`: joriy konfiguratsiyaning JSON-sxemaga o'xshash shaklini qaytaradi
- `validateConfig(config)`: `{ valid, errors[] }` ni qaytaradi

Roʻyxatdan oʻtishda qabul qilishdan oldin `assertValidEngine()` va `validateConfig(defaultConfig)` ni chaqiruvchi `registerCompressionEngine(engine)` (yoki ilgʻor holatlar uchun `registerEngine` ) ishlatiladi. Dvigatelni ish vaqtida olib tashlash uchun `unregisterCompressionEngine(id)` foydalaning.

`strategySelector.ts` o'rnatilgan dvigatellarni siqish boshlanishidan oldin ro'yxatdan o'tkazadi. Bu oldindan ko'rish, ish vaqtini siqish, to'plangan rejim, testlar va kelajakdagi dvigatellar bir xil bajarish yo'lidan foydalanish imkonini beradi.

### MCP tavsifini siqish (bog'liq)

Alohida ro'yxatga olish kitobi MCP vositasi tavsifi metama'lumotlarini registr darajasidagi — siqib chiqaradi, qarang `open-sse/mcp-server/descriptionCompressor.ts` va [MCP-SERVER.md](../frameworks/MCP-SERVER.md). U Caveman qoidalarini qayta ishlatadi, lekin foydali yuklarni so'ramaydi, balki asbob metama'lumotlarida ishlaydi.

### Qo'shimcha o'rnatilgan dvigatellar

Caveman, RTK va LLMLingua-2 dan tashqari, ro'yxatga olish kitobi bir nechta ixtisoslashgan yo'qotishsiz / tizimli dvigatellarni (to'plangan quvurlar, o'yin maydonchalari va sinovlar tomonidan qo'llaniladi) yuboradi:

| Dvigatel        | Id              | Nima qiladi                                                                                                                                                                                             |
| --------------- | --------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| CCR             | `ccr`           | Content-Compress-Retrieve (H4): katta qo'shni matn bloklarini kontent manzilli havolalar bilan almashtiradi, shuning uchun repeated/large bloklari bir marta yuboriladi va undan keyin havola qilinadi. |
| bosh joyi       | `headroom`      | SmartCrusher (H3 + N5): bir hil JSON massividagi foydali yuklarni ustunli `[N rows]` shakliga yo'qotishsiz jadvalli siqish.                                                                             |
| ionlashtiruvchi | `ionizer`       | juda katta bir hil bloklar uchun Head/middle/tail qator namuna olish, CCR kontent manzilli ma'lumotnoma sifatida elided o'rta saqlash.                                                                  |
| seans-deup      | `session-dedup` | Kontentga asoslangan oʻzaro burilishli deduplikatsiya (TokenMizer tomonidan ilhomlantirilgan): xuddi shu seansning oldingi burilishlarida allaqachon koʻrilgan matnni elaydi.                           |

**CCR olish-protokol ko'rsatmasi (#8033):** CCR birinchi marta so‘rovda ≥ 1 blokini almashtirganda, vosita qo‘ng‘iroq qiluvchiga → belgisini o‘rgatish uchun yagona, idempotent `system` xabarini ( `[CCR protocol]` sentinel bilan olib boradi) qo‘yadi: `[CCR retrieve hash=<24hex> chars=N]` belgisi nimani anglatadi, xeshni so‘zma-so‘z ko‘chirib olish kerak (barcha 24 hexqihepi noto‘g‘ri sabab bo‘lishi mumkin" topilmadi" o'tkazib yuborilgan) va — belgisi " `[dedup:ref sha=...]` chaqirish" emas, balki "tarixga nazar tashlash" degan ma'noni anglatadi. Eslatma in'ektsiya qilinadi** faqat qo'ng'iroq qiluvchining e'lon qilingan `tools[]` haqiqatda `omniroute_ccr_retrieve` erishish mumkinligini isbotlaganida** (`callerSupportsCcrRetrieve()` in `open-sse/services/compression/engines/ccr/protocolInstruction.ts`) — oddiy OpenAI-ga mos keladigan qo'ng'iroq qiluvchi ushbu vositasiz hech qachon u erisha olmaydigan narsaga qo'ng'iroq qilish ko'rsatmasini olmaydi. Idempotentlik in'ektsiyadan oldin sentinel uchun xabarlar tarixini skanerlash orqali amalga oshiriladi, shuning uchun ko'p navbatli so'rovlar (oldingi xabarlarni takrorlaydigan) eslatmani har bir navbatga bir marta to'plamaydi.

## G'or odami

G'or odami rejimi oddiy nasrning semantik kondensatsiyasiga e'tibor qaratadi:

- kod bloklari, URLs, JSON, yo'llar va tuzilgan ma'lumotlarni saqlaydi
- toʻldiruvchini, himoyalanishni, takrorlangan kontekstni va batafsil bogʻlovchi iboralarni olib tashlaydi
- `open-sse/services/compression/rules/` da tilni biladigan fayl qoidalari paketlarini qo'llab-quvvatlaydi
- eski `standard`, `aggressive` va `ultra` rejimlari orqali mavjud bo'lib qoladi

Boshqaruv paneli yuzasi `Dashboard -> Context & Cache -> Caveman`.

Caveman upstream `~75%` kamroq chiqish tokenlari, `22-87%` diapazoniga ega benchmarklarda `65%` o'rtacha ishlab chiqarish tejamkorligi va `~46%` kiritish-siqish vositasi haqida xabar beradi. OmniRoute yig'ilgan prompt/context jamg'armalarini hujjatlashtirishda Caveman kiritish tomoni raqamidan foydalanadi; Caveman chiqish rejimi alohida javob-xulq-atvor xususiyati bo'lib qoladi.

## RTK

RTK rejimi buyruq va asboblar chiqishiga qaratilgan:

- `git status`, `git branch`, `git diff`, Vitest/Jest/Pytest, Cargo/Go testlari, TypeScript/Vite/Webpack tuzilmalari, ESLint, npm audit/installs, Docker jurnallari, qobiq `find`/`grep`, stek izlari va umumiy jurnallar kabi chiqish sinflarini aniqlaydi
- `open-sse/services/compression/engines/rtk/filters/` dan 49 JSON filtrini qo'llaydi
- RTK uslubidagi deklarativ quvur liniyasini qo'llab-quvvatlaydi: ANSI o'chirish, almashtirish, mos chiqish qisqa tutashuvi, strip/keep liniyalari, har bir satrda kesish, head/tail/max-line qirqish va bo'sh orqaga qaytarish
- `.rtk/filters.json` -da ishonchli himoyalangan loyiha filtrlarini va `DATA_DIR/rtk/filters.json`-da global filtrlarni qo'llab-quvvatlaydi
- chiziqlar ANSI ketma-ketligi, harakat shovqini, takroriy satrlar va foydasiz boilerplate
- harakat qilish mumkin bo'lgan nosozliklar, ogohlantirishlar, xulosalar, o'zgartirilgan fayllar va kontekstni saqlaydi
- ixtiyoriy ravishda autentifikatsiya qilingan boshqaruv marshrutlari orqali recovery/debugging uchun tahrirlangan xom ashyoni saqlab qolishi mumkin

Boshqaruv paneli yuzasi `Dashboard -> Context & Cache -> RTK`.

Maxsus filtrlar, ishonch, tekshirish va xom-ashyoni qayta tiklash uchun operatsion tafsilotlar [`RTK_COMPRESSION.md`](./RTK_COMPRESSION.md) da mavjud.

RTK upstream buyruq-chiqarish siqish uchun `60-90%` tejash xabar beradi. Uning README misolida `~118,000` tokenlaridan `~23,900` ga yoki `79.7%` saqlangan 30 daqiqalik Claude Code seansi ko‘rsatilgan.

## LLMLingua-2 (semantik kesish)

LLMLingua-2 rejimi ishlaydi** semantik tokenni kesish** qoidaga asoslangan Caveman va RTK dvigatellarini to'ldiruvchi kichik ONNX token klassifikatoridan foydalangan holda nasrda:

- faqat tizimdan tashqari xabarlardagi nasrni siqadi; o'ralgan kod bloklari va boshqa saqlanib qolgan konstruktsiyalar hech qachon o'zgartirilmaydi
- ishchi ish zarrachasida `@atjsh/llmlingua-2` backend (ONNX via `@huggingface/transformers`) ni ishga tushiradi, shuning uchun model xulosasi hech qachon so'rov hodisasini bloklamaydi
- hisoblanadi** yig'iladigan** (`stackPriority` 35): stacked quvur liniyasida u strukturaviy dvigatellardan keyin ishlaydi (CCR, session-dedup, headroom, Caveman) lekin `ultra` dan oldin, chunki semantik kesish allaqachon tizimli siqilgan — matnida eng samarali hisoblanadi, masalan `rtk -> caveman -> llmlingua`
- **har qanday xatoda muvaffaqiyatsiz ochiladi** (ixtiyoriy deps, ishchi paydo bo'lishi, model yuki, xulosa yoki vaqt tugashi yo'q) → asl matn o'zgarmagan holda qaytariladi, hech qachon xatolik yuz bermaydi

Dvigatel joylashuvi: `open-sse/services/compression/engines/llmlingua/`. Boshqaruv paneli yuzasi `Dashboard -> Context & Cache -> LLMLingua`.

### Modellar

Standart model**TinyBERT** (`atjsh/llmlingua-2-js-tinybert-meetingbank`, ~ 57 MB, tez). Yuqori aniqlik** BERT bazasi** model (`Arcoldd/llmlingua4j-bert-base-onnx`, ~ 710 MB) dvigatel konfiguratsiyasi `model` maydoni orqali mavjud. `@huggingface/transformers` tanlangan modelni dangasalik bilan HuggingFace Hub dan birinchi qo‘ng‘iroqda `${DATA_DIR}/models/llmlingua` ga yuklaydi (`modelStore.ts`); `modelPath` konfiguratsiyasini bekor qilish uning o'rniga mahalliy nusxaga ishora qiladi (oflayn / havo o'tkazmaydigan o'rnatishlar).

### Ixtiyoriy bog'liqliklar va talab bo'yicha o'rnatish

Prunable LLMLingua runtime peer stack hisoblanadi** ixtiyoriy** . Ikkita paket `package.json` da `optionalDependencies` deb e'lon qilinadi va saqlanadi** tashqi** ishlab chiqarish qurilishi bo'yicha (`scripts/build/prepublish.ts` ularni birlashtirmaydi):

| Paket                | Versiya (pin) | Eslatmalar                                           |
| -------------------- | ------------- | ---------------------------------------------------- |
| `@atjsh/llmlingua-2` | `2.0.5`       | Kirish paketi; boshqalarni tengdosh deb e'lon qiladi |
| `js-tiktoken`        | `^1.0.20`     | Tokenizer                                            |

`@huggingface/transformers` `^4.2.0` -ga mahkamlanadi (mahalliy o'rnatish yo'li bilan baham ko'riladi va shuningdek, mustaqil to'plamda kuzatiladi); `@atjsh/llmlingua-2@2.0.5` tengdoshlari `"^3.5.2 || ^4.0.0"` bilan ishlaydi, shuning uchun ham Transformers.js v3 va v4 qo'llab-quvvatlanadi. 2.0.4 dan boshlab, `@atjsh/llmlingua-2` endi `@tensorflow/tfjs` talab qilmaydi, bu esa SLM stekidan eng katta yagona hissa qo'shuvchini (TensorFlow.js) olib tashladi. Faqat yuqoridagi ikkita paket SLM tengdoshlari hisoblanadi. Standart `npm install` (dev) ixtiyoriy bog'liqliklar o'tkazib yuborilmasa, ixtiyoriy stekni avtomatik ravishda o'rnatadi.

**Nima uchun talab bo'yicha:** npm tomonidan nashr etilgan to'plam, mustaqil to'plam va Docker tasvir kemasi** holda** bu deps nozik bo'lib qolish uchun. Ular yo'q bo'lganda, ishchining qaramlik eshigi ( `worker.ts` dagi `@atjsh/llmlingua-2` hal tekshiruvi) ishlamay qoladi va dvigatel ishlamay qoladi.** muvaffaqiyatsiz - jimgina ochiladi** — LLMLingua tanlash no-opga aylanadi (matn o'zgarmagan holda qaytariladi, hech qanday xato qayd etilmaydi). Uni kesilgan muhitda faollashtirish uchun ixtiyoriy stekni o'rnating:

```bash
# pin to the versions declared in package.json optionalDependencies
npm install @atjsh/llmlingua-2@2.0.5 js-tiktoken
```

`@tensorflow/tfjs` olib tashlash (2.0.4 +) avval ustun bo'lgan ~ 800 MB hissa qo'shuvchi — yo'q qiladi, qolgan iz transformers.js + onnxruntime-tugun ish vaqtlari va TinyBERT modeli (~ 57 MB) birinchi marta yuklab olinmagan.

Atrof-muhit bo'yicha:

- **Dev / `npm install`** `--omit=optional` (yoki `--no-optional`) dan o'tmasangiz, — avtomatik ravishda o'rnatiladi. Harakat kerak emas.
- **Global npm (`npm i -g omniroute`) / mustaqil** — o'rnatilgan paketlar katalogida yuqoridagi o'rnatish buyrug'ini ishga tushiring yoki ixtiyoriy depslarni qoldirmasdan qayta o'rnating.
- **Docker** — olingan tasvir qatlamiga o'rnatish buyrug'ini qo'shing; nashr etilgan tasvir dizayni bo'yicha nozik bo'ladi.
- **VPS (PM2)** — ilovasining `node_modules` ga o'rnating, so'ngra jarayonni qayta ishga tushiring, shunda ishchi eshikni qayta tekshiradi.
- **Raw Next mustaqil (`npm run build` → `.build/next/standalone/server.js`)** — mustaqil kuzatuv kemalari ishchini ham, ixtiyoriy depsni ham NEITHER, shuning uchun dvigatel jimgina ishlamay qoladi. `scripts/build/colocate-standalone.mjs` ikkalasini ham qayta qo'llaydi (ishchi esbuild + mustaqil daraxtga ixtiyoriy-dep yopish); u har bir qurishdan keyin `postbuild` npm kancasi orqali avtomatik ravishda ishlaydi. Idempotent, deps mavjud bo'lmaganda ishlamay qoladi.

**Uning faolligini tekshiring:** tanlangan LLMLingua bilan haqiqiy nasr aslida qisqaradi (dvigatel muvaffaqiyatsiz ochilishni to'xtatadi) va birinchi so'rov modelni `${DATA_DIR}/models/llmlingua` ga yuklab olishni boshlaydi. Darvoza qasddan faqat `@atjsh/llmlingua-2` — tekshiradi, boshqa tengdoshlar faqat ESM-dir va `require.resolve` — mavjud bo'lganda ham ularga tashlaydi, shuning uchun `import()` vaqtida biron bir tengdosh yo'qolgan bo'lsa, ishchi baribir ochilmay qoladi.

## Yig'ilgan quvurlar

Stacked rejimi quvur bosqichlarini tartibda boshqaradi. Standart:

```txt
rtk -> caveman
```

Buni kodlash-agent seanslari uchun foydalaning, bunda buyruq chiqishini inson yoki yordamchi nasr bilan birlashtiradi. RTK avval shovqinli asboblar jurnallarini kamaytiradi, keyin Caveman qolgan tabiiy tilni siqib chiqaradi.

Quvur liniyasi bosqichlari siqish sozlamalarida yoki siqish kombinatsiyalari orqali `stackedPipeline` bilan tuzilgan.

Ikkala dvigatel ham bir xil foydali yukni kamaytirsa, tejamkorlik birikmasi:

```txt
combined = 1 - (1 - RTK savings) * (1 - Caveman input savings)
average  = 1 - (1 - 0.80) * (1 - 0.46) = 89.2%
range    = 1 - (1 - 0.60..0.90) * (1 - 0.46) = 78.4-94.6%
```

## MCP Maxsus imkoniyatlar daraxti filtri

MCP accessibility-tree aqlli filtri MCP -da ishlaydigan bajarilgandan keyingi siqish qatlamidir.** vosita natijalari** , takliflar yoki kontekstda emas. Playwright, kompyuterdan foydalanish va brauzerni avtomatlashtirish MCP serverlari kabi vositalar tomonidan qaytariladigan batafsil foydalanish imkoniyati daraxti va brauzerning oniy tasvir yuklamalariga qaratilgan.

### Nima qiladi

1. **Shovqinni olib tashlash** — bo'sh generic/text yozuvlarini o'chiradi (`- generic:`, `- text: ""`)
2. **Birodarning qulashi** — qachon ≥ `collapseThreshold` (standart 30) ketma-ket satrlar tuzilmaviy takrorlar bo‘lsa, ularni birinchi `collapseKeepHead` (standart 10) satrlarga yig‘adi + a hisoblash xulosasi + oxirgi `collapseKeepTail` (standart 5) satrlar
3. **Refni saqlash** Playwright/computer-use tomonidan talab qilinadigan — `[ref=eXX]` langarlariga hech qachon tegilmaydi
4. **Qattiq kesish** — agar siqilgandan keyin matn hali ham `maxTextChars` dan oshsa (standart 50 000), agent ishlashni davom ettirishi uchun navigatsiya maslahati bilan qisqartiriladi

### Dvigatel joylashuvi

```txt
open-sse/services/compression/engines/mcpAccessibility/
  index.ts            ← smartFilterText() entry point
  collapseRepeated.ts ← sibling-collapse algorithm
  constants.ts        ← DEFAULT_MCP_ACCESSIBILITY_CONFIG
```

### Konfiguratsiya

Global sozlamalarda `compression.mcpAccessibility` tomonidan boshqariladi (migratsiya 056). Standart konfiguratsiya:

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

Filtr faqat `type` `"text"` bo‘lgan va uzunligi `minLengthToProcess` ortiq bo‘lgan asbob-natijali foydali yuklarga qo‘llaniladi. Bu tezkor siqish yoki so'rov yuklariga ta'sir qilmaydi.

### Kutilayotgan tejash

Sahifaning murakkabligiga qarab, brauzerning suratga olish vositasi natijalarida 60–80%. Yiqilish algoritmi qatorlar sonida O(n) bo'lib, ahamiyatsiz kechikish vaqtini qo'shadi.

### Ushbu filtr yuqoridagi siqish dvigatellariga nisbatan

| Aspekt           | Caveman / RTK / Stacked | MCP mavjudlik filtri                   |
| ---------------- | ----------------------- | -------------------------------------- |
| Maqsad           | So'rovlar / kontekst    | MCP vositasi natijalari                |
| Trigger          | Siqish rejimini sozlash | `compression.mcpAccessibility.enabled` |
| Qo'llash doirasi | Barcha SSE xabarlar     | Faqat asboblar natijalari              |
| Ref langarlar    | N/A                     | Shartsiz saqlanadi                     |

---

## Siqish kombinatsiyalari

Siqish kombinatsiyalari marshrutlash kombinatsiyalariga tayinlanishi mumkin bo'lgan siqish profillari deb ataladi:

- `compression_combos`: rejim, quvur liniyasi, RTK konfiguratsiyasi, til konfiguratsiyasi va standart markerni saqlaydi
- `compression_combo_assignments`: siqish kombinatsiyasini marshrutlash kombinatsiyasiga moslashtiradi
- ish vaqti integratsiyasi umumiy kombinatsiyani bekor qilishdan oldin tayinlangan siqish kombinatsiyasini hal qiladi
- analitikaga `compression_combo_id` va `engine` kiradi

Boshqaruv paneli yuzasi: `Dashboard -> Context & Cache -> Compression Combos`.

## Old shartlar / operator qo'llanmasi (CCR & session-dedup)

CCR (`ccr`) va `session-dedup` matnni almashtiradi yoki siljitadi va a qoldiradi** marker** orqasida. Ushbu bo'lim mijozni ulash, ikkita markerni o'qish va ko'rsatilgan tarkibni olish yoki diagnostika qilish uchun operator ma'lumotnomasidir. Har bir dvigatelning mexanikasi yuqorida yoritilgan; bu "qanday ishga tushiraman" qatlami.

### Transport va oxirgi nuqtalar

CCR vositalarini ochadigan MCP serveriga uchta yo'l bilan kirish mumkin. Standart URL bazasi `http://localhost:20128` (`OMNIROUTE_BASE_URL`):

| Transport                            | URL / buyruq                            | Eslatmalar                                                                                                                                   |
| ------------------------------------ | --------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------- |
| Oqimli HTTP (mijoz, tavsiya etiladi) | `http://localhost:20128/api/mcp/stream` | Hozirgi MCP mijozlari bilan gaplashadigan oxirgi nuqta.                                                                                      |
| Eski SSE singleton                   | `http://localhost:20128/api/mcp/sse`    | Qadimgi singleton transporti. Bu** yopiladi** oqimli seanslar; `streamable-http` mijozlaridan `/api/mcp/stream` qarshi foydalaning, bu emas. |
| stdio                                | `omniroute --mcp`                       | Jarayonni keltirib chiqaradigan IDE MCP konfiguratsiyasi uchun. `--dev` bayrog'i yo'q; `omniroute --mcp` - stdio kirish nuqtasi.             |

### Saqlash darajalari (qayta ishga tushirilganda omon qoladi)

CCR - a** ikki bosqichli** do'kon, faqat xotirada emas:

- **Issiq xotira darajasi** — bosh blok uchun 2 MiB, boshiga 16 MiB, global 64 MiB. Yozuvlar standart 24 soat TTL (maksimal 7 kun). Xotiradan to'liq MCP olish 256 KiB bilan cheklangan; har qanday kattaroq narsaga diapazonli/grep rejimlari orqali erishish mumkin.
- **Bardoshli SQLite darajasi** (`ccr_blocks`, `COMPRESSION_CCR_DURABLE_STORE`, sukut boʻyicha yoqilgan) — xotiradagi sathni qoʻllab-quvvatlaydi, shuning uchun blok LRU koʻchirilishi, qayta ishga tushirilishi yoki boshqa nusxada qoʻnishi mumkin boʻlmaganda omon qoladi. Qator blokning TTL saqlaydi, shuning uchun uning TTL dan o‘tgan blok ikkala sathdan ham o‘chib ketadi.

Uchta qo'riqchi bardoshli darajani chegaralangan — a blok xotirada qoladi - faqat quyidagi hollarda:

1. blok tugadi** 512 KB** (`MAX_DURABLE_BLOCK_BYTES`);
2. ish vaqti bulutli ish vaqti (mahalliy disk yo'q);
3. `COMPRESSION_CCR_DURABLE_STORE=false`.

Shunday qilib, "blok yo'qoldi" qayta ishga tushirish hikoyasi emas: mahalliy, bulutli bo'lmagan ish vaqtidagi sub-512 KB bloki TTL tugaguniga qadar chidamli qatlam orqali qayta ishga tushirilganda omon qoladi. O'zgaruvchi uchun [Atrof-muhit ma'lumotnomasiga](../reference/ENVIRONMENT.md) qarang.

### Ikkita belgi

| Marker                                | Ma'nosi                                                                                                                                             | Model nima qilishi kerak                                                                                                                                                                                                                    |
| ------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| `[CCR retrieve hash=<24hex> chars=N]` | Katta blok kontent-manzilli saqlangan.                                                                                                              | bilan `omniroute_ccr_retrieve` ga qo'ng'iroq qiling** 24-hex xesh so'zma-so'z ko'chirildi** asl matnni qaytarish uchun.                                                                                                                     |
| `[dedup:ref sha=…]`                   | `session-dedup` elided matn allaqachon xuddi shu seansning oldingi navbatida yuborilgan. Bu a** qasddan orqaga qarash** , yo'qotish yoki xato emas. | Do** emas** har qanday vositani chaqiring va bajaring** emas** uni "qayta qurishga" harakat qiling. Matnning birinchi paydo bo'lishi kanonik nusxadir; joriy navbat hech qachon qayta yozilmaydi, u keyingi burilishda deduktsiya qilinadi. |

`[dedup:ref]` orqaga qarash - bu ataylab qabul qilingan protokol qarori — oldindan yuborish rekonstruksiyasi yo'q. Buni "aynan ushbu matn ushbu sessiyada avvalroq simda bo'lgan" deb hisoblang.

### Mijoz uchun zaruriy shartlar

- **Kalit (stdio):** stdio qo'ng'iroq qiluvchisi har bir so'rov identifikatoriga ega emas, shuning uchun u `OMNIROUTE_API_KEY` bilan autentifikatsiya qiladi ( MCP serverining `env` ga o'rnatilgan). Busiz qo'ng'iroq qiluvchi anonim bo'lib qoladi va direktor talab qiladigan vositalar yomonlashishi mumkin.
- **`tools[]` - inyeksiyaning old sharti.** CCR retrieve-protocol ko'rsatmasi (#8033) kiritiladi** faqat** so'rovning e'lon qilingan `tools[]` mijozning `omniroute_ccr_retrieve` erishishi mumkinligini isbotlaganida. Moslik ajratuvchi (`__`, `.`, `/`, `:`) — hech qachon yalang'och pastki qator — bilan chegaralangan so'nggi segment mosligidir, shuning uchun `mcp__gateway__omniroute_ccr_retrieve` kabi nomlar oralig'idagi nom hali ham hisobga olinadi. Yo'q yoki mos kelmaydigan `tools[]` ko'rsatma dizayn bo'yicha kiritilmaganligini bildiradi.
- **`codemode:false` (OpenCode mijozlari).** OpenCode sukut bo'yicha Kod rejimiga o'rnatiladi, bu modelga faqat o'zining mahalliy vositalarini reklama qiladi va** qilmaydi** MCP vositalarini mahalliy `tools[]` ro'yxatiga qo'ying. MCP server yozuviga `codemode: false` o'rnating, shuning uchun `omniroute_ccr_*` vositalari reklama qilinadi. Bu a** mijoz** sozlash, OmniRoute emas. U hali CCR ko'rsatmasini kiritmaydi: OpenCode asbobni `<server>_<tool>` deb nomlaydi, shuning uchun `omniroute` deb nomlangan server `omniroute_omniroute_ccr_retrieve` ochib beradi va `_` mos ajratuvchilardan biri emas.
- **Direktorlar.** Saqlash va olish autentifikatsiya qilingan asosiy (har bir API kaliti uchun) uchun ajratilgan. Kalit faqat o'z bloklarini ko'radi.

### Har bir asbob uchun doiralar

Dar doiradagi HTTP/SSE qo‘ng‘iroq qiluvchilar uchun amal qilish doirasi doimo yoniq. `omniroute_` CCR asboblari quyidagilarni talab qiladi:

| Asbob                    | Qo'llash doirasi    |
| ------------------------ | ------------------- |
| `omniroute_ccr_store`    | `write:compression` |
| `omniroute_ccr_delete`   | `write:compression` |
| `omniroute_ccr_retrieve` | `read:compression`  |
| `omniroute_ccr_inspect`  | `read:compression`  |
| `omniroute_ccr_list`     | `read:compression`  |
| `omniroute_ccr_stats`    | `read:compression`  |

Yo'qolgan qamrov a ni qaytaradi**MCP vositasi xatosi natijasi** (`isError: true`, HTTP 403 — emas, `403 LOCAL_ONLY` alohida orqaga qaytish marshruti qo‘riqlash authidir): `Error: Insufficient MCP scopes for <tool>. Missing: <scope>.` Minimal masofaviy kalit `mcp:connect` (faqat `/api/mcp/` mahalliy o‘yib chiqarishga ruxsat beradi) va unga kerak bo‘lgan maxsus read/write doirasini ushlab turishi mumkin.

### Mijoz matritsasi

| Mijoz                   | Transport                          | Foydalanish uchun konfiguratsiya                                                                                                                                                                                                                                               | `tools[]` reklama qilinganmi? (→ CCR ko'rsatmasi kiritilgan)                                                                                                                                                      |
| ----------------------- | ---------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Claude kodi             | oqimli-http                        | `claude mcp add --transport http omniroute http://localhost:20128/api/mcp/stream`                                                                                                                                                                                              | Ha — MCP-qobiliyati; in'ektsiya qilingan.                                                                                                                                                                         |
| Cursor / Cline          | `stdio`** yoki** `streamable-http` | stdio: `env` dagi `OMNIROUTE_API_KEY` bilan `omniroute --mcp` ; yoki `http://localhost:20128/api/mcp/stream` ga ishora qiluvchi masofaviy MCP yozuvi (qarang: [→ MCP mijoz konfiguratsiyasini sozlash bo‘yicha qo‘llanma](../guides/SETUP_GUIDE.md#mcp-client-configuration) ) | Ha — `omniroute_ccr_*` vositalarini reklama qiling.                                                                                                                                                               |
| OpenCode                | oqimli-http                        | `opencode mcp add omniroute --url http://localhost:20128/api/mcp/stream`, plus `codemode: false`                                                                                                                                                                               | Faqat `codemode: false` bilan reklama qilingan asboblar; ko'rsatma hali ham kiritilmagan, chunki `omniroute_omniroute_ccr_retrieve` mos kelmaydi ( [mijoz uchun zarur shartlarga](#client-prerequisites) qarang). |
| OpenAI bilan mos keladi | OpenAI-mos HTTP (chat yakunlari)   | OpenAI-mos keladigan so'nggi nuqtaga qarshi standart chat-to'ldirish mijozi                                                                                                                                                                                                    | **Hech qachon** — oddiy OpenAI-ga mos keladigan qo'ng'iroq qiluvchiga hech qachon asbobga qo'ng'iroq qilish aytilmaydi va ko'rsatma kiritilmaydi.                                                                 |

### Qidiruv cheklovlari va sahifalash

MCP vositasi matn natijalari `mcpAccessibility.maxTextChars` atrofida kesiladi (standart `50000`). Blokni `full` olish 256 KiB — bilan cheklangan** cheksiz to'liq olish yo'q** . Blokning `chars=N` katta bo'lsa, hamma narsani tortib olish o'rniga uni sahifalang:

- Asosiy qoida:**`chars > 40000` → `mode` dan foydalaning** , hech qachon yalang'och to'la.
- `mode:"grep"` — regex `pattern` satr satrga mos keladi, 1000 tagacha mos keladigan satrlar (`unique: true` tomchilar takrorlanadi), "menga kerak bo'lgan bitta qatorni toping" uchun eng arzon.
- `mode:"lines"` — 1-indekslangan qator diapazoni; `start` ham, `end` kerak.
- `mode:"head"` / `mode:"tail"` — first/last `n` chiziqlari.
- `mode:"stats"` — satr, belgi va bayt sonini tanasiz.

Bir vaqtning o'zida hamma narsani so'rash o'rniga, sahifalar bo'ylab uzoq masofani bosib o'tish uchun `start`/`end` bilan `mode:"lines"` foydalaning.

### Asbobga nom berish

Qayta tiklash vositasi hozirda `omniroute_ccr_retrieve` deb nomlangan ( `omniroute_` prefiksi serverlar o'rtasidagi nomlar to'qnashuvi uchun sanalangan vaqtinchalik yechimdir). Tozaroq chegaralangan qo'shimchali asbob nomi va MCP JSON natijalari uchun tuzatish o'rta qatorning kesilgan qismi yuqori oqim kuzatuvi sifatida kuzatiladi; bu sahifa faqat joriy, yuborilgan xatti-harakatni hujjatlashtiradi.

### Seansning hayot aylanishi

Streamable-HTTP seanslari ishlamay qoladi va server ularni yig'adi; bo'sh turgan oyna `MCP_SESSION_IDLE_MS` doimiysi (qattiq kodlangan qiymat emas, nomi bilan ko'rsatilgan, shuning uchun u o'zgarganda bu sahifa siljimaydi). Bekor qilingan seansning alomati HTTP 404 bilan `Unknown Mcp-Session-Id` — bo'lib, chora seansni qayta ulash yoki qayta boshlashdir,** emas** tugmani aylantirish, doirani o'zgartirish yoki asbob nomini o'zgartirish uchun.

## API Surface

| Marshrut                               | Maqsad                                                                              |
| -------------------------------------- | ----------------------------------------------------------------------------------- |
| `/api/settings/compression`            | Global siqish sozlamalari ( `mcpAccessibility` konfiguratsiyasini o'z ichiga oladi) |
| `/api/compression/preview`             | Har qanday siqish rejimini oldindan ko'ring                                         |
| `/api/compression/language-packs`      | Mavjud Caveman til paketlarini ro'yxatlang                                          |
| `/api/context/caveman/config`          | Caveman sozlamalari taxallus                                                        |
| `/api/context/rtk/config`              | RTK standarti va sozlamalari                                                        |
| `/api/context/rtk/filters`             | RTK filtri katalogi                                                                 |
| `/api/context/rtk/test`                | RTK preview/test oxirgi nuqtasi                                                     |
| `/api/context/rtk/raw-output/[id]`     | Tasdiqlangan redaktsiyalangan xom ashyoni qayta tiklash                             |
| `/api/context/combos`                  | Kombo siqish CRUD                                                                   |
| `/api/context/combos/[id]/assignments` | Marshrutlash-kombo tayinlash CRUD                                                   |
| `/api/context/analytics`               | Siqish tahlili taxalluslari                                                         |

Boshqaruv marshrutlari boshqaruv autentifikatsiyasini yoki API kaliti siyosatini tekshirishni talab qiladi.

## MCP vositalari

Siqish beshta MCP vositalarini ochib beradi:

| Asbob                               | Qo'llash doirasi    | Maqsad                                       |
| ----------------------------------- | ------------------- | -------------------------------------------- |
| `omniroute_compression_status`      | `read:compression`  | Sozlamalar, tahlillar, kesh statistikasi     |
| `omniroute_compression_configure`   | `write:compression` | Global sozlamalarni yangilang                |
| `omniroute_set_compression_engine`  | `write:compression` | O'rnatish rejimi va ixtiyoriy quvur liniyasi |
| `omniroute_list_compression_combos` | `read:compression`  | Siqish kombinatsiyalarini ro'yxatlash        |
| `omniroute_compression_combo_stats` | `read:compression`  | combo/engine tahlilini o'qing                |

## Qo'llash doirasi va istisnolar

**O'rnatishlar hech qachon siqilmaydi.** `open-sse/handlers/embeddings.ts` hech qachon hech qanday siqish dvigatelini — chaqirmaydi request/response jismlari to'g'ridan-to'g'ri bajaruvchiga tegmasdan o'tadi. Bu bugungi kunda tizimli (o'rnatishlar va chat yakunlari bir-biridan ajratilgan ishlov beruvchilar), ish vaqtini tekshirish emas, lekin bu #8034 -dagi vektor-buzilish muammosi o'rnatish yo'lida ta'sir qilish yuzasiga ega emasligini anglatadi.

**Per-model/endpoint istisno filtri (#8034).** Suhbatni yakunlash uchun operator hech qachon siqilmasligi kerak bo'lgan model identifikatorlari / `provider/model` maqsadlarini nomlashi mumkin — siqish keyinchalik qo'shni yo'lga yaqinroq o'rnatilgan bo'lsa foydali bo'lgan himoya panjarasi va odatda baytga aniq ko'rsatkichlari muhim bo'lgan har qanday model uchun foydalidir (deterministik baholashlar, keshga sezgir prefikslar va boshqalar).

- Sozlamalar maydoni: global siqish konfiguratsiyasidagi `exclusions?: string[]` (`GET`/`PUT /api/settings/compression`), mavjud `key_value` siqish nom maydoni (`src/lib/db/compression.ts`) orqali davom etdi — yangi jadval yo‘q.
- Boshqaruv paneli yorlig'i:** Boshqaruv paneli → Compression → Istisnolar** (`/dashboard/compression/exclusions`).
- Shakl sintaksisi: `*` yagona joker belgidir. Shakldagi har bir boshqa regex meta-belgi moslashishdan oldin chiqarib tashlanadi, shuning uchun `gpt-5.6` faqat literal satrga mos keladi, hech qachon `gpt-5x6` (ReDoS-xavfsiz, chegaralangan, ichki o'rnatilgan kvantlar yo'q). Naqshlar yalang'och model identifikatori va `provider/model` kompozit — `gpt-5-6`, `openai/gpt-5-6` va `openai/*` bilan katta-kichik harflarga mos keladi, barchasi ishlaydi va faqat `*` har bir modelni istisno qiladi.
- Moslash: `isCompressionExcluded()` / `normalizeCompressionExclusions()` in `open-sse/services/compression/exclusions.ts`. `chatCore.ts` siqish sozlamalarini hal qilgandan so'ng darhol chiqarib tashlangan maqsadni tekshiradi,** har qanday dvigatel ishga tushishidan oldin** , va moslikni xuddi siqishni global miqyosda o'chirib qo'yilgani kabi ko'rib chiqadi — so'rovning tanasi bayt jihatidan bir xil. Oʻtkazib yuborish tahliliy koʻrinish uchun `writeCompressionSkip(..., "excluded")` orqali yozib olinadi.
- Standart (empty/absent ro'yxati):#8034 oldingi xatti-harakatlarga o'xshash — hech narsa chiqarib tashlanmaydi.

## Ma'lum cheklovlar

- **LLMLingua-2 (SLM) birgalikda joylashgan ixtiyoriy depslarni talab qiladi.** Ishchi faqat `@atjsh/llmlingua-2` + tengdoshlari `dist/node_modules` ga birlashganda ishlab chiqarish qurilishida ishlaydi (qarang: `scripts/build/colocateOptionals.mjs`, #4286). Ularsiz vosita ishlamay qoladi (asl matnni qaytaradi). Ishchi ruxsati endi `import.meta.url` ga bog'liq emas (u mustaqil to'plamda o'ladi) — u cwd / `argv[1]` ish vaqtiga bog'laydi.
- **Caveman til paketlari `de` / `fr` / `ja` qisman.** Ular `context` + `filler` + `structural` qoidalarini jo‘natadi, lekin `dedup` / `ultra` paketlari yo‘q, shuning uchun `ultra` intensivligi bu tillar uchun `full` dan kuchliroq emas (ular faqat o‘z qoidalaridan foydalanadilar — ingliz tilidagi `dedup`/`ultra` qoidalariga jimgina qaytish yo‘q, bu chet el matnini buzadi). `en` / `es` / `id` / `pt-BR` to'liq. Qisman paketlar uchun `dedup.json` + `ultra.json` hissalari qabul qilinadi.
- **Yig'ilgan telemetriya faqat siqilgan dvigatellarning ro'yxatini ko'rsatadi.** Dvigatel ishlagan, lekin 0% tejamkorlik hosil qilgan qatlamli quvur liniyasi bosqichi `stats:null` qaytaradi va shuning uchun `engineBreakdown` — da o‘tkazib yuborilgan qadamdan farq qilmaydigan ko‘rinmaydi. “Yugurgan, 0%”ni “o‘tkazib yuborilgan”dan farqlash modelni o‘zgartirishni talab qiladi va keyinga qoldiriladi.

## Tasdiqlash

Ushbu hudud uchun yo'naltirilgan eshiklar:

```bash
node --import tsx/esm --test tests/unit/compression/rtk-*.test.ts tests/unit/compression/pipeline-integration.test.ts tests/unit/compression/context-compression-api.test.ts
node --import tsx/esm --test tests/unit/compression/*.test.ts tests/golden-set/*.test.ts tests/integration/compression-pipeline.test.ts tests/unit/api/compression/compression-api.test.ts
node --import tsx/esm --test tests/unit/compression/mcpAccessibility*.test.ts
npm run typecheck:core
```
