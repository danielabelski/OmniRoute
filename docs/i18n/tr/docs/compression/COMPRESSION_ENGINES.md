# Compression Engines (Türkçe)

🌐 **Languages:** 🇺🇸 [English](../../../../compression/COMPRESSION_ENGINES.md) · 🇪🇹 [am](../../../am/docs/compression/COMPRESSION_ENGINES.md) · 🇸🇦 [ar](../../../ar/docs/compression/COMPRESSION_ENGINES.md) · 🇦🇿 [az](../../../az/docs/compression/COMPRESSION_ENGINES.md) · 🇧🇬 [bg](../../../bg/docs/compression/COMPRESSION_ENGINES.md) · 🇧🇩 [bn](../../../bn/docs/compression/COMPRESSION_ENGINES.md) · 🇧🇦 [bs](../../../bs/docs/compression/COMPRESSION_ENGINES.md) · 🇨🇿 [cs](../../../cs/docs/compression/COMPRESSION_ENGINES.md) · 🇩🇰 [da](../../../da/docs/compression/COMPRESSION_ENGINES.md) · 🇩🇪 [de](../../../de/docs/compression/COMPRESSION_ENGINES.md) · 🇬🇷 [el](../../../el/docs/compression/COMPRESSION_ENGINES.md) · 🇪🇸 [es](../../../es/docs/compression/COMPRESSION_ENGINES.md) · 🇪🇪 [et](../../../et/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇷 [fa](../../../fa/docs/compression/COMPRESSION_ENGINES.md) · 🇫🇮 [fi](../../../fi/docs/compression/COMPRESSION_ENGINES.md) · 🇫🇷 [fr](../../../fr/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇪 [ga](../../../ga/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [gu](../../../gu/docs/compression/COMPRESSION_ENGINES.md) · 🇳🇬 [ha](../../../ha/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇱 [he](../../../he/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [hi](../../../hi/docs/compression/COMPRESSION_ENGINES.md) · 🇭🇷 [hr](../../../hr/docs/compression/COMPRESSION_ENGINES.md) · 🇭🇺 [hu](../../../hu/docs/compression/COMPRESSION_ENGINES.md) · 🇦🇲 [hy](../../../hy/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇩 [id](../../../id/docs/compression/COMPRESSION_ENGINES.md) · 🇳🇬 [ig](../../../ig/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇹 [it](../../../it/docs/compression/COMPRESSION_ENGINES.md) · 🇯🇵 [ja](../../../ja/docs/compression/COMPRESSION_ENGINES.md) · 🇬🇪 [ka](../../../ka/docs/compression/COMPRESSION_ENGINES.md) · 🇰🇭 [km](../../../km/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [kn](../../../kn/docs/compression/COMPRESSION_ENGINES.md) · 🇰🇷 [ko](../../../ko/docs/compression/COMPRESSION_ENGINES.md) · 🇱🇹 [lt](../../../lt/docs/compression/COMPRESSION_ENGINES.md) · 🇱🇻 [lv](../../../lv/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [ml](../../../ml/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [mr](../../../mr/docs/compression/COMPRESSION_ENGINES.md) · 🇲🇾 [ms](../../../ms/docs/compression/COMPRESSION_ENGINES.md) · 🇲🇹 [mt](../../../mt/docs/compression/COMPRESSION_ENGINES.md) · 🇲🇲 [my](../../../my/docs/compression/COMPRESSION_ENGINES.md) · 🇳🇵 [ne](../../../ne/docs/compression/COMPRESSION_ENGINES.md) · 🇳🇱 [nl](../../../nl/docs/compression/COMPRESSION_ENGINES.md) · 🇳🇴 [no](../../../no/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [or](../../../or/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [pa](../../../pa/docs/compression/COMPRESSION_ENGINES.md) · 🇵🇭 [phi](../../../phi/docs/compression/COMPRESSION_ENGINES.md) · 🇵🇱 [pl](../../../pl/docs/compression/COMPRESSION_ENGINES.md) · 🇵🇹 [pt](../../../pt/docs/compression/COMPRESSION_ENGINES.md) · 🇧🇷 [pt-BR](../../../pt-BR/docs/compression/COMPRESSION_ENGINES.md) · 🇷🇴 [ro](../../../ro/docs/compression/COMPRESSION_ENGINES.md) · 🇷🇺 [ru](../../../ru/docs/compression/COMPRESSION_ENGINES.md) · 🇱🇰 [si](../../../si/docs/compression/COMPRESSION_ENGINES.md) · 🇸🇰 [sk](../../../sk/docs/compression/COMPRESSION_ENGINES.md) · 🇸🇮 [sl](../../../sl/docs/compression/COMPRESSION_ENGINES.md) · 🇷🇸 [sr](../../../sr/docs/compression/COMPRESSION_ENGINES.md) · 🇸🇪 [sv](../../../sv/docs/compression/COMPRESSION_ENGINES.md) · 🇰🇪 [sw](../../../sw/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [ta](../../../ta/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [te](../../../te/docs/compression/COMPRESSION_ENGINES.md) · 🇹🇭 [th](../../../th/docs/compression/COMPRESSION_ENGINES.md) · 🇺🇦 [uk-UA](../../../uk-UA/docs/compression/COMPRESSION_ENGINES.md) · 🇵🇰 [ur](../../../ur/docs/compression/COMPRESSION_ENGINES.md) · 🇺🇿 [uz](../../../uz/docs/compression/COMPRESSION_ENGINES.md) · 🇻🇳 [vi](../../../vi/docs/compression/COMPRESSION_ENGINES.md) · 🇳🇬 [yo](../../../yo/docs/compression/COMPRESSION_ENGINES.md) · 🇨🇳 [zh-CN](../../../zh-CN/docs/compression/COMPRESSION_ENGINES.md) · 🇹🇼 [zh-TW](../../../zh-TW/docs/compression/COMPRESSION_ENGINES.md)

---

OmniRoute sıkıştırması motor sözleşmeleri etrafında oluşturulmuştur. Bir mod, bir motoru doğrudan (`caveman` veya `rtk`) çalıştırabilir veya birden fazla motoru sırayla çalıştıran deterministik yığılmış bir hattı çalıştırabilir.

## Modlar

| Mod          | Motor yolu                                                                                 | Amaçlanan giriş                                       |
| ------------ | ------------------------------------------------------------------------------------------ | ----------------------------------------------------- |
| `off`        | hiçbiri                                                                                    | Tam anında koruma                                     |
| `lite`       | Mağara adamı lite yardımcıları                                                             | Düşük riskli her zaman açık temizleme                 |
| `standard`   | Mağara adamı                                                                               | Doğal dilde hızlı yoğunlaştırma                       |
| `aggressive` | Caveman + history/tool özetleyiciler                                                       | Uzun sohbet oturumları                                |
| `ultra`      | Mağara adamı + budama yardımcıları                                                         | Bağlam sınırı kurtarma                                |
| `rtk`        | RTK                                                                                        | Terminal, kabuk, derleme, test ve git çıktısı         |
| `omniglyph`  | OmniGlyph                                                                                  | Yerel sağlayıcı kablosunda görüntü olarak bağlam      |
| `stacked`    | Boru hattı. İsteğin varsayılanı `session-dedup -> lite`. `rtk -> caveman` isteğe bağlıdır. | Karışık araç günlükleri ve düzyazı, maksimum tasarruf |

### OmniGlyph sıkıştırma profilleri

`omniglyph` motoru (paket `omniglyph`, 1.4.0 +), sıkıştırma ayarlarında `omniglyph.profile` aracılığıyla genel olarak veya yığılmış ardışık düzenin adım yapılandırmasında adım başına ayarlanan adlandırılmış bir anlamsal profili kabul eder:

| Profil        | Sınır                                                                                                   |
| ------------- | ------------------------------------------------------------------------------------------------------- |
| `aggressive`  | Varsayılan. Yayınlanan makbuzların ölçüldüğü politika — görüntü sistemi, araç belgeleri ve yoğun geçmiş |
| `balanced`    | Canlı durumu yerel tutar, son 8 dönüşü korur, eski kapalı geçmişi daraltır                              |
| `coding-safe` | Yetkiyi, araç şemalarını ve canlı araç çıktısını yerel tutar, son 12 dönüşü korur                       |
| `passthrough` | Dönüştürülmeden rotalar; motor atlandı                                                                  |

Profil bir** zemin değil tavan** : Paketteki `mergeCompressionProfileOptions` arayan kişinin profilin kapalı olduğu kayıplı bir şeridi yeniden açmasını geçersiz kılmayı reddeder, dolayısıyla adım başına `preserveSystemPrompt: false` `coding-safe` altında sistem sıkıştırmasını yeniden etkinleştiremez.

Bu kod temelinde ölçülür: `coding-safe` ve `balanced` `minCompressChars` maksimuma çıkarır ve sistemi, araç şemalarını ve araç sonuçlarını yerel tutar; böylece geçmişi biriktirmemiş bir oturum henüz `below_min_chars` durur ve motor hiçbir şeyi dönüştürmez. Bu nedenle varsayılan profil en güvenli profil yerine `aggressive`.

Paket, kendi model kapsamını ve profilini ortam yapılandırmasından çözer. OmniRoute asla kararı devretmez: bağdaştırıcı, model kapısını paketin en kısıtlayıcı kapsamına sabitler, böylece ana bilgisayar ortamı ayarları izin verilenler listesini yalnızca daraltabilir, asla OmniRoute ölçülen alımlarını aşacak şekilde genişletemez.

## Motor Kaydı

Kayıt defteri `open-sse/services/compression/engines/registry.ts` yaşıyor. Motorlar paylaşılan bir sözleşmeyi ortaya çıkarır:

- `id`: `caveman` veya `rtk` gibi kararlı motor kimliği
- `apply(text, config)`: yığılmış işlem hatları tarafından kullanılan eski yürütme yolu
- `compress(input, config)`: metin + istatistiklerini döndüren birincil yürütme yolu
- `getConfigSchema()`: geçerli yapılandırmanın JSON Şeması benzeri şeklini döndürür
- `validateConfig(config)`: `{ valid, errors[] }` döndürür

Kayıt, kabul etmeden önce `assertValidEngine()` ve `validateConfig(defaultConfig)` çağıran `registerCompressionEngine(engine)` (veya gelişmiş durumlar için `registerEngine` ) kullanır. Çalışma zamanında bir motoru kaldırmak için `unregisterCompressionEngine(id)` kullanın.

`strategySelector.ts` sıkıştırma çalıştırılmadan önce yerleşik motorları kaydeder. Bu, önizlemenin, çalışma zamanı sıkıştırmasının, yığın modunun, testlerin ve gelecekteki motorların aynı yürütme yolunu kullanmasına olanak tanır.

### MCP açıklama sıkıştırması (ilgili)

Ayrı bir kayıt defteri, MCP aracı açıklama meta verilerini kayıt defteri düzeyinde sıkıştırır — (bkz. `open-sse/mcp-server/descriptionCompressor.ts` ve [MCP-SERVER.md](../frameworks/MCP-SERVER.md). Caveman kurallarını yeniden kullanır ancak talep yükleri yerine araç meta verileri üzerinde çalışır.

### Ek yerleşik motorlar

Caveman, RTK ve LLMLingua-2 ötesinde, kayıt defteri birkaç özel kayıpsız/yapısal motor (yığılmış boru hatları, oyun alanı ve testler tarafından kullanılır) gönderir:

| Motor                  | İD              | Ne işe yarar                                                                                                                                                                      |
| ---------------------- | --------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| CCR                    | `ccr`           | İçerik Sıkıştırma-Alma (H4): büyük bitişik metin bloklarını içerik adresli referanslarla değiştirir, böylece repeated/large blokları bir kez gönderilir ve daha sonra başvurulur. |
| boşluk payı            | `headroom`      | SmartCrusher (H3 + N5): homojen JSON dizisi yüklerinin sütunlu bir `[N rows]` formuna kayıpsız tablo halinde sıkıştırılması.                                                      |
| iyonlaştırıcı          | `ionizer`       | Çok büyük homojen bloklar için Head/middle/tail satır örneklemesi, atlanan ortayı CCR içerik adresli bir referans olarak saklar.                                                  |
| oturum tekilleştirildi | `session-dedup` | İçerik adresli çapraz dönüş tekilleştirme (TokenMizer'dan ilham alınmıştır): aynı oturumun önceki dönüşlerinde zaten görülen metni ortadan kaldırır.                              |

**CCR alma protokolü talimatı (#8033):** CCR bir istekte ≥ 1 bloğunun yerini ilk aldığında, motor arayana işaretleyici → aracı sözleşmesini öğreten tek, bağımsız `system` mesajı ( `[CCR protocol]` sentinel ile başlayan) hazırlar: bir `[CCR retrieve hash=<24hex> chars=N]` işaretleyicinin ne anlama geldiğini, hash'in kelimesi kelimesine kopyalanması gerektiğini ( — yanlış kopyalanan 24 hex karakterin tümü, "blok bulunamadı" hatalarının olası nedenidir) ve bir `[dedup:ref sha=...]` işaretleyicisinin şu anlama geldiğini gösterir: "Aracı çağır" değil, "geçmişe bakın". Not enjekte edildi** yalnızca arayanın reklamı yapılan `tools[]` gerçekten `omniroute_ccr_retrieve` ulaşabileceğini kanıtladığında** (`callerSupportsCcrRetrieve()` `open-sse/services/compression/engines/ccr/protocolInstruction.ts`) — Bu araca sahip olmayan, OpenAI uyumlu bir arayan asla ulaşamayacağı bir şeyi arama talimatı almaz. Idempotency, enjekte etmeden önce sentinel için mesaj geçmişinin taranmasıyla uygulanır, bu nedenle çok turlu istekler (önceki mesajları tekrarlayan) notu her turda bir kez istiflemez.

## Mağara adamı

Mağara Adamı modu normal düzyazının anlamsal yoğunlaştırılmasına odaklanır:

- kod bloklarını, URLs, JSON, yolları ve yapılandırılmış verileri korur
- dolguyu, korunmayı, tekrarlanan bağlamı ve ayrıntılı bağlayıcı ifadeleri ortadan kaldırır
- `open-sse/services/compression/rules/` dile duyarlı dosya kural paketlerini destekler
- eski `standard`, `aggressive` ve `ultra` modları aracılığıyla kullanılabilir olmaya devam eder

Gösterge paneli yüzeyi `Dashboard -> Context & Cache -> Caveman`.

Caveman upstream, `~75%` daha az çıkış tokenı, `22-87%` aralığına sahip kıyaslamalarda `65%` ortalama çıktı tasarrufu ve bir `~46%` giriş sıkıştırma aracı rapor ediyor. OmniRoute yığılmış prompt/context tasarruflarını belgelendirirken Caveman giriş tarafı numarasını kullanır; Mağara Adamı çıkış modu ayrı bir tepki-davranış özelliği olmaya devam ediyor.

## RTK

RTK modu komut ve araç çıktısına odaklanır:

- `git status`, `git branch`, `git diff`, Vitest/Jest/Pytest, Cargo/Go testleri, TypeScript/Vite/Webpack yapıları, ESLint, npm audit/installs, Docker günlükleri, kabuk `find`/`grep`, yığın izlemeleri ve genel günlükler gibi çıktı sınıflarını algılar
- `open-sse/services/compression/engines/rtk/filters/` 49 JSON filtresi uygular
- RTK tarzı bildirimsel boru hattını destekler: ANSI çıkarma, değiştirme, çıkış kısa devresini eşleştirme, strip/keep hatları, hat başına kesme, head/tail/max-line kesme ve boş durumda geri dönüş
- `.rtk/filters.json` güven kapılı proje filtrelerini ve `DATA_DIR/rtk/filters.json` global filtreleri destekler
- ANSI dizilerini, ilerleme gürültüsünü, tekrarlanan satırları ve yardımcı olmayan standart metinleri çıkarır
- eyleme geçirilebilir arızaları, uyarıları, özetleri, değiştirilen dosyaları ve kuyruk içeriğini korur
- isteğe bağlı olarak kimliği doğrulanmış yönetim yolları aracılığıyla recovery/debugging için düzenlenmiş ham çıktıyı koruyabilir

Gösterge paneli yüzeyi `Dashboard -> Context & Cache -> RTK`.

Özel filtreler, güven, doğrulama ve ham çıktı kurtarmaya ilişkin operasyonel ayrıntılar [`RTK_COMPRESSION.md`](./RTK_COMPRESSION.md) yayında.

RTK upstream, komut çıkışı sıkıştırması için `60-90%` tasarrufunu bildirir. README örneği, `~118,000` belirteçlerinden `~23,900` veya kaydedilen `79.7%` giden 30 dakikalık bir Claude Code oturumunu gösterir.

## LLMLingua-2 (Anlamsal Budama)

LLMLingua-2 modu gerçekleştirir** anlamsal belirteç budama** kural tabanlı Caveman ve RTK motorlarını tamamlayan küçük bir ONNX belirteç sınıflandırıcı kullanarak düzyazı üzerinde:

- düzyazıyı yalnızca sistem dışı mesajlarda sıkıştırır; çitlerle çevrili kod blokları ve diğer korunmuş yapılar asla değiştirilmez
- `@atjsh/llmlingua-2` arka ucunu (ONNX aracılığıyla `@huggingface/transformers`) bir çalışan iş parçacığında çalıştırır, böylece model çıkarımı hiçbir zaman istek olayı döngüsünü engellemez
- öyle** istiflenebilir** (`stackPriority` 35): yığılmış bir ardışık düzende yapısal motorlardan sonra (CCR, oturum-dedup, headroom, Caveman) sonra ancak `ultra` önce çalışır, çünkü anlamsal budama zaten yapısal olarak sıkıştırılmış metin — üzerinde en etkilidir, örneğin `rtk -> caveman -> llmlingua`
- **herhangi bir hata durumunda başarısız olarak açılır** (isteğe bağlı derinlikler, çalışanların ortaya çıkışı, model yükü, çıkarım veya zaman aşımı eksik) → orijinal metin değişmeden döndürülür, hiçbir zaman hata olmaz

Motor konumu: `open-sse/services/compression/engines/llmlingua/`. Gösterge paneli yüzeyi `Dashboard -> Context & Cache -> LLMLingua`.

### Modeller

Varsayılan model**TinyBERT** (`atjsh/llmlingua-2-js-tinybert-meetingbank`, ~ 57 MB, hızlı). Daha yüksek doğruluk** BERT tabanı** model (`Arcoldd/llmlingua4j-bert-base-onnx`, ~ 710 MB), motor yapılandırması `model` alanı aracılığıyla kullanılabilir. `@huggingface/transformers` seçilen modeli ilk çağrıda (`modelStore.ts`) yavaş bir şekilde HuggingFace Hub'dan `${DATA_DIR}/models/llmlingua` indirir; `modelPath` yapılandırma geçersiz kılma, bunun yerine yerel bir kopyaya işaret eder (çevrimdışı / hava boşluklu kurulumlar).

### İsteğe bağlı bağımlılıklar ve isteğe bağlı yükleme

Budanabilir LLMLingua çalışma zamanı eş yığını:** isteğe bağlı** . İki paket `package.json` `optionalDependencies` olarak bildirilir ve saklanır** harici** üretim yapısına göre (`scripts/build/prepublish.ts` bunları paketlemez):

| Paket                | Sürüm (pin) | Notlar                                           |
| -------------------- | ----------- | ------------------------------------------------ |
| `@atjsh/llmlingua-2` | `2.0.5`     | Giriş paketi; diğerlerini akran olarak ilan eder |
| `js-tiktoken`        | `^1.0.20`   | Tokenlaştırıcı                                   |

`@huggingface/transformers` `^4.2.0` sabitlenir (yerel yerleştirme yoluyla paylaşılır ve ayrıca bağımsız pakette de izlenir); `@atjsh/llmlingua-2@2.0.5`, `"^3.5.2 || ^4.0.0"` ile eşleştiğinden hem Transformers.js v3 hem de v4 desteklenir. 2.0.4'ten bu yana, `@atjsh/llmlingua-2` artık `@tensorflow/tfjs` ihtiyaç duymuyor, bu da SLM yığınından en büyük tek katkıyı (TensorFlow.js) kaldırıyor. Yalnızca yukarıdaki iki paket budanabilir SLM eşleridir. Standart bir `npm install` (dev), isteğe bağlı bağımlılıklar atlanmadığı sürece isteğe bağlı yığını otomatik olarak yükler.

**Neden isteğe bağlı:** npm tarafından yayınlanan paket, bağımsız paket ve Docker görüntü gönderimi** olmadan** bu derinlikler ince kalmak için. Bunlar olmadığında, çalışanın bağımlılık kapısı ( `worker.ts` içindeki `@atjsh/llmlingua-2` çözümleme probu) başarısız olur ve motor** başarısızlıkla sessizce açılır** — LLMLingua seçmesi işlem dışı hale gelir (metin değiştirilmeden döndürülür, günlüğe hata kaydedilmez). Budanmış bir ortamda etkinleştirmek için isteğe bağlı yığını yükleyin:

```bash
# pin to the versions declared in package.json optionalDependencies
npm install @atjsh/llmlingua-2@2.0.5 js-tiktoken
```

`@tensorflow/tfjs` kaldırılması (2.0.4 +), önceden baskın olan ~ 800 MB katılımcısını ortadan kaldırır — kalan ayak izi, transformers.js + onnxruntime-node çalışma zamanları artı ilk kullanımda indirilen TinyBERT modelidir (~ 57 MB) (npm aracılığıyla değil).

Ortam başına:

- **Dev / `npm install`** `--omit=optional` (veya `--no-optional`) geçmediğiniz sürece — otomatik olarak yüklenir. Hiçbir eyleme gerek yok.
- **Küresel npm (`npm i -g omniroute`) / bağımsız** — kurulu paket dizininde yukarıdaki install komutunu çalıştırın veya isteğe bağlı deps'i atlamadan yeniden yükleyin.
- **Docker** — türetilmiş bir görüntü katmanına install komutunu ekleyin; yayınlanan görsel tasarım gereği ince bir şekilde gönderilir.
- **VPS (PM2)** — uygulamanın `node_modules` yükleyin, ardından çalışanın kapıyı yeniden araştırması için süreci yeniden başlatın.
- **Raw Sonraki bağımsız (`npm run build` → `.build/next/standalone/server.js`)** bağımsız izleme NEITHER veya isteğe bağlı depolara —, böylece motor sessizce arızalanır. `scripts/build/colocate-standalone.mjs` her ikisini de yeniden uygular (worker esbuild + isteğe bağlı derin kapatmayı bağımsız ağaca); her yapıdan sonra `postbuild` npm kancası aracılığıyla otomatik olarak çalışır. Idempotent, derinlikler olmadığında başarısız.

**Etkin olduğunu doğrulayın:** LLMLingua seçildiğinde, gerçek düzyazı aslında küçülür (motor arızalı açılmayı durdurur) ve ilk istek, modelin `${DATA_DIR}/models/llmlingua` indirilmesini tetikler. Kapı kasıtlı olarak yalnızca `@atjsh/llmlingua-2` — araştırır, diğer eşler yalnızca ESM'dir ve `require.resolve`, — mevcutken bile onlara atar, böylece `import()` zamanında herhangi bir eş gerçekten eksikse çalışan hala arızalı olarak açılır.

## Yığılmış Boru Hatları

Yığılmış mod, işlem hattı adımlarını sırayla çalıştırır. Varsayılan:

```txt
rtk -> caveman
```

Bir istemin komut çıktısını insan veya yardımcı düzyazıyla birleştirdiği kodlama aracısı oturumları için bunu kullanın. RTK önce gürültülü araç günlüklerini azaltır, ardından Caveman kalan doğal dili sıkıştırır.

İşlem hattı adımları, sıkıştırma ayarlarında `stackedPipeline` ile veya sıkıştırma kombinasyonları aracılığıyla yapılandırılır.

Her iki motor da aynı uygun taşıma yükünü azalttığında tasarruflar artar:

```txt
combined = 1 - (1 - RTK savings) * (1 - Caveman input savings)
average  = 1 - (1 - 0.80) * (1 - 0.46) = 89.2%
range    = 1 - (1 - 0.60..0.90) * (1 - 0.46) = 78.4-94.6%
```

## MCP Erişilebilirlik Ağacı Filtresi

MCP erişilebilirlik ağacı akıllı filtresi, MCP üzerinde çalışan bir yürütme sonrası sıkıştırma katmanıdır** araç sonuçları** , istemlerde veya bağlamda değil. Playwright, bilgisayar kullanımı ve tarayıcı otomasyonu MCP sunucuları gibi araçlar tarafından döndürülen ayrıntılı erişilebilirlik ağacını ve tarayıcı anlık görüntüsü verilerini hedefler.

### Ne işe yarar

1. **Gürültü sıyırma** — boş generic/text girişlerini kaldırır (`- generic:`, `- text: ""`)
2. **Kardeş çöküşü** — ≥ `collapseThreshold` (varsayılan 30) ardışık satırlar yapısal tekrarlar olduğunda, bunları ilk `collapseKeepHead` (varsayılan 10) satıra daraltır + bir sayım özeti + son `collapseKeepTail` (varsayılan 5) satır
3. **Referans koruması** Playwright/computer-use gerektirdiği — `[ref=eXX]` çapalarına hiçbir zaman dokunulmaz
4. **Sert kesme** — daraltıldıktan sonra metin hala `maxTextChars` (varsayılan 50.000) aşıyorsa, aracının çalışmaya devam edebilmesi için bir gezinme ipucuyla kesilir

### Motor konumu

```txt
open-sse/services/compression/engines/mcpAccessibility/
  index.ts            ← smartFilterText() entry point
  collapseRepeated.ts ← sibling-collapse algorithm
  constants.ts        ← DEFAULT_MCP_ACCESSIBILITY_CONFIG
```

### Yapılandırma

Küresel ayarlarda `compression.mcpAccessibility` tarafından kontrol edilir (geçiş 056). Varsayılan yapılandırma:

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

Filtre yalnızca `type` `"text"` olan ve uzunluğu `minLengthToProcess` aşan araç sonuç veri yüklerine uygulanır. Anında sıkıştırmayı veya talep yüklerini etkilemez.

### Beklenen tasarruf

Sayfa karmaşıklığına bağlı olarak tarayıcı anlık görüntü aracı sonuçlarında %60-80. Çökme algoritması satır sayısında O(n)'dir ve ihmal edilebilir bir gecikme ekler.

### Bu filtre yukarıdaki sıkıştırma motorlarına karşı

| Bakış açısı       | Mağara Adamı / RTK / Yığılmış | MCP erişilebilirlik filtresi           |
| ----------------- | ----------------------------- | -------------------------------------- |
| Hedef             | Talep istemleri/bağlam        | MCP aracı sonuçları                    |
| Tetiklemek        | Sıkıştırma modu ayarı         | `compression.mcpAccessibility.enabled` |
| Kapsam            | Tüm SSE mesajları             | Yalnızca araç sonuçları                |
| Referans çapaları | N/A                           | Koşulsuz olarak korunur                |

---

## Sıkıştırma Kombinasyonları

Sıkıştırma kombinasyonları, yönlendirme kombinasyonlarına atanabilen sıkıştırma profilleri olarak adlandırılır:

- `compression_combos`: modu, boru hattını, RTK yapılandırmasını, dil yapılandırmasını ve varsayılan işaretçiyi depolar
- `compression_combo_assignments`: bir sıkıştırma birleşimini bir yönlendirme birleşimine eşler
- çalışma zamanı entegrasyonu, genel birleşik geçersiz kılmadan önce atanmış bir sıkıştırma birleşimini çözer
- analizler `compression_combo_id` ve `engine` içerir

Kontrol paneli yüzeyi: `Dashboard -> Context & Cache -> Compression Combos`.

## Önkoşullar / operatör kılavuzu (CCR ve oturum tekilleştirme)

CCR (`ccr`) ve `session-dedup` metni değiştirin veya silin ve bir** işaretleyici** arka. Bu bölüm, istemcinin kablolarını bağlamak, iki işaretçiyi okumak ve atlanan içeriği almak veya teşhis etmek için operatör referansıdır. Her motorun mekaniği yukarıda ele alınmıştır; bu "nasıl çalıştırırım" katmanıdır.

### Taşımalar ve uç noktalar

CCR araçlarını kullanıma sunan MCP sunucusuna üç yoldan ulaşılabilir. Varsayılan URL tabanı `http://localhost:20128` (`OMNIROUTE_BASE_URL`):

| Taşıma                                    | URL / komut                             | Notlar                                                                                                                                         |
| ----------------------------------------- | --------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------- |
| Akış yapılabilir HTTP (istemci, önerilir) | `http://localhost:20128/api/mcp/stream` | Mevcut MCP istemcilerinin konuştuğu uç nokta.                                                                                                  |
| Eski SSE singleton                        | `http://localhost:20128/api/mcp/sse`    | Daha eski tekil taşıma. BT** kapatır** yayınlanabilir oturumlar; `streamable-http` istemcilerini `/api/mcp/stream` karşı kullanın, buna değil. |
| stdio                                     | `omniroute --mcp`                       | Süreci başlatan IDE MCP yapılandırması için. `--dev` bayrağı yok; `omniroute --mcp` stdio giriş noktasıdır.                                    |

### Depolama katmanları (yeniden başlatmadan sonra hayatta kalanlar)

CCR bir** iki katmanlı** mağaza, yalnızca bellekte değil:

- **Sıcak bellek içi katman** — blok başına üst sınır 2 MiB, anapara başına 16 MiB, global 64 MiB. Girişler varsayılan olarak 24 saatlik TTL (maksimum 7 gün). Bellekten tam MCP alımı 256 KiB ile sınırlıdır; ranged / grep modları aracılığıyla daha büyük herhangi bir şeye hala ulaşılabilir.
- **Dayanıklı SQLite katmanı** (`ccr_blocks`, `COMPRESSION_CCR_DURABLE_STORE`, varsayılan olarak açık) — bellek içi katmanı destekler, böylece bir blok LRU çıkarma, yeniden başlatma veya başka bir örneğe geri alma inişinden sonra hayatta kalır. Satır bloğun TTL korur, dolayısıyla TTL değerini aşan bir blok her iki katmandan da çıkarılır.

Üç koruma, dayanıklı katman sınırlı — aşağıdaki durumlarda bir bloğun yalnızca bellekte kalmasını sağlar:

1. blok bitti** 512 KB** (`MAX_DURABLE_BLOCK_BYTES`);
2. çalışma zamanı bir bulut çalışma zamanıdır (yerel disk yoktur);
3. `COMPRESSION_CCR_DURABLE_STORE=false`.

Yani "blok ortadan kayboldu" genel bir yeniden başlatma hikayesi değil: Yerel, bulut olmayan bir çalışma zamanındaki bir sub-512 KB bloğu, TTL bitene kadar dayanıklı katman aracılığıyla yeniden başlatmadan sağ çıkar. Değişken için [Ortam referansına](../reference/ENVIRONMENT.md) bakın.

### İki işaretleyici

| işaretleyici                          | Anlam                                                                                                                                                     | Modelin ne yapması gerektiği                                                                                                                                                                                                      |
| ------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| `[CCR retrieve hash=<24hex> chars=N]` | İçerik adresli olarak büyük bir blok depolandı.                                                                                                           | `omniroute_ccr_retrieve` şu numarayla arayın:** 24-hex karma kelimesi kelimesine kopyalandı** Orijinal metni geri almak için.                                                                                                     |
| `[dedup:ref sha=…]`                   | `session-dedup` aynı oturumun daha önceki bir aşamasında zaten gönderilmiş olan metni atladı. Bu bir** kasıtlı geriye bakma** bir kayıp ya da hata değil. | Yapmak** Olumsuz** herhangi bir aracı arayın ve yapın** Olumsuz** onu "yeniden inşa etmeye" çalışın. Metnin ilk geçtiği yer kanonik kopyadır; mevcut sıra hiçbir zaman yeniden yazılmaz, daha sonraki bir sırada tekilleştirilir. |

`[dedup:ref]` geriye dönük incelemesi kasıtlı bir protokol kararıdır — gönderme öncesi yeniden yapılanma yoktur. Bunu "bu tam metin zaten bu oturumun başlarında telgrafta mevcuttu" olarak değerlendirin.

### Müşteri önkoşulları

- **Anahtar (stdio):** stdio arayan, istek başına kimlik taşımaz, bu nedenle `OMNIROUTE_API_KEY` ile kimlik doğrulaması yapar ( MCP sunucusunun `env` dosyasında ayarlanır). Bu olmadan, arayan kişi anonimdir ve bir anapara gerektiren araçlar bozulabilir.
- **`tools[]` enjeksiyonun önkoşuludur.** CCR alma protokolü talimatı (#8033) enjekte edilir** sadece** isteğin tanıtılan `tools[]` müşterinin gerçekten `omniroute_ccr_retrieve` ulaşabileceğini kanıtladığında. Eşleşme, bir ayırıcıyla (`__`, `.`, `/`, `:`) sınırlanan bir takip eden bölüm eşleşmesidir — hiçbir zaman çıplak bir — alt dizisi değildir, bu nedenle `mcp__gateway__omniroute_ccr_retrieve` gibi ad alanlı bir ad yine de sayılır. Eksik veya eşleşmeyen bir `tools[]` talimatın tasarım gereği enjekte edilmediği anlamına gelir.
- **`codemode:false` (OpenCode istemcileri).** OpenCode varsayılan olarak yalnızca kendi yerel araçlarını modele tanıtan Kod Moduna sahiptir ve** değil** MCP araçlarını yerel `tools[]` listesine yerleştirin. `omniroute_ccr_*` araçlarının tanıtılması için MCP sunucusu girişinde `codemode: false` ayarlayın. Bu bir** müşteri** ayar, OmniRoute ayarı değil. Henüz CCR komutunu enjekte etmiyor: OpenCode `<server>_<tool>` aracını adlandırıyor, dolayısıyla `omniroute` adlı bir sunucu `omniroute_omniroute_ccr_retrieve` ortaya çıkarıyor ve `_` eşleşen ayırıcılardan biri değil.
- **Müdürler.** Depolama ve alma, kimliği doğrulanmış prensip başına ( API anahtarı başına) izole edilmiştir. Bir anahtar yalnızca kendi bloklarını görür.

### Araç başına kapsamlar

Kapsam yaptırımı, dar kapsamlı HTTP/SSE arayanları için her zaman açıktır. `omniroute_` CCR araçları şunları gerektirir:

| Alet                     | Kapsam              |
| ------------------------ | ------------------- |
| `omniroute_ccr_store`    | `write:compression` |
| `omniroute_ccr_delete`   | `write:compression` |
| `omniroute_ccr_retrieve` | `read:compression`  |
| `omniroute_ccr_inspect`  | `read:compression`  |
| `omniroute_ccr_list`     | `read:compression`  |
| `omniroute_ccr_stats`    | `read:compression`  |

Eksik bir kapsam şunu döndürür:**MCP aracı hatası sonucu** (`isError: true`, HTTP 403 — değil, `403 LOCAL_ONLY` ayrı bir geridöngü rota koruma kimlik doğrulamasıdır): `Error: Insufficient MCP scopes for <tool>. Missing: <scope>.` Minimal bir uzaktan anahtar, `mcp:connect` (yalnızca yerel `/api/mcp/` ayrıştırılmasına izin verir) artı ihtiyaç duyduğu belirli read/write kapsamını tutabilir.

### Müşteri matrisi

| Müşteri        | Taşıma                                    | Kullanılacak yapılandırma                                                                                                                                                                                                                        | `tools[]` reklamı yapıldı mı? (→ CCR talimatı enjekte edildi)                                                                                                                                   |
| -------------- | ----------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Claude Kodu    | yayınlanabilir-http                       | `claude mcp add --transport http omniroute http://localhost:20128/api/mcp/stream`                                                                                                                                                                | Evet — MCP özellikli; enjekte edildi.                                                                                                                                                           |
| Cursor / Cline | `stdio`** veya** `streamable-http`        | stdio: `env` `OMNIROUTE_API_KEY` ile `omniroute --mcp` ; veya `http://localhost:20128/api/mcp/stream` işaret eden uzak bir MCP girişi (bkz. [Kurulum Kılavuzu → MCP İstemci Yapılandırması](../guides/SETUP_GUIDE.md#mcp-client-configuration) ) | Evet — `omniroute_ccr_*` araçlarının reklamını yapıyor.                                                                                                                                         |
| OpenCode       | yayınlanabilir-http                       | `opencode mcp add omniroute --url http://localhost:20128/api/mcp/stream` artı `codemode: false`                                                                                                                                                  | Yalnızca `codemode: false` ile reklamı yapılan araçlar; `omniroute_omniroute_ccr_retrieve` eşleşmediğinden talimat hala enjekte edilmiyor (bkz. [İstemci önkoşulları](#client-prerequisites) ). |
| OpenAI uyumlu  | OpenAI uyumlu HTTP (sohbet tamamlamaları) | OpenAI uyumlu uç noktaya karşı standart sohbet tamamlama istemcisi                                                                                                                                                                               | **Asla** — Düz bir OpenAI uyumlu arayana asla aracı çağırması söylenmez ve talimat enjekte edilmez.                                                                                             |

### Alma sınırları ve sayfalandırma

MCP aracı metni sonuçları `mcpAccessibility.maxTextChars` (varsayılan `50000`) çevresinde kırpılır. Bir bloğun `full` alımı 256 KiB — ile sınırlıdır** sınırsız tam alma yoktur** . Bir bloğun `chars=N` büyük olduğunda, tamamını çekmek yerine onu sayfalayın:

- Temel kural:**`chars > 40000` → `mode` kullanın** , asla tamamen dolu değil.
- `mode:"grep"` — regex `pattern` satır satır eşleşti, 1.000'e kadar eşleşen satır (`unique: true` damla tekrarları), "ihtiyacım olan tek satırı bul" için en ucuzu.
- `mode:"lines"` — 1 dizinli bir satır aralığı; hem `start` hem de `end` ihtiyacı var.
- `mode:"head"` / `mode:"tail"` — first/last `n` satırları.
- `mode:"stats"` — gövde olmadan satır, karakter ve bayt sayıları.

Her şeyi bir kerede istemek yerine sayfalar halinde uzun bir blok yürümek için `start`/`end` ile `mode:"lines"` kullanın.

### Araç adlandırma

Geri alma aracı şu anda `omniroute_ccr_retrieve` olarak adlandırılıyor ( `omniroute_` öneki, sunucular arası ad çakışmaları için tarihli bir geçici çözümdür). Daha temiz bir sınırlı son ek aracı adı ve dizenin ortasında kesilmiş MCP JSON sonuçları için bir düzeltme, yukarı akış takipleri olarak izlenir; bu sayfa yalnızca geçerli, sevk edilen davranışı belgelemektedir.

### Oturum yaşam döngüsü

Yayınlanabilir HTTP oturumları boşta kalır ve sunucu bunları toplar; boş pencere `MCP_SESSION_IDLE_MS` sabitidir (kodlanmış bir değer değil, adla başvurulur, bu nedenle bu sayfa değiştiğinde kaymaz). Boşta toplanan bir oturumun belirtisi, `Unknown Mcp-Session-Id` — bir HTTP 404'tür, bunun çaresi oturumu yeniden bağlamak veya yeniden başlatmaktır,** Olumsuz** Bir anahtarı döndürmek, kapsamı değiştirmek veya bir aracı yeniden adlandırmak için.

## API Yüzey

| Rota                                   | Amaç                                                                    |
| -------------------------------------- | ----------------------------------------------------------------------- |
| `/api/settings/compression`            | Genel sıkıştırma ayarları ( `mcpAccessibility` yapılandırmasını içerir) |
| `/api/compression/preview`             | Herhangi bir sıkıştırma modunu önizleyin                                |
| `/api/compression/language-packs`      | Mevcut Caveman dil paketlerini listeleyin                               |
| `/api/context/caveman/config`          | Mağara adamı ayarları takma adı                                         |
| `/api/context/rtk/config`              | RTK varsayılanları ve ayarları                                          |
| `/api/context/rtk/filters`             | RTK filtre kataloğu                                                     |
| `/api/context/rtk/test`                | RTK preview/test uç noktası                                             |
| `/api/context/rtk/raw-output/[id]`     | Kimliği doğrulanmış, düzenlenmiş ham çıktı kurtarma                     |
| `/api/context/combos`                  | Sıkıştırma kombinasyonu CRUD                                            |
| `/api/context/combos/[id]/assignments` | Yönlendirme-birleşik atama CRUD                                         |
| `/api/context/analytics`               | Sıkıştırma analitiği takma adı                                          |

Yönetim yolları, yönetim kimlik doğrulaması veya API anahtarı ilkesi kontrolleri gerektirir.

## MCP Araçları

Sıkıştırma beş MCP aracını ortaya çıkarır:

| Alet                                | Kapsam              | Amaç                                        |
| ----------------------------------- | ------------------- | ------------------------------------------- |
| `omniroute_compression_status`      | `read:compression`  | Ayarlar, analizler, önbellek istatistikleri |
| `omniroute_compression_configure`   | `write:compression` | Genel ayarları güncelle                     |
| `omniroute_set_compression_engine`  | `write:compression` | Modu ve isteğe bağlı boru hattını ayarlayın |
| `omniroute_list_compression_combos` | `read:compression`  | Sıkıştırma kombinasyonlarını listeleyin     |
| `omniroute_compression_combo_stats` | `read:compression`  | combo/engine analitiğini okuyun             |

## Kapsam ve istisnalar

**Gömmeler hiçbir zaman sıkıştırılmaz.** `open-sse/handlers/embeddings.ts` hiçbir zaman herhangi bir sıkıştırma motorunu — çağırmaz, request/response gövdeleri dokunulmadan doğrudan uygulayıcıya geçer. Bu günümüzde yapısaldır (yerleştirmeler ve sohbet tamamlamaları ayrık işleyicilerdir), bir çalışma zamanı kontrolü değildir, ancak #8034 vektör distorsiyon sorununun yerleştirme yolunda herhangi bir maruz kalma yüzeyi olmadığı anlamına gelir.

**Per-model/endpoint hariç tutma filtresi (#8034).** Sohbet tamamlamaları için bir operatör, hiçbir zaman sıkıştırılmaması gereken model kimliklerini / `provider/model` hedeflerini adlandırabilir — sıkıştırmanın daha sonra gömmelere bitişik bir yola daha yakın bir şekilde bağlanması durumunda faydalı bir koruma duvarıdır ve genellikle bayt başına bayt isteminin önemli olduğu herhangi bir model için kullanışlıdır (deterministik değerlendirmeler, önbelleğe duyarlı önekler, vb.).

- Ayarlar alanı: genel sıkıştırma yapılandırmasındaki `exclusions?: string[]` (`GET`/`PUT /api/settings/compression`), mevcut `key_value` sıkıştırma ad alanı (`src/lib/db/compression.ts`) aracılığıyla sürdürüldü — yeni tablo yok.
- Kontrol paneli sekmesi:** Kontrol Paneli → Sıkıştırma → Hariç Tutulanlar** (`/dashboard/compression/exclusions`).
- Desen sözdizimi: `*` tek joker karakterdir. Bir modeldeki diğer tüm normal ifade meta karakterlerinin tümü eşleşmeden önce çıkarılır, bu nedenle `gpt-5.6` yalnızca gerçek dizeyle eşleşir, asla `gpt-5x6` ile eşleşmez (ReDoS açısından güvenli, sınırlı, iç içe niceleyici yok). Desenler, hem çıplak model kimliğine hem de `provider/model` bileşiği — `gpt-5-6`, `openai/gpt-5-6` ve `openai/*` karşı büyük/küçük harfe duyarlı olmadan eşleşir ve `*` tek başına her modeli hariç tutar.
- Eşleştirme: `open-sse/services/compression/exclusions.ts` `isCompressionExcluded()` / `normalizeCompressionExclusions()`. `chatCore.ts` sıkıştırma ayarlarını çözdükten hemen sonra hariç tutulan hedefi kontrol eder,** herhangi bir motor çalışmadan önce** ve istek gövdesinin baytla aynı olduğu kanıtlanabildiği —, bir eşleşmeye tam olarak sıkıştırmanın genel olarak devre dışı bırakılması gibi davranır. Atlama, analitik görünürlüğü için `writeCompressionSkip(..., "excluded")` aracılığıyla kaydedilir.
- Varsayılan (empty/absent listesi):#8034 öncesi davranışla aynıdır — hiçbir şey hariç tutulmaz.

## Bilinen sınırlamalar

- **LLMLingua-2 (SLM), aynı yerde bulunan isteğe bağlı depoları gerektirir.** İşçi yalnızca `@atjsh/llmlingua-2` + eşleri `dist/node_modules` aynı yerde bulunduğunda bir üretim yapısında çalışır (bkz. `scripts/build/colocateOptionals.mjs`, #4286). Bunlar olmadan motor arızalanır (orijinal metni döndürür). Çalışan çözünürlüğü artık `import.meta.url` bağlı değildir (bağımsız pakette ölür) — çalışma zamanı cwd / `argv[1]` bağlanır.
- **Mağara adamı dil paketleri `de` / `fr` / `ja` kısmidir.** `context` + `filler` + `structural` kuralları gönderirler ancak `dedup` / `ultra` paketleri yoktur, dolayısıyla `ultra` yoğunluğu bu diller için `full` daha güçlü değildir (yalnızca kendi kurallarını kullanırlar —, yabancı metni karıştırabilecek İngilizce `dedup`/`ultra` kurallarına sessiz bir geri dönüş yoktur). `en` / `es` / `id` / `pt-BR` tamamlandı. Kısmi paketler için `dedup.json` + `ultra.json` katkıları memnuniyetle karşılanır.
- **Yığılmış telemetri yalnızca sıkıştırılmış motorları listeler.** Motoru çalışan ancak %0 tasarruf sağlayan yığılmış boru hattı adımı `stats:null` ve bu nedenle `engineBreakdown` — atlanan bir adımdan ayırt edilemeyecek şekilde görünmez. "Çalıştırıldı, %0" ile "atlandı" ifadesinin ayırt edilmesi, döküm modeli değişikliği gerektirir ve ertelenir.

## Doğrulama

Bu alan için odaklanmış kapılar şunlardır:

```bash
node --import tsx/esm --test tests/unit/compression/rtk-*.test.ts tests/unit/compression/pipeline-integration.test.ts tests/unit/compression/context-compression-api.test.ts
node --import tsx/esm --test tests/unit/compression/*.test.ts tests/golden-set/*.test.ts tests/integration/compression-pipeline.test.ts tests/unit/api/compression/compression-api.test.ts
node --import tsx/esm --test tests/unit/compression/mcpAccessibility*.test.ts
npm run typecheck:core
```
