# 🌐 OmniRoute Proxy Guide (Azərbaycan dili)

🌐 **Languages:** 🇺🇸 [English](../../../../ops/PROXY_GUIDE.md) · 🇪🇹 [am](../../../am/docs/ops/PROXY_GUIDE.md) · 🇸🇦 [ar](../../../ar/docs/ops/PROXY_GUIDE.md) · 🇧🇬 [bg](../../../bg/docs/ops/PROXY_GUIDE.md) · 🇧🇩 [bn](../../../bn/docs/ops/PROXY_GUIDE.md) · 🇧🇦 [bs](../../../bs/docs/ops/PROXY_GUIDE.md) · 🇨🇿 [cs](../../../cs/docs/ops/PROXY_GUIDE.md) · 🇩🇰 [da](../../../da/docs/ops/PROXY_GUIDE.md) · 🇩🇪 [de](../../../de/docs/ops/PROXY_GUIDE.md) · 🇬🇷 [el](../../../el/docs/ops/PROXY_GUIDE.md) · 🇪🇸 [es](../../../es/docs/ops/PROXY_GUIDE.md) · 🇪🇪 [et](../../../et/docs/ops/PROXY_GUIDE.md) · 🇮🇷 [fa](../../../fa/docs/ops/PROXY_GUIDE.md) · 🇫🇮 [fi](../../../fi/docs/ops/PROXY_GUIDE.md) · 🇫🇷 [fr](../../../fr/docs/ops/PROXY_GUIDE.md) · 🇮🇪 [ga](../../../ga/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [gu](../../../gu/docs/ops/PROXY_GUIDE.md) · 🇳🇬 [ha](../../../ha/docs/ops/PROXY_GUIDE.md) · 🇮🇱 [he](../../../he/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [hi](../../../hi/docs/ops/PROXY_GUIDE.md) · 🇭🇷 [hr](../../../hr/docs/ops/PROXY_GUIDE.md) · 🇭🇺 [hu](../../../hu/docs/ops/PROXY_GUIDE.md) · 🇦🇲 [hy](../../../hy/docs/ops/PROXY_GUIDE.md) · 🇮🇩 [id](../../../id/docs/ops/PROXY_GUIDE.md) · 🇳🇬 [ig](../../../ig/docs/ops/PROXY_GUIDE.md) · 🇮🇹 [it](../../../it/docs/ops/PROXY_GUIDE.md) · 🇯🇵 [ja](../../../ja/docs/ops/PROXY_GUIDE.md) · 🇬🇪 [ka](../../../ka/docs/ops/PROXY_GUIDE.md) · 🇰🇭 [km](../../../km/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [kn](../../../kn/docs/ops/PROXY_GUIDE.md) · 🇰🇷 [ko](../../../ko/docs/ops/PROXY_GUIDE.md) · 🇱🇹 [lt](../../../lt/docs/ops/PROXY_GUIDE.md) · 🇱🇻 [lv](../../../lv/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [ml](../../../ml/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [mr](../../../mr/docs/ops/PROXY_GUIDE.md) · 🇲🇾 [ms](../../../ms/docs/ops/PROXY_GUIDE.md) · 🇲🇹 [mt](../../../mt/docs/ops/PROXY_GUIDE.md) · 🇲🇲 [my](../../../my/docs/ops/PROXY_GUIDE.md) · 🇳🇵 [ne](../../../ne/docs/ops/PROXY_GUIDE.md) · 🇳🇱 [nl](../../../nl/docs/ops/PROXY_GUIDE.md) · 🇳🇴 [no](../../../no/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [or](../../../or/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [pa](../../../pa/docs/ops/PROXY_GUIDE.md) · 🇵🇭 [phi](../../../phi/docs/ops/PROXY_GUIDE.md) · 🇵🇱 [pl](../../../pl/docs/ops/PROXY_GUIDE.md) · 🇵🇹 [pt](../../../pt/docs/ops/PROXY_GUIDE.md) · 🇧🇷 [pt-BR](../../../pt-BR/docs/ops/PROXY_GUIDE.md) · 🇷🇴 [ro](../../../ro/docs/ops/PROXY_GUIDE.md) · 🇷🇺 [ru](../../../ru/docs/ops/PROXY_GUIDE.md) · 🇱🇰 [si](../../../si/docs/ops/PROXY_GUIDE.md) · 🇸🇰 [sk](../../../sk/docs/ops/PROXY_GUIDE.md) · 🇸🇮 [sl](../../../sl/docs/ops/PROXY_GUIDE.md) · 🇷🇸 [sr](../../../sr/docs/ops/PROXY_GUIDE.md) · 🇸🇪 [sv](../../../sv/docs/ops/PROXY_GUIDE.md) · 🇰🇪 [sw](../../../sw/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [ta](../../../ta/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [te](../../../te/docs/ops/PROXY_GUIDE.md) · 🇹🇭 [th](../../../th/docs/ops/PROXY_GUIDE.md) · 🇹🇷 [tr](../../../tr/docs/ops/PROXY_GUIDE.md) · 🇺🇦 [uk-UA](../../../uk-UA/docs/ops/PROXY_GUIDE.md) · 🇵🇰 [ur](../../../ur/docs/ops/PROXY_GUIDE.md) · 🇺🇿 [uz](../../../uz/docs/ops/PROXY_GUIDE.md) · 🇻🇳 [vi](../../../vi/docs/ops/PROXY_GUIDE.md) · 🇳🇬 [yo](../../../yo/docs/ops/PROXY_GUIDE.md) · 🇨🇳 [zh-CN](../../../zh-CN/docs/ops/PROXY_GUIDE.md) · 🇹🇼 [zh-TW](../../../zh-TW/docs/ops/PROXY_GUIDE.md)

---

> **Coğrafi blokları keçin, şəxsiyyətinizi qoruyun və AI trafikini sıfır konfiqurasiya mürəkkəbliyi ilə istənilən proxy — vasitəsilə yönləndirin.**

OmniRoute sizə HTTP, HTTPS və ya SOCKS5 proksiləri vasitəsilə yuxarı AI provayder trafikini yönləndirməyə imkan verən tam funksiyalı proksi idarəetmə sistemini ehtiva edir. Bloklanmış bölgədə olmağınızdan, IP fırlanmasına ehtiyacınızdan və ya gizli barmaq izini istəməyinizdən asılı olmayaraq — bu təlimat hər şeyi əhatə edir.

---

## Mündəricat

- [Niyə Proksilərdən istifadə edin?](#why-use-proxies)
- [Memarlığa Baxış](#architecture-overview)
- [4 Səviyyəli Proksi Sistemi](#4-level-proxy-system)
- [Proksi Qeydiyyatı (CRUD)](#proxy-registry-crud)
- [1proxy Pulsuz Marketplace](#1proxy-free-proxy-marketplace)
- [Proksi fırlanması](#proxy-rotation)
- [Aşkarlanma və Gizlilik](#anti-detection--stealth)
- [Upstream Proxy Rejimləri](#upstream-proxy-modes)
- [İdarə paneli UI](#dashboard-ui)
- [API İstinad](#api-reference)
- [Ətraf Mühit Dəyişənləri](#environment-variables)
- [Problemlərin aradan qaldırılması](#troubleshooting)

---

## Niyə Proksilərdən istifadə edin?

Bir çox AI provayderi coğrafi bölgəyə görə girişi məhdudlaşdırır. Tərtibatçılar** Rusiya, Çin, İran, Kuba, Türkiyə** , və digər ölkələr belə xətalarla qarşılaşır:

```
unsupported_country_region_territory
```

Hətta bloklanmış bölgələrdən kənarda belə proksilər aşağıdakılar üçün faydalıdır:

| İstifadə Case     | Təsvir                                                                            |
| ----------------- | --------------------------------------------------------------------------------- |
| **Coğrafi keçid** | Bloklanmış ölkələrdən OpenAI, Anthropic, Codex, Copilot daxil olun                |
| **IP fırlanma**   | Məhdudiyyət dərəcəsinin qarşısını almaq üçün sorğuları bir neçə IPs üzrə paylayın |
| **Məxfilik**      | Həqiqi IP nı yuxarı provayderlərdən gizlədin                                      |
| **Uyğunluq**      | Müəyyən yurisdiksiyalar üzrə nəqliyyat marşrutu                                   |
| **Test**          | Müxtəlif bölgələrdən gələn sorğuları simulyasiya edin                             |

---

## Memarlığa Baxış

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

### Əsas Komponentlər

| Komponent               | Fayl                                         | Rol                                                         |
| ----------------------- | -------------------------------------------- | ----------------------------------------------------------- |
| **Proksi reyestri**     | `src/lib/db/proxies.ts`                      | proxy girişləri üçün CRUD + əhatə dairəsi təyinatları       |
| **Proksi dispetçer**    | `open-sse/utils/proxyDispatcher.ts`          | Keşləmə ilə `undici` ProxyAgent/SOCKS dispetçerləri yaradır |
| **Proksi Alma**         | `open-sse/utils/proxyFetch.ts`               | Proksi dispetçer inyeksiyası ilə `fetch()` əhatə edir       |
| **Parametrlər Marşrut** | `src/app/api/settings/proxy/route.ts`        | Köhnə proxy konfiqurasiyası API (GET/PUT/DELETE)            |
| **İdarəetmə marşrutu**  | `src/app/api/v1/management/proxies/route.ts` | Qeydiyyat CRUD API (GET/POST/PATCH/DELETE)                  |
| **1 proxy DB**          | `src/lib/db/oneproxy.ts`                     | Pulsuz proxy bazarının davamlılığı                          |

---

## Yeni hesablar üçün defolt proksi vəziyyəti

In** Parametrlər → Proxy → Qlobal konfiqurasiya** , istifadə edin** Yeni bağlantılar üçün defolt olaraq proksi-ni aktivləşdirin** yeni əlavə edilmiş provayder hesablarının ilkin proksi vəziyyətini seçmək üçün.

Yeni parametr yeni əlavə edilmiş provayder hesablarının ilkin proksi vəziyyətinə nəzarət edir. O, mövcud hesabları dəyişdirmir və ya qlobal proxy keçidini əvəz etmir. Onun ilkin dəyəri əvvəlki davranışı qoruyur. Defolt olaraq deaktiv edilmiş proxy ilə gələcək hesablar yaratmaq üçün onu bir dəfə söndürün.

Üstünlük mövcud Parametrlər API vasitəsilə `defaultNewConnectionProxyEnabled` kimi saxlanılır. Heç vaxt saxlanmadıqda standart olaraq `true` dir. `false` saxlanması yenidən başlamadan sonrakı yeni hesablar üçün qüvvəyə minir. `POST /api/providers` isteğe bağlı ciddi boolean `proxyEnabled` qəbul edir; açıq `true` və ya `false` yaradılması defoltundan üstündür. Dublikat hesabda buraxılma və ya OAuth yenidən qoşulma həmin hesabın saxlanmış vəziyyətini qoruyur. Fərdi hesablar daha sonra aktivləşdirilə və ya deaktiv edilə bilər.

Seçilmiş provayder köçürmələri yeni hesablar üçün təyinat quraşdırmasının defoltundan istifadə edir və mövcud hesabları əvəz edərkən təyinat siyasətini qoruyur. Proksi keçidləri portativ ötürmə sahələri deyil. Tam ehtiyat nüsxəsinin bərpası və tarixi JSON/SQL miqrasiyası saxlanmış hesab dəyərləri və köhnə sxem defoltları daxil olmaqla, mövcud bərpa semantikasını saxlayır; tam parametrlərin bərpası da bu üstünlükləri bərpa edə bilər.

Bu üstünlük proksi təyin etmir və ya onun sağlam və ya istifadədə olduğunu müəyyən etmir. Faktiki marşrutlaşdırma hələ də qlobal proksi keçidindən və müvafiq proksi konfiqurasiyasından asılıdır. Davamlı hesabı olmayan sintetik provayderlər, hesab yaratmazdan əvvəl OAuth trafiki, environment/system proksiləri və xarici backendlər şəbəkəsi onun əhatə dairəsindən kənardadır.

## 4 Səviyyəli Proksi Sistemi

OmniRoute proksi konfiqurasiyasını dəstəkləyir** dörd müstəqil əhatə dairəsi** , prioritet qaydada həll edilir:

```
Priority Resolution Order (highest → lowest):

  1. 🔵 Account/Connection Proxy  →  per API key / OAuth connection
  2. 🟡 Provider Proxy            →  per provider (e.g., all OpenAI traffic)
  3. 🟠 Combo Proxy               →  per combo/routing configuration
  4. 🟢 Global Proxy              →  all traffic, all providers
```

### Qətnamə necə işləyir

OmniRoute yuxarı axın provayderinə sorğu göndərdikdə, hər səviyyəni ardıcıllıqla yoxlayan `resolveProxyForConnectionFromRegistry()` çağırır:

1. **Hesab səviyyəsi** — Bu xüsusi əlaqə ID üçün təyin edilmiş proxy varmı?
2. **Provayder səviyyəsində** — Bu provayderə təyin edilmiş proksi varmı (məsələn, `openai`)?
3. **Qlobal səviyyədə** — Qlobal proxy konfiqurasiya olunubmu?
4. **Proksi yoxdur** — Provayderlə birbaşa əlaqə.

İlk matç qalib gəlir. Bu o deməkdir ki, siz qlobal proxy-ni ehtiyat kimi təyin edə bilərsiniz, lakin onu xüsusi provayderlər və ya əlaqələr üçün ləğv edə bilərsiniz.

### Nə Proksiləşdirilir

| Trafik növü            | Proksili? | Qeydlər                                          |
| ---------------------- | --------- | ------------------------------------------------ |
| Söhbət tamamlandı      | ✅        | Bütün `/v1/chat/completions` sorğuları           |
| Yerləşdirmələr         | ✅        | `/v1/embeddings`                                 |
| Şəkil generasiyası     | ✅        | `/v1/images/generations`                         |
| Audio (TTS/STT)        | ✅        | `/v1/audio/*`                                    |
| OAuth token mübadiləsi | ✅        | `unsupported_country_region_territory` həll edir |
| Bağlantı testləri      | ✅        | "Bağlantı testi" düyməsi proksidən istifadə edir |
| Token yeniləməsi       | ✅        | Fon OAuth yenilənməsi                            |
| Model sinxronizasiyası | ✅        | Modelin siyahısı və kəşfi                        |

---

## Proksi Qeydiyyatı (CRUD)

Proksi reyestri bütün proksilərinizi saxlayan SQLite cədvəlidir (`proxy_registry`). Hər bir proxy var:

| Sahə       | Növ      | Təsvir                                       |
| ---------- | -------- | -------------------------------------------- |
| `id`       | UUID     | Unikal identifikator                         |
| `name`     | Simli    | İnsan tərəfindən oxuna bilən etiket          |
| `type`     | Simli    | Protokol: `http`, `https`, `socks5`          |
| `host`     | Simli    | Proksi host adı və ya IP                     |
| `port`     | Tam ədəd | Port nömrəsi                                 |
| `username` | Simli    | Auth istifadəçi adı (istirahətdə şifrələnir) |
| `password` | Simli    | Doğrulama parolu (istirahətdə şifrələnir)    |
| `region`   | Simli    | Coğrafi bölgə etiketi                        |
| `notes`    | Simli    | Pulsuz mətn qeydləri                         |
| `status`   | Simli    | `active` və ya `inactive`                    |
| `source`   | Simli    | `manual` və ya `oneproxy`                    |

### Proksi yaradılması

**İdarə Paneli vasitəsilə:**

1. gedin** Parametrlər → Proxy**
2. klikləyin** Proksi əlavə edin**
3. Növ, host, port və isteğe bağlı auth etimadnaməsini doldurun
4. Saxla

**API vasitəsilə:**

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

### Proksi yenilənir

```bash
curl -X PATCH http://localhost:20128/api/v1/management/proxies \
  -H "Content-Type: application/json" \
  -d '{
    "id": "proxy-uuid-here",
    "host": "new-proxy.example.com",
    "port": 9090
  }'
```

> **Qeyd:** Siz açıq şəkildə boş olmayan əvəzləmələr göndərməsəniz, etimadnamələr qorunur. `username`/`password` üçün boş sətirlərin göndərilməsi saxlanılan dəyərləri saxlayacaq.

### Proksinin silinməsi

```bash
# Fails if proxy is assigned to any scope
curl -X DELETE "http://localhost:20128/api/v1/management/proxies?id=proxy-uuid"

# Force delete (removes assignments too)
curl -X DELETE "http://localhost:20128/api/v1/management/proxies?id=proxy-uuid&force=1"
```

### Proksilərin siyahısı

```bash
curl "http://localhost:20128/api/v1/management/proxies?limit=50&offset=0"
```

### Əhatə dairələrinə Proksilərin Təyin edilməsi

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

### Effektiv Proksi həlli

Verilmiş əlaqə üçün hansı proksinin istifadə olunacağını yoxlayın:

```bash
curl "http://localhost:20128/api/settings/proxy?resolve=connection-uuid"
```

Səviyyəsi (`account`, `provider` və ya `global`) və mənbəyi ilə həll edilmiş proksi qaytarır.

### Toplu Təyinat

Birdən çox provayderə və ya əlaqəyə bir proksi təyin edin:

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

Proksilər daxildir**Backup/Restore** sistemi. OmniRoute konfiqurasiyanızı ixrac edərkən:

1. gedin** İdarə paneli → Parametrləri → Yedəkləmə**
2. klikləyin** İxrac** — proxy reyestri və tapşırıqlar daxildir
3. Bərpa etmək üçün vurun** İdxal** və ehtiyat faylı yükləyin

Proksi reyestr də dəstəkləyir** host + portu ilə upsert** — artıq mövcud olan bir proksi (eyni host və port) idxal etsəniz, o, dublikat yaratmaq əvəzinə yenilənir.

### Legacy Miqrasiya

Əgər proksiləri köhnə versiyada (əvvəlcədən qeydiyyat) konfiqurasiya etmisinizsə, OmniRoute onları avtomatik köçürür:

```
Legacy key_value store → proxy_registry + proxy_assignments
```

Bu, təkmilləşdirmədən sonra ilk işə salındıqda bir dəfə baş verir. Yenidən işləmək üçün `migrateLegacyProxyConfigToRegistry({ force: true })` istifadə edin.

---

## 1proxy Pulsuz Proksi Marketplace

> 🆕** [@oyi77](https://github.com/oyi77) tərəfindən töhfə** — PR [#1847](https://github.com/diegosouzapw/OmniRoute/pull/1847) (Məsələ [#1788](https://github.com/diegosouzapw/OmniRoute/issues/1788) )

OmniRoute ilə inteqrasiya olunur** [1 proksi](https://1proxy-api.aitradepulse.com)** girişi təmin etmək üçün icma platforması** yüzlərlə pulsuz, təsdiqlənmiş proksi** dünyanın hər yerindən. Bu, öz proxy infrastrukturu olmayan istifadəçilər üçün mükəmməldir.

### Necə işləyir

```
┌─────────────┐     Sync      ┌─────────────────┐    Rotate     ┌──────────┐
│  1proxy API │ ────────────▶ │  proxy_registry  │ ────────────▶ │ Provider │
│  (external) │   up to 500   │  source=oneproxy │  by quality   │   API    │
└─────────────┘    proxies    └─────────────────┘               └──────────┘
```

1. **Sinxronizasiya** — OmniRoute təsdiqlənmiş proksiləri 1proxy API-dən alır
2. **Mağaza** — Proksilər `source = 'oneproxy'` ilə eyni `proxy_registry` cədvəlində saxlanılır
3. **Filtr** — Protokol, ölkə, keyfiyyət balı ilə süzün
4. **Döndürün** — Keyfiyyətli, təsadüfi və ya ardıcıl strategiyalardan istifadə edərək ən yaxşı proksi seçin
5. **Avtomatik deqradasiya** — Uğursuz proksilər keyfiyyət xalını azaldır; eşikdən aşağı → qeyri-aktiv olaraq qeyd edildi

### Proksilərin sinxronizasiyası

**İdarə Paneli vasitəsilə:**

1. gedin** Parametrlər → 1proxy** nişanı
2. klikləyin** "İndi sinxronlaşdır"**
3. Statistikaya baxın: ümumi etibarnamələr, aktiv sayı, orta keyfiyyət, ölkə üzrə bölgü

**API vasitəsilə:**

```bash
# Trigger sync
curl -X POST http://localhost:20128/api/settings/oneproxy \
  -H "Content-Type: application/json" \
  -d '{}'

# Response:
# { "success": true, "added": 127, "updated": 45, "failed": 2, "total": 172 }
```

### Proksilərin filtrlənməsi

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

### Proksi keyfiyyət balları

Hər 1 proksi proksi metadata ilə gəlir:

| Sahə            | Təsvir                                            |
| --------------- | ------------------------------------------------- |
| `qualityScore`  | 1 proksi təsdiqindən 0-100 reytinq                |
| `latencyMs`     | Ölçülmüş şəbəkə gecikməsi                         |
| `anonymity`     | `transparent`, `anonymous` və ya `elite`          |
| `googleAccess`  | Proksinin Google xidmətlərinə daxil olub-olmaması |
| `countryCode`   | İki hərfli ISO ölkə kodu                          |
| `lastValidated` | Son doğrulamanın vaxt möhürü                      |

Keyfiyyət balları dinamik şəkildə tənzimlənir:

- **Uğursuz sorğular** xalı 10 bal azaltmaq
- **Hesab ≤ 10-a enir** → proxy `inactive` ilə işarələnib
- Qeyri-aktiv proksilər rotasiyadan xaric edilir

### Rotasiya strategiyaları

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

### Circuit Breaker

1proxy sinxronizasiyası daxili elektrik açarına malikdir:

- sonra** 5 ardıcıl sinxronizasiya uğursuzluğu** , əlavə sinxronizasiya cəhdləri bloklanır
- Sıfırlayın: `resetOneproxyCircuitBreaker()` və ya serveri yenidən başladın
- Sinxronizasiya statusu `GET /api/settings/oneproxy?action=status`-da mövcuddur

### 1 proksi proksilərin təmizlənməsi

```bash
# Delete a single 1proxy proxy
curl -X DELETE "http://localhost:20128/api/settings/oneproxy?id=proxy-uuid"

# Clear ALL 1proxy proxies (manual proxies are untouched)
curl -X DELETE "http://localhost:20128/api/settings/oneproxy?clearAll=1"
```

---

## Aşkarlanma və Gizlilik

OmniRoute yalnız — proksi vasitəsilə trafiki yönləndirmir, həm də trafiki qanuni göstərir:

### TLS Barmaq izi saxtakarlığı

Qeyri-brauzer TLS əl sıxmalarını qeyd edən bot aşkarlama sistemlərindən yan keçərək, brauzerə bənzər TLS barmaq izləri yaratmaq üçün `wreq-js` istifadə edir.

### CLI Barmaq İzi Uyğunluğu

The**CLI Barmaq izi keçidi** (`Settings → Security`) HTTP başlıqlarını və JSON əsas sahələrini yerli CLI ikili faylların (Claude Kodu, Codex və s.) dəqiq imzasına uyğunlaşdırmaq üçün yenidən sıralayır. Bu işləyir** üstündə** proxy:

```
Your IP (blocked) → Proxy IP (US) → Provider API
                    + TLS spoof
                    + CLI fingerprint
```

Hər ikisini alırsınız**IP maskalanması** və** həqiqiliyini tələb edin** eyni vaxtda.

### Proksi IP qorunması

İdarə panelindəki rəng kodlu nişanlar hansı proksi səviyyəsinin aktiv olduğunu göstərir:

| Nişan | Səviyyə   | Mənası                                             |
| ----- | --------- | -------------------------------------------------- |
| 🟢    | Qlobal    | Bütün trafik bu proxy vasitəsilə keçir             |
| 🟡    | Provayder | Yalnız bu provayderin trafiki proksiləşdirilmişdir |
| 🔵    | Əlaqə     | Bu xüsusi key/account bu proksidən istifadə edir   |

Nişan, həmçinin yoxlama üçün həll edilmiş proksi IP göstərir.

---

## Upstream Proxy Rejimləri

CLIProxyAPI modelindən istifadə edən provayderlər üçün OmniRoute üç yuxarı proksi rejimini dəstəkləyir:

| Rejim         | Təsvir                                                     |
| ------------- | ---------------------------------------------------------- |
| `native`      | OmniRoute proksi yönləndirməni birbaşa idarə edir (defolt) |
| `cliproxyapi` | Xarici CLIProxyAPI instansiyasına nümayəndələr             |
| `fallback`    | Əvvəlcə doğma dilini sınayır, CLIProxyAPI ya qayıdır       |

Hər provayder üçün konfiqurasiya edin:

```bash
curl -X PUT "http://localhost:20128/api/upstream-proxy/openai" \
  -H "Content-Type: application/json" \
  -d '{"mode": "native", "enabled": true}'
```

---

## İdarə paneli UI

### Parametrlər → Proxy Tab

- **Qlobal proxy** konfiqurasiya (bütün trafik üçün bir dəfə təyin olunur)
- **Hər provayder proksi** üstələyir
- **Hər bağlantı üçün proksi** tapşırıqlar
- **Bağlantı testi** konfiqurasiya edilmiş proxy vasitəsilə
- **Rəng kodlu nişanlar** aktiv proxy səviyyəsini göstərir

### Parametrlər → 1proxy Tab

- **İndi Sinxronlaşdırın** pulsuz proksiləri əldə etmək üçün düymə
- **Statistika kartları** : Ümumi, Aktiv, Orta Keyfiyyət, Son Sinxronizasiya
- **Filtrlər** : Protokol, Ölkə Kodu, Min Keyfiyyət
- **Proksi cədvəli** host, protokol, ölkə, keyfiyyət hesabı, gecikmə, anonimlik, Google girişi ilə
- **Sinxronizasiya statusu** success/failure izləmə və ardıcıl uğursuzluq sayına malik panel
- **Hamısını Sil** bütün 1 proksi girişini silmək üçün

---

## API İstinad

### Proksi Parametrləri API

| Metod    | Son nöqtə                                      | Təsvir                                |
| -------- | ---------------------------------------------- | ------------------------------------- |
| `GET`    | `/api/settings/proxy`                          | Tam proxy konfiqurasiyasını əldə edin |
| `GET`    | `/api/settings/proxy?level=global`             | Qlobal proxy əldə edin                |
| `GET`    | `/api/settings/proxy?level=provider&id=openai` | Provayder proksisini əldə edin        |
| `GET`    | `/api/settings/proxy?resolve=connectionId`     | Effektiv proxy həll edin              |
| `PUT`    | `/api/settings/proxy`                          | Proksi konfiqurasiyasını yeniləyin    |
| `DELETE` | `/api/settings/proxy?level=provider&id=openai` | Səviyyədə proxy-ni silin              |

### Proxy Registry API

| Metod    | Son nöqtə                                         | Təsvir                        |
| -------- | ------------------------------------------------- | ----------------------------- |
| `GET`    | `/api/v1/management/proxies`                      | Bütün proksiləri sadalayın    |
| `GET`    | `/api/v1/management/proxies?id=uuid`              | ID ilə proxy alın             |
| `GET`    | `/api/v1/management/proxies?id=uuid&where_used=1` | Proksi təyinatları alın       |
| `POST`   | `/api/v1/management/proxies`                      | Proksi yaradın                |
| `PATCH`  | `/api/v1/management/proxies`                      | Proksini yeniləyin            |
| `DELETE` | `/api/v1/management/proxies?id=uuid`              | Proksi silin                  |
| `DELETE` | `/api/v1/management/proxies?id=uuid&force=1`      | Silməyə məcbur edin           |
| `POST`   | `/api/v1/management/proxies/bulk-assign`          | Toplu təyinat                 |
| `GET`    | `/api/v1/management/proxies/assignments`          | Tapşırıqları siyahıya alın    |
| `GET`    | `/api/v1/management/proxies/health`               | Proksi sağlamlıq statistikası |

### Tunellər API

Proksi vasitəsilə gedəni yönləndirmək əvəzinə OmniRoute nümunənizi ictimai internetə (Cloudflare/ngrok/Tailscale) göstərmək üçün [TUNNELS_GUIDE.md-](./TUNNELS_GUIDE.md) ə baxın. Tuneli REST API `/api/tunnels/{cloudflared,ngrok,tailscale}/*` altında yaşayır və yuxarıda sənədləşdirilmiş gedən proxy zəncirinə ortoqonaldır.

### 1 proxy API

| Metod    | Son nöqtə                              | Təsvir                                     |
| -------- | -------------------------------------- | ------------------------------------------ |
| `GET`    | `/api/settings/oneproxy`               | 1 proksi proksi siyahıya alın              |
| `GET`    | `/api/settings/oneproxy?action=stats`  | Stats + sinxronizasiya statusunu əldə edin |
| `GET`    | `/api/settings/oneproxy?action=status` | Yalnız sinxronizasiya statusunu əldə edin  |
| `POST`   | `/api/settings/oneproxy`               | Sinxronizasiyanı işə salın                 |
| `POST`   | `/api/settings/oneproxy/rotate`        | Növbəti proksiyə çevirin                   |
| `DELETE` | `/api/settings/oneproxy?id=uuid`       | Birini silin                               |
| `DELETE` | `/api/settings/oneproxy?clearAll=1`    | Hamısını silin                             |

### Upstream Proxy API

| Metod    | Son nöqtə                         | Təsvir                                    |
| -------- | --------------------------------- | ----------------------------------------- |
| `GET`    | `/api/upstream-proxy/:providerId` | Yuxarı proksi konfiqurasiyasını əldə edin |
| `PUT`    | `/api/upstream-proxy/:providerId` | Upstream proksi rejimini qurun            |
| `DELETE` | `/api/upstream-proxy/:providerId` | Yuxarı proksi konfiqurasiyasını silin     |

---

## Ətraf Mühit Dəyişənləri

| Dəyişən               | Defolt | Təsvir                                                                    |
| --------------------- | ------ | ------------------------------------------------------------------------- |
| `ENABLE_SOCKS5_PROXY` | `true` | SOCKS5 proksi dəstəyini aktivləşdirin ( `.env.example`-də defolt `true` ) |

---

## Problemlərin aradan qaldırılması

### "SOCKS5 proksi deaktivdir"

`.env` faylınızda `ENABLE_SOCKS5_PROXY=true` qurun və yenidən başladın.

### proxy vasitəsilə "socket as up" xətaları

Boş bağlantıları buraxan ucuz proksilərlə bu normaldır. OmniRoute artıq bunu idarə edir:

- Proksi bağlantılarında canlı saxlamağın deaktiv edilməsi (`keepAliveTimeout: 1`)
- Boru kəmərinin deaktiv edilməsi (`pipelining: 0`)
- Təkrar əl sıxmalarının qarşısını almaq üçün dispetçerləri keşləmə

Davam edərsə, başqa proksi cəhd edin və ya 1proksi fırlanma xüsusiyyətindən istifadə edin.

### OAuth zamanı "supported_country_region_territory"

Proksinin konfiqurasiya edildiyinə əmin olun** əvvəl** OAuth axını başlayır. OmniRoute marşrutları OAuth token mübadiləsini konfiqurasiya edilmiş proxy vasitəsilə. Əvvəlcə qlobal və ya provayder səviyyəsində proksi təyin edin, sonra qoşulun.

### Proksi istifadə edilmir

Qətnamə qaydasını yoxlayın:

1. `GET /api/settings/proxy?resolve=your-connection-id` ilə yoxlayın
2. Proksi `status` `active` ( `inactive` deyil) olub olmadığını yoxlayın
3. Proksi təyinat dairəsinin bağlantınıza uyğun olduğundan əmin olun

### 1 proksi sinxronizasiya uğursuz oldu

Sinxronizasiya vəziyyətini yoxlayın:

```bash
curl "http://localhost:20128/api/settings/oneproxy?action=status"
```

`consecutiveFailures >= 5` olarsa, elektrik açarı işə salınmışdır. Sıfırlamaq üçün serveri yenidən başladın və ya əl ilə sıfırlanmasını gözləyin.

---

## Verilənlər bazası sxemi

### `proxy_registry` Cədvəli

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

### `proxy_assignments` Cədvəli

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

## Proksi Sağlamlığının Yoxlanması (v3.8.16 +)

OmniRoute's** proxy sürətli uğursuzluq** mexanizm (`src/lib/proxyHealth.ts`) sürətli TCP əlaqə yoxlanışı vasitəsilə < 2s-də ölü proksiləri aşkar edir, sonra** nəticəni yaddaşda saxlayır** hər sorğuya əlavə xərclərdən qaçınmaq üçün.

### Necə işləyir

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

Bu olmadan, ölü bir proksi uğursuzluqdan əvvəl tam `PROXY_TIMEOUT_MS` (standart 30s) üçün hər sorğunu bloklayardı.

### Tənzimlənən Mühit Dəyişənləri

| Dəyişən                      | Defolt  | Məqsəd                                                  |
| ---------------------------- | ------- | ------------------------------------------------------- |
| `PROXY_FAST_FAIL_TIMEOUT_MS` | `2000`  | sağlamlıq yoxlanışı üçün TCP bağlantısı fasiləsi        |
| `PROXY_HEALTH_CACHE_TTL_MS`  | `30000` | Sağlamlıq nəticəsi nə qədər müddətə yaddaşda saxlanılır |

**Tövsiyə olunan dəyərlər:**

| Ssenari                     | Sürətli uğursuzluq fasiləsi | Cache TTL | Əsaslandırma                                                                         |
| --------------------------- | --------------------------- | --------- | ------------------------------------------------------------------------------------ |
| Yüksək ötürücülü API şlüzü  | 1500ms                      | 60000ms   | Çekləri azaltmaq üçün aqressiv uğursuzluq, daha uzun keş                             |
| Geo-paylanmış qovşaqlar     | 3000ms                      | 15000ms   | Daha yavaş şəbəkələr daha çox vaxt tələb edir; sürətli uğursuzluq üçün daha qısa keş |
| İnkişaf / sınaq             | 1000ms                      | 10000ms   | Yerli proksilərdə sürətli iterasiya                                                  |
| Gizli / aşkarlanma əleyhinə | 2500ms                      | 45000ms   | Sürət limitlərinə səbəb ola biləcək sürətli araşdırmalardan çəkinin                  |

### Proxy Sağlamlığının yoxlanılması

```ts
import { getAllProxyHealthStatuses, invalidateProxyHealth } from "omniroute/proxyHealth";

const statuses = getAllProxyHealthStatuses();
for (const s of statuses) {
  console.log(`${s.proxyUrl} → healthy=${s.healthy}, stale=${s.stale}`);
}

// Force re-check a specific proxy
invalidateProxyHealth("http://user:pass@203.0.113.7:8080");
```

Keş girişi `HEALTH_CACHE_TTL_MS` keçdikdə `stale` bayrağı `true` olur və növbəti sorğu yeni yoxlamaya səbəb olacaq.

### Baş Proksi Tip Defoltları

Sağlamlıq yoxlaması URL sxeminə əsaslanan həssas defoltlardan istifadə edir:

| Sxem                       | Defolt port |
| -------------------------- | ----------- |
| `http://`                  | 8080        |
| `https://`                 | 443         |
| `socks5://` / `socks5h://` | 1080        |

URL da (`http://host:9999`) xüsusi portlar həmişə standart sxemdən üstündür.

---

## Proksi Analitika və Müşahidə Olunabilirlik

OmniRoute operatorlara marşrutlaşdırma nümunələri, gecikmə sıçrayışları və təkrarlanan uğursuzluqları diaqnoz etməyə kömək etmək üçün hər bir proksi istifadəsini izləyir.

### Nə İzlənir

Konfiqurasiya edilmiş proxy vasitəsilə hər sorğu üçün OmniRoute qeyd edir:

| Metrik       | Təsvir                                             |
| ------------ | -------------------------------------------------- |
| `proxy_url`  | Tam proxy URL (identifikasiya məlumatları maskalı) |
| `provider`   | Upstream provayder ID (açıq, antropik və s.)       |
| `latency_ms` | Proksi əl sıxma daxil olmaqla ümumi gediş vaxtı    |
| `connect_ms` | TCP yalnız əlaqə vaxtı                             |
| `status`     | yuxarıdan HTTP status kodu                         |
| `error`      | Sorğu uğursuz olarsa, xəta sinfi                   |
| `timestamp`  | ISO 8601 UTC                                       |

### Məlumata daxil olmaq

```bash
# Recent proxy events
curl -H "Authorization: Bearer $OMNIROUTE_KEY" \
  "http://localhost:20128/api/usage/proxy-logs?limit=100"
```

Həqiqi son nöqtə `/api/usage/proxy-logs` (bax `src/app/api/usage/proxy-logs/route.ts`). Bu son nöqtə dəstəkləyir:

- `GET /api/usage/proxy-logs` — proksi qeydlərini əldə edin
- `DELETE /api/usage/proxy-logs` — bütün proxy qeydlərini təmizləyin

Lazım gələrsə, ümumi statistika birbaşa `proxy_logs` cədvəlindən SQL vasitəsilə sorğulana bilər. İdarə paneli UI ümumi görünüşlər təklif edə bilər.

### Ümumi Nümunələr

**Çılpaq proksi aşkar edin** ( success/failure arasında dəyişir):

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

**Yavaş proksiləri tapın** (p95 gecikmə > 2s):

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

## Rotasiya Strategiyası Qərar Ağacı

Çoxsaylı proksilər əhatə dairəsinə təyin edildikdə, OmniRoute a istifadə edir** fırlanma strategiyası** hər sorğu üçün hansının istifadə olunacağını seçin. Strategiya əhatə səviyyəsində konfiqurasiya edilir (qlobal, hər provayder, hər hesab, hər kombi).

### Mövcud Strategiyalar

| Strategiya         | Nə vaxt istifadə etməli                  | Mübadilə                                                                          |
| ------------------ | ---------------------------------------- | --------------------------------------------------------------------------------- |
| `quality` (defolt) | Qarışıq keyfiyyətli proksilərlə istehsal | Yüksək reytinqli proksilərə üstünlük verir; aşağı reytinqli olanlar ac qala bilər |
| `random`           | Yük paylanması, məxfilik                 | bərabər paylama; keyfiyyət siqnallarına məhəl qoymur                              |
| `sequential`       | Sazlama, deterministik test              | Proksilər arasında ardıcıl olaraq dövr edir; əsaslandırmaq asandır                |

### Qərar ağacı

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

## Öz Proksiləriniz üçün Avtomatik Uğursuzluq İstisnası

1proksi bazarı hovuzu artıq özbaşına uğursuz proksiləri avtomatik pisləşdirir (bax: [Proksi Keyfiyyət Xalları](#proxy-quality-scores) ). Proksilər üçün** sən** reyestrə əlavə edildikdə, fon sağlamlığı planlaşdırıcısı (`src/lib/proxyHealth/scheduler.ts`) heç nəyi silmədən eyni "ölü üzvü avtomatik olaraq zəncirdən çıxarmaq" davranışını təmin edir:

```bash
# .env — soft-disable a proxy after 3 consecutive failed probes, re-enable it
# automatically once it starts answering probes again.
PROXY_AUTO_DISABLE=true
PROXY_AUTO_REMOVE_AFTER=3
```

Çox proksi zəncirinə necə uyğun gəlir:

1. Planlayıcı hər bir qeydə alınmış proksi-ni hər `PROXY_HEALTH_INTERVAL_MS` yoxlayır (standart 10 dəqiqə; minimum 1 dəq).
2. Ardıcıl `PROXY_AUTO_REMOVE_AFTER` sonra** yekun** uğursuzluqlar (həqiqi əlaqə nasazlığı — a timeout və ya zond hədəfinin öz 5xx heç vaxt sayılmaz, bax [Proxy Sağlamlığının Yoxlanması](#proxy-health-checking-v3816) ), proksinin `status` `dead` olaraq təyin edilib.
3. `dead` pool/rotation rezolyusiyasının istifadə etdiyi canlı status filtrinin istisna etdiyi statuslardan biridir, ona görə də əhatə dairəsinin fırlanması (dairəvi rejimli / təsadüfi / yapışqan / gecikmə — [Fırlanma Strategiyası Qərar Ağacına](#rotation-strategy-decision-tree) baxın) həmin proksinin yeni sorğulara verilməsini dərhal dayandırır. Hovuzdakı başqa heç bir proksi təsirlənmir və bütün hovuz heç vaxt səssizcə birbaşa əlaqəyə qayıtmır — [4-Səviyyəli Proksi Sistemi](#4-level-proxy-system) uğursuz qapalı qoruyucuya baxın.
4. The scheduler keeps probing `dead` proxies on the same interval. The next successful probe flips `status` back to `active` and it re-enters rotation — no manual re-add required.

Bu qəsdəndir** qoşulma və dağıdıcı olmayan** : defolt olaraq planlayıcı yalnız uğursuzluqları hesablayır və qeyd edir ( `decision.ts`-da C siyasətinə baxın) və `PROXY_AUTO_DISABLE` heç vaxt ayrı, daha aqressiv `PROXY_AUTO_REMOVE` bayrağının məqsədi olan — cərgəsini silmir. Hər ikisi `true` olaraq təyin edilərsə, `PROXY_AUTO_REMOVE` qalib gəlir (silinmək üzrə olan proksi aralarındakı yumşaq deaktiv üçün heç bir faydası yoxdur). Tam dəyişən siyahısı üçün [Ətraf Mühitin Konfiqurasiyası](../reference/ENVIRONMENT.md) arayışına baxın.

---

> 📖** Əlaqədar sənədlər:**
>
> - [İstifadəçi Təlimatı](../guides/USER_GUIDE.md) — Ümumi quraşdırma və konfiqurasiya - [API İstinad](../reference/API_REFERENCE.md) — Tam API sənədləri - [Ətraf Mühit Konfiqurasiyası](../reference/ENVIRONMENT.md) — Bütün mühit dəyişənləri
