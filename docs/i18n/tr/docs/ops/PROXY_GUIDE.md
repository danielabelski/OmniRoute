# 🌐 OmniRoute Proxy Guide (Türkçe)

🌐 **Languages:** 🇺🇸 [English](../../../../ops/PROXY_GUIDE.md) · 🇪🇹 [am](../../../am/docs/ops/PROXY_GUIDE.md) · 🇸🇦 [ar](../../../ar/docs/ops/PROXY_GUIDE.md) · 🇦🇿 [az](../../../az/docs/ops/PROXY_GUIDE.md) · 🇧🇬 [bg](../../../bg/docs/ops/PROXY_GUIDE.md) · 🇧🇩 [bn](../../../bn/docs/ops/PROXY_GUIDE.md) · 🇧🇦 [bs](../../../bs/docs/ops/PROXY_GUIDE.md) · 🇨🇿 [cs](../../../cs/docs/ops/PROXY_GUIDE.md) · 🇩🇰 [da](../../../da/docs/ops/PROXY_GUIDE.md) · 🇩🇪 [de](../../../de/docs/ops/PROXY_GUIDE.md) · 🇬🇷 [el](../../../el/docs/ops/PROXY_GUIDE.md) · 🇪🇸 [es](../../../es/docs/ops/PROXY_GUIDE.md) · 🇪🇪 [et](../../../et/docs/ops/PROXY_GUIDE.md) · 🇮🇷 [fa](../../../fa/docs/ops/PROXY_GUIDE.md) · 🇫🇮 [fi](../../../fi/docs/ops/PROXY_GUIDE.md) · 🇫🇷 [fr](../../../fr/docs/ops/PROXY_GUIDE.md) · 🇮🇪 [ga](../../../ga/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [gu](../../../gu/docs/ops/PROXY_GUIDE.md) · 🇳🇬 [ha](../../../ha/docs/ops/PROXY_GUIDE.md) · 🇮🇱 [he](../../../he/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [hi](../../../hi/docs/ops/PROXY_GUIDE.md) · 🇭🇷 [hr](../../../hr/docs/ops/PROXY_GUIDE.md) · 🇭🇺 [hu](../../../hu/docs/ops/PROXY_GUIDE.md) · 🇦🇲 [hy](../../../hy/docs/ops/PROXY_GUIDE.md) · 🇮🇩 [id](../../../id/docs/ops/PROXY_GUIDE.md) · 🇳🇬 [ig](../../../ig/docs/ops/PROXY_GUIDE.md) · 🇮🇹 [it](../../../it/docs/ops/PROXY_GUIDE.md) · 🇯🇵 [ja](../../../ja/docs/ops/PROXY_GUIDE.md) · 🇬🇪 [ka](../../../ka/docs/ops/PROXY_GUIDE.md) · 🇰🇭 [km](../../../km/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [kn](../../../kn/docs/ops/PROXY_GUIDE.md) · 🇰🇷 [ko](../../../ko/docs/ops/PROXY_GUIDE.md) · 🇱🇹 [lt](../../../lt/docs/ops/PROXY_GUIDE.md) · 🇱🇻 [lv](../../../lv/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [ml](../../../ml/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [mr](../../../mr/docs/ops/PROXY_GUIDE.md) · 🇲🇾 [ms](../../../ms/docs/ops/PROXY_GUIDE.md) · 🇲🇹 [mt](../../../mt/docs/ops/PROXY_GUIDE.md) · 🇲🇲 [my](../../../my/docs/ops/PROXY_GUIDE.md) · 🇳🇵 [ne](../../../ne/docs/ops/PROXY_GUIDE.md) · 🇳🇱 [nl](../../../nl/docs/ops/PROXY_GUIDE.md) · 🇳🇴 [no](../../../no/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [or](../../../or/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [pa](../../../pa/docs/ops/PROXY_GUIDE.md) · 🇵🇭 [phi](../../../phi/docs/ops/PROXY_GUIDE.md) · 🇵🇱 [pl](../../../pl/docs/ops/PROXY_GUIDE.md) · 🇵🇹 [pt](../../../pt/docs/ops/PROXY_GUIDE.md) · 🇧🇷 [pt-BR](../../../pt-BR/docs/ops/PROXY_GUIDE.md) · 🇷🇴 [ro](../../../ro/docs/ops/PROXY_GUIDE.md) · 🇷🇺 [ru](../../../ru/docs/ops/PROXY_GUIDE.md) · 🇱🇰 [si](../../../si/docs/ops/PROXY_GUIDE.md) · 🇸🇰 [sk](../../../sk/docs/ops/PROXY_GUIDE.md) · 🇸🇮 [sl](../../../sl/docs/ops/PROXY_GUIDE.md) · 🇷🇸 [sr](../../../sr/docs/ops/PROXY_GUIDE.md) · 🇸🇪 [sv](../../../sv/docs/ops/PROXY_GUIDE.md) · 🇰🇪 [sw](../../../sw/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [ta](../../../ta/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [te](../../../te/docs/ops/PROXY_GUIDE.md) · 🇹🇭 [th](../../../th/docs/ops/PROXY_GUIDE.md) · 🇺🇦 [uk-UA](../../../uk-UA/docs/ops/PROXY_GUIDE.md) · 🇵🇰 [ur](../../../ur/docs/ops/PROXY_GUIDE.md) · 🇺🇿 [uz](../../../uz/docs/ops/PROXY_GUIDE.md) · 🇻🇳 [vi](../../../vi/docs/ops/PROXY_GUIDE.md) · 🇳🇬 [yo](../../../yo/docs/ops/PROXY_GUIDE.md) · 🇨🇳 [zh-CN](../../../zh-CN/docs/ops/PROXY_GUIDE.md) · 🇹🇼 [zh-TW](../../../zh-TW/docs/ops/PROXY_GUIDE.md)

---

> **Sıfır yapılandırma karmaşıklığıyla coğrafi blokları aşın, kimliğinizi koruyun ve AI trafiğini herhangi bir proxy — üzerinden yönlendirin.**

OmniRoute yukarı akışlı AI sağlayıcı trafiğini HTTP, HTTPS veya SOCKS5 proxy'leri aracılığıyla yönlendirmenize olanak tanıyan tam özellikli bir proxy yönetim sistemi içerir. İster engellenmiş bir bölgede olun, ister IP rotasyonuna ihtiyacınız olsun, ister gizli — parmak izi almak isteyin, bu kılavuz her şeyi kapsar.

---

## İçindekiler

- [Neden Proxy Kullanmalı?](#why-use-proxies)
- [Mimariye Genel Bakış](#architecture-overview)
- [4 Seviyeli Proxy Sistemi](#4-level-proxy-system)
- [Vekil Kayıt Defteri (CRUD)](#proxy-registry-crud)
- [1proxy Ücretsiz Pazar Yeri](#1proxy-free-proxy-marketplace)
- [Vekalet Rotasyonu](#proxy-rotation)
- [Algılanma Önleme ve Gizlilik](#anti-detection--stealth)
- [Yukarı Akış Proxy Modları](#upstream-proxy-modes)
- [Kontrol paneli UI](#dashboard-ui)
- [API Referansı](#api-reference)
- [Ortam Değişkenleri](#environment-variables)
- [Sorun giderme](#troubleshooting)

---

## Neden Proxy Kullanmalı?

Birçok AI sağlayıcısı erişimi coğrafi bölgeye göre kısıtlıyor. Geliştiriciler** Rusya, Çin, İran, Küba, Türkiye** ve diğer ülkeler aşağıdaki gibi hatalarla karşılaşıyor:

```
unsupported_country_region_territory
```

Engellenen bölgelerin dışında bile proxy'ler aşağıdakiler için faydalıdır:

| Kullanım Örneği    | Tanım                                                             |
| ------------------ | ----------------------------------------------------------------- |
| **Coğrafi bypass** | Engellenen ülkelerden OpenAI, Anthropic, Codex, Copilot erişin    |
| **IP rotasyonu**   | Hız sınırlamasını önlemek için istekleri birden fazla IPs dağıtın |
| **Mahremiyet**     | Gerçek IP yukarı akış sağlayıcılarından gizleyin                  |
| **Uyumluluk**      | Trafiği belirli yetki alanları üzerinden yönlendirin              |
| **Test**           | Farklı bölgelerden gelen istekleri simüle edin                    |

---

## Mimariye Genel Bakış

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

### Anahtar Bileşenler

| Bileşen             | Dosya                                        | Rol                                                                 |
| ------------------- | -------------------------------------------- | ------------------------------------------------------------------- |
| **Vekil Kaydı**     | `src/lib/db/proxies.ts`                      | proxy girişleri için CRUD + kapsam atamaları                        |
| **Vekil Gönderici** | `open-sse/utils/proxyDispatcher.ts`          | Önbelleğe alma ile `undici` ProxyAgent/SOCKS dağıtıcıları oluşturur |
| **Proxy Getirme**   | `open-sse/utils/proxyFetch.ts`               | `fetch()` proxy dağıtıcı eklemeyle sarar                            |
| **Ayarlar Rota**    | `src/app/api/settings/proxy/route.ts`        | Eski proxy yapılandırması API (GET/PUT/DELETE)                      |
| **Yönetim Rotası**  | `src/app/api/v1/management/proxies/route.ts` | Kayıt defteri CRUD API (GET/POST/PATCH/DELETE)                      |
| **1 vekil DB**      | `src/lib/db/oneproxy.ts`                     | Ücretsiz proxy pazar kalıcılığı                                     |

---

## Yeni hesaplar için varsayılan proxy durumu

İçinde** Ayarlar → Proxy → Genel yapılandırma** , kullanmak** Yeni bağlantılar için proxy'yi varsayılan olarak etkinleştirin** yeni eklenen sağlayıcı hesaplarının ilk proxy durumunu seçmek için.

Yeni ayar, yeni eklenen sağlayıcı hesaplarının başlangıçtaki proxy durumunu kontrol eder. Mevcut hesapları değiştirmez veya genel proxy anahtarının yerini almaz. Başlangıç değeri önceki davranışı korur. Gelecekte proxy'nin varsayılan olarak devre dışı olduğu hesaplar oluşturmak için bunu bir kez kapatın.

Tercih, mevcut Ayarlar API aracılığıyla `defaultNewConnectionProxyEnabled` olarak saklanır. Hiçbir zaman kaydedilmediğinde varsayılan olarak `true` olur. `false` kaydedilmesi, sonraki yeni hesaplar için yeniden başlatma gerekmeden geçerli olur. `POST /api/providers` isteğe bağlı katı bir boolean `proxyEnabled` kabul eder; açık bir `true` veya `false` oluşturma varsayılanına göre önceliklidir. Yinelenen bir hesabın ihmal edilmesi veya OAuth yeniden bağlanması, o hesabın kayıtlı durumunu korur. Bireysel hesaplar daha sonra yine etkinleştirilebilir veya devre dışı bırakılabilir.

Seçici sağlayıcı aktarımları, yeni hesaplar için hedef kurulumun varsayılanını kullanır ve mevcut hesapları değiştirirken hedef ilkesini korur. Proxy geçişleri taşınabilir aktarım alanları değildir. Tam yedekleme geri yüklemesi ve geçmiş JSON/SQL geçişi, kayıtlı hesap değerleri ve eski şema varsayılanları dahil olmak üzere mevcut geri yükleme anlamlarını korur; tam ayarların geri yüklenmesi de bu tercihi geri yükleyebilir.

Bu tercih bir vekil atamaz veya kişinin sağlıklı veya kullanımda olduğunu belirlemez. Gerçek yönlendirme hâlâ genel proxy anahtarına ve geçerli proxy yapılandırmasına bağlıdır. Kalıcı bir hesaba sahip olmayan sentetik sağlayıcılar, hesap oluşturmadan önceki OAuth trafiği, environment/system proxy'leri ve harici arka uçların ağ iletişimi kapsamı dışındadır.

## 4 Seviyeli Proxy Sistemi

OmniRoute şu adreste proxy yapılandırmasını destekler:** dört bağımsız kapsam** , öncelik sırasına göre çözüldü:

```
Priority Resolution Order (highest → lowest):

  1. 🔵 Account/Connection Proxy  →  per API key / OAuth connection
  2. 🟡 Provider Proxy            →  per provider (e.g., all OpenAI traffic)
  3. 🟠 Combo Proxy               →  per combo/routing configuration
  4. 🟢 Global Proxy              →  all traffic, all providers
```

### Çözünürlük Nasıl Çalışır?

OmniRoute bir yukarı akış sağlayıcısına bir istek gönderdiğinde, her seviyeyi sırayla kontrol eden `resolveProxyForConnectionFromRegistry()` çağırır:

1. **Hesap düzeyinde** — Bu özel ID bağlantısına atanmış bir proxy var mı?
2. **Sağlayıcı düzeyinde** — Bu sağlayıcıya atanmış bir proxy var mı (ör. `openai`)?
3. **Küresel düzeyde** — Yapılandırılmış genel bir proxy var mı?
4. **Proxy yok** — Sağlayıcıya doğrudan bağlantı.

İlk maç kazanır. Bu, genel bir proxy'yi geri dönüş olarak ayarlayabileceğiniz ancak bunu belirli sağlayıcılar veya bağlantılar için geçersiz kılabileceğiniz anlamına gelir.

### Neler Proxy Edilir?

| Trafik Türü           | Vekaleten mi? | Notlar                                        |
| --------------------- | ------------- | --------------------------------------------- |
| Sohbet tamamlamaları  | ✅            | Tüm `/v1/chat/completions` istekleri          |
| Gömmeler              | ✅            | `/v1/embeddings`                              |
| Görüntü oluşturma     | ✅            | `/v1/images/generations`                      |
| Ses (TTS/STT)         | ✅            | `/v1/audio/*`                                 |
| OAuth token değişimi  | ✅            | `unsupported_country_region_territory` çözer  |
| Bağlantı testleri     | ✅            | "Bağlantıyı Test Et" düğmesi proxy kullanıyor |
| Jeton yenileme        | ✅            | Arka plan OAuth yenilemesi                    |
| Model senkronizasyonu | ✅            | Model listeleme ve keşif                      |

---

## Vekil Kayıt Defteri (CRUD)

Proxy kaydı, tüm proxy'lerinizi saklayan bir SQLite tablosudur (`proxy_registry`). Her proxy şunları içerir:

| Alan       | Tip     | Tanım                                                         |
| ---------- | ------- | ------------------------------------------------------------- |
| `id`       | UUID    | Benzersiz tanımlayıcı                                         |
| `name`     | Sicim   | İnsan tarafından okunabilen etiket                            |
| `type`     | Sicim   | Protokol: `http`, `https`, `socks5`                           |
| `host`     | Sicim   | Proxy ana bilgisayar adı veya IP                              |
| `port`     | Tamsayı | Bağlantı noktası numarası                                     |
| `username` | Sicim   | Kimlik doğrulama kullanıcı adı (beklemedeyken şifrelenmiştir) |
| `password` | Sicim   | Kimlik doğrulama şifresi (beklemedeyken şifrelenir)           |
| `region`   | Sicim   | Coğrafi bölge etiketi                                         |
| `notes`    | Sicim   | Serbest metinli notlar                                        |
| `status`   | Sicim   | `active` veya `inactive`                                      |
| `source`   | Sicim   | `manual` veya `oneproxy`                                      |

### Proxy Oluşturma

**Kontrol Paneli aracılığıyla:**

1. Git** Ayarlar → Proxy'si**
2. Tıklamak** Proxy Ekle**
3. Tür, ana bilgisayar, bağlantı noktası ve isteğe bağlı kimlik doğrulama bilgilerini girin
4. Kaydetmek

**API aracılığıyla:**

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

### Proxy Güncelleme

```bash
curl -X PATCH http://localhost:20128/api/v1/management/proxies \
  -H "Content-Type: application/json" \
  -d '{
    "id": "proxy-uuid-here",
    "host": "new-proxy.example.com",
    "port": 9090
  }'
```

> **Not:** Boş olmayan değiştirmeleri açıkça göndermediğiniz sürece kimlik bilgileriniz korunur. `username`/`password` için boş dizelerin gönderilmesi, saklanan değerleri koruyacaktır.

### Proxy'yi Silme

```bash
# Fails if proxy is assigned to any scope
curl -X DELETE "http://localhost:20128/api/v1/management/proxies?id=proxy-uuid"

# Force delete (removes assignments too)
curl -X DELETE "http://localhost:20128/api/v1/management/proxies?id=proxy-uuid&force=1"
```

### Proxy'leri Listeleme

```bash
curl "http://localhost:20128/api/v1/management/proxies?limit=50&offset=0"
```

### Kapsamlara Proxy Atama

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

### Etkili Proxy Çözümü

Belirli bir bağlantı için hangi proxy'nin kullanılacağını kontrol edin:

```bash
curl "http://localhost:20128/api/settings/proxy?resolve=connection-uuid"
```

Çözümlenen proxy'yi düzeyi (`account`, `provider` veya `global`) ve kaynağıyla birlikte döndürür.

### Toplu Atama

Bir proxy'yi aynı anda birden fazla sağlayıcıya veya bağlantıya atayın:

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

Proxy'ler dahildir**Backup/Restore** sistem. OmniRoute yapılandırmanızı dışa aktardığınızda:

1. Git** Kontrol Paneli → Ayarları → Yedekleme**
2. Tıklamak** İhracat** — proxy kaydı ve atamaları dahildir
3. Geri yüklemek için tıklayın** İçe aktarmak** ve yedekleme dosyasını yükleyin

Proxy kayıt defteri de destekler** ana bilgisayar + bağlantı noktası tarafından yükseltildi** —, zaten var olan bir proxy'yi (aynı ana bilgisayar ve bağlantı noktası) içe aktarırsanız, bir kopya oluşturmak yerine güncellenir.

### Eski Taşıma

Proxy'leri daha eski bir sürümde (ön kayıt) yapılandırdıysanız OmniRoute bunları otomatik olarak taşır:

```
Legacy key_value store → proxy_registry + proxy_assignments
```

Bu, yükseltme sonrasında ilk başlatmada bir kez gerçekleşir. Yeniden çalıştırmak için `migrateLegacyProxyConfigToRegistry({ force: true })` kullanın.

---

## 1proxy Ücretsiz Proxy Pazarı

> 🆕** Katkıda bulunan: [@oyi77](https://github.com/oyi77)** — PR [#1847](https://github.com/diegosouzapw/OmniRoute/pull/1847) (Sayı [#1788](https://github.com/diegosouzapw/OmniRoute/issues/1788) )

OmniRoute ile entegre olur** [1 vekil](https://1proxy-api.aitradepulse.com)** erişim sağlamak için topluluk platformu** yüzlerce ücretsiz, doğrulanmış proxy** dünyanın dört bir yanından. Bu, kendi proxy altyapısına sahip olmayan kullanıcılar için mükemmeldir.

### Nasıl Çalışır?

```
┌─────────────┐     Sync      ┌─────────────────┐    Rotate     ┌──────────┐
│  1proxy API │ ────────────▶ │  proxy_registry  │ ────────────▶ │ Provider │
│  (external) │   up to 500   │  source=oneproxy │  by quality   │   API    │
└─────────────┘    proxies    └─────────────────┘               └──────────┘
```

1. **Senkronizasyon** — OmniRoute, 1proxy API doğrulanmış proxy'leri getirir
2. **Mağaza** — Proxy'ler `source = 'oneproxy'` ile aynı `proxy_registry` tablosuna kaydedilir
3. **Filtre** — Protokole, ülkeye, kalite puanına göre filtrele
4. **Döndür** — Kaliteli, rastgele veya sıralı stratejiler kullanarak en iyi proxy'yi seçin
5. **Otomatik bozulma** — Başarısız proxy'lerin kalite puanları düşer; eşiğin altında → etkin değil olarak işaretlendi

### Proxy'leri Senkronize Etme

**Kontrol Paneli aracılığıyla:**

1. Git** Ayarlar → 1proxy** sekme
2. Tıklamak** "Şimdi Eşitle"**
3. İstatistikleri görüntüleyin: toplam proxy sayısı, aktif sayı, ortalama kalite, ülkeye göre dağılım

**API aracılığıyla:**

```bash
# Trigger sync
curl -X POST http://localhost:20128/api/settings/oneproxy \
  -H "Content-Type: application/json" \
  -d '{}'

# Response:
# { "success": true, "added": 127, "updated": 45, "failed": 2, "total": 172 }
```

### Proxy'leri Filtreleme

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

### Proxy Kalite Puanları

Her 1proxy proxy'si meta verilerle birlikte gelir:

| Alan            | Tanım                                              |
| --------------- | -------------------------------------------------- |
| `qualityScore`  | 1proxy doğrulamasından 0-100 derecelendirme        |
| `latencyMs`     | Ölçülen ağ gecikmesi                               |
| `anonymity`     | `transparent`, `anonymous` veya `elite`            |
| `googleAccess`  | Proxy'nin Google hizmetlerine erişip erişemeyeceği |
| `countryCode`   | İki harfli ISO ülke kodu                           |
| `lastValidated` | Son doğrulamanın zaman damgası                     |

Kalite puanları dinamik olarak ayarlanır:

- **Başarısız istekler** puanı 10 puan düşürün
- **Puan ≤ 10'a düşüyor** → proxy'si `inactive` işaretlenmiştir
- Etkin olmayan proxy'ler rotasyonun dışında bırakılır

### Rotasyon Stratejileri

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

### Devre Kesici

1proxy senkronizasyonunda yerleşik bir devre kesici bulunur:

- Sonrasında** 5 ardışık senkronizasyon hatası** , daha fazla senkronizasyon girişimi engellenir
- Şununla sıfırlayın: `resetOneproxyCircuitBreaker()` veya sunucuyu yeniden başlatın
- Senkronizasyon durumu `GET /api/settings/oneproxy?action=status` mevcuttur

### 1proxy Proxy'lerini Temizleme

```bash
# Delete a single 1proxy proxy
curl -X DELETE "http://localhost:20128/api/settings/oneproxy?id=proxy-uuid"

# Clear ALL 1proxy proxies (manual proxies are untouched)
curl -X DELETE "http://localhost:20128/api/settings/oneproxy?clearAll=1"
```

---

## Algılanma Önleme ve Gizlilik

OmniRoute trafiği yalnızca bir proxy — üzerinden yönlendirmekle kalmaz, trafiğin meşru görünmesini de sağlar:

### TLS Parmak İzi Sahtekarlığı

Tarayıcı dışı TLS el sıkışmalarını işaretleyen bot algılama sistemlerini atlayarak tarayıcı benzeri TLS parmak izleri oluşturmak için `wreq-js` kullanır.

### CLI Parmak İzi Eşleştirme

**CLI Parmak İzi Geçişi** (`Settings → Security`) HTTP başlıklarını ve JSON gövde alanlarını, yerel CLI ikili dosyalarının (Claude Code, Codex vb.) tam imzasıyla eşleşecek şekilde yeniden sıralar. Bu işe yarıyor** üstüne** vekil:

```
Your IP (blocked) → Proxy IP (US) → Provider API
                    + TLS spoof
                    + CLI fingerprint
```

İkisini de alırsın**IP maskeleme** Ve** özgünlük iste** aynı anda.

### Proxy IP Koruması

Kontrol panelindeki renk kodlu rozetler hangi proxy düzeyinin etkin olduğunu gösterir:

| Rozet | Seviye    | Anlam                                                |
| ----- | --------- | ---------------------------------------------------- |
| 🟢    | Küresel   | Tüm trafik bu proxy üzerinden geçiyor                |
| 🟡    | sağlayıcı | Yalnızca bu sağlayıcının trafiğine proxy uygulanıyor |
| 🔵    | Bağlantı  | Bu belirli key/account bu proxy'yi kullanıyor        |

Rozet ayrıca doğrulama için çözümlenen proxy IP da gösterir.

---

## Yukarı Akış Proxy Modları

CLIProxyAPI modelini kullanan sağlayıcılar için OmniRoute, üç yukarı akış proxy modunu destekler:

| Mod           | Tanım                                                       |
| ------------- | ----------------------------------------------------------- |
| `native`      | OmniRoute proxy yönlendirmeyi doğrudan yönetir (varsayılan) |
| `cliproxyapi` | Harici bir CLIProxyAPI örneğine delegeler                   |
| `fallback`    | Önce yerel dener, CLIProxyAPI geri döner                    |

Sağlayıcıya göre yapılandırın:

```bash
curl -X PUT "http://localhost:20128/api/upstream-proxy/openai" \
  -H "Content-Type: application/json" \
  -d '{"mode": "native", "enabled": true}'
```

---

## Kontrol paneli UI

### Ayarlar → Proxy Sekmesi

- **Küresel vekil** yapılandırma (tüm trafik için bir kez ayarlanır)
- **Sağlayıcı başına proxy** geçersiz kılmalar
- **Bağlantı başına proxy** atamalar
- **Bağlantı testi** yapılandırılmış proxy aracılığıyla
- **Renk kodlu rozetler** aktif proxy seviyesini gösteriyor

### Ayarlar → 1proxy Sekmesi

- **Şimdi Senkronize Et** ücretsiz proxy'leri almak için düğme
- **İstatistik kartları** : Toplam, Etkin, Ort. Kalite, Son Senkronizasyon
- **Filtreler** : Protokol, Ülke Kodu, Min Kalite
- **Vekil tablo** ana bilgisayar, protokol, ülke, kalite puanı, gecikme, anonimlik, Google erişimi ile
- **Senkronizasyon durumu** success/failure takibi ve ardışık arıza sayımı içeren panel
- **Tümünü Temizle** tüm 1proxy girişlerini kaldırmak için

---

## API Referansı

### Proxy Ayarları API

| Yöntem   | Uç nokta                                       | Tanım                             |
| -------- | ---------------------------------------------- | --------------------------------- |
| `GET`    | `/api/settings/proxy`                          | Tam proxy yapılandırmasını edinin |
| `GET`    | `/api/settings/proxy?level=global`             | Küresel proxy'yi edinin           |
| `GET`    | `/api/settings/proxy?level=provider&id=openai` | Sağlayıcı proxy'sini edinin       |
| `GET`    | `/api/settings/proxy?resolve=connectionId`     | Etkili proxy'yi çözümleyin        |
| `PUT`    | `/api/settings/proxy`                          | Proxy yapılandırmasını güncelle   |
| `DELETE` | `/api/settings/proxy?level=provider&id=openai` | Proxy'yi düzeyde kaldır           |

### Vekil Kayıt Defteri API

| Yöntem   | Uç nokta                                          | Tanım                       |
| -------- | ------------------------------------------------- | --------------------------- |
| `GET`    | `/api/v1/management/proxies`                      | Tüm proxy'leri listele      |
| `GET`    | `/api/v1/management/proxies?id=uuid`              | ID tarafından proxy alın    |
| `GET`    | `/api/v1/management/proxies?id=uuid&where_used=1` | Proxy atamalarını alın      |
| `POST`   | `/api/v1/management/proxies`                      | Proxy oluştur               |
| `PATCH`  | `/api/v1/management/proxies`                      | Proxy'yi güncelle           |
| `DELETE` | `/api/v1/management/proxies?id=uuid`              | Proxy'yi sil                |
| `DELETE` | `/api/v1/management/proxies?id=uuid&force=1`      | Silmeye zorla               |
| `POST`   | `/api/v1/management/proxies/bulk-assign`          | Toplu atama                 |
| `GET`    | `/api/v1/management/proxies/assignments`          | Ödevleri listeleme          |
| `GET`    | `/api/v1/management/proxies/health`               | Proxy sağlık istatistikleri |

### Tüneller API

OmniRoute örneğinizi bir proxy aracılığıyla giden yolu yönlendirmek yerine genel internete (Cloudflare/ngrok/Tailscale) açmak için bkz. [TUNNELS_GUIDE.md](./TUNNELS_GUIDE.md). REST API tüneli `/api/tunnels/{cloudflared,ngrok,tailscale}/*` altında bulunur ve yukarıda belgelenen giden proxy zincirine diktir.

### 1 vekil API

| Yöntem   | Uç nokta                               | Tanım                                         |
| -------- | -------------------------------------- | --------------------------------------------- |
| `GET`    | `/api/settings/oneproxy`               | 1proxy proxy'sini listele                     |
| `GET`    | `/api/settings/oneproxy?action=stats`  | İstatistikleri + senkronizasyon durumunu alın |
| `GET`    | `/api/settings/oneproxy?action=status` | Yalnızca senkronizasyon durumunu al           |
| `POST`   | `/api/settings/oneproxy`               | Senkronizasyonu tetikle                       |
| `POST`   | `/api/settings/oneproxy/rotate`        | Sonraki proxy'ye döndür                       |
| `DELETE` | `/api/settings/oneproxy?id=uuid`       | Birini sil                                    |
| `DELETE` | `/api/settings/oneproxy?clearAll=1`    | Tümünü temizle                                |

### Yukarı Akış Proxy'si API

| Yöntem   | Uç nokta                          | Tanım                                     |
| -------- | --------------------------------- | ----------------------------------------- |
| `GET`    | `/api/upstream-proxy/:providerId` | Yukarı akış proxy yapılandırmasını edinin |
| `PUT`    | `/api/upstream-proxy/:providerId` | Yukarı akış proxy modunu ayarlayın        |
| `DELETE` | `/api/upstream-proxy/:providerId` | Yukarı akış proxy yapılandırmasını kaldır |

---

## Ortam Değişkenleri

| Değişken              | Varsayılan | Tanım                                                                     |
| --------------------- | ---------- | ------------------------------------------------------------------------- |
| `ENABLE_SOCKS5_PROXY` | `true`     | SOCKS5 proxy desteğini etkinleştirin ( `.env.example` varsayılan `true` ) |

---

## Sorun giderme

### "SOCKS5 proxy'si devre dışı"

`.env` dosyanızda `ENABLE_SOCKS5_PROXY=true` ayarlayın ve yeniden başlatın.

### Proxy aracılığıyla "soket kapatma" hataları

Boşta kalan bağlantıları kesen ucuz proxy'lerde bu normaldir. OmniRoute bunu zaten şu şekilde hallediyor:

- Proxy bağlantılarında (`keepAliveTimeout: 1`) canlı tutmayı devre dışı bırakma
- Ardışık düzenin devre dışı bırakılması (`pipelining: 0`)
- Tekrarlanan el sıkışmalarını önlemek için sevk görevlilerini önbelleğe almak

Devam ederse farklı bir proxy deneyin veya 1proxy döndürme özelliğini kullanın.

### OAuth sırasında "desteklenmeyen_ülke_region_territory"

Proxy'nin yapılandırıldığından emin olun** önce** OAuth akışını başlatıyorum. OmniRoute OAuth token değişimini yapılandırılmış proxy aracılığıyla yönlendirir. Önce genel veya sağlayıcı düzeyinde bir proxy ayarlayın, ardından bağlanın.

### Proxy kullanılmıyor

Çözünürlük sırasını kontrol edin:

1. `GET /api/settings/proxy?resolve=your-connection-id` ile doğrula
2. Proxy `status` `active` olup olmadığını kontrol edin ( `inactive` değil)
3. Proxy atama kapsamının bağlantınızla eşleştiğinden emin olun

### 1proxy senkronizasyonu başarısız

Senkronizasyon durumunu kontrol edin:

```bash
curl "http://localhost:20128/api/settings/oneproxy?action=status"
```

`consecutiveFailures >= 5` ise devre kesici açmıştır. Sıfırlamak için sunucuyu yeniden başlatın veya manuel sıfırlamayı bekleyin.

---

## Veritabanı Şeması

### `proxy_registry` Tablosu

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

### `proxy_assignments` Tablosu

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

## Proxy Durum Kontrolü (v3.8.16 +)

OmniRoute** proxy hızlı başarısız** mekanizma (`src/lib/proxyHealth.ts`), hızlı bir TCP bağlantı kontrolü yoluyla < 2'lerdeki ölü proxy'leri algılar ve ardından** sonucu önbelleğe alır** istek başına ek yükten kaçınmak için.

### Nasıl Çalışır?

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

Bu olmadan ölü bir proxy, başarısız olmadan önce tam `PROXY_TIMEOUT_MS` (varsayılan 30'lar) yönelik her isteği engeller.

### Ayarlanabilir Ortam Değişkenleri

| Değişken                     | Varsayılan | Amaç                                                 |
| ---------------------------- | ---------- | ---------------------------------------------------- |
| `PROXY_FAST_FAIL_TIMEOUT_MS` | `2000`     | Durum denetimi başına TCP bağlantı zaman aşımı       |
| `PROXY_HEALTH_CACHE_TTL_MS`  | `30000`    | Bir sağlık sonucu ne kadar süreyle önbelleğe alınır? |

**Önerilen değerler:**

| Senaryo                                 | Hızlı arıza zaman aşımı | Önbellek TTL | muhakeme                                                                                         |
| --------------------------------------- | ----------------------- | ------------ | ------------------------------------------------------------------------------------------------ |
| Yüksek verimli API ağ geçidi            | 1500ms                  | 60000ms      | Kontrolleri azaltmak için agresif arıza hızlı, daha uzun önbellek                                |
| Coğrafi olarak dağıtılmış düğümler      | 3000ms                  | 15000ms      | Daha yavaş ağların daha fazla zamana ihtiyacı vardır; hızlı yük devretme için daha kısa önbellek |
| Geliştirme / test etme                  | 1000ms                  | 10000ms      | Yerel proxy'lerde hızlı yineleme                                                                 |
| Gizlilik / tespit edilmeye karşı koruma | 2500ms                  | 45000ms      | Hız limitlerini tetikleyebilecek hızlı problamadan kaçının                                       |

### Proxy Sağlığını Denetleme

```ts
import { getAllProxyHealthStatuses, invalidateProxyHealth } from "omniroute/proxyHealth";

const statuses = getAllProxyHealthStatuses();
for (const s of statuses) {
  console.log(`${s.proxyUrl} → healthy=${s.healthy}, stale=${s.stale}`);
}

// Force re-check a specific proxy
invalidateProxyHealth("http://user:pass@203.0.113.7:8080");
```

Önbellek girişi `HEALTH_CACHE_TTL_MS` aştığında `stale` bayrağı `true` olur ve bir sonraki istek yeni bir kontrolü tetikler.

### Proxy Başına Tür Varsayılanları

Durum kontrolü, URL şemasını temel alan makul varsayılanları kullanır:

| Şema                       | Varsayılan bağlantı noktası |
| -------------------------- | --------------------------- |
| `http://`                  | 8080                        |
| `https://`                 | 443                         |
| `socks5://` / `socks5h://` | 1080                        |

URL (`http://host:9999`) özel bağlantı noktaları her zaman şema varsayılanına göre önceliklidir.

---

## Proxy Analizi ve Gözlemlenebilirlik

OmniRoute operatörlerin yönlendirme modellerini, gecikme artışlarını ve yinelenen hataları teşhis etmesine yardımcı olmak için proxy başına kullanımı izler.

### Neler Takip Ediliyor

Yapılandırılmış bir proxy aracılığıyla yapılan her istek için OmniRoute şunları kaydeder:

| Metrik       | Tanım                                                     |
| ------------ | --------------------------------------------------------- |
| `proxy_url`  | Tam proxy URL (kimlik kimlik bilgileri maskelenmiş halde) |
| `provider`   | Yukarı akış sağlayıcısı ID (openai, antropik vb.)         |
| `latency_ms` | Vekil el sıkışma dahil toplam gidiş-dönüş süresi          |
| `connect_ms` | yalnızca TCP bağlantı süresi                              |
| `status`     | yukarı akıştan HTTP durum kodu                            |
| `error`      | İstek başarısız olursa hata sınıfı                        |
| `timestamp`  | ISO 8601 UTC                                              |

### Verilere Erişim

```bash
# Recent proxy events
curl -H "Authorization: Bearer $OMNIROUTE_KEY" \
  "http://localhost:20128/api/usage/proxy-logs?limit=100"
```

Gerçek son nokta `/api/usage/proxy-logs` (bkz. `src/app/api/usage/proxy-logs/route.ts`). Bu uç nokta şunları destekler:

- `GET /api/usage/proxy-logs` — proxy günlüklerini al
- `DELETE /api/usage/proxy-logs` — tüm proxy günlüklerini temizle

Toplu istatistikler gerekirse SQL aracılığıyla doğrudan `proxy_logs` tablosundan sorgulanabilir. Kontrol paneli UI toplu görünümler sunabilir.

### Ortak Desenler

**Çırpınan bir proxy'yi algılama** ( success/failure arasında geçiş yapar):

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

**Yavaş proxy'ler bulun** (p95 gecikme > 2s):

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

## Rotasyon Stratejisi Karar Ağacı

Bir kapsama birden fazla proxy atandığında OmniRoute,** rotasyon stratejisi** Her istek için hangisinin kullanılacağını seçmek için. Strateji kapsam düzeyinde (genel, sağlayıcı başına, hesap başına, kombinasyon başına) yapılandırılır.

### Mevcut Stratejiler

| Strateji               | Ne zaman kullanılmalı               | Değiş tokuş                                                                  |
| ---------------------- | ----------------------------------- | ---------------------------------------------------------------------------- |
| `quality` (varsayılan) | Karışık kalitede proxy'lerle üretim | Yüksek dereceli proxy'leri tercih eder; düşük puanlı olanları aç bırakabilir |
| `random`               | Yük dağıtımı, gizlilik              | Eşit dağıtım; kalite sinyallerini göz ardı eder                              |
| `sequential`           | Hata ayıklama, deterministik test   | Proxy'ler arasında sırayla geçiş yapar; hakkında mantık yürütmek kolay       |

### Karar Ağacı

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

## Kendi Proxy'leriniz için Otomatik Arıza Hariç Tutma

1proxy pazar havuzu, başarısız olan proxy'leri zaten kendi başına otomatik olarak düşürür (bkz. [Proxy Kalite Puanları](#proxy-quality-scores) ). Vekiller için** Sen** Kayıt defterine eklenen arka plan sağlık planlayıcısı (`src/lib/proxyHealth/scheduler.ts`), hiçbir şeyi silmeden aynı "ölü bir üyeyi zincirden otomatik olarak hariç tut" davranışını sağlar:

```bash
# .env — soft-disable a proxy after 3 consecutive failed probes, re-enable it
# automatically once it starts answering probes again.
PROXY_AUTO_DISABLE=true
PROXY_AUTO_REMOVE_AFTER=3
```

Çoklu proxy zincirine nasıl uyar:

1. Zamanlayıcı her kayıtlı proxy'yi her `PROXY_HEALTH_INTERVAL_MS` araştırır (varsayılan 10 dakika; minimum 1 dakika).
2. `PROXY_AUTO_REMOVE_AFTER` sonra ardışık** kesin** başarısızlıklar (gerçek bir bağlantı hatası — zaman aşımı veya araştırma hedefinin kendi 5xx'i hiçbir zaman sayılmaz, bkz. [Proxy Sağlık Kontrolü](#proxy-health-checking-v3816) ), proxy'nin `status` `dead` olarak ayarlanır.
3. `dead` pool/rotation çözümlemesi tarafından kullanılan canlı durum filtresinin hariç tuttuğu durumlardan biridir, dolayısıyla bir kapsamın rotasyonu (yuvarlak-robin / rastgele / yapışkan / gecikme — bkz. [Rotasyon Stratejisi Karar Ağacı](#rotation-strategy-decision-tree) ) bu proxy'yi yeni isteklere vermeyi anında durdurur. Havuzdaki başka hiçbir proxy etkilenmez ve havuzun tamamı hiçbir zaman sessizce doğrudan bağlantıya geri dönmez. [4 Seviyeli Proxy Sisteminin](#4-level-proxy-system) arıza kapatma korumasına —.
4. Zamanlayıcı `dead` proxy'lerini aynı aralıkta incelemeye devam eder. Bir sonraki başarılı prob, `status` `active` geri çevirir ve manuel olarak yeniden eklemeye gerek kalmadan — dönüşüne yeniden girer.

Bu kasıtlı olarak** isteğe bağlı ve tahribatsız** : varsayılan olarak zamanlayıcı yalnızca hataları sayar ve günlüğe kaydeder ( `decision.ts` C politikasına bakın) ve `PROXY_AUTO_DISABLE`, ayrı, daha agresif `PROXY_AUTO_REMOVE` bayrağının amacı olan — satırını asla silmez. Her ikisi de `true` olarak ayarlanırsa `PROXY_AUTO_REMOVE` kazanır (silinmek üzere olan bir proxy'nin aradaki geçici devre dışı bırakma işleminin hiçbir faydası yoktur). Değişken listesinin tamamı için [Ortam Yapılandırması](../reference/ENVIRONMENT.md) referansına bakın.

---

> 📖** İlgili belgeler:**
>
> - [Kullanıcı Kılavuzu](../guides/USER_GUIDE.md) — Genel kurulum ve yapılandırma - [API Referans](../reference/API_REFERENCE.md) — Tam API belgeleri - [Ortam Yapılandırması](../reference/ENVIRONMENT.md) — Tüm ortam değişkenleri
