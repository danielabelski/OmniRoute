# Compression Engines (Azərbaycan dili)

🌐 **Languages:** 🇺🇸 [English](../../../../compression/COMPRESSION_ENGINES.md) · 🇪🇹 [am](../../../am/docs/compression/COMPRESSION_ENGINES.md) · 🇸🇦 [ar](../../../ar/docs/compression/COMPRESSION_ENGINES.md) · 🇧🇬 [bg](../../../bg/docs/compression/COMPRESSION_ENGINES.md) · 🇧🇩 [bn](../../../bn/docs/compression/COMPRESSION_ENGINES.md) · 🇧🇦 [bs](../../../bs/docs/compression/COMPRESSION_ENGINES.md) · 🇨🇿 [cs](../../../cs/docs/compression/COMPRESSION_ENGINES.md) · 🇩🇰 [da](../../../da/docs/compression/COMPRESSION_ENGINES.md) · 🇩🇪 [de](../../../de/docs/compression/COMPRESSION_ENGINES.md) · 🇬🇷 [el](../../../el/docs/compression/COMPRESSION_ENGINES.md) · 🇪🇸 [es](../../../es/docs/compression/COMPRESSION_ENGINES.md) · 🇪🇪 [et](../../../et/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇷 [fa](../../../fa/docs/compression/COMPRESSION_ENGINES.md) · 🇫🇮 [fi](../../../fi/docs/compression/COMPRESSION_ENGINES.md) · 🇫🇷 [fr](../../../fr/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇪 [ga](../../../ga/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [gu](../../../gu/docs/compression/COMPRESSION_ENGINES.md) · 🇳🇬 [ha](../../../ha/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇱 [he](../../../he/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [hi](../../../hi/docs/compression/COMPRESSION_ENGINES.md) · 🇭🇷 [hr](../../../hr/docs/compression/COMPRESSION_ENGINES.md) · 🇭🇺 [hu](../../../hu/docs/compression/COMPRESSION_ENGINES.md) · 🇦🇲 [hy](../../../hy/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇩 [id](../../../id/docs/compression/COMPRESSION_ENGINES.md) · 🇳🇬 [ig](../../../ig/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇹 [it](../../../it/docs/compression/COMPRESSION_ENGINES.md) · 🇯🇵 [ja](../../../ja/docs/compression/COMPRESSION_ENGINES.md) · 🇬🇪 [ka](../../../ka/docs/compression/COMPRESSION_ENGINES.md) · 🇰🇭 [km](../../../km/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [kn](../../../kn/docs/compression/COMPRESSION_ENGINES.md) · 🇰🇷 [ko](../../../ko/docs/compression/COMPRESSION_ENGINES.md) · 🇱🇹 [lt](../../../lt/docs/compression/COMPRESSION_ENGINES.md) · 🇱🇻 [lv](../../../lv/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [ml](../../../ml/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [mr](../../../mr/docs/compression/COMPRESSION_ENGINES.md) · 🇲🇾 [ms](../../../ms/docs/compression/COMPRESSION_ENGINES.md) · 🇲🇹 [mt](../../../mt/docs/compression/COMPRESSION_ENGINES.md) · 🇲🇲 [my](../../../my/docs/compression/COMPRESSION_ENGINES.md) · 🇳🇵 [ne](../../../ne/docs/compression/COMPRESSION_ENGINES.md) · 🇳🇱 [nl](../../../nl/docs/compression/COMPRESSION_ENGINES.md) · 🇳🇴 [no](../../../no/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [or](../../../or/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [pa](../../../pa/docs/compression/COMPRESSION_ENGINES.md) · 🇵🇭 [phi](../../../phi/docs/compression/COMPRESSION_ENGINES.md) · 🇵🇱 [pl](../../../pl/docs/compression/COMPRESSION_ENGINES.md) · 🇵🇹 [pt](../../../pt/docs/compression/COMPRESSION_ENGINES.md) · 🇧🇷 [pt-BR](../../../pt-BR/docs/compression/COMPRESSION_ENGINES.md) · 🇷🇴 [ro](../../../ro/docs/compression/COMPRESSION_ENGINES.md) · 🇷🇺 [ru](../../../ru/docs/compression/COMPRESSION_ENGINES.md) · 🇱🇰 [si](../../../si/docs/compression/COMPRESSION_ENGINES.md) · 🇸🇰 [sk](../../../sk/docs/compression/COMPRESSION_ENGINES.md) · 🇸🇮 [sl](../../../sl/docs/compression/COMPRESSION_ENGINES.md) · 🇷🇸 [sr](../../../sr/docs/compression/COMPRESSION_ENGINES.md) · 🇸🇪 [sv](../../../sv/docs/compression/COMPRESSION_ENGINES.md) · 🇰🇪 [sw](../../../sw/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [ta](../../../ta/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [te](../../../te/docs/compression/COMPRESSION_ENGINES.md) · 🇹🇭 [th](../../../th/docs/compression/COMPRESSION_ENGINES.md) · 🇹🇷 [tr](../../../tr/docs/compression/COMPRESSION_ENGINES.md) · 🇺🇦 [uk-UA](../../../uk-UA/docs/compression/COMPRESSION_ENGINES.md) · 🇵🇰 [ur](../../../ur/docs/compression/COMPRESSION_ENGINES.md) · 🇺🇿 [uz](../../../uz/docs/compression/COMPRESSION_ENGINES.md) · 🇻🇳 [vi](../../../vi/docs/compression/COMPRESSION_ENGINES.md) · 🇳🇬 [yo](../../../yo/docs/compression/COMPRESSION_ENGINES.md) · 🇨🇳 [zh-CN](../../../zh-CN/docs/compression/COMPRESSION_ENGINES.md) · 🇹🇼 [zh-TW](../../../zh-TW/docs/compression/COMPRESSION_ENGINES.md)

---

OmniRoute sıxılma mühərrik müqavilələri ətrafında qurulur. Rejim birbaşa bir mühərriki (`caveman` və ya `rtk`) və ya bir neçə mühərriki ardıcıllıqla icra edən deterministik yığılmış boru kəmərini işlədə bilər.

## Rejimlər

| Rejim        | Mühərrik yolu                                                                    | Nəzərdə tutulan giriş                          |
| ------------ | -------------------------------------------------------------------------------- | ---------------------------------------------- |
| `off`        | heç biri                                                                         | Dəqiq operativ qorunma                         |
| `lite`       | Caveman lite köməkçiləri                                                         | Aşağı riskli həmişə təmizlik                   |
| `standard`   | Mağara adamı                                                                     | Təbii dildə sürətli kondensasiya               |
| `aggressive` | Caveman + history/tool xülasəsi                                                  | Uzun söhbət seansları                          |
| `ultra`      | Mağara adamı + budama köməkçiləri                                                | Kontekst limitinin bərpası                     |
| `rtk`        | RTK                                                                              | Terminal, shell, build, test və git çıxışı     |
| `omniglyph`  | OmniGlyph                                                                        | Doğma provayder telində şəkil kimi kontekst    |
| `stacked`    | Boru kəməri. Defolt sorğu `session-dedup -> lite` dır. `rtk -> caveman` qoşulur. | Qarışıq alət qeydləri və nəsr, maksimum qənaət |

### OmniGlyph sıxılma profilləri

`omniglyph` mühərriki (paket `omniglyph`, 1.4.0 +) adlandırılmış semantik profili qəbul edir, sıxılma parametrlərində `omniglyph.profile` vasitəsilə qlobal olaraq və ya yığılmış boru kəmərinin addım konfiqurasiyası vasitəsilə hər addım üçün təyin edilir:

| Profil        | Sərhəd                                                                                             |
| ------------- | -------------------------------------------------------------------------------------------------- |
| `aggressive`  | Defolt. Dərc edilmiş qəbzlərin siyasəti — şəkillər sistemini, alət sənədlərini və sıx tarixi ölçdü |
| `balanced`    | Canlı ştatı yerli saxlayır, son 8 dönüşü qoruyur, köhnə qapalı tarixi çökdürür                     |
| `coding-safe` | Səlahiyyət, alət sxemləri və canlı alət çıxışını yerli saxlayır, son 12 dönüşü qoruyur             |
| `passthrough` | Transformasiya edilmədən marşrutlar; mühərrik atılır                                               |

Profil a** tavan, döşəmə deyil** : paketdəki `mergeCompressionProfileOptions` zəng edənin bağlanmış profili itirmiş zolağı yenidən açmasına icazə verməkdən imtina edir, buna görə də hər bir addım `preserveSystemPrompt: false` `coding-safe` altında sistemin sıxılmasını yenidən aktivləşdirə bilməz.

Bu kod bazasında ölçülür: `coding-safe` və `balanced` `minCompressChars` maksimuma qaldırır və sistemi, alət sxemlərini və alət nəticələrini yerli saxlayır, beləliklə, hələ tarix toplamamış sessiya `below_min_chars` -də dayanır və mühərrik heç nəyi dəyişdirmir. Buna görə defolt ən təhlükəsiz profildən çox `aggressive` dir.

Paket ətraf mühit konfiqurasiyasından öz model əhatə dairəsini və profilini həll edir. OmniRoute heç vaxt qərarı həvalə etmir: adapter model qapısını paketin ən məhdudlaşdırıcı əhatə dairəsinə bağlayır, ona görə də host mühitinin parametrləri yalnız icazə verilən siyahını daralda bilər, heç vaxt onu OmniRoute-nin ölçülmüş qəbzlərindən sonra genişləndirə bilməz.

## Mühərrik reyestri

Reyestr `open-sse/services/compression/engines/registry.ts` yaşayır. Mühərriklər ortaq müqaviləni ifşa edir:

- `id`: `caveman` və ya `rtk` kimi sabit mühərrik id
- `apply(text, config)`: yığılmış boru kəmərləri tərəfindən istifadə edilən köhnə icra yolu
- `compress(input, config)`: mətn + statistikasını qaytaran əsas icra yolu
- `getConfigSchema()`: etibarlı konfiqurasiyanın JSON-Sxema kimi formasını qaytarır
- `validateConfig(config)`: `{ valid, errors[] }` qaytarır

Qeydiyyat qəbul etməzdən əvvəl `assertValidEngine()` və `validateConfig(defaultConfig)` çağıran `registerCompressionEngine(engine)` (və ya qabaqcıl hallar üçün `registerEngine` ) istifadə edir. Mühərriki iş vaxtında çıxarmaq üçün `unregisterCompressionEngine(id)` istifadə edin.

`strategySelector.ts` sıxılmadan əvvəl quraşdırılmış mühərrikləri qeyd edir. Bu, önizləmə, iş vaxtının sıxılması, yığılmış rejim, testlər və gələcək mühərriklərə eyni icra yolundan istifadə etməyə imkan verir.

### MCP təsviri sıxılma (əlaqəli)

Ayrı bir reyestr MCP alətinin təsviri metadatasını reyestr səviyyəsində — sıxışdırır, bax `open-sse/mcp-server/descriptionCompressor.ts` və [MCP-SERVER.md](../frameworks/MCP-SERVER.md). O, Caveman qaydalarını təkrar istifadə edir, lakin faydalı yükləri tələb etmir, alət metadatasında işləyir.

### Əlavə quraşdırılmış mühərriklər

Caveman, RTK və LLMLingua-2 dan başqa, reyestr bir neçə ixtisaslaşdırılmış itkisiz/struktur mühərrikləri (yığılmış boru kəmərləri, oyun meydançası və sınaqlar tərəfindən istifadə olunur) göndərir:

| Mühərrik     | İd              | Nə edir                                                                                                                                                                              |
| ------------ | --------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| CCR          | `ccr`           | Content-Compress-Retrieve (H4): böyük bitişik mətn bloklarını məzmun ünvanlı istinadlarla əvəz edir, beləliklə, repeated/large blokları bir dəfə göndərilir və sonra istinad edilir. |
| baş boşluğu  | `headroom`      | SmartCrusher (H3 + N5): homojen JSON massivinin faydalı yüklərinin sütunlu `[N rows]` formasına itkisiz cədvəl şəklində sıxlaşdırılması.                                             |
| ionlaşdırıcı | `ionizer`       | çox böyük homojen bloklar üçün Head/middle/tail sıra seçmə, CCR məzmun ünvanlı arayış kimi örtülmüş ortanı saxlayır.                                                                 |
| sessiya-deup | `session-dedup` | Məzmun ünvanlı çarpaz növbəli təkmilləşdirmə (TokenMizer-dən ilhamlanmış): eyni sessiyanın əvvəlki növbələrində artıq görünən mətni silir.                                           |

**CCR retrieve-protocol təlimatı (#8033):** CCR sorğuda ilk dəfə ≥ 1 blokunu əvəz etdikdə, mühərrik zəng edənə marker → alət müqaviləsini öyrədən tək, idempotent `system` mesajını ( `[CCR protocol]` sentinel ilə aparır) əvvəldən hazırlayır: `[CCR retrieve hash=<24hex> chars=N]` markeri nə deməkdir, heş sözbəsöz kopyalanmalıdır (bütün 24 hexlock simvolu səhv səbəb ola bilər" tapılmadı" səhvləri) və — markerinin `[dedup:ref sha=...]` alətə zəng etmək" deyil, "tarixə nəzər salmaq" mənasını verir. Qeyd enjekte edilir** yalnız zəng edənin elan etdiyi `tools[]` həqiqətən `omniroute_ccr_retrieve` çata biləcəyini sübut etdikdə** (`callerSupportsCcrRetrieve()` in `open-sse/services/compression/engines/ccr/protocolInstruction.ts`) — sadə OpenAI-a uyğun gələn zəng edən, bu aləti olmayan heç vaxt çata bilmədiyi bir şeyə zəng etmək üçün göstəriş almır. Idempotency inyeksiyadan əvvəl gözətçi üçün mesaj tarixçəsini skan etməklə tətbiq edilir, beləliklə, çoxdövrəli sorğular (əvvəlki mesajları təkrarlayan) qeydi hər növbəyə bir dəfə yığmaz.

## Mağara adamı

Caveman rejimi normal nəsrin semantik kondensasiyasına diqqət yetirir:

- kod bloklarını, URLs, JSON, yolları və strukturlaşdırılmış məlumatları qoruyur
- doldurucu, hedcinq, təkrar kontekst və ətraflı birləşdirici ifadələri silir
- `open-sse/services/compression/rules/` da dildən xəbərdar olan fayl qaydaları paketlərini dəstəkləyir
- köhnə `standard`, `aggressive` və `ultra` rejimləri vasitəsilə əlçatan olaraq qalır

Tablosunun səthi `Dashboard -> Context & Cache -> Caveman`.

Caveman upstream `~75%` daha az çıxış tokeni, `22-87%` diapazonu olan etalonlarda `65%` orta çıxış qənaəti və `~46%` giriş-sıxılma aləti haqqında məlumat verir. OmniRoute yığılmış prompt/context qənaətlərini sənədləşdirərkən Caveman giriş tərəfindəki nömrədən istifadə edir; Caveman çıxış rejimi ayrıca cavab-davranış xüsusiyyəti olaraq qalır.

## RTK

RTK rejimi əmr və alət çıxışına diqqət yetirir:

- `git status`, `git branch`, `git diff`, Vitest/Jest/Pytest, Cargo/Go testləri, TypeScript/Vite/Webpack qurmaları, ESLint, npm audit/installs, Docker logs, shell `find`/`grep`, stack traces və generic logs kimi çıxış siniflərini aşkar edir
- `open-sse/services/compression/engines/rtk/filters/` dən 49 JSON filtr tətbiq edir
- RTK tipli deklarativ boru kəmərini dəstəkləyir: ANSI soyulması, dəyişdirilməsi, uyğun çıxış qısaqapanması, strip/keep xətləri, hər sətirdə kəsilmə, head/tail/max-line kəsilməsi və boş geri qaytarma
- `.rtk/filters.json` -da güvənli layihə filtrlərini və `DATA_DIR/rtk/filters.json`-də qlobal filtrləri dəstəkləyir
- zolaqlar ANSI ardıcıllığı, irəliləyiş səs-küyü, təkrarlanan xətlər və faydasız qazan lövhəsi
- təsirli uğursuzluqları, xəbərdarlıqları, xülasələri, dəyişdirilmiş faylları və quyruq kontekstini qoruyur
- isteğe bağlı olaraq təsdiqlənmiş idarəetmə marşrutları vasitəsilə recovery/debugging üçün redaktə edilmiş xam məhsulu saxlaya bilər

Tablosunun səthi `Dashboard -> Context & Cache -> RTK`.

Fərdi filtrlər, etibar, doğrulama və xammalın bərpası üçün əməliyyat təfərrüatları [`RTK_COMPRESSION.md`](./RTK_COMPRESSION.md) -da canlıdır.

RTK upstream, əmr-çıxış sıxışdırması üçün `60-90%` qənaətini bildirir. Onun README nümunəsi `~118,000` tokenlərindən `~23,900` və ya `79.7%` saxlanmasına gedən 30 dəqiqəlik Claude Kod sessiyasını göstərir.

## LLMLingua-2 (Semantik Budama)

LLMLingua-2 rejimi həyata keçirir** semantik işarə budaması** Qayda əsaslı Caveman və RTK mühərriklərini tamamlayan kiçik ONNX token klassifikatorundan istifadə edərək nəsrdə:

- yalnız sistem olmayan mesajlarda nəsri sıxışdırır; hasarlanmış kod blokları və digər qorunan konstruksiyalar heç vaxt dəyişdirilmir
- `@atjsh/llmlingua-2` backendini (ONNX via `@huggingface/transformers`) işçi ipdə işlədir, buna görə də model nəticəsi sorğu hadisəsi dövrəsini heç vaxt bloklamır.
- edir** yığıla bilən** (`stackPriority` 35): yığılmış boru kəmərində o, struktur mühərriklərdən (CCR, session-dedup, headroom, Caveman) sonra, lakin `ultra` əvvəl işləyir, çünki semantik budama artıq struktur olaraq sıxılmış mətn — məsələn, `rtk -> caveman -> llmlingua` üzərində ən effektivdir.
- **hər hansı bir səhvdə uğursuz açılır** (isteğe bağlı deps, işçi kürü, model yükü, nəticə və ya vaxt aşımı yoxdur) → orijinal mətn dəyişdirilmədən qaytarılır, heç vaxt xəta yoxdur

Mühərrik yeri: `open-sse/services/compression/engines/llmlingua/`. Tablosunun səthi `Dashboard -> Context & Cache -> LLMLingua`.

### Modellər

Standart modeldir**TinyBERT** (`atjsh/llmlingua-2-js-tinybert-meetingbank`, ~ 57 MB, sürətli). Daha yüksək dəqiqlik** BERT bazası** model (`Arcoldd/llmlingua4j-bert-base-onnx`, ~ 710 MB) mühərrik konfiqurasiyası `model` sahəsi vasitəsilə mövcuddur. `@huggingface/transformers` seçilmiş modeli tənbəlliklə HuggingFace Hub-dan ilk zəngdə `${DATA_DIR}/models/llmlingua` -a endirir (`modelStore.ts`); `modelPath` konfiqurasiyasının ləğvi onu yerli nüsxədə göstərir (oflayn / hava boşluqlu quraşdırmalar).

### Könüllü asılılıqlar və tələb üzrə quraşdırma

Prunable LLMLingua runtime peer stack edir** isteğe bağlıdır** . İki paket `package.json` -də `optionalDependencies` olaraq elan edilir və saxlanılır** xarici** istehsal quruluşuna görə (`scripts/build/prepublish.ts` onları birləşdirmir):

| Paket                | Versiya (pin) | Qeydlər                                          |
| -------------------- | ------------- | ------------------------------------------------ |
| `@atjsh/llmlingua-2` | `2.0.5`       | Giriş paketi; digərlərini həmyaşıdları elan edir |
| `js-tiktoken`        | `^1.0.20`     | Tokenizer                                        |

`@huggingface/transformers` `^4.2.0` -də bərkidilir (yerli daxiletmə yolu ilə paylaşılır və həmçinin müstəqil paketdə izlənilir); `@atjsh/llmlingua-2@2.0.5` `"^3.5.2 || ^4.0.0"` ilə həmyaşıddır, ona görə də həm Transformers.js v3, həm də v4 dəstəklənir. 2.0.4-dən bəri, `@atjsh/llmlingua-2` artıq `@tensorflow/tfjs` tələb etmir, bu da ən böyük tək iştirakçını (TensorFlow.js) SLM yığınından çıxardı. Yalnız yuxarıdakı iki paket prunable SLM həmyaşıdlarıdır. Standart `npm install` (dev) isteğe bağlı asılılıqlar buraxılmadığı təqdirdə isteğe bağlı yığını avtomatik quraşdırır.

**Niyə tələb üzrə:** npm tərəfindən nəşr olunan paket, müstəqil paket və Docker təsvir gəmisi** olmadan** bu deps incə qalmaq üçün. Onlar olmadıqda, işçinin asılılıq qapısı ( `worker.ts`-də `@atjsh/llmlingua-2` həll zondu) uğursuz olur və mühərrik** uğursuz-səssiz açılır** — seçilməsi LLMLingua qeyri-op olur (mətn dəyişdirilmədən qaytarılır, xəta qeydə alınmır). Onu budanmış mühitdə aktivləşdirmək üçün əlavə yığını quraşdırın:

```bash
# pin to the versions declared in package.json optionalDependencies
npm install @atjsh/llmlingua-2@2.0.5 js-tiktoken
```

`@tensorflow/tfjs` silinməsi (2.0.4 +) əvvəllər dominant olan ~ 800 MB töhfəçini — aradan qaldırır, qalan iz transformers.js + onnxruntime-node işləmə müddətləri, üstəgəl TinyBERT modeli (~ 57 MB) atpm vasitəsilə endirilməmişdir.

Ətraf mühitə görə:

- **Dev / `npm install`** `--omit=optional` (və ya `--no-optional`) keçmədiyiniz halda — avtomatik olaraq quraşdırılır. Fəaliyyətə ehtiyac yoxdur.
- **Qlobal npm (`npm i -g omniroute`) / müstəqil** — quraşdırılmış paket qovluğunda yuxarıdakı quraşdırma əmrini işlədin və ya isteğe bağlı depsləri buraxmadan yenidən quraşdırın.
- **Docker** — əldə edilmiş şəkil qatına quraşdırma əmrini əlavə edin; nəşr olunan təsvir dizayn baxımından incədir.
- **VPS (PM2)** — tətbiqin `node_modules` ə quraşdırın, sonra prosesi yenidən başladın ki, işçi qapını yenidən yoxlasın.
- **Raw Next müstəqil (`npm run build` → `.build/next/standalone/server.js`)** — müstəqil izləmə gəmiləri nə işçiyə, nə də isteğe bağlı deplərə NEITHER, beləliklə mühərrik səssizcə sıradan çıxır. `scripts/build/colocate-standalone.mjs` hər ikisini yenidən tətbiq edir (işçi esbuild + isteğe bağlı-dep bağlanması müstəqil ağaca); hər qurduqdan sonra `postbuild` npm çəngəl vasitəsilə avtomatik işləyir. İdempotent, deps olmadıqda uğursuz-yumşaq.

**Aktiv olduğunu yoxlayın:** LLMLingua seçildikdə, real nəsr əslində kiçilir (mühərrik uğursuz açılışı dayandırır) və ilk sorğu modelin `${DATA_DIR}/models/llmlingua`-ə endirilməsini tetikler. Qapı qəsdən yalnız `@atjsh/llmlingua-2` — yoxlayır, digər həmyaşıdlar yalnız ESM-dir və `require.resolve` hətta mövcud — olduqda belə onlara atır, beləliklə, `import()` vaxtında hər hansı həmyaşıd həqiqətən itibsə, işçi hələ də uğursuz açılır.

## Yığılmış boru kəmərləri

Yığılmış rejim boru kəməri addımlarını ardıcıllıqla icra edir. Varsayılan olaraq:

```txt
rtk -> caveman
```

Bunu, əmr çıxışını insan və ya köməkçi nəsrlə birləşdirdiyi kodlaşdırma-agent seansları üçün istifadə edin. RTK əvvəlcə səs-küylü alət qeydlərini azaldır, sonra Caveman qalan təbii dili sıxır.

Boru kəməri addımları sıxılma parametrlərində və ya sıxılma kombinasiyalarında `stackedPipeline` ilə konfiqurasiya edilir.

Hər iki mühərrik eyni uyğun yükü azaltdıqda, qənaət kompleksi yaranır:

```txt
combined = 1 - (1 - RTK savings) * (1 - Caveman input savings)
average  = 1 - (1 - 0.80) * (1 - 0.46) = 89.2%
range    = 1 - (1 - 0.60..0.90) * (1 - 0.46) = 78.4-94.6%
```

## MCP Əlçatanlıq Ağacı Filtri

MCP accessibility-tree smart filter MCP üzərində işləyən icradan sonrakı sıxılma qatıdır.** alət nəticələri** , göstərişlər və ya kontekstdə deyil. O Playwright, kompüter istifadəsi və brauzer avtomatlaşdırılması MCP serverləri kimi alətlər tərəfindən qaytarılan ətraflı əlçatanlıq ağacını və brauzerin snapshot yüklərini hədəfləyir.

### Nə edir

1. **Səs-küyün çıxarılması** — boş generic/text girişlərini silir (`- generic:`, `- text: ""`)
2. **Qardaşın dağılması** — ≥ `collapseThreshold` (defolt 30) ardıcıl sətirlər struktur təkrarları olduqda, onları ilk `collapseKeepHead` (standart 10) sətirlərə yığır + a count xülasə + sonuncu `collapseKeepTail` (defolt 5) sətirlər
3. **Ref mühafizəsi** Playwright/computer-use tərəfindən tələb olunan — `[ref=eXX]` lövbərlərinə heç vaxt toxunulmur
4. **Sərt kəsmə** — çökdükdən sonra mətn hələ də `maxTextChars` (defolt 50,000) keçirsə, naviqasiya işarəsi ilə kəsilir ki, agent işə davam edə bilsin

### Mühərrikin yeri

```txt
open-sse/services/compression/engines/mcpAccessibility/
  index.ts            ← smartFilterText() entry point
  collapseRepeated.ts ← sibling-collapse algorithm
  constants.ts        ← DEFAULT_MCP_ACCESSIBILITY_CONFIG
```

### Konfiqurasiya

Qlobal parametrlərdə `compression.mcpAccessibility` tərəfindən idarə olunur (miqrasiya 056). Defolt konfiqurasiya:

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

Filtr yalnız `type` `"text"` olan və uzunluğu `minLengthToProcess` çox olan alət-nəticə yüklərinə tətbiq edilir. Bu, tez sıxılmaya və ya tələb yüklərinə təsir etmir.

### Gözlənilən qənaət

Səhifənin mürəkkəbliyindən asılı olaraq brauzer snapshot aləti nəticələrində 60-80%. Dağılma alqoritmi sətir sayında O(n)-dir və əhəmiyyətsiz gecikmə əlavə edir.

### Bu filtr yuxarıdakı sıxılma mühərriklərinə qarşı

| Aspekt         | Mağara adamı / RTK / Yığılmış | MCP əlçatanlıq filtri                  |
| -------------- | ----------------------------- | -------------------------------------- |
| Hədəf          | Sorğu göstərişləri / kontekst | MCP alətinin nəticələri                |
| Tətik          | Sıxılma rejiminin təyini      | `compression.mcpAccessibility.enabled` |
| Əhatə dairəsi  | Bütün SSE mesajları           | Yalnız alət nəticələri                 |
| Ref lövbərləri | N/A                           | Şərtsiz saxlanılır                     |

---

## Sıxılma birləşmələri

Sıxılma kombinləri marşrutlaşdırıcı kombinələrə təyin edilə bilən sıxılma profilləri adlanır:

- `compression_combos`: rejimi, boru xəttini, RTK konfiqurasiyasını, dil konfiqurasiyasını və defolt markeri saxlayır
- `compression_combo_assignments`: sıxılma kombinasiyasını marşrutlaşdırma kombinasiyası ilə əlaqələndirir
- iş vaxtı inteqrasiyası təyin edilmiş sıxılma kombinasiyasını ümumi kombin ləğv etməzdən əvvəl həll edir
- analitikaya `compression_combo_id` və `engine` daxildir

Tablosunun səthi: `Dashboard -> Context & Cache -> Compression Combos`.

## İlkin şərtlər / operator təlimatı (CCR & session-dedup)

CCR (`ccr`) və `session-dedup` mətni əvəz edir və ya silir və tərk edir a** marker** arxada. Bu bölmə müştəriyə naqil çəkmək, iki markeri oxumaq və örtülmüş məzmunu əldə etmək və ya diaqnostika etmək üçün operator istinadıdır. Hər bir mühərrikin mexanikası yuxarıda əhatə olunmuşdur; bu "necə işlədirəm" təbəqəsidir.

### Nəqliyyatlar və son nöqtələr

CCR alətlərini ifşa edən MCP serverinə üç yolla çatmaq olar. Defolt əsas URL `http://localhost:20128` (`OMNIROUTE_BASE_URL`):

| Nəqliyyat                                        | URL / əmr                               | Qeydlər                                                                                                                                                 |
| ------------------------------------------------ | --------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Yayım edilə bilən HTTP (müştəri, tövsiyə olunur) | `http://localhost:20128/api/mcp/stream` | Mövcud MCP müştərilərinin danışdıqları son nöqtə.                                                                                                       |
| Legacy SSE singleton                             | `http://localhost:20128/api/mcp/sse`    | Köhnə singleton nəqliyyatı. Bu** bağlayır** axın edilə bilən seanslar; `streamable-http` müştərilərini `/api/mcp/stream` qarşı istifadə edin, bu deyil. |
| stdio                                            | `omniroute --mcp`                       | Prosesi doğuran IDE MCP konfiqurasiyası üçün. `--dev` bayrağı yoxdur; `omniroute --mcp` stdio giriş nöqtəsidir.                                         |

### Yaddaş səviyyələri (yenidən başladıqdan sonra sağ qalan)

CCR a** iki qatlı** mağaza, yalnız yaddaşda deyil:

- **İsti yaddaşdaxili səviyyə** — hər blok üçün qapaq 2 MiB, hər əsas üzrə 16 MiB, qlobal 64 MiB. Girişlər standart olaraq 24 saat TTL (maksimum 7 gün). Yaddaşdan tam MCP axtarışı 256 KiB ilə məhdudlaşır; Menzilli / grep rejimləri vasitəsilə daha böyük hər hansı bir şey əldə edilə bilər.
- **Davamlı SQLite səviyyəsi** (`ccr_blocks`, `COMPRESSION_CCR_DURABLE_STORE`, defolt olaraq aktivdir) — yaddaşdaxili pilləni dəstəkləyir, beləliklə blok LRU çıxarılmasından, yenidən işə salınmadan və ya başqa nüsxədə bərpa enişindən sağ qalsın. Sətir blokun TTL saxlayır, ona görə də TTL dən keçən blok hər iki səviyyədən ayrılır.

Üç mühafizəçi dayanıqlı səviyyəni məhdudlaşdıran — blokunu yalnız aşağıdakı hallarda yaddaşda saxlayır:

1. blok bitdi** 512 KB** (`MAX_DURABLE_BLOCK_BYTES`);
2. iş vaxtı bulud işləmə vaxtıdır (yerli disk yoxdur);
3. `COMPRESSION_CCR_DURABLE_STORE=false`.

Beləliklə, "blok itdi" ümumi yenidən başladın hekayəsi deyil: yerli, buludsuz işləmə müddətindəki sub-512 KB bloku TTL bitənə qədər dayanıqlı səviyyə vasitəsilə yenidən başlamağa davam edir. Dəyişən üçün [Ətraf Mühit arayışına](../reference/ENVIRONMENT.md) baxın.

### İki marker

| Marker                                | Mənası                                                                                                                                        | Model nə etməlidir                                                                                                                                                                                    |
| ------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| `[CCR retrieve hash=<24hex> chars=N]` | Böyük bir blok məzmun ünvanlı saxlanıldı.                                                                                                     | ilə `omniroute_ccr_retrieve` zəng edin** 24 hex hex hərfi kopyalandı** orijinal mətni geri almaq üçün.                                                                                                |
| `[dedup:ref sha=…]`                   | `session-dedup` elided mətn artıq eyni sessiyanın əvvəlki növbəsində göndərilmişdir. Bu bir** qəsdən geriyə baxmaq** , itki və ya səhv deyil. | Et** yox** istənilən alətə zəng edin və edin** yox** onu "yenidən qurmağa" çalışın. Mətnin ilk təkrarlanması kanonik surətdir; cari növbə heç vaxt yenidən yazılmır, sonrakı döngədə deupsiya edilir. |

Bu `[dedup:ref]` geri baxış qəsdən protokol qərar — heç bir əvvəlcədən göndərmə yenidən qurulması var. Bunu "bu dəqiq mətn bu sessiyada əvvəllər teldə idi" kimi qəbul edin.

### Müştəri ilkin şərtləri

- **Açar (stdio):** stdio zəng edən şəxs hər sorğu üçün şəxsiyyət daşımır, ona görə də o, `OMNIROUTE_API_KEY` ilə autentifikasiya edir ( MCP serverinin `env` də təyin olunur). Onsuz zəng edən şəxs anonimdir və direktor tələb edən alətlər pisləşə bilər.
- **`tools[]` inyeksiya üçün ilkin şərtdir.** CCR retrieve-protocol təlimatı (#8033) yeridilir** yalnız** sorğunun elan edilmiş `tools[]` müştərinin həqiqətən `omniroute_ccr_retrieve` çata biləcəyini sübut etdikdə. Uyğunluq ayırıcı (`__`, `.`, `/`, `:`) ilə məhdudlaşan arxa seqment uyğunluğudur — heç vaxt çılpaq alt sətir — buna görə də `mcp__gateway__omniroute_ccr_retrieve` kimi ad boşluqlu ad hələ də sayılır. Qeyri-uyğun və ya uyğun olmayan `tools[]` o deməkdir ki, təlimat dizayna görə yeridilməyib.
- **`codemode:false` (OpenCode müştəriləri).** OpenCode defolt olaraq Kod Rejiminə uyğun olaraq modelə yalnız yerli alətlərini reklam edir və** etmir** MCP alətlərini yerli `tools[]` siyahısına qoyun. MCP server girişində `codemode: false` təyin edin ki, `omniroute_ccr_*` alətləri reklam olunsun. Bu a** müştəri** qəbulu, bir OmniRoute bir deyil. O, hələ CCR təlimatını daxil etmir: OpenCode aləti `<server>_<tool>` adlandırır, ona görə də `omniroute` adlı server `omniroute_omniroute_ccr_retrieve` ifşa edir və `_` uyğun separatorlardan biri deyil.
- **Direktorlar.** Saxlama və axtarış autentifikasiya edilmiş əsas üzrə ( API açarına görə) təcrid olunur. Açar yalnız öz bloklarını görür.

### Alət üçün əhatə dairəsi

Dar əhatəli HTTP/SSE zəng edənlər üçün əhatə dairəsinin tətbiqi həmişə aktivdir. `omniroute_` CCR alətləri tələb edir:

| Alət                     | Əhatə dairəsi       |
| ------------------------ | ------------------- |
| `omniroute_ccr_store`    | `write:compression` |
| `omniroute_ccr_delete`   | `write:compression` |
| `omniroute_ccr_retrieve` | `read:compression`  |
| `omniroute_ccr_inspect`  | `read:compression`  |
| `omniroute_ccr_list`     | `read:compression`  |
| `omniroute_ccr_stats`    | `read:compression`  |

Çatışmayan əhatə dairəsi a qaytarır**MCP aləti xətası nəticəsi** (`isError: true`, HTTP 403 — deyil, `403 LOCAL_ONLY` ayrıca geri dönmə marşrutu qoruyucu auth-dur): `Error: Insufficient MCP scopes for <tool>. Missing: <scope>.` Minimal uzaqdan idarəetmə açarı `mcp:connect` (yalnız `/api/mcp/` yerli kəsilməsinə icazə verir) və ona lazım olan xüsusi read/write əhatəsini saxlaya bilər.

### Müştəri matrisi

| Müştəri           | Nəqliyyat                              | İstifadə etmək üçün konfiqurasiya                                                                                                                                                                                                                        | `tools[]` reklam olunur? (→ CCR təlimatı yeridildi)                                                                                                                                             |
| ----------------- | -------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Claude kodu       | axın edilə bilən-http                  | `claude mcp add --transport http omniroute http://localhost:20128/api/mcp/stream`                                                                                                                                                                        | Bəli — MCP qabiliyyəti; enjekte edilir.                                                                                                                                                         |
| Cursor / Cline    | `stdio`** və ya** `streamable-http`    | stdio: `env` ilə `OMNIROUTE_API_KEY` ilə `omniroute --mcp` ; və ya `http://localhost:20128/api/mcp/stream` yə işarə edən uzaq MCP girişi (bax. [Quraşdırma Bələdçisi → MCP Müştəri Konfiqurasiyası](../guides/SETUP_GUIDE.md#mcp-client-configuration) ) | Bəli — `omniroute_ccr_*` alətlərini reklam edin.                                                                                                                                                |
| OpenCode          | axın edilə bilən-http                  | `opencode mcp add omniroute --url http://localhost:20128/api/mcp/stream`, plus `codemode: false`                                                                                                                                                         | Yalnız `codemode: false` ilə reklam edilən alətlər; təlimat hələ də yeridilməyib, çünki `omniroute_omniroute_ccr_retrieve` uyğun gəlmir (bax [Müştəri ilkin şərtləri](#client-prerequisites) ). |
| OpenAI-a uyğundur | OpenAI uyğun HTTP (chat tamamlamaları) | OpenAI uyğun son nöqtəyə qarşı standart söhbət tamamlama müştərisi                                                                                                                                                                                       | **Heç vaxt** — adi OpenAI-a uyğun gələn zəng edənə heç vaxt alətə zəng etmək deyilmir və təlimat vurulmur.                                                                                      |

### Axtarış limitləri və səhifələşdirmə

MCP alətinin mətn nəticələri `mcpAccessibility.maxTextChars` ətrafında kəsilir (defolt `50000`). Blokun `full` axtarışı 256 KiB — ilə məhdudlaşır** heç bir məhdudiyyətsiz tam bərpa yoxdur** . Blokun `chars=N` böyük olduqda, hər şeyi çəkmək əvəzinə onu səhifələyin:

- Əsas qayda:**`chars > 40000` → `mode` istifadə edin** , heç vaxt çılpaq dolu.
- `mode:"grep"` — regex `pattern` sətir-sətir, 1000-ə qədər uyğun sətir (`unique: true` düşmə təkrarlanır), "lazım olan bir xətti tap" üçün ən ucuzdur.
- `mode:"lines"` — 1 indeksli xətt diapazonu; həm `start`, həm də `end` lazımdır.
- `mode:"head"` / `mode:"tail"` — first/last `n` xətləri.
- `mode:"stats"` — sətri, simvolu və bayt sayları gövdəsiz.

Hər şeyi bir anda tələb etməkdənsə, səhifələrdə uzun bir blok gəzmək üçün `start`/`end` ilə `mode:"lines"` istifadə edin.

### Alətin adlandırılması

Axtarış aləti hazırda `omniroute_ccr_retrieve` adlanır ( `omniroute_` prefiksi serverlər arası adların toqquşması üçün tarixi keçmiş həll yoludur). Daha təmiz məhdudlaşdırılmış şəkilçi alət adı və MCP JSON nəticələri üçün düzəliş, kəsilmiş orta sətir yuxarı axın izləmələri kimi izlənilir; bu səhifə yalnız cari, göndərilmiş davranışı sənədləşdirir.

### Sessiyanın həyat dövrü

Streamable-HTTP seansları boş qalır və server onları yığır; boş pəncərə `MCP_SESSION_IDLE_MS` sabitidir (sabit kodlaşdırılmış dəyər deyil, adla istinad edilir, ona görə də bu səhifə dəyişdikdə sürüşmür). Boş qalan sessiyanın simptomu `Unknown Mcp-Session-Id` — ilə HTTP 404-dür, çarə sessiyanı yenidən qoşmaq və ya yenidən başlatmaqdır,** yox** düyməni fırlatmaq, əhatə dairəsini dəyişdirmək və ya alətin adını dəyişmək üçün.

## API Səthi

| Marşrut                                | Məqsəd                                                                     |
| -------------------------------------- | -------------------------------------------------------------------------- |
| `/api/settings/compression`            | Qlobal sıxılma parametrləri ( `mcpAccessibility` konfiqurasiyası daxildir) |
| `/api/compression/preview`             | İstənilən sıxılma rejiminə baxın                                           |
| `/api/compression/language-packs`      | Mövcud Caveman dil paketlərini sadalayın                                   |
| `/api/context/caveman/config`          | Caveman parametrləri ləqəbi                                                |
| `/api/context/rtk/config`              | RTK defoltları və parametrləri                                             |
| `/api/context/rtk/filters`             | RTK filtr kataloqu                                                         |
| `/api/context/rtk/test`                | RTK preview/test son nöqtəsi                                               |
| `/api/context/rtk/raw-output/[id]`     | Təsdiqlənmiş redaktə edilmiş xam-çıxış bərpası                             |
| `/api/context/combos`                  | Kompress CRUD                                                              |
| `/api/context/combos/[id]/assignments` | Marşrutlaşdırma-kombo təyinatı CRUD                                        |
| `/api/context/analytics`               | Sıxılma analitik ləqəbi                                                    |

İdarəetmə marşrutları idarəetmə identifikasiyası və ya API açarı siyasətinin yoxlanılmasını tələb edir.

## MCP Alətləri

Sıxılma beş MCP alətini ifşa edir:

| Alət                                | Əhatə dairəsi       | Məqsəd                                   |
| ----------------------------------- | ------------------- | ---------------------------------------- |
| `omniroute_compression_status`      | `read:compression`  | Parametrlər, analitika, keş statistikası |
| `omniroute_compression_configure`   | `write:compression` | Qlobal parametrləri yeniləyin            |
| `omniroute_set_compression_engine`  | `write:compression` | Rejimi və əlavə boru kəmərini təyin edin |
| `omniroute_list_compression_combos` | `read:compression`  | Sıxılma kombinlərinin siyahısı           |
| `omniroute_compression_combo_stats` | `read:compression`  | combo/engine analitikasını oxuyun        |

## Əhatə dairəsi və istisnalar

**Yerləşdirmələr heç vaxt sıxılmır.** `open-sse/handlers/embeddings.ts` heç vaxt heç bir sıxılma mühərriki — çağırmır request/response gövdələri toxunulmamış birbaşa icraçıya keçir. Bu, bu gün strukturdur (yerləşdirilmələr və söhbət tamamlamaları ayrı-ayrı idarəçilərdir), iş vaxtının yoxlanışı deyil, lakin bu o deməkdir ki #8034 -də vektor təhrif probleminin yerləşdirmə yolunda heç bir məruz qalma səthi yoxdur.

**Per-model/endpoint istisna filtri (#8034).** Söhbətin tamamlanması üçün operator heç vaxt sıxılmamalı model identifikatorlarını / `provider/model` hədəflərini adlandıra bilər. — sıxılma sonradan əlavələr üçün bitişik yola daha da yaxınlaşdıqda faydalı olan qoruyucu və ümumiyyətlə bayt üçün dəqiq məlumat tələb edən hər hansı model üçün faydalıdır (deterministik qiymətləndirmələr, keş-həssas prefikslər və s.).

- Parametrlər sahəsi: qlobal sıxılma konfiqurasiyasında `exclusions?: string[]` (`GET`/`PUT /api/settings/compression`), mövcud `key_value` sıxılma ad məkanı (`src/lib/db/compression.ts`) vasitəsilə davam etdi — yeni cədvəl yoxdur.
- İdarə paneli nişanı:** Dashboard → Compression → İstisnalar** (`/dashboard/compression/exclusions`).
- Nümunə sintaksisi: `*` yeganə joker simvoldur. Nümunədəki hər bir digər regex metaxarakteri uyğunlaşmadan əvvəl qaçır, ona görə də `gpt-5.6` yalnız hərfi sətirlə uyğun gəlir, heç vaxt `gpt-5x6` deyil (ReDoS-təhlükəsiz, məhdud, iç-içə kəmiyyət göstəriciləri yoxdur). Nümunələr həm çılpaq model id-si, həm də `provider/model` kompozit — `gpt-5-6`, `openai/gpt-5-6` və `openai/*` ilə böyük hərf-həssas olmayan şəkildə uyğunlaşır və hamısı işləyir və tək `*` hər modeli istisna edir.
- Uyğunluq: `isCompressionExcluded()` / `normalizeCompressionExclusions()` in `open-sse/services/compression/exclusions.ts`. `chatCore.ts` sıxılma parametrlərini həll etdikdən dərhal sonra xaric edilmiş hədəfi yoxlayır,** hər hansı bir mühərrik işləməzdən əvvəl** , və uyğunluğu tam olaraq qlobal miqyasda deaktiv edilmiş sıxılma kimi rəftar edir — sorğu orqanının bayt-eynidir. Analitikanın görünməsi üçün keçid `writeCompressionSkip(..., "excluded")` vasitəsilə qeydə alınır.
- Defolt (empty/absent siyahısı):#8034 dən əvvəlki davranışla eynidir, — heç nə istisna edilmir.

## Məlum məhdudiyyətlər

- **LLMLingua-2 (SLM) birgə yerləşdirilmiş isteğe bağlı deps tələb edir.** İşçi yalnız `@atjsh/llmlingua-2` + həmyaşıdları `dist/node_modules` -də birgə yerləşdikdə istehsal quruluşunda işləyir (bax: `scripts/build/colocateOptionals.mjs`, #4286). Onlar olmadan mühərrik uğursuz olur (orijinal mətni qaytarır). İşçinin həlli artıq cwd / `argv[1]` işləmə müddətində lövbər etdiyi `import.meta.url` — (müstəqil paketdə ölür) asılı deyil.
- **Caveman dil paketləri `de` / `fr` / `ja` qisməndir.** Onlar `context` + `filler` + `structural` qaydaları göndərirlər, lakin `dedup` / `ultra` paketləri yoxdur, buna görə də `ultra` intensivliyi həmin dillər üçün `full` -dən güclü deyil (onlar yalnız öz qaydalarından istifadə edirlər — İngilis dili `dedup`/`ultra` qaydalarına səssiz geri dönmə yoxdur, bu da xarici mətni pozar). `en` / `es` / `id` / `pt-BR` tamamlandı. Qismən paketlər üçün `dedup.json` + `ultra.json` töhfələri qəbul edilir.
- **Yığılmış telemetriya yalnız sıxılmış mühərrikləri siyahıya alır.** Mühərriki işləyən, lakin 0% qənaət hasil edən yığılmış boru kəməri addımı `stats:null` qaytarır və beləliklə `engineBreakdown` — atlanan addımdan fərqlənə bilməyəcək şəkildə görünmür. "Qaçdı, 0 %"ni "atlandı"dan fərqləndirmək parçalanma modelinin dəyişdirilməsini tələb edir və təxirə salınır.

## Doğrulama

Bu sahə üçün diqqət mərkəzində olan qapılar:

```bash
node --import tsx/esm --test tests/unit/compression/rtk-*.test.ts tests/unit/compression/pipeline-integration.test.ts tests/unit/compression/context-compression-api.test.ts
node --import tsx/esm --test tests/unit/compression/*.test.ts tests/golden-set/*.test.ts tests/integration/compression-pipeline.test.ts tests/unit/api/compression/compression-api.test.ts
node --import tsx/esm --test tests/unit/compression/mcpAccessibility*.test.ts
npm run typecheck:core
```
