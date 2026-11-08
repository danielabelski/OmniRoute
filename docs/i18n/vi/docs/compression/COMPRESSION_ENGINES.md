# Compression Engines (Tiếng Việt)

🌐 **Languages:** 🇺🇸 [English](../../../../compression/COMPRESSION_ENGINES.md) · 🇪🇹 [am](../../../am/docs/compression/COMPRESSION_ENGINES.md) · 🇸🇦 [ar](../../../ar/docs/compression/COMPRESSION_ENGINES.md) · 🇦🇿 [az](../../../az/docs/compression/COMPRESSION_ENGINES.md) · 🇧🇬 [bg](../../../bg/docs/compression/COMPRESSION_ENGINES.md) · 🇧🇩 [bn](../../../bn/docs/compression/COMPRESSION_ENGINES.md) · 🇧🇦 [bs](../../../bs/docs/compression/COMPRESSION_ENGINES.md) · 🇨🇿 [cs](../../../cs/docs/compression/COMPRESSION_ENGINES.md) · 🇩🇰 [da](../../../da/docs/compression/COMPRESSION_ENGINES.md) · 🇩🇪 [de](../../../de/docs/compression/COMPRESSION_ENGINES.md) · 🇬🇷 [el](../../../el/docs/compression/COMPRESSION_ENGINES.md) · 🇪🇸 [es](../../../es/docs/compression/COMPRESSION_ENGINES.md) · 🇪🇪 [et](../../../et/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇷 [fa](../../../fa/docs/compression/COMPRESSION_ENGINES.md) · 🇫🇮 [fi](../../../fi/docs/compression/COMPRESSION_ENGINES.md) · 🇫🇷 [fr](../../../fr/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇪 [ga](../../../ga/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [gu](../../../gu/docs/compression/COMPRESSION_ENGINES.md) · 🇳🇬 [ha](../../../ha/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇱 [he](../../../he/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [hi](../../../hi/docs/compression/COMPRESSION_ENGINES.md) · 🇭🇷 [hr](../../../hr/docs/compression/COMPRESSION_ENGINES.md) · 🇭🇺 [hu](../../../hu/docs/compression/COMPRESSION_ENGINES.md) · 🇦🇲 [hy](../../../hy/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇩 [id](../../../id/docs/compression/COMPRESSION_ENGINES.md) · 🇳🇬 [ig](../../../ig/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇹 [it](../../../it/docs/compression/COMPRESSION_ENGINES.md) · 🇯🇵 [ja](../../../ja/docs/compression/COMPRESSION_ENGINES.md) · 🇬🇪 [ka](../../../ka/docs/compression/COMPRESSION_ENGINES.md) · 🇰🇭 [km](../../../km/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [kn](../../../kn/docs/compression/COMPRESSION_ENGINES.md) · 🇰🇷 [ko](../../../ko/docs/compression/COMPRESSION_ENGINES.md) · 🇱🇹 [lt](../../../lt/docs/compression/COMPRESSION_ENGINES.md) · 🇱🇻 [lv](../../../lv/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [ml](../../../ml/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [mr](../../../mr/docs/compression/COMPRESSION_ENGINES.md) · 🇲🇾 [ms](../../../ms/docs/compression/COMPRESSION_ENGINES.md) · 🇲🇹 [mt](../../../mt/docs/compression/COMPRESSION_ENGINES.md) · 🇲🇲 [my](../../../my/docs/compression/COMPRESSION_ENGINES.md) · 🇳🇵 [ne](../../../ne/docs/compression/COMPRESSION_ENGINES.md) · 🇳🇱 [nl](../../../nl/docs/compression/COMPRESSION_ENGINES.md) · 🇳🇴 [no](../../../no/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [or](../../../or/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [pa](../../../pa/docs/compression/COMPRESSION_ENGINES.md) · 🇵🇭 [phi](../../../phi/docs/compression/COMPRESSION_ENGINES.md) · 🇵🇱 [pl](../../../pl/docs/compression/COMPRESSION_ENGINES.md) · 🇵🇹 [pt](../../../pt/docs/compression/COMPRESSION_ENGINES.md) · 🇧🇷 [pt-BR](../../../pt-BR/docs/compression/COMPRESSION_ENGINES.md) · 🇷🇴 [ro](../../../ro/docs/compression/COMPRESSION_ENGINES.md) · 🇷🇺 [ru](../../../ru/docs/compression/COMPRESSION_ENGINES.md) · 🇱🇰 [si](../../../si/docs/compression/COMPRESSION_ENGINES.md) · 🇸🇰 [sk](../../../sk/docs/compression/COMPRESSION_ENGINES.md) · 🇸🇮 [sl](../../../sl/docs/compression/COMPRESSION_ENGINES.md) · 🇷🇸 [sr](../../../sr/docs/compression/COMPRESSION_ENGINES.md) · 🇸🇪 [sv](../../../sv/docs/compression/COMPRESSION_ENGINES.md) · 🇰🇪 [sw](../../../sw/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [ta](../../../ta/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [te](../../../te/docs/compression/COMPRESSION_ENGINES.md) · 🇹🇭 [th](../../../th/docs/compression/COMPRESSION_ENGINES.md) · 🇹🇷 [tr](../../../tr/docs/compression/COMPRESSION_ENGINES.md) · 🇺🇦 [uk-UA](../../../uk-UA/docs/compression/COMPRESSION_ENGINES.md) · 🇵🇰 [ur](../../../ur/docs/compression/COMPRESSION_ENGINES.md) · 🇺🇿 [uz](../../../uz/docs/compression/COMPRESSION_ENGINES.md) · 🇳🇬 [yo](../../../yo/docs/compression/COMPRESSION_ENGINES.md) · 🇨🇳 [zh-CN](../../../zh-CN/docs/compression/COMPRESSION_ENGINES.md) · 🇹🇼 [zh-TW](../../../zh-TW/docs/compression/COMPRESSION_ENGINES.md)

---

nén OmniRoute được xây dựng dựa trên hợp đồng động cơ. Một chế độ có thể chạy trực tiếp một công cụ (`caveman` hoặc `rtk`) hoặc một đường ống xếp chồng xác định thực thi nhiều công cụ theo thứ tự.

## Chế độ

| Cách thức    | Đường dẫn động cơ                                                                            | Đầu vào dự kiến                                           |
| ------------ | -------------------------------------------------------------------------------------------- | --------------------------------------------------------- |
| `off`        | không có                                                                                     | Bảo quản kịp thời chính xác                               |
| `lite`       | Người trợ giúp nhẹ nhàng của Caveman                                                         | Dọn dẹp luôn có rủi ro thấp                               |
| `standard`   | người thượng cổ                                                                              | Ngưng tụ nhanh chóng bằng ngôn ngữ tự nhiên               |
| `aggressive` | Caveman + history/tool tắt                                                                   | Những buổi trò chuyện dài                                 |
| `ultra`      | Người trợ giúp cắt tỉa Caveman +                                                             | Phục hồi giới hạn ngữ cảnh                                |
| `rtk`        | RTK                                                                                          | Đầu ra terminal, shell, build, test và git                |
| `omniglyph`  | OmniGlyph                                                                                    | Ngữ cảnh dưới dạng hình ảnh trên dây của nhà cung cấp gốc |
| `stacked`    | Đường ống. Yêu cầu mặc định là `session-dedup -> lite`. `rtk -> caveman` được chọn tham gia. | Nhật ký công cụ hỗn hợp và văn xuôi, tiết kiệm tối đa     |

### hồ sơ nén OmniGlyph

Công cụ `omniglyph` (gói `omniglyph`, 1.4.0 +) chấp nhận cấu hình ngữ nghĩa được đặt tên, được đặt trên toàn cầu thông qua `omniglyph.profile` trong cài đặt nén hoặc mỗi bước thông qua cấu hình bước của đường ống xếp chồng:

| Hồ sơ         | ranh giới                                                                                                       |
| ------------- | --------------------------------------------------------------------------------------------------------------- |
| `aggressive`  | Mặc định. Chính sách biên lai được công bố đã đo lường hệ thống hình ảnh —, tài liệu công cụ và lịch sử dày đặc |
| `balanced`    | Giữ nguyên trạng thái trực tiếp, bảo vệ 8 lượt cuối cùng, thu gọn lịch sử đóng cũ hơn                           |
| `coding-safe` | Giữ nguyên quyền, lược đồ công cụ và đầu ra công cụ trực tiếp, bảo vệ 12 lượt cuối cùng                         |
| `passthrough` | Các tuyến đường không chuyển đổi; động cơ bị bỏ qua                                                             |

Hồ sơ là một** trần chứ không phải sàn** : `mergeCompressionProfileOptions` trong gói từ chối cho phép người gọi ghi đè mở lại làn đường bị mất mà hồ sơ đã đóng, do đó `preserveSystemPrompt: false` mỗi bước không thể kích hoạt lại tính năng nén hệ thống trong `coding-safe`.

Được đo lường trên cơ sở mã này: `coding-safe` và `balanced` tăng `minCompressChars` lên mức tối đa và giữ nguyên hệ thống, lược đồ công cụ và kết quả công cụ, do đó, một phiên chưa tích lũy lịch sử vẫn dừng ở `below_min_chars` và công cụ không biến đổi gì. Đó là lý do tại sao mặc định là `aggressive` chứ không phải hồ sơ an toàn nhất.

Gói này giải quyết phạm vi và hồ sơ mô hình của chính nó từ cấu hình môi trường của nó. OmniRoute không bao giờ ủy quyền quyết định: bộ điều hợp ghim cổng mô hình vào phạm vi hạn chế nhất của gói, do đó, cài đặt môi trường máy chủ chỉ có thể thu hẹp danh sách cho phép, không bao giờ mở rộng danh sách này vượt quá biên nhận đo được của OmniRoute.

## Đăng ký động cơ

Cơ quan đăng ký tồn tại ở `open-sse/services/compression/engines/registry.ts`. Động cơ đưa ra một hợp đồng chung:

- `id`: id động cơ ổn định như `caveman` hoặc `rtk`
- `apply(text, config)`: đường dẫn thực thi kế thừa được sử dụng bởi các đường ống xếp chồng lên nhau
- `compress(input, config)`: đường dẫn thực thi chính trả về số liệu thống kê + văn bản
- `getConfigSchema()`: trả về hình dạng giống lược đồ JSON của cấu hình hợp lệ
- `validateConfig(config)`: trả về `{ valid, errors[] }`

Đăng ký sử dụng `registerCompressionEngine(engine)` (hoặc `registerEngine` cho các trường hợp nâng cao), gọi `assertValidEngine()` và `validateConfig(defaultConfig)` trước khi chấp nhận. Sử dụng `unregisterCompressionEngine(id)` để xóa công cụ khi chạy.

`strategySelector.ts` đăng ký các công cụ tích hợp trước khi chạy nén. Điều này cho phép xem trước, nén thời gian chạy, chế độ xếp chồng, kiểm tra và các công cụ trong tương lai sử dụng cùng một đường dẫn thực thi.

### nén mô tả MCP (có liên quan)

Một sổ đăng ký riêng biệt nén siêu dữ liệu mô tả công cụ MCP ở cấp đăng ký — xem `open-sse/mcp-server/descriptionCompressor.ts` và [MCP-SERVER.md](../frameworks/MCP-SERVER.md). Nó sử dụng lại các quy tắc Caveman nhưng hoạt động trên siêu dữ liệu của công cụ chứ không phải tải trọng yêu cầu.

### Động cơ tích hợp bổ sung

Ngoài Caveman, RTK và LLMLingua-2, cơ quan đăng ký còn cung cấp một số động cơ kết cấu/không tổn hao chuyên dụng (được sử dụng bởi các đường ống xếp chồng lên nhau, sân chơi và các thử nghiệm):

| Động cơ               | Nhận dạng       | Nó làm gì                                                                                                                                                                             |
| --------------------- | --------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| CCR                   | `ccr`           | Nội dung-Nén-Truy xuất (H4): thay thế các khối văn bản liền kề lớn bằng các tham chiếu có địa chỉ nội dung, do đó các khối repeated/large được gửi một lần và được tham chiếu sau đó. |
| khoảng không trên đầu | `headroom`      | SmartCrusher (H3 + N5): nén dạng bảng không mất dữ liệu của các tải trọng mảng JSON đồng nhất thành dạng `[N rows]` cột.                                                              |
| chất ion hóa          | `ionizer`       | lấy mẫu hàng Head/middle/tail cho các khối đồng nhất rất lớn, lưu trữ phần giữa được tách ra dưới dạng tham chiếu có địa chỉ nội dung CCR.                                            |
| phiên bản bị loại bỏ  | `session-dedup` | Sao chép chéo theo địa chỉ nội dung (lấy cảm hứng từ TokenMizer): bỏ qua văn bản đã thấy trong các phiên trước đó của cùng một phiên.                                                 |

**lệnh truy xuất giao thức CCR (#8033):** Lần đầu tiên CCR thay thế khối ≥ 1 trong một yêu cầu, công cụ sẽ thêm vào trước một thông báo `system` bình thường (dẫn đầu với `[CCR protocol]` trọng điểm) dạy cho người gọi hợp đồng công cụ đánh dấu → : điểm đánh dấu `[CCR retrieve hash=<24hex> chars=N]` nghĩa là gì, hàm băm phải được sao chép nguyên văn (tất cả 24 ký tự hex mà các giá trị băm — sao chép sai có thể là nguyên nhân dẫn đến lỗi "không tìm thấy khối") và điểm đánh dấu `[dedup:ref sha=...]` có nghĩa là "nhìn lại history", chứ không phải "gọi công cụ". Ghi chú được tiêm** chỉ khi `tools[]` được quảng cáo của người gọi chứng minh rằng nó thực sự có thể đạt tới `omniroute_ccr_retrieve`** (`callerSupportsCcrRetrieve()` trong `open-sse/services/compression/engines/ccr/protocolInstruction.ts`) — một trình gọi đơn giản tương thích với OpenAI mà không có công cụ đó sẽ không bao giờ nhận được hướng dẫn gọi thứ gì đó mà nó không thể tiếp cận được. Tính bình thường được thực thi bằng cách quét lịch sử tin nhắn để tìm trọng điểm trước khi đưa vào, do đó, các yêu cầu nhiều lượt (phát lại các tin nhắn trước đó) không xếp chồng ghi chú một lần mỗi lượt.

## người thượng cổ

Chế độ thượng cổ tập trung vào việc cô đọng ngữ nghĩa của văn xuôi thông thường:

- bảo toàn các khối mã, URLs, JSON, đường dẫn và dữ liệu có cấu trúc
- loại bỏ phần bổ sung, phòng ngừa rủi ro, bối cảnh lặp lại và cụm từ liên kết dài dòng
- hỗ trợ các gói quy tắc tệp nhận biết ngôn ngữ trong `open-sse/services/compression/rules/`
- vẫn có sẵn thông qua các chế độ `standard`, `aggressive` và `ultra` cũ

Bề mặt bảng điều khiển là `Dashboard -> Context & Cache -> Caveman`.

Thượng nguồn Caveman báo cáo `~75%` ít mã thông báo đầu ra hơn, mức tiết kiệm đầu ra trung bình `65%` trong các điểm chuẩn với phạm vi `22-87%` và công cụ nén đầu vào `~46%`. OmniRoute sử dụng số phía đầu vào Caveman khi ghi lại các khoản tiết kiệm prompt/context xếp chồng; Chế độ đầu ra Caveman vẫn là một tính năng hành vi phản hồi riêng biệt.

## RTK

chế độ RTK tập trung vào đầu ra lệnh và công cụ:

- phát hiện các lớp đầu ra như `git status`, `git branch`, `git diff`, Vitest/Jest/Pytest, Cargo/Go test, TypeScript/Vite/Webpack build, ESLint, npm audit/installs, Docker logs, shell `find`/`grep`, dấu vết ngăn xếp và nhật ký chung
- áp dụng 49 bộ lọc JSON từ `open-sse/services/compression/engines/rtk/filters/`
- hỗ trợ đường dẫn khai báo kiểu RTK: tước ANSI, thay thế, đoản mạch đầu ra khớp, dòng strip/keep, cắt ngắn trên mỗi dòng, cắt ngắn head/tail/max-line và dự phòng khi trống
- hỗ trợ các bộ lọc dự án được kiểm soát tin cậy trong `.rtk/filters.json` và các bộ lọc toàn cầu trong `DATA_DIR/rtk/filters.json`
- loại bỏ các chuỗi ANSI, nhiễu tiến trình, các dòng lặp lại và bản soạn sẵn không hữu ích
- lưu giữ các lỗi có thể xử lý, cảnh báo, tóm tắt, tệp đã thay đổi và ngữ cảnh đuôi
- có thể tùy chọn giữ lại đầu ra thô đã được xử lý lại cho recovery/debugging thông qua các tuyến quản lý được xác thực

Bề mặt bảng điều khiển là `Dashboard -> Context & Cache -> RTK`.

Chi tiết hoạt động cho các bộ lọc tùy chỉnh, tin cậy, xác minh và khôi phục đầu ra thô có trong [`RTK_COMPRESSION.md`](./RTK_COMPRESSION.md).

RTK ngược dòng báo cáo mức tiết kiệm `60-90%` để nén đầu ra lệnh. Ví dụ README của nó hiển thị phiên Mã Claude dài 30 phút chuyển từ mã thông báo `~118,000` sang `~23,900` hoặc `79.7%` được lưu.

## LLMLingua-2 (Cắt tỉa ngữ nghĩa)

chế độ LLMLingua-2 thực hiện** cắt tỉa mã thông báo ngữ nghĩa** về văn xuôi sử dụng bộ phân loại mã thông báo ONNX nhỏ, bổ sung cho các công cụ Caveman và RTK dựa trên quy tắc:

- chỉ nén văn xuôi trong các tin nhắn không thuộc hệ thống; khối mã có rào chắn và các cấu trúc được bảo tồn khác không bao giờ bị thay đổi
- chạy phần phụ trợ `@atjsh/llmlingua-2` (ONNX qua `@huggingface/transformers`) trong một luồng công việc, do đó suy luận mô hình không bao giờ chặn vòng lặp sự kiện yêu cầu
- là** có thể xếp chồng lên nhau** (`stackPriority` 35): trong một đường dẫn xếp chồng, nó chạy sau các công cụ cấu trúc (CCR, session-dedup, headroom, Caveman) nhưng trước `ultra`, vì việc cắt tỉa ngữ nghĩa có hiệu quả nhất trên văn bản đã được nén về mặt cấu trúc — ví dụ `rtk -> caveman -> llmlingua`
- **không mở được khi có bất kỳ lỗi nào** (thiếu deps tùy chọn, sinh sản của nhân viên, tải mô hình, suy luận hoặc hết thời gian chờ) → văn bản gốc được trả về không thay đổi, không bao giờ có lỗi

Vị trí động cơ: `open-sse/services/compression/engines/llmlingua/`. Bề mặt bảng điều khiển là `Dashboard -> Context & Cache -> LLMLingua`.

### Người mẫu

Mô hình mặc định là**TinyBERT** (`atjsh/llmlingua-2-js-tinybert-meetingbank`, ~ 57 MB, nhanh). Độ chính xác cao hơn** Cơ sở BERT** mô hình (`Arcoldd/llmlingua4j-bert-base-onnx`, ~ 710 MB) có sẵn thông qua trường `model` cấu hình động cơ. `@huggingface/transformers` tải xuống mô hình đã chọn một cách lười biếng từ HuggingFace Hub vào `${DATA_DIR}/models/llmlingua` trong cuộc gọi đầu tiên (`modelStore.ts`); Thay vào đó, ghi đè cấu hình `modelPath` sẽ trỏ nó vào một bản sao cục bộ (cài đặt ngoại tuyến/không bị chặn).

### Phụ thuộc tùy chọn & cài đặt theo yêu cầu

Ngăn xếp ngang hàng thời gian chạy LLMLingua có thể cắt bớt là** không bắt buộc** . Hai gói được khai báo là `optionalDependencies` trong `package.json` và được giữ** bên ngoài** bởi bản dựng sản xuất (`scripts/build/prepublish.ts` không gói chúng):

| Bưu kiện             | Phiên bản (pin) | Ghi chú                                               |
| -------------------- | --------------- | ----------------------------------------------------- |
| `@atjsh/llmlingua-2` | `2.0.5`         | Gói đầu vào; tuyên bố những người khác là đồng nghiệp |
| `js-tiktoken`        | `^1.0.20`       | Mã thông báo                                          |

`@huggingface/transformers` được ghim tại `^4.2.0` (được chia sẻ với đường dẫn nhúng cục bộ và cũng được truy tìm vào gói độc lập); `@atjsh/llmlingua-2@2.0.5` ngang hàng với nó với `"^3.5.2 || ^4.0.0"`, vì vậy cả Transformers.js v3 và v4 đều được hỗ trợ. Kể từ phiên bản 2.0.4, `@atjsh/llmlingua-2` không còn yêu cầu `@tensorflow/tfjs` nữa, điều này đã loại bỏ thành phần đóng góp lớn nhất (TensorFlow.js) khỏi ngăn xếp SLM. Chỉ có hai gói ở trên là các gói SLM có thể cắt tỉa được. `npm install` (dev) tiêu chuẩn sẽ tự động cài đặt ngăn xếp tùy chọn trừ khi bỏ qua các phần phụ thuộc tùy chọn.

**Tại sao theo yêu cầu:** gói được xuất bản npm, gói độc lập và tàu hình ảnh Docker** không có** những thứ này để giữ dáng thon gọn. Khi chúng vắng mặt, cổng phụ thuộc của công nhân (đầu dò giải quyết `@atjsh/llmlingua-2` trong `worker.ts`) không thành công và động cơ** không mở được âm thầm** — việc chọn LLMLingua sẽ trở thành không hoạt động (văn bản được trả về không thay đổi, không có lỗi được ghi lại). Để kích hoạt nó trong môi trường được cắt bớt, hãy cài đặt ngăn xếp tùy chọn:

```bash
# pin to the versions declared in package.json optionalDependencies
npm install @atjsh/llmlingua-2@2.0.5 js-tiktoken
```

Việc loại bỏ `@tensorflow/tfjs` (2.0.4 +) sẽ loại bỏ — đóng góp ~ 800 MB chiếm ưu thế trước đó, dấu chân còn lại là thời gian chạy nút transformers.js + onnxruntime, cộng với mô hình TinyBERT (~ 57 MB) được tải xuống ở lần sử dụng đầu tiên (không qua npm).

Mỗi môi trường:

- **Dev / `npm install`** — được cài đặt tự động trừ khi bạn vượt qua `--omit=optional` (hoặc `--no-optional`). Không cần hành động.
- **Npm toàn cầu (`npm i -g omniroute`) / độc lập** — chạy lệnh cài đặt ở trên bên trong thư mục gói đã cài đặt hoặc cài đặt lại mà không bỏ qua các phần tùy chọn.
- **Docker** — thêm lệnh cài đặt vào lớp hình ảnh dẫn xuất; hình ảnh được công bố có thiết kế mỏng.
- **VPS (PM2)** cài đặt — vào `node_modules` của ứng dụng, sau đó khởi động lại quy trình để nhân viên thăm dò lại cổng.
- **Raw Tiếp theo độc lập (`npm run build` → `.build/next/standalone/server.js`)** — dấu vết độc lập vận chuyển NEITHER công nhân cũng như các bộ phận tùy chọn, do đó động cơ không mở được trong âm thầm. `scripts/build/colocate-standalone.mjs` áp dụng lại cả hai (worker esbuild + đóng tùy chọn-dep vào cây độc lập); nó chạy tự động thông qua hook `postbuild` npm sau mỗi lần xây dựng. Bình thường, thất bại khi không có dep.

**Xác minh nó đang hoạt động:** với LLMLingua được chọn, văn xuôi thực sự thực sự co lại (động cơ dừng mở không thành công) và yêu cầu đầu tiên kích hoạt tải xuống mô hình vào `${DATA_DIR}/models/llmlingua`. Cổng cố tình chỉ thăm dò `@atjsh/llmlingua-2` — các đồng nghiệp khác chỉ có ESM và `require.resolve` ném vào chúng ngay cả khi có —, vì vậy nhân viên vẫn không mở được nếu bất kỳ đồng nghiệp nào thực sự bị thiếu tại thời điểm `import()`.

## Đường ống xếp chồng lên nhau

Chế độ xếp chồng chạy các bước quy trình theo thứ tự. Mặc định là:

```txt
rtk -> caveman
```

Sử dụng tính năng này cho các phiên tác nhân mã hóa trong đó lời nhắc kết hợp đầu ra lệnh với văn xuôi của con người hoặc trợ lý. RTK trước tiên giảm tiếng ồn của nhật ký công cụ, sau đó Caveman nén ngôn ngữ tự nhiên còn lại.

Các bước quy trình được định cấu hình bằng `stackedPipeline` trong cài đặt nén hoặc thông qua các tổ hợp nén.

Khi cả hai động cơ đều giảm tải trọng đủ điều kiện như nhau, mức tiết kiệm sẽ tăng lên:

```txt
combined = 1 - (1 - RTK savings) * (1 - Caveman input savings)
average  = 1 - (1 - 0.80) * (1 - 0.46) = 89.2%
range    = 1 - (1 - 0.60..0.90) * (1 - 0.46) = 78.4-94.6%
```

## Bộ lọc cây trợ năng MCP

Bộ lọc thông minh cây trợ năng MCP là lớp nén sau thực thi chạy trên MCP** kết quả công cụ** , không phải trên lời nhắc hoặc ngữ cảnh. Nó nhắm đến các tải trọng chi tiết về cây trợ năng và ảnh chụp nhanh của trình duyệt được trả về bởi các công cụ như Playwright, máy chủ sử dụng máy tính và máy chủ MCP tự động hóa trình duyệt.

### Nó làm gì

1. **Loại bỏ tiếng ồn** — xóa các mục generic/text trống (`- generic:`, `- text: ""`)
2. **Anh chị em suy sụp** — khi ≥ `collapseThreshold` (mặc định 30) các dòng liên tiếp lặp lại cấu trúc, thu gọn chúng thành các dòng `collapseKeepHead` (mặc định 10) đầu tiên + một bản tóm tắt đếm + các dòng `collapseKeepTail` (mặc định 5) cuối cùng
3. **Bảo quản tham chiếu** neo — `[ref=eXX]` theo yêu cầu của Playwright/computer-use không bao giờ được chạm vào
4. **Cắt ngắn cứng** — nếu văn bản sau khi thu gọn vẫn vượt quá `maxTextChars` (mặc định 50.000), hãy cắt bớt bằng gợi ý điều hướng để tổng đài viên có thể tiếp tục làm việc

### Vị trí động cơ

```txt
open-sse/services/compression/engines/mcpAccessibility/
  index.ts            ← smartFilterText() entry point
  collapseRepeated.ts ← sibling-collapse algorithm
  constants.ts        ← DEFAULT_MCP_ACCESSIBILITY_CONFIG
```

### Cấu hình

Được kiểm soát bởi `compression.mcpAccessibility` trong cài đặt chung (di chuyển 056). Cấu hình mặc định:

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

Bộ lọc chỉ được áp dụng cho tải trọng kết quả công cụ có `type` là `"text"` và có độ dài vượt quá `minLengthToProcess`. Nó không ảnh hưởng đến việc nén nhanh chóng hoặc yêu cầu tải trọng.

### Tiết kiệm dự kiến

60–80% kết quả của công cụ chụp nhanh trình duyệt, tùy thuộc vào độ phức tạp của trang. Thuật toán thu gọn có số lượng dòng là O(n) và thêm độ trễ không đáng kể.

### Bộ lọc này so với các công cụ nén ở trên

| Diện mạo       | Thượng cổ / RTK / Xếp chồng lên nhau | bộ lọc khả năng truy cập MCP           |
| -------------- | ------------------------------------ | -------------------------------------- |
| Mục tiêu       | Yêu cầu lời nhắc/ngữ cảnh            | kết quả của công cụ MCP                |
| Cò súng        | Cài đặt chế độ nén                   | `compression.mcpAccessibility.enabled` |
| Phạm vi        | Tất cả tin nhắn SSE                  | Chỉ kết quả công cụ                    |
| Neo giới thiệu | N/A                                  | Bảo quản vô điều kiện                  |

---

## Combo nén

Tổ hợp nén được đặt tên là cấu hình nén có thể được gán cho tổ hợp định tuyến:

- `compression_combos`: lưu trữ chế độ, đường ống, cấu hình RTK, cấu hình ngôn ngữ và điểm đánh dấu mặc định
- `compression_combo_assignments`: ánh xạ tổ hợp nén thành tổ hợp định tuyến
- Tích hợp thời gian chạy giải quyết tổ hợp nén được chỉ định trước khi ghi đè tổ hợp chung
- phân tích bao gồm `compression_combo_id` và `engine`

Bề mặt bảng điều khiển: `Dashboard -> Context & Cache -> Compression Combos`.

## Điều kiện tiên quyết/hướng dẫn vận hành (CCR & session-dedup)

CCR (`ccr`) và `session-dedup` thay thế hoặc loại bỏ văn bản và để lại một** điểm đánh dấu** phía sau. Phần này là tài liệu tham khảo của nhà điều hành để kết nối máy khách, đọc hai điểm đánh dấu và truy xuất hoặc chẩn đoán nội dung được chọn lọc. Cơ học của từng động cơ được đề cập ở trên; đây là lớp "làm cách nào để chạy nó".

### Vận chuyển & điểm cuối

Có thể truy cập máy chủ MCP hiển thị các công cụ CCR theo ba cách. URL cơ sở mặc định là `http://localhost:20128` (`OMNIROUTE_BASE_URL`):

| Chuyên chở                                                 | URL /lệnh                               | Ghi chú                                                                                                                                                           |
| ---------------------------------------------------------- | --------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| HTTP có thể phát trực tuyến (khách hàng, được khuyến nghị) | `http://localhost:20128/api/mcp/stream` | Điểm cuối mà khách hàng MCP hiện tại nói chuyện.                                                                                                                  |
| Di sản SSE singleton                                       | `http://localhost:20128/api/mcp/sse`    | Vận chuyển đơn lẻ cũ hơn. Nó** đóng cửa** phiên có thể phát trực tuyến; sử dụng ứng dụng khách `streamable-http` chống lại `/api/mcp/stream`, không phải cái này. |
| phòng thu âm                                               | `omniroute --mcp`                       | Đối với cấu hình IDE MCP sẽ tạo ra quy trình. Không có cờ `--dev` ; `omniroute --mcp` là điểm vào stdio.                                                          |

### Các tầng lưu trữ (những gì còn sót lại sau khi khởi động lại)

CCR là một** hai tầng** lưu trữ, không chỉ trong bộ nhớ:

- **Cấp nóng trong bộ nhớ** — giới hạn mỗi khối 2 MiB, mỗi gốc 16 MiB, 64 MiB toàn cầu. Các mục nhập mặc định là 24 giờ TTL (tối đa 7 ngày). Việc truy xuất MCP đầy đủ từ bộ nhớ bị giới hạn ở mức 256 KiB; mọi thứ lớn hơn vẫn có thể truy cập được thông qua chế độ ranged/grep.
- **Cấp SQLite bền bỉ** (`ccr_blocks`, `COMPRESSION_CCR_DURABLE_STORE`, bật theo mặc định) — sao lưu tầng trong bộ nhớ để một khối tồn tại sau khi bị trục xuất LRU, khởi động lại hoặc truy xuất trên một phiên bản khác. Hàng giữ TTL của khối, do đó, một khối vượt qua TTL của nó sẽ bị loại khỏi cả hai tầng.

Ba người bảo vệ giữ cho lớp — được giới hạn bền vững một khối chỉ tồn tại trong bộ nhớ khi:

1. khối đã kết thúc** 512 KB** (`MAX_DURABLE_BLOCK_BYTES`);
2. thời gian chạy là thời gian chạy trên đám mây (không có đĩa cục bộ);
3. `COMPRESSION_CCR_DURABLE_STORE=false`.

Vì vậy, "khối biến mất" không phải là một câu chuyện khởi động lại toàn diện: khối sub-512 KB trên thời gian chạy cục bộ, không có đám mây sẽ tồn tại sau khi khởi động lại thông qua cấp độ bền cho đến khi hết TTL. Xem [Tài liệu tham khảo môi trường](../reference/ENVIRONMENT.md) để biết biến.

### Hai điểm đánh dấu

| Điểm đánh dấu                         | Nghĩa                                                                                                                                                | Người mẫu nên làm gì                                                                                                                                                                                 |
| ------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| `[CCR retrieve hash=<24hex> chars=N]` | Một khối lớn được lưu trữ theo địa chỉ nội dung.                                                                                                     | Gọi `omniroute_ccr_retrieve` bằng** Băm 24-hex được sao chép nguyên văn** để lấy lại văn bản gốc.                                                                                                    |
| `[dedup:ref sha=…]`                   | văn bản `session-dedup` elided đã được gửi trong lượt trước đó của cùng một phiên. Đây là một** cố ý nhìn lại** , không phải là mất mát hay sai sót. | LÀM** không** gọi bất kỳ công cụ nào và làm** không** cố gắng "tái tạo" nó. Lần xuất hiện đầu tiên của văn bản là bản kinh điển; lượt hiện tại không bao giờ được viết lại, nó sẽ bị trừ ở lượt sau. |

Việc xem lại `[dedup:ref]` là một quyết định giao thức có chủ ý — không có sự tái cấu trúc trước khi gửi. Hãy coi nó như "văn bản chính xác này đã có trên mạng trước đó trong phiên này."

### Điều kiện tiên quyết của khách hàng

- **Chìa khóa (stdio):** người gọi stdio không mang danh tính theo yêu cầu, do đó, nó xác thực bằng `OMNIROUTE_API_KEY` (được đặt trong `env` của máy chủ MCP ). Nếu không có nó, người gọi sẽ ẩn danh và các công cụ yêu cầu hiệu trưởng có thể bị suy giảm.
- **`tools[]` là điều kiện tiên quyết để tiêm.** Lệnh truy xuất giao thức CCR (#8033) được đưa vào** chỉ một** khi `tools[]` được quảng cáo của yêu cầu chứng minh rằng khách hàng thực sự có thể tiếp cận `omniroute_ccr_retrieve`. Trận đấu là một trận đấu phân đoạn cuối được giới hạn bởi một dấu phân cách (`__`, `.`, `/`, `:`) — không bao giờ là một chuỗi con trần — nên một tên được đặt tên như `mcp__gateway__omniroute_ccr_retrieve` vẫn được tính. `tools[]` vắng mặt hoặc không khớp có nghĩa là lệnh không được đưa vào theo thiết kế.
- **`codemode:false` (máy khách OpenCode ).** OpenCode mặc định ở Chế độ mã, chế độ này chỉ quảng cáo các công cụ gốc của nó cho mô hình và** không** đưa các công cụ MCP vào danh sách `tools[]` gốc. Đặt `codemode: false` trên mục nhập máy chủ MCP để các công cụ `omniroute_ccr_*` được quảng cáo. Đây là một** khách hàng** cài đặt, không phải là OmniRoute. Nó chưa nhận được hướng dẫn CCR : OpenCode đặt tên cho một công cụ `<server>_<tool>`, do đó, một máy chủ có tên `omniroute` hiển thị `omniroute_omniroute_ccr_retrieve` và `_` không phải là một trong những dấu phân cách phù hợp.
- **Hiệu trưởng.** Việc lưu trữ và truy xuất được cách ly theo từng hiệu trưởng được xác thực (mỗi khóa API ). Một khóa chỉ nhìn thấy các khối của chính nó.

### Phạm vi cho mỗi công cụ

Việc thực thi phạm vi luôn được áp dụng đối với người gọi HTTP/SSE ở phạm vi hẹp. Các công cụ `omniroute_` CCR yêu cầu:

| Dụng cụ                  | Phạm vi             |
| ------------------------ | ------------------- |
| `omniroute_ccr_store`    | `write:compression` |
| `omniroute_ccr_delete`   | `write:compression` |
| `omniroute_ccr_retrieve` | `read:compression`  |
| `omniroute_ccr_inspect`  | `read:compression`  |
| `omniroute_ccr_list`     | `read:compression`  |
| `omniroute_ccr_stats`    | `read:compression`  |

Một phạm vi bị thiếu sẽ trả về một** kết quả lỗi công cụ MCP** (`isError: true`, không phải HTTP 403 — `403 LOCAL_ONLY` là xác thực bảo vệ tuyến đường vòng lặp riêng biệt): `Error: Insufficient MCP scopes for <tool>. Missing: <scope>.` Một khóa từ xa tối thiểu có thể giữ `mcp:connect` (cho phép khắc `/api/mcp/` chỉ cục bộ) cộng với phạm vi read/write cụ thể mà nó cần.

### Ma trận khách hàng

| Khách hàng         | Chuyên chở                                          | Cấu hình để sử dụng                                                                                                                                                                                                                             | `tools[]` được quảng cáo? ( lệnh → CCR được chèn)                                                                                                                                                        |
| ------------------ | --------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Claude             | có thể phát trực tuyến-http                         | `claude mcp add --transport http omniroute http://localhost:20128/api/mcp/stream`                                                                                                                                                               | Có — MCP có khả năng; được tiêm.                                                                                                                                                                         |
| Cursor / Cline     | `stdio`** hoặc** `streamable-http`                  | stdio: `omniroute --mcp` với `OMNIROUTE_API_KEY` trong `env`; hoặc một mục MCP từ xa trỏ vào `http://localhost:20128/api/mcp/stream` (xem [Hướng dẫn thiết lập → MCP Client Configuration](../guides/SETUP_GUIDE.md#mcp-client-configuration) ) | Có — quảng cáo các công cụ `omniroute_ccr_*`.                                                                                                                                                            |
| OpenCode           | có thể phát trực tuyến-http                         | `opencode mcp add omniroute --url http://localhost:20128/api/mcp/stream`, cộng với `codemode: false`                                                                                                                                            | Công cụ chỉ được quảng cáo với `codemode: false`; hướng dẫn vẫn chưa được đưa vào, vì `omniroute_omniroute_ccr_retrieve` không khớp (xem [Điều kiện tiên quyết của khách hàng](#client-prerequisites) ). |
| Tương thích OpenAI | HTTP tương thích với OpenAI (hoàn thành trò chuyện) | ứng dụng khách hoàn thành trò chuyện tiêu chuẩn dựa trên điểm cuối tương thích với OpenAI                                                                                                                                                       | **Không bao giờ** — người gọi tương thích với OpenAI đơn giản không bao giờ được yêu cầu gọi công cụ và hướng dẫn không được đưa vào.                                                                    |

### Giới hạn truy xuất và phân trang

kết quả văn bản của công cụ MCP được cắt bớt xung quanh `mcpAccessibility.maxTextChars` ( `50000` mặc định). Truy xuất `full` của một khối được giới hạn ở 256 KiB —** không có truy xuất đầy đủ không giới hạn** . Khi `chars=N` của một khối lớn, hãy phân trang nó thay vì kéo toàn bộ nội dung:

- Quy tắc ngón tay cái:**`chars > 40000` → sử dụng `mode`** , không bao giờ đầy đủ.
- `mode:"grep"` — Regex `pattern` khớp từng dòng, tối đa 1.000 dòng khớp (`unique: true` giảm lặp lại), rẻ nhất để "tìm một dòng tôi cần".
- `mode:"lines"` — một phạm vi dòng có 1 chỉ mục; cần cả `start` và `end`.
- `mode:"head"` / `mode:"tail"` — first/last `n`.
- số dòng, ký tự và byte `mode:"stats"` — không có phần thân.

Sử dụng `mode:"lines"` với `start`/`end` để đi qua một khối dài trong các trang thay vì yêu cầu toàn bộ nội dung cùng một lúc.

### Đặt tên công cụ

Công cụ truy xuất hiện được đặt tên là `omniroute_ccr_retrieve` (tiền tố `omniroute_` là giải pháp thay thế lỗi thời cho xung đột tên giữa các máy chủ). Tên công cụ có hậu tố giới hạn rõ ràng hơn và bản sửa lỗi cho các kết quả MCP JSON bị cắt ở giữa chuỗi được theo dõi dưới dạng phần tiếp theo ngược dòng; trang này chỉ ghi lại hành vi hiện tại, được vận chuyển.

### Vòng đời phiên

Các phiên HTTP có thể phát trực tuyến không hoạt động và máy chủ sẽ thu thập chúng; cửa sổ nhàn rỗi là hằng số `MCP_SESSION_IDLE_MS` (được tham chiếu theo tên, không phải giá trị được mã hóa cứng, vì vậy trang này không bị trôi khi thay đổi). Triệu chứng của phiên không hoạt động là HTTP 404 với `Unknown Mcp-Session-Id` — biện pháp khắc phục là kết nối lại hoặc khởi động lại phiên,** không** để xoay một phím, thay đổi phạm vi hoặc đổi tên một công cụ.

## bề mặt API

| Tuyến đường                            | Mục đích                                                 |
| -------------------------------------- | -------------------------------------------------------- |
| `/api/settings/compression`            | Cài đặt nén chung (bao gồm cấu hình `mcpAccessibility` ) |
| `/api/compression/preview`             | Xem trước mọi chế độ nén                                 |
| `/api/compression/language-packs`      | Liệt kê các gói ngôn ngữ Caveman có sẵn                  |
| `/api/context/caveman/config`          | Bí danh cài đặt Caveman                                  |
| `/api/context/rtk/config`              | mặc định và cài đặt RTK                                  |
| `/api/context/rtk/filters`             | danh mục bộ lọc RTK                                      |
| `/api/context/rtk/test`                | điểm cuối RTK preview/test                               |
| `/api/context/rtk/raw-output/[id]`     | Phục hồi đầu ra thô đã được xác thực lại                 |
| `/api/context/combos`                  | Combo nén CRUD                                           |
| `/api/context/combos/[id]/assignments` | Phân công tổ hợp định tuyến CRUD                         |
| `/api/context/analytics`               | Bí danh phân tích nén                                    |

Các tuyến quản lý yêu cầu xác thực quản lý hoặc kiểm tra chính sách khóa API.

## Công cụ MCP

Nén hiển thị năm công cụ MCP :

| Dụng cụ                             | Phạm vi             | Mục đích                            |
| ----------------------------------- | ------------------- | ----------------------------------- |
| `omniroute_compression_status`      | `read:compression`  | Cài đặt, phân tích, thống kê bộ đệm |
| `omniroute_compression_configure`   | `write:compression` | Cập nhật cài đặt chung              |
| `omniroute_set_compression_engine`  | `write:compression` | Đặt chế độ và đường dẫn tùy chọn    |
| `omniroute_list_compression_combos` | `read:compression`  | Liệt kê các tổ hợp nén              |
| `omniroute_compression_combo_stats` | `read:compression`  | Đọc phân tích combo/engine          |

## Phạm vi & loại trừ

**Nhúng không bao giờ được nén.** `open-sse/handlers/embeddings.ts` không bao giờ gọi bất kỳ công cụ nén nào — phần thân request/response chuyển thẳng đến người thực thi mà không bị ảnh hưởng. Ngày nay, đây là cấu trúc (các phần nhúng và hoàn thành trò chuyện là các trình xử lý rời rạc), không phải là kiểm tra thời gian chạy, nhưng điều đó có nghĩa là mối lo ngại về biến dạng vectơ trong #8034 không có bề mặt hiển thị trong đường dẫn nhúng.

**bộ lọc loại trừ Per-model/endpoint (#8034).** Để hoàn thành trò chuyện, người vận hành có thể đặt tên cho các id mô hình / mục tiêu `provider/model` không bao giờ được nén — một lan can hữu ích nếu quá trình nén được nối gần hơn với đường dẫn liền kề với phần nhúng sau này và thường hữu ích cho bất kỳ mô hình nào có lời nhắc chính xác về từng byte (evals xác định, tiền tố nhạy cảm với bộ đệm, v.v.).

- Trường cài đặt: `exclusions?: string[]` trên cấu hình nén chung (`GET`/`PUT /api/settings/compression`), tồn tại thông qua không gian tên nén `key_value` hiện có (`src/lib/db/compression.ts`) — không có bảng mới.
- Tab bảng điều khiển:** Bảng điều khiển → → Loại trừ** (`/dashboard/compression/exclusions`).
- Cú pháp mẫu: `*` là ký tự đại diện duy nhất. Mọi siêu ký tự biểu thức chính quy khác trong một mẫu đều được thoát trước khi khớp, vì vậy `gpt-5.6` chỉ khớp với chuỗi ký tự, không bao giờ khớp `gpt-5x6` (ReDoS-safe, giới hạn, không có bộ định lượng lồng nhau). Các mẫu khớp không phân biệt chữ hoa chữ thường với cả id mô hình trần và hỗn hợp `provider/model` — `gpt-5-6`, `openai/gpt-5-6` và `openai/*` đều hoạt động và chỉ riêng `*` sẽ loại trừ mọi mô hình.
- So khớp: `isCompressionExcluded()` / `normalizeCompressionExclusions()` trong `open-sse/services/compression/exclusions.ts`. `chatCore.ts` kiểm tra mục tiêu bị loại trừ ngay sau khi giải quyết cài đặt nén,** trước khi bất kỳ động cơ nào chạy** và xử lý kết quả khớp giống hệt như tính năng nén bị vô hiệu hóa trên toàn cầu — nội dung yêu cầu có thể được chứng minh là giống hệt byte. Việc bỏ qua được ghi lại qua `writeCompressionSkip(..., "excluded")` để hiển thị phân tích.
- Mặc định (danh sách empty/absent ): giống hệt với hành vi trước #8034 — không có gì bị loại trừ.

## Những hạn chế đã biết

- **LLMLingua-2 (SLM) yêu cầu các deps tùy chọn cùng vị trí.** Công nhân chỉ chạy trong bản dựng sản xuất khi các đồng nghiệp `@atjsh/llmlingua-2` + được đặt cùng vị trí trong `dist/node_modules` (xem `scripts/build/colocateOptionals.mjs`, #4286). Không có chúng, động cơ sẽ không mở được (trả về văn bản gốc). Độ phân giải của công nhân không còn phụ thuộc vào `import.meta.url` (nó chết trong gói độc lập) — nó neo trong thời gian chạy cwd / `argv[1]`.
- **Gói ngôn ngữ Caveman `de` / `fr` / `ja` là một phần.** Họ gửi các quy tắc `context` + `filler` + `structural` nhưng không có gói `dedup` / `ultra`, vì vậy cường độ `ultra` không mạnh hơn `full` đối với các ngôn ngữ đó (họ chỉ sử dụng quy tắc riêng của họ — không có sự chuyển đổi im lặng sang quy tắc `dedup`/`ultra` tiếng Anh, điều này sẽ đọc sai văn bản nước ngoài). `en` / `es` / `id` / `pt-BR` đã hoàn tất. Những đóng góp của `dedup.json` + `ultra.json` cho các gói một phần đều được hoan nghênh.
- **Phương pháp đo từ xa xếp chồng chỉ liệt kê các động cơ đã nén.** Một bước trong đường ống xếp chồng có động cơ chạy nhưng tạo ra mức tiết kiệm 0 % trả về `stats:null` và do đó không xuất hiện trong `engineBreakdown` — và không thể phân biệt được với một bước đã bị bỏ qua. Việc phân biệt "đã chạy, 0 %" với "bị bỏ qua" sẽ yêu cầu thay đổi mô hình phân tích và bị trì hoãn.

## Xác thực

Các cổng tập trung cho khu vực này là:

```bash
node --import tsx/esm --test tests/unit/compression/rtk-*.test.ts tests/unit/compression/pipeline-integration.test.ts tests/unit/compression/context-compression-api.test.ts
node --import tsx/esm --test tests/unit/compression/*.test.ts tests/golden-set/*.test.ts tests/integration/compression-pipeline.test.ts tests/unit/api/compression/compression-api.test.ts
node --import tsx/esm --test tests/unit/compression/mcpAccessibility*.test.ts
npm run typecheck:core
```
