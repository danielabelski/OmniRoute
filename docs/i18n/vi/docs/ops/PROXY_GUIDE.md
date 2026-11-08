# 🌐 OmniRoute Proxy Guide (Tiếng Việt)

🌐 **Languages:** 🇺🇸 [English](../../../../ops/PROXY_GUIDE.md) · 🇪🇹 [am](../../../am/docs/ops/PROXY_GUIDE.md) · 🇸🇦 [ar](../../../ar/docs/ops/PROXY_GUIDE.md) · 🇦🇿 [az](../../../az/docs/ops/PROXY_GUIDE.md) · 🇧🇬 [bg](../../../bg/docs/ops/PROXY_GUIDE.md) · 🇧🇩 [bn](../../../bn/docs/ops/PROXY_GUIDE.md) · 🇧🇦 [bs](../../../bs/docs/ops/PROXY_GUIDE.md) · 🇨🇿 [cs](../../../cs/docs/ops/PROXY_GUIDE.md) · 🇩🇰 [da](../../../da/docs/ops/PROXY_GUIDE.md) · 🇩🇪 [de](../../../de/docs/ops/PROXY_GUIDE.md) · 🇬🇷 [el](../../../el/docs/ops/PROXY_GUIDE.md) · 🇪🇸 [es](../../../es/docs/ops/PROXY_GUIDE.md) · 🇪🇪 [et](../../../et/docs/ops/PROXY_GUIDE.md) · 🇮🇷 [fa](../../../fa/docs/ops/PROXY_GUIDE.md) · 🇫🇮 [fi](../../../fi/docs/ops/PROXY_GUIDE.md) · 🇫🇷 [fr](../../../fr/docs/ops/PROXY_GUIDE.md) · 🇮🇪 [ga](../../../ga/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [gu](../../../gu/docs/ops/PROXY_GUIDE.md) · 🇳🇬 [ha](../../../ha/docs/ops/PROXY_GUIDE.md) · 🇮🇱 [he](../../../he/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [hi](../../../hi/docs/ops/PROXY_GUIDE.md) · 🇭🇷 [hr](../../../hr/docs/ops/PROXY_GUIDE.md) · 🇭🇺 [hu](../../../hu/docs/ops/PROXY_GUIDE.md) · 🇦🇲 [hy](../../../hy/docs/ops/PROXY_GUIDE.md) · 🇮🇩 [id](../../../id/docs/ops/PROXY_GUIDE.md) · 🇳🇬 [ig](../../../ig/docs/ops/PROXY_GUIDE.md) · 🇮🇹 [it](../../../it/docs/ops/PROXY_GUIDE.md) · 🇯🇵 [ja](../../../ja/docs/ops/PROXY_GUIDE.md) · 🇬🇪 [ka](../../../ka/docs/ops/PROXY_GUIDE.md) · 🇰🇭 [km](../../../km/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [kn](../../../kn/docs/ops/PROXY_GUIDE.md) · 🇰🇷 [ko](../../../ko/docs/ops/PROXY_GUIDE.md) · 🇱🇹 [lt](../../../lt/docs/ops/PROXY_GUIDE.md) · 🇱🇻 [lv](../../../lv/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [ml](../../../ml/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [mr](../../../mr/docs/ops/PROXY_GUIDE.md) · 🇲🇾 [ms](../../../ms/docs/ops/PROXY_GUIDE.md) · 🇲🇹 [mt](../../../mt/docs/ops/PROXY_GUIDE.md) · 🇲🇲 [my](../../../my/docs/ops/PROXY_GUIDE.md) · 🇳🇵 [ne](../../../ne/docs/ops/PROXY_GUIDE.md) · 🇳🇱 [nl](../../../nl/docs/ops/PROXY_GUIDE.md) · 🇳🇴 [no](../../../no/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [or](../../../or/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [pa](../../../pa/docs/ops/PROXY_GUIDE.md) · 🇵🇭 [phi](../../../phi/docs/ops/PROXY_GUIDE.md) · 🇵🇱 [pl](../../../pl/docs/ops/PROXY_GUIDE.md) · 🇵🇹 [pt](../../../pt/docs/ops/PROXY_GUIDE.md) · 🇧🇷 [pt-BR](../../../pt-BR/docs/ops/PROXY_GUIDE.md) · 🇷🇴 [ro](../../../ro/docs/ops/PROXY_GUIDE.md) · 🇷🇺 [ru](../../../ru/docs/ops/PROXY_GUIDE.md) · 🇱🇰 [si](../../../si/docs/ops/PROXY_GUIDE.md) · 🇸🇰 [sk](../../../sk/docs/ops/PROXY_GUIDE.md) · 🇸🇮 [sl](../../../sl/docs/ops/PROXY_GUIDE.md) · 🇷🇸 [sr](../../../sr/docs/ops/PROXY_GUIDE.md) · 🇸🇪 [sv](../../../sv/docs/ops/PROXY_GUIDE.md) · 🇰🇪 [sw](../../../sw/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [ta](../../../ta/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [te](../../../te/docs/ops/PROXY_GUIDE.md) · 🇹🇭 [th](../../../th/docs/ops/PROXY_GUIDE.md) · 🇹🇷 [tr](../../../tr/docs/ops/PROXY_GUIDE.md) · 🇺🇦 [uk-UA](../../../uk-UA/docs/ops/PROXY_GUIDE.md) · 🇵🇰 [ur](../../../ur/docs/ops/PROXY_GUIDE.md) · 🇺🇿 [uz](../../../uz/docs/ops/PROXY_GUIDE.md) · 🇳🇬 [yo](../../../yo/docs/ops/PROXY_GUIDE.md) · 🇨🇳 [zh-CN](../../../zh-CN/docs/ops/PROXY_GUIDE.md) · 🇹🇼 [zh-TW](../../../zh-TW/docs/ops/PROXY_GUIDE.md)

---

> **Bỏ qua các khối địa lý, bảo vệ danh tính của bạn và định tuyến lưu lượng truy cập AI thông qua bất kỳ — proxy nào mà không có độ phức tạp về cấu hình.**

OmniRoute bao gồm một hệ thống quản lý proxy đầy đủ tính năng cho phép bạn định tuyến lưu lượng truy cập của nhà cung cấp AI ngược dòng thông qua các proxy HTTP, HTTPS hoặc SOCKS5. Cho dù bạn đang ở trong khu vực bị chặn, cần xoay IP hay muốn lấy dấu vân tay ẩn — hướng dẫn này sẽ bao gồm mọi thứ.

---

## Mục lục

- [Tại sao nên sử dụng proxy?](#why-use-proxies)
- [Tổng quan về kiến trúc](#architecture-overview)
- [Hệ thống proxy 4 cấp](#4-level-proxy-system)
- [Đăng ký proxy (CRUD)](#proxy-registry-crud)
- [Thị trường miễn phí 1proxy](#1proxy-free-proxy-marketplace)
- [Xoay vòng proxy](#proxy-rotation)
- [Chống phát hiện & tàng hình](#anti-detection--stealth)
- [Chế độ proxy ngược dòng](#upstream-proxy-modes)
- [Trang tổng quan UI](#dashboard-ui)
- [tham khảo API](#api-reference)
- [Biến môi trường](#environment-variables)
- [Khắc phục sự cố](#troubleshooting)

---

## Tại sao nên sử dụng proxy?

Nhiều nhà cung cấp AI hạn chế quyền truy cập theo khu vực địa lý. Nhà phát triển ở** Nga, Trung Quốc, Iran, Cuba, Thổ Nhĩ Kỳ** , và các nước khác gặp lỗi như:

```
unsupported_country_region_territory
```

Ngay cả bên ngoài các khu vực bị chặn, proxy vẫn hữu ích cho:

| Trường hợp sử dụng     | Sự miêu tả                                                         |
| ---------------------- | ------------------------------------------------------------------ |
| **Đường tránh địa lý** | Truy cập OpenAI, Anthropic, Codex, Copilot từ các quốc gia bị chặn |
| **xoay IP**            | Phân phối yêu cầu trên nhiều IPs để tránh giới hạn tốc độ          |
| **Sự riêng tư**        | Ẩn IP thực sự của bạn khỏi các nhà cung cấp ngược dòng             |
| **Sự tuân thủ**        | Định tuyến lưu lượng truy cập thông qua các khu vực pháp lý cụ thể |
| **Kiểm tra**           | Mô phỏng các yêu cầu từ các khu vực khác nhau                      |

---

## Tổng quan về kiến trúc

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

### Thành phần chính

| Thành phần                | Tài liệu                                     | Vai trò                                                   |
| ------------------------- | -------------------------------------------- | --------------------------------------------------------- |
| **Đăng ký proxy**         | `src/lib/db/proxies.ts`                      | CRUD cho các mục proxy phép gán phạm vi +                 |
| **Người điều phối proxy** | `open-sse/utils/proxyDispatcher.ts`          | Tạo bộ điều phối `undici` ProxyAgent/SOCKS với bộ nhớ đệm |
| **Tìm nạp proxy**         | `open-sse/utils/proxyFetch.ts`               | Kết thúc `fetch()` bằng cách chèn bộ điều phối proxy      |
| **Lộ trình cài đặt**      | `src/app/api/settings/proxy/route.ts`        | Cấu hình proxy kế API (GET/PUT/DELETE)                    |
| **Lộ trình quản lý**      | `src/app/api/v1/management/proxies/route.ts` | Đăng ký CRUD API (GET/POST/PATCH/DELETE)                  |
| **1proxy DB**             | `src/lib/db/oneproxy.ts`                     | Sự kiên trì của thị trường proxy miễn phí                 |

---

## Trạng thái proxy mặc định cho tài khoản mới

TRONG** Cài đặt → Proxy → Cấu hình toàn cầu** , sử dụng** Bật proxy theo mặc định cho các kết nối mới** để chọn trạng thái proxy ban đầu của tài khoản nhà cung cấp mới được thêm vào.

Cài đặt mới kiểm soát trạng thái proxy ban đầu của tài khoản nhà cung cấp mới được thêm vào. Nó không thay đổi các tài khoản hiện có hoặc thay thế chuyển đổi proxy toàn cầu. Giá trị ban đầu của nó duy trì hành vi trước đó. Tắt nó một lần để tạo các tài khoản trong tương lai với proxy bị tắt theo mặc định.

Tùy chọn được lưu trữ dưới dạng `defaultNewConnectionProxyEnabled` thông qua Cài đặt API hiện có. Nó mặc định là `true` khi không bao giờ được lưu. Việc lưu `false` có hiệu lực đối với các tài khoản mới tiếp theo mà không cần khởi động lại. `POST /api/providers` chấp nhận một boolean `proxyEnabled` nghiêm ngặt tùy chọn; `true` hoặc `false` rõ ràng được ưu tiên hơn mặc định tạo. Việc bỏ sót một tài khoản trùng lặp hoặc kết nối lại OAuth sẽ duy trì trạng thái được lưu trữ của tài khoản đó. Tài khoản cá nhân vẫn có thể được kích hoạt hoặc vô hiệu hóa sau đó.

Chuyển nhà cung cấp có chọn lọc sử dụng cài đặt mặc định của cài đặt đích cho các tài khoản mới và duy trì chính sách đích khi thay thế các tài khoản hiện có. Chuyển đổi proxy không phải là trường chuyển di động. Khôi phục sao lưu toàn bộ và di chuyển JSON/SQL lịch sử giữ lại ngữ nghĩa khôi phục hiện có của chúng, bao gồm các giá trị tài khoản đã lưu và mặc định lược đồ cũ; khôi phục cài đặt đầy đủ cũng có thể khôi phục tùy chọn này.

Tùy chọn này không chỉ định proxy hoặc xác nhận rằng proxy đó hoạt động tốt hoặc đang được sử dụng. Định tuyến thực tế vẫn phụ thuộc vào chuyển đổi proxy toàn cầu và cấu hình proxy hiện hành. Các nhà cung cấp tổng hợp không có tài khoản liên tục, lưu lượng truy cập OAuth trước khi tạo tài khoản, proxy environment/system và mạng của các chương trình phụ trợ bên ngoài đều nằm ngoài phạm vi của nó.

## Hệ thống proxy 4 cấp

OmniRoute hỗ trợ cấu hình proxy tại** bốn phạm vi độc lập** , giải quyết theo thứ tự ưu tiên:

```
Priority Resolution Order (highest → lowest):

  1. 🔵 Account/Connection Proxy  →  per API key / OAuth connection
  2. 🟡 Provider Proxy            →  per provider (e.g., all OpenAI traffic)
  3. 🟠 Combo Proxy               →  per combo/routing configuration
  4. 🟢 Global Proxy              →  all traffic, all providers
```

### Độ phân giải hoạt động như thế nào

Khi OmniRoute gửi yêu cầu đến nhà cung cấp ngược dòng, nó sẽ gọi `resolveProxyForConnectionFromRegistry()` để kiểm tra từng cấp độ theo thứ tự:

1. **Cấp tài khoản** — Có proxy nào được chỉ định cho kết nối ID cụ thể này không?
2. **Cấp nhà cung cấp** — Có proxy nào được chỉ định cho nhà cung cấp này không (ví dụ: `openai`)?
3. **Cấp độ toàn cầu** — Có proxy toàn cầu được định cấu hình không?
4. **Không có proxy** — Kết nối trực tiếp với nhà cung cấp.

Trận đầu tiên thắng. Điều này có nghĩa là bạn có thể đặt proxy chung làm dự phòng nhưng ghi đè proxy đó cho các nhà cung cấp hoặc kết nối cụ thể.

### Những gì được ủy quyền

| Loại lưu lượng truy cập     | Được ủy quyền? | Ghi chú                                           |
| --------------------------- | -------------- | ------------------------------------------------- |
| Hoàn thành trò chuyện       | ✅             | Tất cả các yêu cầu `/v1/chat/completions`         |
| Nhúng                       | ✅             | `/v1/embeddings`                                  |
| Tạo hình ảnh                | ✅             | `/v1/images/generations`                          |
| Âm thanh (TTS/STT)          | ✅             | `/v1/audio/*`                                     |
| trao đổi mã thông báo OAuth | ✅             | Giải quyết `unsupported_country_region_territory` |
| Kiểm tra kết nối            | ✅             | Nút "Kiểm tra kết nối" sử dụng proxy              |
| Làm mới mã thông báo        | ✅             | Gia hạn nền tảng OAuth                            |
| Đồng bộ hóa mô hình         | ✅             | Danh sách và khám phá mô hình                     |

---

## Đăng ký proxy (CRUD)

Sổ đăng ký proxy là một bảng SQLite (`proxy_registry`) lưu trữ tất cả các proxy của bạn. Mỗi proxy có:

| Cánh đồng  | Kiểu      | Sự miêu tả                                           |
| ---------- | --------- | ---------------------------------------------------- |
| `id`       | UUID      | Mã định danh duy nhất                                |
| `name`     | Sợi dây   | Nhãn có thể đọc được                                 |
| `type`     | Sợi dây   | Giao thức: `http`, `https`, `socks5`                 |
| `host`     | Sợi dây   | Tên máy chủ proxy hoặc IP                            |
| `port`     | số nguyên | Số cổng                                              |
| `username` | Sợi dây   | Tên người dùng xác thực (được mã hóa ở phần còn lại) |
| `password` | Sợi dây   | Mật khẩu xác thực (được mã hóa ở phần còn lại)       |
| `region`   | Sợi dây   | Nhãn khu vực địa lý                                  |
| `notes`    | Sợi dây   | Ghi chú văn bản tự do                                |
| `status`   | Sợi dây   | `active` hoặc `inactive`                             |
| `source`   | Sợi dây   | `manual` hoặc `oneproxy`                             |

### Tạo một proxy

**Thông qua Bảng điều khiển:**

1. đi đến** Cài đặt → Proxy**
2. nhấp chuột** Thêm proxy**
3. Điền vào loại, máy chủ, cổng và thông tin xác thực tùy chọn
4. Cứu

**Thông qua API:**

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

### Cập nhật proxy

```bash
curl -X PATCH http://localhost:20128/api/v1/management/proxies \
  -H "Content-Type: application/json" \
  -d '{
    "id": "proxy-uuid-here",
    "host": "new-proxy.example.com",
    "port": 9090
  }'
```

> **Ghi chú:** Thông tin xác thực được giữ nguyên trừ khi bạn gửi rõ ràng các thông tin thay thế không trống. Gửi chuỗi trống cho `username`/`password` sẽ giữ các giá trị được lưu trữ.

### Xóa proxy

```bash
# Fails if proxy is assigned to any scope
curl -X DELETE "http://localhost:20128/api/v1/management/proxies?id=proxy-uuid"

# Force delete (removes assignments too)
curl -X DELETE "http://localhost:20128/api/v1/management/proxies?id=proxy-uuid&force=1"
```

### Liệt kê proxy

```bash
curl "http://localhost:20128/api/v1/management/proxies?limit=50&offset=0"
```

### Gán proxy cho phạm vi

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

### Giải quyết Proxy hiệu quả

Kiểm tra proxy nào sẽ được sử dụng cho một kết nối nhất định:

```bash
curl "http://localhost:20128/api/settings/proxy?resolve=connection-uuid"
```

Trả về proxy đã giải quyết với cấp độ (`account`, `provider` hoặc `global`) và nguồn của nó.

### Bài tập hàng loạt

Chỉ định một proxy cho nhiều nhà cung cấp hoặc kết nối cùng một lúc:

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

Proxy được bao gồm trong**Backup/Restore** hệ thống. Khi bạn xuất cấu hình OmniRoute của mình:

1. đi đến** Bảng điều khiển → Cài đặt → Sao lưu**
2. nhấp chuột** Xuất khẩu** đăng ký proxy — và các bài tập được bao gồm
3. Để khôi phục, hãy nhấp vào** Nhập khẩu** và tải lên tập tin sao lưu

Cơ quan đăng ký proxy cũng hỗ trợ** upsert bởi cổng + máy chủ** — nếu bạn nhập một proxy đã tồn tại (cùng máy chủ và cổng), nó sẽ cập nhật thay vì tạo một bản sao.

### Di chuyển kế thừa

Nếu bạn đã định cấu hình proxy ở phiên bản cũ hơn (đăng ký trước), OmniRoute sẽ tự động di chuyển chúng:

```
Legacy key_value store → proxy_registry + proxy_assignments
```

Điều này xảy ra một lần trong lần khởi động đầu tiên sau khi nâng cấp. Sử dụng `migrateLegacyProxyConfigToRegistry({ force: true })` để chạy lại.

---

## Thị trường proxy miễn phí 1proxy

> 🆕** Được đóng góp bởi [@oyi77](https://github.com/oyi77)** — PR [#1847](https://github.com/diegosouzapw/OmniRoute/pull/1847) (Vấn đề [#1788](https://github.com/diegosouzapw/OmniRoute/issues/1788) )

OmniRoute tích hợp với** [1 người đại diện](https://1proxy-api.aitradepulse.com)** nền tảng cộng đồng để cung cấp quyền truy cập vào** hàng trăm proxy miễn phí, được xác thực** từ khắp nơi trên thế giới. Điều này hoàn hảo cho những người dùng không có cơ sở hạ tầng proxy của riêng họ.

### Nó hoạt động như thế nào

```
┌─────────────┐     Sync      ┌─────────────────┐    Rotate     ┌──────────┐
│  1proxy API │ ────────────▶ │  proxy_registry  │ ────────────▶ │ Provider │
│  (external) │   up to 500   │  source=oneproxy │  by quality   │   API    │
└─────────────┘    proxies    └─────────────────┘               └──────────┘
```

1. **Đồng bộ hóa** — OmniRoute tìm nạp các proxy đã được xác thực từ 1proxy API
2. **Cửa hàng** Proxy — được lưu trong cùng bảng `proxy_registry` với `source = 'oneproxy'`
3. **Lọc** — Lọc theo giao thức, quốc gia, điểm chất lượng
4. **Quay** — Chọn proxy tốt nhất bằng cách sử dụng các chiến lược chất lượng, ngẫu nhiên hoặc tuần tự
5. **Tự động xuống cấp** — Proxy không thành công sẽ bị giảm điểm chất lượng; dưới ngưỡng → được đánh dấu là không hoạt động

### Đồng bộ hóa proxy

**Thông qua Bảng điều khiển:**

1. đi đến** Cài đặt → 1proxy** tab
2. nhấp chuột** "Đồng bộ hóa ngay bây giờ"**
3. Xem số liệu thống kê: tổng số proxy, số lượng hoạt động, chất lượng trung bình, phân tích theo quốc gia

**Thông qua API:**

```bash
# Trigger sync
curl -X POST http://localhost:20128/api/settings/oneproxy \
  -H "Content-Type: application/json" \
  -d '{}'

# Response:
# { "success": true, "added": 127, "updated": 45, "failed": 2, "total": 172 }
```

### Lọc proxy

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

### Điểm chất lượng proxy

Mỗi proxy 1proxy đi kèm với siêu dữ liệu:

| Cánh đồng       | Sự miêu tả                                          |
| --------------- | --------------------------------------------------- |
| `qualityScore`  | Xếp hạng 0-100 từ xác thực 1proxy                   |
| `latencyMs`     | Độ trễ mạng được đo                                 |
| `anonymity`     | `transparent`, `anonymous` hoặc `elite`             |
| `googleAccess`  | Liệu proxy có thể truy cập dịch vụ Google hay không |
| `countryCode`   | Mã quốc gia ISO hai chữ cái                         |
| `lastValidated` | Dấu thời gian xác thực lần cuối                     |

Điểm chất lượng được điều chỉnh linh hoạt:

- **Yêu cầu không thành công** giảm điểm 10
- **Điểm giảm xuống ≤ 10** proxy → được đánh dấu `inactive`
- Proxy không hoạt động được loại trừ khỏi vòng quay

### Chiến lược luân chuyển

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

### Bộ ngắt mạch

Đồng bộ hóa 1proxy có bộ ngắt mạch tích hợp:

- Sau đó** 5 lỗi đồng bộ liên tiếp** , các nỗ lực đồng bộ hóa tiếp theo sẽ bị chặn
- Đặt lại bằng: `resetOneproxyCircuitBreaker()` hoặc khởi động lại máy chủ
- Trạng thái đồng bộ hóa có sẵn tại `GET /api/settings/oneproxy?action=status`

### Xóa 1 proxy proxy

```bash
# Delete a single 1proxy proxy
curl -X DELETE "http://localhost:20128/api/settings/oneproxy?id=proxy-uuid"

# Clear ALL 1proxy proxies (manual proxies are untouched)
curl -X DELETE "http://localhost:20128/api/settings/oneproxy?clearAll=1"
```

---

## Chống phát hiện & tàng hình

OmniRoute không chỉ định tuyến lưu lượng truy cập thông qua — proxy mà nó còn làm cho lưu lượng truy cập trông có vẻ hợp pháp:

### TLS mạo dấu vân tay

Sử dụng `wreq-js` để tạo dấu vân tay TLS giống trình duyệt, bỏ qua các hệ thống phát hiện bot gắn cờ các lần bắt tay TLS không phải trình duyệt.

### Đối sánh dấu vân tay CLI

các** chuyển đổi vân tay CLI** (`Settings → Security`) sắp xếp lại các tiêu đề HTTP và các trường nội dung JSON để khớp với chữ ký chính xác của các tệp nhị phân CLI gốc (Claude Code, Codex, v.v.). Cái này hoạt động** trên đầu trang** người đại diện:

```
Your IP (blocked) → Proxy IP (US) → Provider API
                    + TLS spoof
                    + CLI fingerprint
```

Bạn nhận được cả hai** mặt nạ IP** Và** yêu cầu tính xác thực** đồng thời.

### Bảo quản IP proxy

Huy hiệu được mã hóa màu trong trang tổng quan cho biết cấp độ proxy nào đang hoạt động:

| Huy hiệu | Mức độ       | Nghĩa                                                     |
| -------- | ------------ | --------------------------------------------------------- |
| 🟢       | Toàn cầu     | Tất cả lưu lượng truy cập đều đi qua proxy này            |
| 🟡       | nhà cung cấp | Chỉ lưu lượng truy cập của nhà cung cấp này được ủy quyền |
| 🔵       | Sự liên quan | key/account cụ thể này sử dụng proxy này                  |

Huy hiệu cũng hiển thị IP proxy đã được giải quyết để xác minh.

---

## Chế độ proxy ngược dòng

Đối với các nhà cung cấp sử dụng mẫu CLIProxyAPI, OmniRoute hỗ trợ ba chế độ proxy ngược dòng:

| Cách thức     | Sự miêu tả                                            |
| ------------- | ----------------------------------------------------- |
| `native`      | OmniRoute xử lý định tuyến proxy trực tiếp (mặc định) |
| `cliproxyapi` | Đại biểu cho một cá thể CLIProxyAPI bên ngoài         |
| `fallback`    | Thử bản địa trước, quay lại CLIProxyAPI               |

Định cấu hình cho mỗi nhà cung cấp:

```bash
curl -X PUT "http://localhost:20128/api/upstream-proxy/openai" \
  -H "Content-Type: application/json" \
  -d '{"mode": "native", "enabled": true}'
```

---

## Trang tổng quan UI

### Cài đặt Tab Proxy →

- **Proxy toàn cầu** cấu hình (đặt một lần cho tất cả lưu lượng truy cập)
- **Proxy của mỗi nhà cung cấp** ghi đè
- **Proxy mỗi kết nối** bài tập
- **Kiểm tra kết nối** thông qua proxy được cấu hình
- **Huy hiệu có mã màu** hiển thị cấp độ proxy hoạt động

### Cài đặt tab → 1proxy

- **Đồng bộ hóa ngay bây giờ** nút để lấy proxy miễn phí
- **Thẻ thống kê** : Tổng cộng, Đang hoạt động, Chất lượng trung bình, Đồng bộ hóa lần cuối
- **Bộ lọc** : Giao thức, Mã quốc gia, Chất lượng tối thiểu
- **Bảng proxy** với máy chủ, giao thức, quốc gia, điểm chất lượng, độ trễ, ẩn danh, quyền truy cập Google
- **Trạng thái đồng bộ hóa** bảng điều khiển với tính năng theo dõi success/failure và số lần thất bại liên tiếp
- **Xóa tất cả** để xóa tất cả các mục 1proxy

---

## tham khảo API

### Cài đặt proxy API

| Phương pháp | Điểm cuối                                      | Sự miêu tả                  |
| ----------- | ---------------------------------------------- | --------------------------- |
| `GET`       | `/api/settings/proxy`                          | Nhận cấu hình proxy đầy đủ  |
| `GET`       | `/api/settings/proxy?level=global`             | Nhận proxy toàn cầu         |
| `GET`       | `/api/settings/proxy?level=provider&id=openai` | Nhận proxy của nhà cung cấp |
| `GET`       | `/api/settings/proxy?resolve=connectionId`     | Giải quyết proxy hiệu quả   |
| `PUT`       | `/api/settings/proxy`                          | Cập nhật cấu hình proxy     |
| `DELETE`    | `/api/settings/proxy?level=provider&id=openai` | Xóa proxy ở cấp độ          |

### Đăng ký proxy API

| Phương pháp | Điểm cuối                                         | Sự miêu tả                               |
| ----------- | ------------------------------------------------- | ---------------------------------------- |
| `GET`       | `/api/v1/management/proxies`                      | Liệt kê tất cả các proxy                 |
| `GET`       | `/api/v1/management/proxies?id=uuid`              | Nhận proxy bằng ID                       |
| `GET`       | `/api/v1/management/proxies?id=uuid&where_used=1` | Nhận nhiệm vụ proxy                      |
| `POST`      | `/api/v1/management/proxies`                      | Tạo proxy                                |
| `PATCH`     | `/api/v1/management/proxies`                      | Cập nhật proxy                           |
| `DELETE`    | `/api/v1/management/proxies?id=uuid`              | Xóa proxy                                |
| `DELETE`    | `/api/v1/management/proxies?id=uuid&force=1`      | Buộc xóa                                 |
| `POST`      | `/api/v1/management/proxies/bulk-assign`          | Chỉ định hàng loạt                       |
| `GET`       | `/api/v1/management/proxies/assignments`          | Liệt kê bài tập                          |
| `GET`       | `/api/v1/management/proxies/health`               | Số liệu thống kê về tình trạng của proxy |

### Đường hầm API

Để hiển thị phiên bản OmniRoute của bạn với internet công cộng (Cloudflare/ngrok/Tailscale) thay vì định tuyến ra ngoài thông qua proxy, hãy xem [TUNNELS_GUIDE.md](./TUNNELS_GUIDE.md). Đường hầm REST API nằm trong `/api/tunnels/{cloudflared,ngrok,tailscale}/*` và trực giao với chuỗi proxy gửi đi được ghi ở trên.

### 1proxy API

| Phương pháp | Điểm cuối                              | Sự miêu tả                                     |
| ----------- | -------------------------------------- | ---------------------------------------------- |
| `GET`       | `/api/settings/oneproxy`               | Liệt kê 1 proxy proxy                          |
| `GET`       | `/api/settings/oneproxy?action=stats`  | Nhận số liệu thống kê trạng thái đồng bộ hóa + |
| `GET`       | `/api/settings/oneproxy?action=status` | Chỉ nhận trạng thái đồng bộ hóa                |
| `POST`      | `/api/settings/oneproxy`               | Đồng bộ hóa kích hoạt                          |
| `POST`      | `/api/settings/oneproxy/rotate`        | Xoay sang proxy tiếp theo                      |
| `DELETE`    | `/api/settings/oneproxy?id=uuid`       | Xóa một                                        |
| `DELETE`    | `/api/settings/oneproxy?clearAll=1`    | Xóa tất cả                                     |

### Proxy ngược dòng API

| Phương pháp | Điểm cuối                         | Sự miêu tả                     |
| ----------- | --------------------------------- | ------------------------------ |
| `GET`       | `/api/upstream-proxy/:providerId` | Nhận cấu hình proxy ngược dòng |
| `PUT`       | `/api/upstream-proxy/:providerId` | Đặt chế độ proxy ngược dòng    |
| `DELETE`    | `/api/upstream-proxy/:providerId` | Xóa cấu hình proxy ngược dòng  |

---

## Biến môi trường

| Biến                  | Mặc định | Sự miêu tả                                                      |
| --------------------- | -------- | --------------------------------------------------------------- |
| `ENABLE_SOCKS5_PROXY` | `true`   | Bật hỗ trợ proxy SOCKS5 ( `true` mặc định trong `.env.example`) |

---

## Khắc phục sự cố

### " proxy SOCKS5 bị tắt"

Đặt `ENABLE_SOCKS5_PROXY=true` trong tệp `.env` của bạn và khởi động lại.

### lỗi "gác máy" thông qua proxy

Điều này là bình thường với các proxy giá rẻ làm mất kết nối nhàn rỗi. OmniRoute đã xử lý việc này bằng cách:

- Vô hiệu hóa tính năng duy trì kết nối proxy (`keepAliveTimeout: 1`)
- Vô hiệu hóa đường ống (`pipelining: 0`)
- Bộ điều phối bộ nhớ đệm để tránh bắt tay nhiều lần

Nếu tình trạng này vẫn tiếp diễn, hãy thử proxy khác hoặc sử dụng tính năng xoay 1proxy.

### "unsupported_country_khu vực_lãnh thổ" trong OAuth

Đảm bảo proxy được định cấu hình** trước** bắt đầu dòng OAuth. OmniRoute định tuyến trao đổi mã thông báo OAuth thông qua proxy được định cấu hình. Trước tiên hãy đặt proxy toàn cầu hoặc cấp nhà cung cấp, sau đó kết nối.

### Proxy không được sử dụng

Kiểm tra thứ tự giải quyết:

1. Xác minh bằng `GET /api/settings/proxy?resolve=your-connection-id`
2. Kiểm tra xem `status` proxy có phải là `active` (không phải `inactive`)
3. Đảm bảo phạm vi gán proxy phù hợp với kết nối của bạn

### 1đồng bộ hóa proxy không thành công

Kiểm tra trạng thái đồng bộ:

```bash
curl "http://localhost:20128/api/settings/oneproxy?action=status"
```

Nếu `consecutiveFailures >= 5`, cầu dao đã bị ngắt. Khởi động lại máy chủ để đặt lại hoặc đợi đặt lại thủ công.

---

## Lược đồ cơ sở dữ liệu

### Bảng `proxy_registry`

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

### Bảng `proxy_assignments`

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

## Kiểm tra tình trạng proxy (v3.8.16 +)

của OmniRoute** proxy nhanh chóng thất bại** cơ chế (`src/lib/proxyHealth.ts`) phát hiện các proxy chết trong < 2s thông qua kiểm tra kết nối TCP nhanh, sau đó** lưu trữ kết quả** để tránh chi phí theo yêu cầu.

### Nó hoạt động như thế nào

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

Nếu không có điều này, một proxy chết sẽ chặn mọi yêu cầu cho toàn bộ `PROXY_TIMEOUT_MS` (30 giây mặc định) trước khi thất bại.

### Biến môi trường có thể điều chỉnh

| Biến                         | Mặc định | Mục đích                                                |
| ---------------------------- | -------- | ------------------------------------------------------- |
| `PROXY_FAST_FAIL_TIMEOUT_MS` | `2000`   | hết thời gian kết nối TCP cho mỗi lần kiểm tra sức khỏe |
| `PROXY_HEALTH_CACHE_TTL_MS`  | `30000`  | Kết quả sức khỏe được lưu trữ trong bao lâu             |

**Giá trị được đề xuất:**

| Kịch bản                  | Thời gian chờ lỗi nhanh | Bộ nhớ cache TTL | Lý luận                                                                             |
| ------------------------- | ----------------------- | ---------------- | ----------------------------------------------------------------------------------- |
| Cổng API thông lượng cao  | 1500 mili giây          | 60000 mili giây  | Lỗi nhanh, bộ đệm dài hơn để giảm kiểm tra                                          |
| Các nút phân phối địa lý  | 3000 mili giây          | 15000 mili giây  | Mạng chậm hơn cần nhiều thời gian hơn; bộ đệm ngắn hơn để chuyển đổi dự phòng nhanh |
| Phát triển/thử nghiệm     | 1000 mili giây          | 10000 mili giây  | Lặp lại nhanh trên proxy cục bộ                                                     |
| Tàng hình/chống phát hiện | 2500 mili giây          | 45000 mili giây  | Tránh việc thăm dò nhanh có thể gây ra giới hạn tốc độ                              |

### Kiểm tra tình trạng proxy

```ts
import { getAllProxyHealthStatuses, invalidateProxyHealth } from "omniroute/proxyHealth";

const statuses = getAllProxyHealthStatuses();
for (const s of statuses) {
  console.log(`${s.proxyUrl} → healthy=${s.healthy}, stale=${s.stale}`);
}

// Force re-check a specific proxy
invalidateProxyHealth("http://user:pass@203.0.113.7:8080");
```

Cờ `stale` là `true` khi mục nhập bộ đệm vượt quá `HEALTH_CACHE_TTL_MS` và yêu cầu tiếp theo sẽ kích hoạt kiểm tra mới.

### Mặc định loại mỗi proxy

Kiểm tra tình trạng sử dụng các giá trị mặc định hợp lý dựa trên sơ đồ URL :

| Cơ chế                     | Cổng mặc định |
| -------------------------- | ------------- |
| `http://`                  | 8080          |
| `https://`                 | 443           |
| `socks5://` / `socks5h://` | 1080          |

Các cổng tùy chỉnh trong URL (`http://host:9999`) luôn được ưu tiên hơn mặc định của lược đồ.

---

## Phân tích proxy & khả năng quan sát

OmniRoute theo dõi mức sử dụng trên mỗi proxy để giúp người vận hành chẩn đoán các kiểu định tuyến, độ trễ tăng đột biến và các lỗi lặp lại.

### Những gì được theo dõi

Đối với mọi yêu cầu thông qua proxy được định cấu hình, OmniRoute sẽ ghi lại:

| Số liệu      | Sự miêu tả                                             |
| ------------ | ------------------------------------------------------ |
| `proxy_url`  | URL proxy đầy đủ (với thông tin xác thực được che dấu) |
| `provider`   | Nhà cung cấp thượng nguồn ID (openai, anthropic, v.v.) |
| `latency_ms` | Tổng thời gian khứ hồi bao gồm cả bắt tay proxy        |
| `connect_ms` | TCP chỉ thời gian kết nối                              |
| `status`     | mã trạng thái HTTP từ thượng nguồn                     |
| `error`      | Lớp lỗi nếu yêu cầu không thành công                   |
| `timestamp`  | ISO 8601 UTC                                           |

### Truy cập dữ liệu

```bash
# Recent proxy events
curl -H "Authorization: Bearer $OMNIROUTE_KEY" \
  "http://localhost:20128/api/usage/proxy-logs?limit=100"
```

Điểm cuối thực sự là `/api/usage/proxy-logs` (xem `src/app/api/usage/proxy-logs/route.ts`). Điểm cuối này hỗ trợ:

- `GET /api/usage/proxy-logs` — truy xuất nhật ký proxy
- `DELETE /api/usage/proxy-logs` — xóa tất cả nhật ký proxy

Số liệu thống kê tổng hợp có thể được truy vấn trực tiếp từ bảng `proxy_logs` qua SQL nếu cần. Trang tổng quan UI có thể cung cấp chế độ xem tổng hợp.

### Các mẫu chung

**Phát hiện proxy vỗ** (xen kẽ giữa success/failure):

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

**Tìm proxy chậm** (độ trễ p95 > 2s):

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

## Cây quyết định chiến lược luân chuyển

Khi nhiều proxy được gán cho một phạm vi, OmniRoute sử dụng một** chiến lược luân chuyển** để chọn cái nào sẽ sử dụng cho mỗi yêu cầu. Chiến lược được định cấu hình ở cấp phạm vi (toàn cầu, mỗi nhà cung cấp, mỗi tài khoản, mỗi tổ hợp).

### Chiến lược có sẵn

| Chiến lược           | Khi nào nên sử dụng                   | Đánh đổi                                                                     |
| -------------------- | ------------------------------------- | ---------------------------------------------------------------------------- |
| `quality` (mặc định) | Sản xuất với proxy chất lượng hỗn hợp | Ủng hộ proxy được đánh giá cao; có thể bỏ đói những người được đánh giá thấp |
| `random`             | Phân phối tải, quyền riêng tư         | Phân phối đồng đều; bỏ qua tín hiệu chất lượng                               |
| `sequential`         | Gỡ lỗi, kiểm tra xác định             | Chuyển qua các proxy theo thứ tự; dễ lý luận về                              |

### Cây quyết định

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

## Tự động loại trừ lỗi cho proxy của riêng bạn

Nhóm thị trường 1proxy đã tự động hạ cấp các proxy không thành công (xem [Điểm chất lượng proxy](#proxy-quality-scores) ). Dành cho proxy** Bạn** được thêm vào sổ đăng ký, bộ lập lịch sức khỏe nền (`src/lib/proxyHealth/scheduler.ts`) cung cấp hành vi "tự động loại trừ một thành viên đã chết khỏi chuỗi" mà không xóa bất cứ điều gì:

```bash
# .env — soft-disable a proxy after 3 consecutive failed probes, re-enable it
# automatically once it starts answering probes again.
PROXY_AUTO_DISABLE=true
PROXY_AUTO_REMOVE_AFTER=3
```

Làm thế nào nó phù hợp với chuỗi nhiều proxy:

1. Bộ lập lịch sẽ thăm dò mọi proxy đã đăng ký mỗi `PROXY_HEALTH_INTERVAL_MS` (mặc định là 10 phút; tối thiểu 1 phút).
2. Sau `PROXY_AUTO_REMOVE_AFTER` liên tiếp** kết luận** lỗi (lỗi kết nối thực sự — hết thời gian chờ hoặc 5xx của chính mục tiêu thăm dò không bao giờ được tính, hãy xem [Kiểm tra tình trạng proxy](#proxy-health-checking-v3816) ), `status` của proxy được đặt thành `dead`.
3. `dead` là một trong những trạng thái mà bộ lọc trạng thái hoạt động được độ phân giải pool/rotation sử dụng loại trừ, do đó, quá trình xoay vòng của phạm vi (quay vòng / ngẫu nhiên / cố định / độ trễ — xem [Cây quyết định chiến lược xoay vòng](#rotation-strategy-decision-tree) ) ngay lập tức ngừng chuyển proxy đó cho các yêu cầu mới. Không có proxy nào khác trong nhóm bị ảnh hưởng và toàn bộ nhóm không bao giờ âm thầm quay trở lại kết nối trực tiếp — xem hệ thống bảo vệ không đóng [của Hệ thống proxy 4 cấp](#4-level-proxy-system).
4. Bộ lập lịch tiếp tục thăm dò các proxy `dead` trong cùng một khoảng thời gian. Đầu dò thành công tiếp theo sẽ lật `status` trở lại `active` và nó quay lại — mà không cần thêm lại thủ công.

Đây là cố tình** chọn tham gia và không phá hủy** : theo mặc định, bộ lập lịch chỉ đếm và ghi lại các lỗi (xem chính sách C trong `decision.ts`) và `PROXY_AUTO_DISABLE` không bao giờ xóa một hàng —, đó là mục đích của cờ `PROXY_AUTO_REMOVE` riêng biệt, linh hoạt hơn. Nếu cả hai được đặt thành `true`, `PROXY_AUTO_REMOVE` sẽ thắng (một proxy sắp bị xóa sẽ không được sử dụng để tắt mềm ở giữa). Xem tài liệu tham khảo [Cấu hình môi trường](../reference/ENVIRONMENT.md) để biết danh sách biến đầy đủ.

---

> 📖** Tài liệu liên quan:**
>
> - [Hướng dẫn sử dụng](../guides/USER_GUIDE.md) — Thiết lập và cấu hình chung - [API Tham khảo](../reference/API_REFERENCE.md) — Tài liệu API đầy đủ - [Cấu hình môi trường](../reference/ENVIRONMENT.md) — Tất cả các biến môi trường
