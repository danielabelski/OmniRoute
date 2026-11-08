# 🌐 OmniRoute Proxy Guide (ქართული)

🌐 **Languages:** 🇺🇸 [English](../../../../ops/PROXY_GUIDE.md) · 🇪🇹 [am](../../../am/docs/ops/PROXY_GUIDE.md) · 🇸🇦 [ar](../../../ar/docs/ops/PROXY_GUIDE.md) · 🇦🇿 [az](../../../az/docs/ops/PROXY_GUIDE.md) · 🇧🇬 [bg](../../../bg/docs/ops/PROXY_GUIDE.md) · 🇧🇩 [bn](../../../bn/docs/ops/PROXY_GUIDE.md) · 🇧🇦 [bs](../../../bs/docs/ops/PROXY_GUIDE.md) · 🇨🇿 [cs](../../../cs/docs/ops/PROXY_GUIDE.md) · 🇩🇰 [da](../../../da/docs/ops/PROXY_GUIDE.md) · 🇩🇪 [de](../../../de/docs/ops/PROXY_GUIDE.md) · 🇬🇷 [el](../../../el/docs/ops/PROXY_GUIDE.md) · 🇪🇸 [es](../../../es/docs/ops/PROXY_GUIDE.md) · 🇪🇪 [et](../../../et/docs/ops/PROXY_GUIDE.md) · 🇮🇷 [fa](../../../fa/docs/ops/PROXY_GUIDE.md) · 🇫🇮 [fi](../../../fi/docs/ops/PROXY_GUIDE.md) · 🇫🇷 [fr](../../../fr/docs/ops/PROXY_GUIDE.md) · 🇮🇪 [ga](../../../ga/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [gu](../../../gu/docs/ops/PROXY_GUIDE.md) · 🇳🇬 [ha](../../../ha/docs/ops/PROXY_GUIDE.md) · 🇮🇱 [he](../../../he/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [hi](../../../hi/docs/ops/PROXY_GUIDE.md) · 🇭🇷 [hr](../../../hr/docs/ops/PROXY_GUIDE.md) · 🇭🇺 [hu](../../../hu/docs/ops/PROXY_GUIDE.md) · 🇦🇲 [hy](../../../hy/docs/ops/PROXY_GUIDE.md) · 🇮🇩 [id](../../../id/docs/ops/PROXY_GUIDE.md) · 🇳🇬 [ig](../../../ig/docs/ops/PROXY_GUIDE.md) · 🇮🇹 [it](../../../it/docs/ops/PROXY_GUIDE.md) · 🇯🇵 [ja](../../../ja/docs/ops/PROXY_GUIDE.md) · 🇰🇭 [km](../../../km/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [kn](../../../kn/docs/ops/PROXY_GUIDE.md) · 🇰🇷 [ko](../../../ko/docs/ops/PROXY_GUIDE.md) · 🇱🇹 [lt](../../../lt/docs/ops/PROXY_GUIDE.md) · 🇱🇻 [lv](../../../lv/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [ml](../../../ml/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [mr](../../../mr/docs/ops/PROXY_GUIDE.md) · 🇲🇾 [ms](../../../ms/docs/ops/PROXY_GUIDE.md) · 🇲🇹 [mt](../../../mt/docs/ops/PROXY_GUIDE.md) · 🇲🇲 [my](../../../my/docs/ops/PROXY_GUIDE.md) · 🇳🇵 [ne](../../../ne/docs/ops/PROXY_GUIDE.md) · 🇳🇱 [nl](../../../nl/docs/ops/PROXY_GUIDE.md) · 🇳🇴 [no](../../../no/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [or](../../../or/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [pa](../../../pa/docs/ops/PROXY_GUIDE.md) · 🇵🇭 [phi](../../../phi/docs/ops/PROXY_GUIDE.md) · 🇵🇱 [pl](../../../pl/docs/ops/PROXY_GUIDE.md) · 🇵🇹 [pt](../../../pt/docs/ops/PROXY_GUIDE.md) · 🇧🇷 [pt-BR](../../../pt-BR/docs/ops/PROXY_GUIDE.md) · 🇷🇴 [ro](../../../ro/docs/ops/PROXY_GUIDE.md) · 🇷🇺 [ru](../../../ru/docs/ops/PROXY_GUIDE.md) · 🇱🇰 [si](../../../si/docs/ops/PROXY_GUIDE.md) · 🇸🇰 [sk](../../../sk/docs/ops/PROXY_GUIDE.md) · 🇸🇮 [sl](../../../sl/docs/ops/PROXY_GUIDE.md) · 🇷🇸 [sr](../../../sr/docs/ops/PROXY_GUIDE.md) · 🇸🇪 [sv](../../../sv/docs/ops/PROXY_GUIDE.md) · 🇰🇪 [sw](../../../sw/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [ta](../../../ta/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [te](../../../te/docs/ops/PROXY_GUIDE.md) · 🇹🇭 [th](../../../th/docs/ops/PROXY_GUIDE.md) · 🇹🇷 [tr](../../../tr/docs/ops/PROXY_GUIDE.md) · 🇺🇦 [uk-UA](../../../uk-UA/docs/ops/PROXY_GUIDE.md) · 🇵🇰 [ur](../../../ur/docs/ops/PROXY_GUIDE.md) · 🇺🇿 [uz](../../../uz/docs/ops/PROXY_GUIDE.md) · 🇻🇳 [vi](../../../vi/docs/ops/PROXY_GUIDE.md) · 🇳🇬 [yo](../../../yo/docs/ops/PROXY_GUIDE.md) · 🇨🇳 [zh-CN](../../../zh-CN/docs/ops/PROXY_GUIDE.md) · 🇹🇼 [zh-TW](../../../zh-TW/docs/ops/PROXY_GUIDE.md)

---

> **გვერდის ავლით გეოგრაფიული ბლოკები, დაიცავით თქვენი ვინაობა და გაატარეთ AI ტრაფიკი ნებისმიერი პროქსი — მეშვეობით ნულოვანი კონფიგურაციის სირთულით.**

OmniRoute მოიცავს სრული გამორჩეული პროქსის მართვის სისტემას, რომელიც საშუალებას გაძლევთ მარშრუტოთ AI პროვაიდერის ტრაფიკი HTTP, HTTPS ან SOCKS5 პროქსიების მეშვეობით. მიუხედავად იმისა, ხართ დაბლოკილ რეგიონში, გჭირდებათ IP როტაცია, ან გსურთ ფარული თითის ანაბეჭდი — ეს სახელმძღვანელო მოიცავს ყველაფერს.

---

## სარჩევი

- [რატომ გამოვიყენოთ პროქსი?](#why-use-proxies)
- [არქიტექტურის მიმოხილვა](#architecture-overview)
- [4-დონიანი პროქსი სისტემა](#4-level-proxy-system)
- [პროქსი რეესტრი (CRUD)](#proxy-registry-crud)
- [1 პროქსი უფასო ბაზარი](#1proxy-free-proxy-marketplace)
- [პროქსის როტაცია](#proxy-rotation)
- [ანტი-გამოვლენა და სტელსი](#anti-detection--stealth)
- [ზედა დინების პროქსი რეჟიმები](#upstream-proxy-modes)
- [დაფა UI](#dashboard-ui)
- [API მითითება](#api-reference)
- [გარემოს ცვლადები](#environment-variables)
- [პრობლემების მოგვარება](#troubleshooting)

---

## რატომ გამოვიყენოთ პროქსი?

ბევრი AI პროვაიდერი ზღუდავს წვდომას გეოგრაფიული რეგიონის მიხედვით. დეველოპერები** რუსეთი, ჩინეთი, ირანი, კუბა, თურქეთი** და სხვა ქვეყნებს ექმნებათ შეცდომები, როგორიცაა:

```
unsupported_country_region_territory
```

დაბლოკილი რეგიონების გარეთაც კი, პროქსი სასარგებლოა:

| გამოიყენეთ საქმე              | აღწერა                                                                     |
| ----------------------------- | -------------------------------------------------------------------------- |
| **გეოგრაფიული შემოვლითი გზა** | წვდომა OpenAI, Anthropic, Codex, Copilot დაბლოკილი ქვეყნებიდან             |
| **IP როტაცია**                | გაანაწილეთ მოთხოვნები მრავალ IPs ზე, რათა თავიდან აიცილოთ ტარიფის შეზღუდვა |
| **კონფიდენციალურობა**         | დამალეთ თქვენი რეალური IP ზედა დინების პროვაიდერებისგან                    |
| **შესაბამისობა**              | მარშრუტის მოძრაობა კონკრეტული იურისდიქციების გავლით                        |
| **ტესტირება**                 | მოთხოვნის სიმულაცია სხვადასხვა რეგიონიდან                                  |

---

## არქიტექტურის მიმოხილვა

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

### ძირითადი კომპონენტები

| კომპონენტი                | ფაილი                                        | როლი                                                       |
| ------------------------- | -------------------------------------------- | ---------------------------------------------------------- |
| **მარიონეტული რეესტრი**   | `src/lib/db/proxies.ts`                      | CRUD მარიონეტული ჩანაწერებისთვის + ფარგლების მინიჭებისთვის |
| **პროქსი დისპეჩერი**      | `open-sse/utils/proxyDispatcher.ts`          | ქმნის `undici` ProxyAgent/SOCKS დისპეტჩერებს ქეშირებით     |
| **პროქსის მიღება**        | `open-sse/utils/proxyFetch.ts`               | ახვევს `fetch()` პროქსი დისპეჩერის ინექციით                |
| **პარამეტრების მარშრუტი** | `src/app/api/settings/proxy/route.ts`        | ლეგატიური პროქსის კონფიგურაცია API (GET/PUT/DELETE)        |
| **მართვის მარშრუტი**      | `src/app/api/v1/management/proxies/route.ts` | რეესტრი CRUD API (GET/POST/PATCH/DELETE)                   |
| **1 პროქსი DB**           | `src/lib/db/oneproxy.ts`                     | უფასო მარიონეტული ბაზრის მდგრადობა                         |

---

## ნაგულისხმევი პროქსი მდგომარეობა ახალი ანგარიშებისთვის

In** პარამეტრები → Proxy → გლობალური კონფიგურაცია** , გამოყენება** ჩართეთ პროქსი ნაგულისხმევად ახალი კავშირებისთვის** ახლად დამატებული პროვაიდერის ანგარიშების საწყისი პროქსი სტატუსის ასარჩევად.

ახალი პარამეტრი აკონტროლებს ახლად დამატებული პროვაიდერის ანგარიშების საწყის პროქსი მდგომარეობას. ის არ ცვლის არსებულ ანგარიშებს და არ ცვლის გლობალურ პროქსი გადამრთველს. მისი საწყისი მნიშვნელობა ინარჩუნებს წინა ქცევას. გამორთეთ ერთხელ, რათა შექმნათ მომავალი ანგარიშები პროქსით ნაგულისხმევად გამორთული.

პრიორიტეტი ინახება როგორც `defaultNewConnectionProxyEnabled` არსებული პარამეტრების API მეშვეობით. ის ნაგულისხმევად არის `true` როდესაც არასოდეს არის შენახული. `false` შენახვა ძალაში შედის შემდგომ ახალ ანგარიშებზე გადატვირთვის გარეშე. `POST /api/providers` იღებს სურვილისამებრ მკაცრი ლოგიკური `proxyEnabled`; აშკარა `true` ან `false` უპირატესობას ანიჭებს შექმნის ნაგულისხმევს. დუბლიკატი ანგარიშის გამოტოვება ან OAuth ხელახლა დაკავშირება ინარჩუნებს ამ ანგარიშის შენახულ მდგომარეობას. ინდივიდუალური ანგარიშების შემდგომი ჩართვა ან გამორთვა მაინც შესაძლებელია.

შერჩევითი პროვაიდერის გადარიცხვები იყენებს დანიშნულების ინსტალაციის ნაგულისხმევს ახალი ანგარიშებისთვის და ინარჩუნებს დანიშნულების პოლიტიკას არსებული ანგარიშების შეცვლისას. პროქსის გადართვები არ არის პორტატული გადაცემის ველები. სრული სარეზერვო აღდგენა და ისტორიული JSON/SQL მიგრაცია ინარჩუნებს აღდგენის არსებულ სემანტიკას, მათ შორის შენახული ანგარიშის მნიშვნელობებს და მოძველებული სქემის ნაგულისხმევს; სრული პარამეტრების აღდგენას ასევე შეუძლია ამ პარამეტრის აღდგენა.

ეს პრიორიტეტი არ ანიჭებს მარიონეტს და არ ადგენს, რომ ის ჯანმრთელია ან გამოიყენება. ფაქტობრივი მარშრუტიზაცია მაინც დამოკიდებულია გლობალურ პროქსი გადამრთველზე და პროქსის მოქმედ კონფიგურაციაზე. სინთეტიკური პროვაიდერები მუდმივი ანგარიშის გარეშე, OAuth ტრაფიკი ანგარიშის შექმნამდე, environment/system მარიონეტები და გარე სარეზერვო ქსელები მის ფარგლებს გარეთაა.

## 4-დონიანი პროქსი სისტემა

OmniRoute მხარს უჭერს პროქსის კონფიგურაციას** ოთხი დამოუკიდებელი სფერო** გადაწყვეტილია პრიორიტეტული თანმიმდევრობით:

```
Priority Resolution Order (highest → lowest):

  1. 🔵 Account/Connection Proxy  →  per API key / OAuth connection
  2. 🟡 Provider Proxy            →  per provider (e.g., all OpenAI traffic)
  3. 🟠 Combo Proxy               →  per combo/routing configuration
  4. 🟢 Global Proxy              →  all traffic, all providers
```

### როგორ მუშაობს რეზოლუცია

როდესაც OmniRoute აგზავნის მოთხოვნას ზედა დინების პროვაიდერთან, ის უწოდებს `resolveProxyForConnectionFromRegistry()`, რომელიც ამოწმებს თითოეულ დონეს თანმიმდევრობით:

1. **ანგარიშის დონეზე** — არის თუ არა პროქსი მინიჭებული ამ კონკრეტულ კავშირზე ID?
2. **პროვაიდერის დონე** — არის თუ არა ამ პროვაიდერს მინიჭებული პროქსი (მაგ., `openai`)?
3. **გლობალურ დონეზე** — არის კონფიგურირებული გლობალური პროქსი?
4. **პროქსი არ არის** — პირდაპირი კავშირი პროვაიდერთან.

პირველი მატჩი იმარჯვებს. ეს ნიშნავს, რომ თქვენ შეგიძლიათ დააყენოთ გლობალური პროქსი, როგორც სარეზერვო, მაგრამ გააუქმოთ იგი კონკრეტული პროვაიდერებისთვის ან კავშირებისთვის.

### რა ხდება პროქსი

| მოძრაობის ტიპი          | პროქსი? | შენიშვნები                                   |
| ----------------------- | ------- | -------------------------------------------- |
| ჩატის დასრულება         | ✅      | ყველა `/v1/chat/completions` ითხოვს          |
| ჩაშენებები              | ✅      | `/v1/embeddings`                             |
| გამოსახულების გენერაცია | ✅      | `/v1/images/generations`                     |
| აუდიო (TTS/STT)         | ✅      | `/v1/audio/*`                                |
| OAuth ნიშნის გაცვლა     | ✅      | ხსნის `unsupported_country_region_territory` |
| კავშირის ტესტები        | ✅      | "ტესტი კავშირი" ღილაკი იყენებს პროქსის       |
| ჟეტონის განახლება       | ✅      | ფონის OAuth განახლება                        |
| მოდელის სინქრონიზაცია   | ✅      | მოდელების ჩამონათვალი და აღმოჩენა            |

---

## პროქსი რეესტრი (CRUD)

პროქსი რეესტრი არის SQLite ცხრილი (`proxy_registry`), რომელიც ინახავს თქვენს ყველა პროქსის. თითოეულ პროქსის აქვს:

| ველი       | ტიპი         | აღწერა                                                        |
| ---------- | ------------ | ------------------------------------------------------------- |
| `id`       | UUID         | უნიკალური იდენტიფიკატორი                                      |
| `name`     | სიმებიანი    | ადამიანისთვის წასაკითხი ეტიკეტი                               |
| `type`     | სიმებიანი    | პროტოკოლი: `http`, `https`, `socks5`                          |
| `host`     | სიმებიანი    | პროქსი ჰოსტის სახელი ან IP                                    |
| `port`     | მთელი რიცხვი | პორტის ნომერი                                                 |
| `username` | სიმებიანი    | მომხმარებლის სახელის ავტორიზაცია (დაშიფრულია დასვენების დროს) |
| `password` | სიმებიანი    | ავტორიზაციის პაროლი (დაშიფრულია დასვენების დროს)              |
| `region`   | სიმებიანი    | გეოგრაფიული რეგიონის ეტიკეტი                                  |
| `notes`    | სიმებიანი    | თავისუფალი ტექსტის შენიშვნები                                 |
| `status`   | სიმებიანი    | `active` ან `inactive`                                        |
| `source`   | სიმებიანი    | `manual` ან `oneproxy`                                        |

### პროქსის შექმნა

**დაფის საშუალებით:**

1. გადადით** პარამეტრები → Proxy**
2. დააწკაპუნეთ** პროქსის დამატება**
3. შეავსეთ ტიპი, ჰოსტი, პორტი და არჩევითი ავტორიზაციის სერთიფიკატები
4. შენახვა

**API მეშვეობით:**

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

### პროქსის განახლება

```bash
curl -X PATCH http://localhost:20128/api/v1/management/proxies \
  -H "Content-Type: application/json" \
  -d '{
    "id": "proxy-uuid-here",
    "host": "new-proxy.example.com",
    "port": 9090
  }'
```

> **შენიშვნა:** რწმუნებათა სიგელები შენახულია, თუ ცალსახად არ გაგზავნით ცარიელ შემცვლელებს. ცარიელი სტრიქონების გაგზავნა `username`/`password` სთვის შეინარჩუნებს შენახულ მნიშვნელობებს.

### პროქსის წაშლა

```bash
# Fails if proxy is assigned to any scope
curl -X DELETE "http://localhost:20128/api/v1/management/proxies?id=proxy-uuid"

# Force delete (removes assignments too)
curl -X DELETE "http://localhost:20128/api/v1/management/proxies?id=proxy-uuid&force=1"
```

### პროქსიების ჩამონათვალი

```bash
curl "http://localhost:20128/api/v1/management/proxies?limit=50&offset=0"
```

### პროქსიების მინიჭება Scopes-ზე

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

### ეფექტური პროქსის გადაჭრა

შეამოწმეთ რომელი პროქსი იქნება გამოყენებული მოცემული კავშირისთვის:

```bash
curl "http://localhost:20128/api/settings/proxy?resolve=connection-uuid"
```

აბრუნებს გადაწყვეტილ პროქსის თავისი დონით (`account`, `provider` ან `global`) და წყარო.

### ნაყარი დავალება

მიანიჭეთ ერთი პროქსი რამდენიმე პროვაიდერს ან კავშირს ერთდროულად:

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

მარიონეტები შედის**Backup/Restore** სისტემა. თქვენი OmniRoute კონფიგურაციის ექსპორტის დროს:

1. გადადით** დაფის → პარამეტრები → სარეზერვო**
2. დააწკაპუნეთ** ექსპორტი** მოყვება — მარიონეტული რეესტრი და დავალებები
3. აღსადგენად დააწკაპუნეთ** იმპორტი** და ატვირთეთ სარეზერვო ფაილი

პროქსი რეესტრი ასევე მხარს უჭერს** upsert მასპინძელი + პორტის მიერ** — თუ თქვენ იმპორტირებთ პროქსი, რომელიც უკვე არსებობს (იგივე ჰოსტი და პორტი), ის განახლდება დუბლიკატის შექმნის ნაცვლად.

### მემკვიდრეობითი მიგრაცია

თუ თქვენ დააკონფიგურირეთ მარიონეტები უფრო ძველ ვერსიაში (წინასწარ რეესტრი), OmniRoute ავტომატურად გადაიტანს მათ:

```
Legacy key_value store → proxy_registry + proxy_assignments
```

ეს ხდება ერთხელ გაშვებისას განახლების შემდეგ. გამოიყენეთ `migrateLegacyProxyConfigToRegistry({ force: true })` ხელახლა გასაშვებად.

---

## 1პროქსი უფასო მარიონეტული ბაზარი

> 🆕** წვლილი შეაქვს [@oyi77-](https://github.com/oyi77) ის მიერ** — PR [#1847](https://github.com/diegosouzapw/OmniRoute/pull/1847) (გამოცემა [#1788](https://github.com/diegosouzapw/OmniRoute/issues/1788) )

OmniRoute აერთიანებს** [1 პროქსი](https://1proxy-api.aitradepulse.com)** საზოგადოების პლატფორმა წვდომის უზრუნველსაყოფად** ასობით უფასო, დადასტურებული პროქსი** მთელი მსოფლიოდან. ეს შესანიშნავია მომხმარებლებისთვის, რომლებსაც არ აქვთ საკუთარი პროქსი ინფრასტრუქტურა.

### როგორ მუშაობს

```
┌─────────────┐     Sync      ┌─────────────────┐    Rotate     ┌──────────┐
│  1proxy API │ ────────────▶ │  proxy_registry  │ ────────────▶ │ Provider │
│  (external) │   up to 500   │  source=oneproxy │  by quality   │   API    │
└─────────────┘    proxies    └─────────────────┘               └──────────┘
```

1. **სინქრონიზაცია** — OmniRoute იღებს დადასტურებულ პროქსიებს 1proxy API დან
2. **მაღაზია** — პროქსი ინახება იმავე `proxy_registry` ცხრილში `source = 'oneproxy'` თან ერთად
3. **ფილტრი** — გაფილტრე პროტოკოლის, ქვეყნის, ხარისხის ქულის მიხედვით
4. **როტაცია** — აირჩიეთ საუკეთესო პროქსი ხარისხის, შემთხვევითი ან თანმიმდევრული სტრატეგიების გამოყენებით
5. **ავტომატური დეგრადაცია** — წარუმატებელი მარიონეტები ამცირებენ ხარისხის ქულას; ზღურბლის ქვემოთ → მონიშნულია არააქტიურად

### პროქსიების სინქრონიზაცია

**დაფის საშუალებით:**

1. გადადით** პარამეტრები → 1proxy** ჩანართი
2. დააწკაპუნეთ** "სინქრონიზაცია ახლა"**
3. სტატისტიკის ნახვა: პროქსიების მთლიანი რაოდენობა, აქტიური რაოდენობა, საშუალო ხარისხი, ქვეყნების მიხედვით

**API მეშვეობით:**

```bash
# Trigger sync
curl -X POST http://localhost:20128/api/settings/oneproxy \
  -H "Content-Type: application/json" \
  -d '{}'

# Response:
# { "success": true, "added": 127, "updated": 45, "failed": 2, "total": 172 }
```

### პროქსიების ფილტრაცია

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

### პროქსის ხარისხის ქულები

თითოეული 1 პროქსი პროქსი მოყვება მეტამონაცემებს:

| ველი            | აღწერა                                          |
| --------------- | ----------------------------------------------- |
| `qualityScore`  | 0-100 რეიტინგი 1 პროქსი ვალიდაციისგან           |
| `latencyMs`     | გაზომილი ქსელის შეყოვნება                       |
| `anonymity`     | `transparent`, `anonymous` ან `elite`           |
| `googleAccess`  | შეუძლია თუ არა პროქსის წვდომა Google სერვისებზე |
| `countryCode`   | ქვეყნის ორასოიანი ISO კოდი                      |
| `lastValidated` | ბოლო დადასტურების დროის შტამპი                  |

ხარისხის ქულები დინამიურად რეგულირდება:

- **წარუმატებელი მოთხოვნები** შეამცირეთ ქულა 10 ქულით
- **ქულა ეცემა ≤ 10-მდე** → პროქსი მონიშნულია `inactive`
- არააქტიური მარიონეტები გამორიცხულია როტაციისგან

### როტაციის სტრატეგიები

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

### ამომრთველი

1proxy სინქრონიზაციას აქვს ჩაშენებული ამომრთველი:

- შემდეგ** ზედიზედ 5 სინქრონიზაციის შეცდომა** , შემდგომი სინქრონიზაციის მცდელობები დაბლოკილია
- გადატვირთეთ: `resetOneproxyCircuitBreaker()` ან გადატვირთეთ სერვერი
- სინქრონიზაციის სტატუსი ხელმისაწვდომია `GET /api/settings/oneproxy?action=status` ზე

### 1 პროქსი პროქსის გასუფთავება

```bash
# Delete a single 1proxy proxy
curl -X DELETE "http://localhost:20128/api/settings/oneproxy?id=proxy-uuid"

# Clear ALL 1proxy proxies (manual proxies are untouched)
curl -X DELETE "http://localhost:20128/api/settings/oneproxy?clearAll=1"
```

---

## ანტი-გამოვლენა და სტელსი

OmniRoute არ მარშრუტებს ტრაფიკს მხოლოდ — პროქსის მეშვეობით, არამედ ტრაფიკს ლეგიტიმურად აქცევს:

### TLS თითის ანაბეჭდის გაფუჭება

იყენებს `wreq-js` ბრაუზერის მსგავსი TLS თითის ანაბეჭდების გენერირებისთვის, ბოტის აღმოჩენის სისტემების გვერდის ავლით, რომლებიც ასახელებენ არაბრაუზერის TLS ხელის ჩამორთმევას.

### CLI თითის ანაბეჭდის შესატყვისი

The**CLI თითის ანაბეჭდის გადართვა** (`Settings → Security`) აწესრიგებს HTTP სათაურებს და JSON სხეულის ველებს, რათა შეესაბამებოდეს მშობლიური CLI ბინარების ზუსტ ხელმოწერას (Claude Code, Codex და ა.შ.). ეს მუშაობს** თავზე** პროქსი:

```
Your IP (blocked) → Proxy IP (US) → Provider API
                    + TLS spoof
                    + CLI fingerprint
```

თქვენ მიიღებთ ორივეს**IP ნიღაბი** და** მოითხოვეთ ავთენტურობა** ერთდროულად.

### პროქსი IP კონსერვაცია

საინფორმაციო დაფაზე ფერადი კოდირებული ბეჯები აჩვენებს, თუ რომელი პროქსის დონეა აქტიური:

| ბეჯი | დონე       | მნიშვნელობა                                      |
| ---- | ---------- | ------------------------------------------------ |
| 🟢   | გლობალური  | მთელი ტრაფიკი გადის ამ პროქსის მეშვეობით         |
| 🟡   | პროვაიდერი | მხოლოდ ამ პროვაიდერის ტრაფიკი არის პროქსიირებული |
| 🔵   | კავშირი    | ეს კონკრეტული key/account იყენებს ამ პროქსის     |

ბეჯი ასევე აჩვენებს გადაწყვეტილ პროქსი IP გადამოწმებისთვის.

---

## ზედა დინების პროქსი რეჟიმები

პროვაიდერებისთვის, რომლებიც იყენებენ CLIProxyAPI შაბლონს, OmniRoute მხარს უჭერს სამ ზედა პროქსი რეჟიმს:

| რეჟიმი        | აღწერა                                                             |
| ------------- | ------------------------------------------------------------------ |
| `native`      | OmniRoute ამუშავებს პროქსის მარშრუტიზაციას პირდაპირ (ნაგულისხმევი) |
| `cliproxyapi` | დელეგატები გარე CLIProxyAPI ინსტანციაში                            |
| `fallback`    | ჯერ მშობლიური ცდის, ისევ CLIProxyAPI მოდის                         |

კონფიგურაცია თითო პროვაიდერზე:

```bash
curl -X PUT "http://localhost:20128/api/upstream-proxy/openai" \
  -H "Content-Type: application/json" \
  -d '{"mode": "native", "enabled": true}'
```

---

## დაფა UI

### პარამეტრები → Proxy Tab

- **გლობალური პროქსი** კონფიგურაცია (დაყენებულია ერთხელ ყველა ტრაფიკისთვის)
- **თითო პროვაიდერის პროქსი** აჭარბებს
- **თითო კავშირის პროქსი** დავალებები
- **კავშირის ტესტი** კონფიგურირებული პროქსის მეშვეობით
- **ფერადი კოდირებული სამკერდე ნიშნები** აქტიური პროქსი დონის ჩვენება

### პარამეტრები → 1proxy Tab

- **სინქრონიზაცია ახლა** ღილაკი უფასო პროქსიების მისაღებად
- **სტატისტიკის ბარათები** : სულ, აქტიური, საშუალო ხარისხი, ბოლო სინქრონიზაცია
- **ფილტრები** : პროტოკოლი, ქვეყნის კოდი, მინიმალური ხარისხი
- **პროქსის ცხრილი** მასპინძელი, პროტოკოლი, ქვეყანა, ხარისხის ქულა, შეყოვნება, ანონიმურობა, Google წვდომა
- **სტატუსის სინქრონიზაცია** პანელი success/failure თვალთვალით და თანმიმდევრული წარუმატებლობის რაოდენობით
- **ყველას გასუფთავება** ყველა 1 პროქსი ჩანაწერის წასაშლელად

---

## API მითითება

### პროქსის პარამეტრები API

| მეთოდი   | ბოლო წერტილი                                   | აღწერა                           |
| -------- | ---------------------------------------------- | -------------------------------- |
| `GET`    | `/api/settings/proxy`                          | მიიღეთ სრული პროქსი კონფიგურაცია |
| `GET`    | `/api/settings/proxy?level=global`             | მიიღეთ გლობალური პროქსი          |
| `GET`    | `/api/settings/proxy?level=provider&id=openai` | მიიღეთ პროვაიდერის პროქსი        |
| `GET`    | `/api/settings/proxy?resolve=connectionId`     | ეფექტური პროქსის გადაჭრა         |
| `PUT`    | `/api/settings/proxy`                          | განაახლეთ პროქსი კონფიგურაცია    |
| `DELETE` | `/api/settings/proxy?level=provider&id=openai` | პროქსის ამოღება დონეზე           |

### პროქსი რეესტრი API

| მეთოდი   | ბოლო წერტილი                                      | აღწერა                          |
| -------- | ------------------------------------------------- | ------------------------------- |
| `GET`    | `/api/v1/management/proxies`                      | ჩამოთვალეთ ყველა პროქსი         |
| `GET`    | `/api/v1/management/proxies?id=uuid`              | მიიღეთ პროქსი ID ს მიერ         |
| `GET`    | `/api/v1/management/proxies?id=uuid&where_used=1` | მიიღეთ მარიონეტული დავალებები   |
| `POST`   | `/api/v1/management/proxies`                      | პროქსის შექმნა                  |
| `PATCH`  | `/api/v1/management/proxies`                      | პროქსის განახლება               |
| `DELETE` | `/api/v1/management/proxies?id=uuid`              | პროქსის წაშლა                   |
| `DELETE` | `/api/v1/management/proxies?id=uuid&force=1`      | იძულებითი წაშლა                 |
| `POST`   | `/api/v1/management/proxies/bulk-assign`          | მასობრივი მინიჭება              |
| `GET`    | `/api/v1/management/proxies/assignments`          | ჩამოთვალეთ დავალებები           |
| `GET`    | `/api/v1/management/proxies/health`               | პროქსის ჯანმრთელობის სტატისტიკა |

### გვირაბები API

თქვენი OmniRoute ეგზემპლარის საჯარო ინტერნეტში (Cloudflare/ngrok/Tailscale) გამოსაქვეყნებლად, პროქსის მეშვეობით გამავალი მარშრუტის ნაცვლად, იხილეთ [TUNNELS_GUIDE.md](./TUNNELS_GUIDE.md). გვირაბი REST API ცხოვრობს `/api/tunnels/{cloudflared,ngrok,tailscale}/*` ქვეშ და არის ორთოგონალური ზემოთ დოკუმენტირებული გამავალი მარიონეტული ჯაჭვის მიმართ.

### 1 პროქსი API

| მეთოდი   | ბოლო წერტილი                           | აღწერა                                      |
| -------- | -------------------------------------- | ------------------------------------------- |
| `GET`    | `/api/settings/oneproxy`               | ჩამოთვალეთ 1 პროქსი პროქსი                  |
| `GET`    | `/api/settings/oneproxy?action=stats`  | მიიღეთ სტატისტიკის + სინქრონიზაციის სტატუსი |
| `GET`    | `/api/settings/oneproxy?action=status` | მიიღეთ მხოლოდ სინქრონიზაციის სტატუსი        |
| `POST`   | `/api/settings/oneproxy`               | ტრიგერების სინქრონიზაცია                    |
| `POST`   | `/api/settings/oneproxy/rotate`        | როტაცია შემდეგ პროქსიზე                     |
| `DELETE` | `/api/settings/oneproxy?id=uuid`       | წაშალე ერთი                                 |
| `DELETE` | `/api/settings/oneproxy?clearAll=1`    | გაასუფთავე ყველა                            |

### Upstream Proxy API

| მეთოდი   | ბოლო წერტილი                      | აღწერა                          |
| -------- | --------------------------------- | ------------------------------- |
| `GET`    | `/api/upstream-proxy/:providerId` | მიიღეთ ზედა პროქსი კონფიგურაცია |
| `PUT`    | `/api/upstream-proxy/:providerId` | დააყენეთ ზედა პროქსი რეჟიმი     |
| `DELETE` | `/api/upstream-proxy/:providerId` | წაშალეთ პროქსის კონფიგურაცია    |

---

## გარემოს ცვლადები

| ცვლადი                | ნაგულისხმევი | აღწერა                                                                   |
| --------------------- | ------------ | ------------------------------------------------------------------------ |
| `ENABLE_SOCKS5_PROXY` | `true`       | ჩართეთ SOCKS5 პროქსის მხარდაჭერა (ნაგულისხმევი `true` `.env.example` ში) |

---

## პრობლემების მოგვარება

### "SOCKS5 პროქსი გამორთულია"

დააყენეთ `ENABLE_SOCKS5_PROXY=true` თქვენს `.env` ფაილში და გადატვირთეთ.

### "სოკეტის გათიშვის" შეცდომები პროქსის საშუალებით

ეს ნორმალურია იაფი მარიონეტებით, რომლებიც წყვეტენ უმოქმედო კავშირებს. OmniRoute უკვე ამუშავებს ამას:

- მარიონეტული კავშირების შენარჩუნების გათიშვა (`keepAliveTimeout: 1`)
- მილსადენის გათიშვა (`pipelining: 0`)
- დისპეტჩერების ქეშირება განმეორებითი ხელის ჩამორთმევის თავიდან ასაცილებლად

თუ ის გრძელდება, სცადეთ სხვა პროქსი ან გამოიყენეთ 1პროქსის როტაციის ფუნქცია.

### "unsupported_country_region_territory" OAuth დროს

დარწმუნდით, რომ პროქსი კონფიგურირებულია** ადრე** OAuth ნაკადის დაწყება. OmniRoute მარშრუტებს OAuth ტოკენის გაცვლას კონფიგურირებული პროქსის მეშვეობით. ჯერ დააყენეთ გლობალური ან პროვაიდერის დონის პროქსი, შემდეგ დააკავშირეთ.

### პროქსი არ გამოიყენება

შეამოწმეთ რეზოლუციის ბრძანება:

1. გადაამოწმეთ `GET /api/settings/proxy?resolve=your-connection-id` ით
2. შეამოწმეთ, არის თუ არა `status` პროქსი `active` (არა `inactive`)
3. დარწმუნდით, რომ პროქსის მინიჭების ფარგლები ემთხვევა თქვენს კავშირს

### 1 პროქსის სინქრონიზაცია ვერ მოხერხდა

შეამოწმეთ სინქრონიზაციის სტატუსი:

```bash
curl "http://localhost:20128/api/settings/oneproxy?action=status"
```

თუ `consecutiveFailures >= 5`, ამომრთველი გამორთულია. გადატვირთეთ სერვერი გადატვირთვისთვის, ან დაელოდეთ ხელით გადატვირთვას.

---

## მონაცემთა ბაზის სქემა

### `proxy_registry` მაგიდა

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

### `proxy_assignments` მაგიდა

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

## პროქსის ჯანმრთელობის შემოწმება (v3.8.16 +)

OmniRoute ს** proxy-ის სწრაფი წარუმატებლობა** მექანიზმი (`src/lib/proxyHealth.ts`) აღმოაჩენს მკვდარ პროქსიებს < 2s-ში TCP კავშირის სწრაფი შემოწმების საშუალებით, შემდეგ** ქეშირებს შედეგს** თითო მოთხოვნის ზედნადების თავიდან ასაცილებლად.

### როგორ მუშაობს

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

ამის გარეშე, მკვდარი პროქსი დაბლოკავს ყველა მოთხოვნას სრული `PROXY_TIMEOUT_MS` სთვის (ნაგულისხმევი 30 წლები) წარუმატებლობამდე.

### რეგულირებადი გარემოს ცვლადები

| ცვლადი                       | ნაგულისხმევი | მიზანი                                       |
| ---------------------------- | ------------ | -------------------------------------------- |
| `PROXY_FAST_FAIL_TIMEOUT_MS` | `2000`       | TCP კავშირის დრო ჯანმრთელობის შემოწმებისთვის |
| `PROXY_HEALTH_CACHE_TTL_MS`  | `30000`      | რამდენ ხანს ინახება ჯანმრთელობის შედეგი      |

**რეკომენდებული მნიშვნელობები:**

| სცენარი                              | სწრაფი წარუმატებლობის დრო | Cache TTL | მსჯელობა                                                                |
| ------------------------------------ | ------------------------- | --------- | ----------------------------------------------------------------------- |
| მაღალი გამტარუნარიანობის API კარიბჭე | 1500 ms                   | 60000 მმ  | აგრესიული წარუმატებლობა, უფრო გრძელი ქეში შემოწმებების შესამცირებლად    |
| გეოგანაწილებული კვანძები             | 3000 მმ                   | 15000 ms  | ნელ ქსელებს მეტი დრო სჭირდება; მოკლე ქეში სწრაფი შეფერხებისთვის         |
| Dev / ტესტირება                      | 1000 ms                   | 10000 ms  | სწრაფი გამეორება ადგილობრივ პროქსიებზე                                  |
| სტელსი / ანტი-გამოვლენა              | 2500 ms                   | 45000 მმ  | მოერიდეთ სწრაფ გამოკვლევას, რამაც შეიძლება გამოიწვიოს სიჩქარის ლიმიტები |

### პროქსი ჯანმრთელობის შემოწმება

```ts
import { getAllProxyHealthStatuses, invalidateProxyHealth } from "omniroute/proxyHealth";

const statuses = getAllProxyHealthStatuses();
for (const s of statuses) {
  console.log(`${s.proxyUrl} → healthy=${s.healthy}, stale=${s.stale}`);
}

// Force re-check a specific proxy
invalidateProxyHealth("http://user:pass@203.0.113.7:8080");
```

`stale` დროშა არის `true`, როდესაც ქეშის ჩანაწერი გადააჭარბებს `HEALTH_CACHE_TTL_MS` და შემდეგი მოთხოვნა გამოიწვევს ახალ შემოწმებას.

### თითო პროქსის ტიპის ნაგულისხმევი

ჯანმრთელობის შემოწმება იყენებს გონივრულ ნაგულისხმევს, URL სქემის საფუძველზე:

| სქემა                      | ნაგულისხმევი პორტი |
| -------------------------- | ------------------ |
| `http://`                  | 8080               |
| `https://`                 | 443                |
| `socks5://` / `socks5h://` | 1080               |

მორგებული პორტები URL ში (`http://host:9999`) ყოველთვის უპირატესობას ანიჭებს სქემის ნაგულისხმევს.

---

## პროქსი ანალიტიკა და დაკვირვება

OmniRoute თვალყურს ადევნებს თითო პროქსის გამოყენებას, რათა დაეხმაროს ოპერატორებს მარშრუტიზაციის შაბლონების, შეყოვნების მწვერვალების და განმეორებადი წარუმატებლობის დიაგნოსტიკაში.

### რა არის თვალყური

კონფიგურირებული პროქსის მეშვეობით ყველა მოთხოვნისთვის, OmniRoute ჩაწერს:

| მეტრიკა      | აღწერა                                                     |
| ------------ | ---------------------------------------------------------- |
| `proxy_url`  | სრული პროქსი URL (ავტორის სერთიფიკატები ნიღბიანი)          |
| `provider`   | ზედა დინების პროვაიდერი ID (openai, anthropic და ა.შ.)     |
| `latency_ms` | მთლიანი ორმხრივი დრო მარიონეტული ხელის ჩამორთმევის ჩათვლით |
| `connect_ms` | მხოლოდ TCP დაკავშირების დრო                                |
| `status`     | HTTP სტატუსის კოდი ზემოდან                                 |
| `error`      | შეცდომის კლასი, თუ მოთხოვნა ვერ მოხერხდა                   |
| `timestamp`  | ISO 8601 UTC                                               |

### მონაცემებზე წვდომა

```bash
# Recent proxy events
curl -H "Authorization: Bearer $OMNIROUTE_KEY" \
  "http://localhost:20128/api/usage/proxy-logs?limit=100"
```

რეალური საბოლოო წერტილი არის `/api/usage/proxy-logs` (იხ. `src/app/api/usage/proxy-logs/route.ts`). ეს საბოლოო წერტილი მხარს უჭერს:

- `GET /api/usage/proxy-logs` — პროქსის ჟურნალების მოძიება
- `DELETE /api/usage/proxy-logs` — გაასუფთავეთ ყველა პროქსის ჟურნალი

საჭიროების შემთხვევაში, მთლიანი სტატისტიკის მოძიება შესაძლებელია პირდაპირ `proxy_logs` ცხრილიდან SQL საშუალებით. UI დაფამ შეიძლება შემოგთავაზოთ მთლიანი ხედები.

### საერთო ნიმუშები

**აღმოაჩინე მბრუნავი პროქსი** (მონაცვლეობს success/failure შორის):

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

**იპოვნეთ ნელი მარიონეტები** (p95 შეყოვნება > 2s):

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

## როტაციის სტრატეგიის გადაწყვეტილების ხე

როდესაც რამდენიმე პროქსი ენიჭება სფეროს, OmniRoute იყენებს a** როტაციის სტრატეგია** აირჩიოს რომელი გამოიყენოს თითოეული მოთხოვნისთვის. სტრატეგია კონფიგურირებულია მოცულობის დონეზე (გლობალური, თითო პროვაიდერზე, თითო ანგარიშზე, თითო კომბინირებულზე).

### ხელმისაწვდომი სტრატეგიები

| სტრატეგია                | როდის გამოვიყენოთ                        | ვაჭრობა                                                                                   |
| ------------------------ | ---------------------------------------- | ----------------------------------------------------------------------------------------- |
| `quality` (ნაგულისხმევი) | წარმოება შერეული ხარისხის პროქსით        | უპირატესობას ანიჭებს მაღალრეიტინგულ მარიონეტებს; შეიძლება შიმშილობდნენ დაბალ რეიტინგულებს |
| `random`                 | დატვირთვის განაწილება, კონფიდენციალურობა | თანაბარი განაწილება; უგულებელყოფს ხარისხის სიგნალებს                                      |
| `sequential`             | გამართვა, დეტერმინისტული ტესტირება       | ციკლი მარიონეტების მეშვეობით თანმიმდევრობით; ადვილი დასაბუთება                            |

### გადაწყვეტილების ხე

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

## ავტომატური წარუმატებლობის გამორიცხვა საკუთარი მარიონეტებისთვის

1proxy marketplace pool უკვე ავტომატურად ახდენს წარუმატებელი პროქსიების დეგრადაციას თავისით (იხილეთ [პროქსის ხარისხის ქულები](#proxy-quality-scores) ). მარიონეტებისთვის** შენ** რეესტრში დამატებული, ჯანმრთელობის ფონური განრიგის (`src/lib/proxyHealth/scheduler.ts`) იგივე ქცევა "გამორიცხეთ მკვდარი წევრი ჯაჭვიდან ავტომატურად", არაფრის წაშლის გარეშე:

```bash
# .env — soft-disable a proxy after 3 consecutive failed probes, re-enable it
# automatically once it starts answering probes again.
PROXY_AUTO_DISABLE=true
PROXY_AUTO_REMOVE_AFTER=3
```

როგორ ჯდება ის მრავალ პროქსი ჯაჭვში:

1. განრიგი იკვლევს ყველა რეგისტრირებულ პროქსის ყოველ `PROXY_HEALTH_INTERVAL_MS` (ნაგულისხმევი 10 წთ; მინიმუმ 1 წთ).
2. შემდეგ `PROXY_AUTO_REMOVE_AFTER` ზედიზედ** გადამწყვეტი** წარუმატებლობა (ნამდვილი კავშირის უკმარისობა — დროის ამოწურვა ან ზონდის სამიზნის საკუთარი 5xx არასოდეს ითვლება, იხილეთ [პროქსის ჯანმრთელობის შემოწმება](#proxy-health-checking-v3816) ), პროქსის `status` დაყენებულია `dead`.
3. `dead` არის ერთ-ერთი სტატუსი, რომელსაც ცოცხალი სტატუსის ფილტრი გამორიცხავს pool/rotation გარჩევადობით, ამიტომ სკოპის როტაცია (მრგვალი / შემთხვევითი / წებოვანი / შეყოვნება — იხილეთ [როტაციის სტრატეგიის გადაწყვეტილების ხე](#rotation-strategy-decision-tree) ) დაუყოვნებლივ აჩერებს ამ პროქსის ახალ მოთხოვნებს. აუზში სხვა მარიონეტები არ დაზარალდება და მთელი აუზი არასოდეს უბრუნდება ჩუმად პირდაპირ კავშირს — იხილეთ [4-დონიანი პროქსი სისტემის](#4-level-proxy-system) გაუმართაობით დახურული დაცვა.
4. განრიგი აგრძელებს `dead` მარიონეტების გამოკვლევებს იმავე ინტერვალზე. შემდეგი წარმატებული ზონდი აბრუნებს `status` `active` ზე და ის ხელახლა შედის ბრუნვაში — ხელით ხელახალი დამატება არ არის საჭირო.

ეს არის შეგნებულად** არჩევითი და არა დესტრუქციული** : ნაგულისხმევად, განრიგი მხოლოდ ითვლის და აღრიცხავს წარუმატებლობებს (იხ. პოლიტიკა C `decision.ts` ში) და `PROXY_AUTO_DISABLE` არასოდეს წაშლის — მწკრივს, რისთვისაც არის ცალკე, უფრო აგრესიული `PROXY_AUTO_REMOVE` დროშა. თუ ორივე დაყენებულია `true` ზე, `PROXY_AUTO_REMOVE` იმარჯვებს (პროქსი, რომელიც უნდა წაიშალოს, არ იყენებს მათ შორის soft-disable). იხილეთ [Environment Config](../reference/ENVIRONMENT.md) მითითება სრული ცვლადების სიისთვის.

---

> 📖** დაკავშირებული დოკუმენტაცია:**
>
> - [მომხმარებლის სახელმძღვანელო](../guides/USER_GUIDE.md) — ზოგადი დაყენება და კონფიგურაცია - [API მითითება](../reference/API_REFERENCE.md) — სრული API დოკუმენტაცია - [გარემო კონფიგურაცია](../reference/ENVIRONMENT.md) — გარემოს ყველა ცვლადი
