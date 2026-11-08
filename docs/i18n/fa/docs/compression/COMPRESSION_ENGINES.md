# Compression Engines (فارسی)

🌐 **Languages:** 🇺🇸 [English](../../../../compression/COMPRESSION_ENGINES.md) · 🇪🇹 [am](../../../am/docs/compression/COMPRESSION_ENGINES.md) · 🇸🇦 [ar](../../../ar/docs/compression/COMPRESSION_ENGINES.md) · 🇦🇿 [az](../../../az/docs/compression/COMPRESSION_ENGINES.md) · 🇧🇬 [bg](../../../bg/docs/compression/COMPRESSION_ENGINES.md) · 🇧🇩 [bn](../../../bn/docs/compression/COMPRESSION_ENGINES.md) · 🇧🇦 [bs](../../../bs/docs/compression/COMPRESSION_ENGINES.md) · 🇨🇿 [cs](../../../cs/docs/compression/COMPRESSION_ENGINES.md) · 🇩🇰 [da](../../../da/docs/compression/COMPRESSION_ENGINES.md) · 🇩🇪 [de](../../../de/docs/compression/COMPRESSION_ENGINES.md) · 🇬🇷 [el](../../../el/docs/compression/COMPRESSION_ENGINES.md) · 🇪🇸 [es](../../../es/docs/compression/COMPRESSION_ENGINES.md) · 🇪🇪 [et](../../../et/docs/compression/COMPRESSION_ENGINES.md) · 🇫🇮 [fi](../../../fi/docs/compression/COMPRESSION_ENGINES.md) · 🇫🇷 [fr](../../../fr/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇪 [ga](../../../ga/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [gu](../../../gu/docs/compression/COMPRESSION_ENGINES.md) · 🇳🇬 [ha](../../../ha/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇱 [he](../../../he/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [hi](../../../hi/docs/compression/COMPRESSION_ENGINES.md) · 🇭🇷 [hr](../../../hr/docs/compression/COMPRESSION_ENGINES.md) · 🇭🇺 [hu](../../../hu/docs/compression/COMPRESSION_ENGINES.md) · 🇦🇲 [hy](../../../hy/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇩 [id](../../../id/docs/compression/COMPRESSION_ENGINES.md) · 🇳🇬 [ig](../../../ig/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇹 [it](../../../it/docs/compression/COMPRESSION_ENGINES.md) · 🇯🇵 [ja](../../../ja/docs/compression/COMPRESSION_ENGINES.md) · 🇬🇪 [ka](../../../ka/docs/compression/COMPRESSION_ENGINES.md) · 🇰🇭 [km](../../../km/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [kn](../../../kn/docs/compression/COMPRESSION_ENGINES.md) · 🇰🇷 [ko](../../../ko/docs/compression/COMPRESSION_ENGINES.md) · 🇱🇹 [lt](../../../lt/docs/compression/COMPRESSION_ENGINES.md) · 🇱🇻 [lv](../../../lv/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [ml](../../../ml/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [mr](../../../mr/docs/compression/COMPRESSION_ENGINES.md) · 🇲🇾 [ms](../../../ms/docs/compression/COMPRESSION_ENGINES.md) · 🇲🇹 [mt](../../../mt/docs/compression/COMPRESSION_ENGINES.md) · 🇲🇲 [my](../../../my/docs/compression/COMPRESSION_ENGINES.md) · 🇳🇵 [ne](../../../ne/docs/compression/COMPRESSION_ENGINES.md) · 🇳🇱 [nl](../../../nl/docs/compression/COMPRESSION_ENGINES.md) · 🇳🇴 [no](../../../no/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [or](../../../or/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [pa](../../../pa/docs/compression/COMPRESSION_ENGINES.md) · 🇵🇭 [phi](../../../phi/docs/compression/COMPRESSION_ENGINES.md) · 🇵🇱 [pl](../../../pl/docs/compression/COMPRESSION_ENGINES.md) · 🇵🇹 [pt](../../../pt/docs/compression/COMPRESSION_ENGINES.md) · 🇧🇷 [pt-BR](../../../pt-BR/docs/compression/COMPRESSION_ENGINES.md) · 🇷🇴 [ro](../../../ro/docs/compression/COMPRESSION_ENGINES.md) · 🇷🇺 [ru](../../../ru/docs/compression/COMPRESSION_ENGINES.md) · 🇱🇰 [si](../../../si/docs/compression/COMPRESSION_ENGINES.md) · 🇸🇰 [sk](../../../sk/docs/compression/COMPRESSION_ENGINES.md) · 🇸🇮 [sl](../../../sl/docs/compression/COMPRESSION_ENGINES.md) · 🇷🇸 [sr](../../../sr/docs/compression/COMPRESSION_ENGINES.md) · 🇸🇪 [sv](../../../sv/docs/compression/COMPRESSION_ENGINES.md) · 🇰🇪 [sw](../../../sw/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [ta](../../../ta/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [te](../../../te/docs/compression/COMPRESSION_ENGINES.md) · 🇹🇭 [th](../../../th/docs/compression/COMPRESSION_ENGINES.md) · 🇹🇷 [tr](../../../tr/docs/compression/COMPRESSION_ENGINES.md) · 🇺🇦 [uk-UA](../../../uk-UA/docs/compression/COMPRESSION_ENGINES.md) · 🇵🇰 [ur](../../../ur/docs/compression/COMPRESSION_ENGINES.md) · 🇺🇿 [uz](../../../uz/docs/compression/COMPRESSION_ENGINES.md) · 🇻🇳 [vi](../../../vi/docs/compression/COMPRESSION_ENGINES.md) · 🇳🇬 [yo](../../../yo/docs/compression/COMPRESSION_ENGINES.md) · 🇨🇳 [zh-CN](../../../zh-CN/docs/compression/COMPRESSION_ENGINES.md) · 🇹🇼 [zh-TW](../../../zh-TW/docs/compression/COMPRESSION_ENGINES.md)

---

فشرده سازی OmniRoute بر اساس قراردادهای موتور ساخته شده است. یک حالت می تواند مستقیماً یک موتور (`caveman` یا `rtk`) یا یک خط لوله انباشته قطعی را اجرا کند که چندین موتور را به ترتیب اجرا می کند.

## حالت ها

| حالت         | مسیر موتور                                                                             | ورودی مورد نظر                                        |
| ------------ | -------------------------------------------------------------------------------------- | ----------------------------------------------------- |
| `off`        | هیچ کدام                                                                               | حفظ دقیق و سریع                                       |
| `lite`       | یاران Caveman Lite                                                                     | پاکسازی دائمی کم خطر                                  |
| `standard`   | غارنشین                                                                                | تراکم سریع زبان طبیعی                                 |
| `aggressive` | غارنشین + history/tool خلاصه کننده                                                     | جلسات چت طولانی                                       |
| `ultra`      | یاوران هرس غارنشین +                                                                   | بازیابی محدودیت زمینه                                 |
| `rtk`        | RTK                                                                                    | خروجی ترمینال، پوسته، ساخت، تست و git                 |
| `omniglyph`  | OmniGlyph                                                                              | متن به عنوان تصویر در سیم ارائه دهنده بومی            |
| `stacked`    | خط لوله. پیش فرض درخواست `session-dedup -> lite` است. `rtk -> caveman` انتخاب شده است. | سیاهههای مربوط به ابزار ترکیبی و نثر، حداکثر پس انداز |

### پروفیل های فشرده سازی OmniGlyph

موتور `omniglyph` (بسته `omniglyph`, 1.4.0 +) یک نمایه معنایی نامگذاری شده را می پذیرد که به صورت سراسری از طریق `omniglyph.profile` در تنظیمات فشرده سازی یا در هر مرحله از طریق پیکربندی گام خط لوله انباشته تنظیم شده است:

| نمایه         | مرز                                                                                                   |
| ------------- | ----------------------------------------------------------------------------------------------------- |
| `aggressive`  | پیش فرض خطمشی که رسیدهای منتشر شده، سیستم تصاویر — ، اسناد ابزار و تاریخچه متراکم را اندازهگیری میکرد |
| `balanced`    | حالت زنده را بومی نگه می دارد، از 8 چرخش آخر محافظت می کند، تاریخچه بسته قدیمی تر را فرو می ریزد      |
| `coding-safe` | قدرت، طرحواره های ابزار و خروجی ابزار زنده را بومی نگه می دارد، از 12 نوبت آخر محافظت می کند          |
| `passthrough` | مسیرهای بدون تبدیل. موتور از بین رفته است                                                             |

مشخصات یک است** سقف نه یک کف** : `mergeCompressionProfileOptions` در بسته به تماس گیرنده اجازه نمی دهد که یک خط پرتلفات را که نمایه بسته است بازگشایی کند، بنابراین یک `preserveSystemPrompt: false` در هر مرحله نمی تواند فشرده سازی سیستم را تحت `coding-safe` دوباره فعال کند.

بر اساس این پایگاه کد اندازهگیری میشود: `coding-safe` و `balanced` `minCompressChars` را به حداکثر میرسانند و سیستم، طرحوارههای ابزار و نتایج ابزار را بومی نگه میدارند، بنابراین جلسهای که هنوز تاریخچه انباشته نشده است در `below_min_chars` متوقف میشود و موتور چیزی را تغییر نمیدهد. به همین دلیل است که پیشفرض `aggressive` است تا امنترین نمایه.

بسته دامنه و مشخصات مدل خود را از پیکربندی محیط خود حل می کند. OmniRoute هرگز تصمیم را محول نمیکند: آداپتور گیت مدل را به محدودترین محدوده بسته پین میکند، بنابراین تنظیمات محیط میزبان فقط میتواند لیست مجاز را محدود کند، هرگز آن را از رسیدهای اندازهگیری شده OmniRoute گسترده نمیکند.

## رجیستری موتور

رجیستری در `open-sse/services/compression/engines/registry.ts` زندگی می کند. موتورها قرارداد مشترک را افشا می کنند:

- `id`: شناسه موتور پایدار مانند `caveman` یا `rtk`
- `apply(text, config)`: مسیر اجرای قدیمی که توسط خطوط لوله انباشته استفاده می شود
- `compress(input, config)`: مسیر اجرای اولیه که متن آمار + را برمی گرداند
- `getConfigSchema()`: شکل JSON-Schema مانند پیکربندی معتبر را برمی گرداند
- `validateConfig(config)`: `{ valid, errors[] }` را برمی گرداند

ثبت نام `registerCompressionEngine(engine)` (یا `registerEngine` برای موارد پیشرفته) استفاده می کند که قبل از پذیرش `assertValidEngine()` و `validateConfig(defaultConfig)` را فراخوانی می کند. `unregisterCompressionEngine(id)` برای حذف موتور در زمان اجرا استفاده کنید.

`strategySelector.ts` موتورهای داخلی را قبل از اجرای فشرده سازی ثبت می کند. این اجازه می دهد تا پیش نمایش، فشرده سازی زمان اجرا، حالت انباشته، تست ها و موتورهای آینده از همان مسیر اجرا استفاده کنند.

### فشرده سازی توضیحات MCP (مرتبط)

یک رجیستری جداگانه ابرداده توضیحات ابزار MCP را در — در سطح رجیستری فشرده می کند `open-sse/mcp-server/descriptionCompressor.ts` و [MCP-SERVER.md](../frameworks/MCP-SERVER.md) را ببینید. از قوانین Caveman مجددا استفاده می کند، اما بر روی ابرداده ابزار عمل می کند، نه بارهای درخواستی.

### موتورهای داخلی اضافی

فراتر از Caveman، RTK و LLMLingua-2، رجیستری چندین موتور تخصصی بدون تلفات/ساختاری (که توسط خطوط لوله انباشته، زمین بازی و آزمایشها استفاده میشوند) ارسال میکند:

| موتور        | شناسه           | کاری که انجام می دهد                                                                                                                                                                            |
| ------------ | --------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| CCR          | `ccr`           | Content-Compress-Retrieve (H4): بلوکهای متنی بزرگ به هم پیوسته را با منابع آدرسدهی محتوا جایگزین میکند، بنابراین بلوکهای repeated/large یکبار ارسال میشوند و پس از آن به آنها ارجاع داده میشود. |
| فضای سر      | `headroom`      | SmartCrusher (H3 + N5): فشرده سازی جدولی بدون تلفات بارهای همگن آرایه JSON به شکل `[N rows]` ستونی.                                                                                             |
| یونیزه کننده | `ionizer`       | نمونهگیری ردیف Head/middle/tail برای بلوکهای همگن بسیار بزرگ، ذخیرهسازی وسط بریده شده به عنوان مرجع آدرسدهی محتوای CCR.                                                                         |
| جلسه لغو     | `session-dedup` | حذف تکراری متقاطع با آدرس محتوا (الهام گرفته از TokenMizer): متن الیدهایی که قبلاً در نوبت های قبلی همان جلسه دیده شده بود.                                                                     |

**دستورالعمل بازیابی پروتکل CCR (#8033):** اولین باری که CCR بلاک ≥ 1 را در یک درخواست جایگزین میکند، موتور یک پیام `system` منفرد و بیتوان (به همراه نگهبان `[CCR protocol]` ) به تماسگیرنده میآموزد که نشانگر → tool contract را به تماسگیرنده میآموزد: نشانگر `[CCR retrieve hash=<24hex> chars=N]` به چه معناست، این که هش باید کلمه به کلمه کپی شود (همه 24 کاراکتر هگزا — اشتباه کپیشدهای هستند و احتمالاً علت آن وجود ندارد. نشانگر `[dedup:ref sha=...]` به معنای "نگاهی به گذشته" است، نه "تلفن ابزار". نت تزریق می شود** تنها زمانی که `tools[]` تبلیغ شده تماسگیرنده ثابت کند که واقعاً میتواند به `omniroute_ccr_retrieve` برسد** (`callerSupportsCcrRetrieve()` در `open-sse/services/compression/engines/ccr/protocolInstruction.ts`) — یک تماس گیرنده ساده سازگار با OpenAI بدون آن ابزار هرگز دستورالعملی برای فراخوانی چیزی که نمی تواند به آن دسترسی پیدا کند دریافت نمی کند. بیتوانی با اسکن تاریخچه پیام برای نگهبان قبل از تزریق اعمال میشود، بنابراین درخواستهای چند نوبتی (که پیامهای قبلی را دوباره پخش میکنند) یادداشت را یک بار در هر نوبت روی هم قرار نمیدهند.

## غارنشین

حالت غارنشین بر تراکم معنایی نثر معمولی تمرکز دارد:

- بلوک های کد، URLs، JSON، مسیرها و داده های ساخت یافته را حفظ می کند
- پرکننده، پوشش، بافت مکرر، و عبارت های پیوندی پرمخاطب را حذف می کند
- از بسته های قانون فایل های آگاه به زبان در `open-sse/services/compression/rules/` پشتیبانی می کند
- از طریق حالتهای قدیمی `standard`، `aggressive` و `ultra` در دسترس باقی میماند

سطح داشبورد `Dashboard -> Context & Cache -> Caveman` است.

Caveman upstream توکنهای خروجی کمتر `~75%` ، میانگین خروجی `65%` صرفهجویی در معیارهای با محدوده `22-87%` و ابزار فشردهسازی ورودی `~46%` را گزارش میدهد. OmniRoute از شماره سمت ورودی Caveman هنگام مستندسازی پساندازهای انباشته prompt/context استفاده میکند. حالت خروجی Caveman یک ویژگی رفتار- پاسخ جداگانه است.

## RTK

حالت RTK بر خروجی فرمان و ابزار تمرکز دارد:

- کلاسهای خروجی مانند `git status`، `git branch`، `git diff`، Vitest/Jest/Pytest، تستهای Cargo/Go ، ساختهای TypeScript/Vite/Webpack ، ESLint، npm audit/installs، Docker log، پوسته `find`/`grep`، stack traces و گزارشهای عمومی را شناسایی میکند.
- 49 فیلتر JSON را از `open-sse/services/compression/engines/rtk/filters/` اعمال می کند
- از خط لوله اعلامی به سبک RTK پشتیبانی می کند: برداشتن ANSI ، جایگزینی، اتصال کوتاه با خروجی مطابقت، خطوط strip/keep ، برش در هر خط، برش head/tail/max-line ، و بازگشت به حالت خالی
- از فیلترهای پروژه دارای دروازه اعتماد در `.rtk/filters.json` و فیلترهای جهانی در `DATA_DIR/rtk/filters.json` پشتیبانی می کند
- سکانس های ANSI ، نویز پیشرفت، خطوط مکرر و دیگ بخار غیر مفید را حذف می کند
- خرابیهای قابل اجرا، هشدارها، خلاصهها، فایلهای تغییر یافته و زمینه دنباله را حفظ میکند
- می تواند به صورت اختیاری خروجی خام ویرایش شده برای recovery/debugging را از طریق مسیرهای مدیریت احراز هویت شده حفظ کند

سطح داشبورد `Dashboard -> Context & Cache -> RTK` است.

جزئیات عملیاتی برای فیلترهای سفارشی، اعتماد، تأیید، و بازیابی خروجی خام در [`RTK_COMPRESSION.md`](./RTK_COMPRESSION.md) زنده هستند.

RTK بالادست کاهش `60-90%` را برای فشرده سازی فرمان-خروجی گزارش می کند. مثال README آن یک جلسه کد Claude 30 دقیقهای را نشان میدهد که از توکنهای `~118,000` به `~23,900` یا `79.7%` ذخیره شده میرود.

## LLMLingua-2 (هرس معنایی)

حالت LLMLingua-2 انجام می شود** هرس نشانه معنایی** در نثر با استفاده از یک طبقهبندی رمز کوچک ONNX ، که مکمل موتورهای Caveman و RTK مبتنی بر قانون است:

- نثر را فقط در پیام های غیر سیستمی فشرده می کند. بلوک های کد حصار شده و سایر ساختارهای حفظ شده هرگز تغییر نمی کنند
- باطن `@atjsh/llmlingua-2` (ONNX از طریق `@huggingface/transformers`) را در یک thread کارگر اجرا می کند، بنابراین استنتاج مدل هرگز حلقه رویداد درخواست را مسدود نمی کند.
- است** قابل انباشته شدن** (`stackPriority` 35): در یک خط لوله انباشته، پس از موتورهای ساختاری (CCR، session-dedup، headroom، Caveman) اما قبل از `ultra` اجرا می شود، زیرا هرس معنایی در متن از قبل فشرده سازی شده ساختاری — به عنوان مثال `rtk -> caveman -> llmlingua` مؤثرتر است.
- **شکست در هر خطایی باز می شود** (فقدان deps اختیاری، worker spawn، بارگذاری مدل، استنتاج، یا timeout) → متن اصلی بدون تغییر برگردانده می شود، هرگز خطایی وجود ندارد

محل موتور: `open-sse/services/compression/engines/llmlingua/`. سطح داشبورد `Dashboard -> Context & Cache -> LLMLingua` است.

### مدل ها

مدل پیش فرض است**TinyBERT** (`atjsh/llmlingua-2-js-tinybert-meetingbank`, ~ 57 MB, fast). دقت بالاتر** پایه BERT** مدل (`Arcoldd/llmlingua4j-bert-base-onnx`, ~ 710 MB) از طریق قسمت پیکربندی موتور `model` در دسترس است. `@huggingface/transformers` در اولین تماس، مدل انتخاب شده را با تنبلی از HuggingFace Hub به `${DATA_DIR}/models/llmlingua` دانلود می کند (`modelStore.ts`). یک تغییر پیکربندی `modelPath` به جای آن به یک کپی محلی اشاره میکند (نصبهای آفلاین / با فاصله هوایی).

### وابستگی های اختیاری و نصب بر اساس تقاضا

پشته همتا زمان اجرا LLMLingua قابل هرس است** اختیاری** . دو بسته به عنوان `optionalDependencies` در `package.json` اعلام شده و نگهداری می شود** خارجی** توسط ساخت تولید (`scripts/build/prepublish.ts` آنها را باندل نمی کند):

| بسته                 | نسخه (پین) | یادداشت ها                              |
| -------------------- | ---------- | --------------------------------------- |
| `@atjsh/llmlingua-2` | `2.0.5`    | بسته ورودی؛ دیگران را همتا اعلام می کند |
| `js-tiktoken`        | `^1.0.20`  | توکن ساز                                |

`@huggingface/transformers` در `^4.2.0` سنجاق میشود (مشترک با مسیر تعبیههای محلی و همچنین در بستهای مستقل ردیابی میشود). `@atjsh/llmlingua-2@2.0.5` روی آن با `"^3.5.2 || ^4.0.0"` همتا می شود، بنابراین هر دو Transformers.js v3 و v4 پشتیبانی می شوند. از نسخه 2.0.4، `@atjsh/llmlingua-2` دیگر به `@tensorflow/tfjs` نیاز ندارد، که بزرگترین تک تک مشارکت کننده (TensorFlow.js) را از پشته SLM حذف کرد. فقط دو بسته بالا همتاهای SLM قابل هرس هستند. یک `npm install` استاندارد (dev) پشته اختیاری را به طور خودکار نصب می کند مگر اینکه وابستگی های اختیاری حذف شوند.

**چرا بر حسب تقاضا:** بسته منتشر شده توسط npm، بسته مستقل، و کشتی تصویر Docker** بدون** این عمق ها برای لاغر ماندن هنگامی که آنها غایب باشند، گیت وابستگی کارگر (کاوشگر حل `@atjsh/llmlingua-2` در `worker.ts`) از کار می افتد و موتور** شکست - بی صدا باز می شود** — انتخاب LLMLingua به یک no-op تبدیل می شود (متن بدون تغییر برگردانده می شود، هیچ خطایی ثبت نشده است). برای فعال کردن آن در یک محیط هرس شده، پشته اختیاری را نصب کنید:

```bash
# pin to the versions declared in package.json optionalDependencies
npm install @atjsh/llmlingua-2@2.0.5 js-tiktoken
```

حذف `@tensorflow/tfjs` (2.0.4 +) مشارکتکننده ~ 800 MB که قبلاً غالب بود را حذف میکند — ردپای باقیمانده زمانهای اجرا transformers.js + onnxruntime-node است، بهعلاوه مدل TinyBERT (~ 57 MB) که در اولین استفاده دانلود شده است (نه از طریق npm).

در هر محیط:

- **Dev / `npm install`** — به طور خودکار نصب می شود مگر اینکه `--omit=optional` (یا `--no-optional`) را پاس کرده باشید. هیچ اقدامی لازم نیست
- **جهانی npm (`npm i -g omniroute`) / مستقل** — دستور install بالا را در دایرکتوری بسته نصب شده اجرا کنید یا بدون حذف deps اختیاری دوباره نصب کنید.
- **Docker** — دستور install را در یک لایه تصویر مشتق شده اضافه کنید. تصویر منتشر شده از نظر طراحی باریک است.
- **VPS (PM2)** — را در `node_modules` برنامه نصب کنید، سپس فرآیند را مجدداً راه اندازی کنید تا کارگر دوباره گیت را بررسی کند.
- **Raw Next مستقل (`npm run build` → `.build/next/standalone/server.js`)** — ردیابی مستقل کشتیهای کارگر و یا عمقهای اختیاری را NEITHER ، بنابراین موتور بیصدا از کار میافتد و باز میشود. `scripts/build/colocate-standalone.mjs` هر دو را مجدداً اعمال می کند (کارگر esbuild + اختیاری-عمق بسته شدن در درخت مستقل). پس از هر ساخت به طور خودکار از طریق قلاب `postbuild` npm اجرا می شود. بیتوان، در صورت عدم وجود عمق، نرم میشود.

**فعال بودن آن را تأیید کنید:** با انتخاب LLMLingua ، نثر واقعی در واقع کوچک میشود (موتور باز نمیشود) و اولین درخواست بارگیری مدل را در `${DATA_DIR}/models/llmlingua` آغاز میکند. گیت به طور عمدی فقط `@atjsh/llmlingua-2` — بررسی می کند و سایر همتایان فقط ESM هستند و `require.resolve` روی آنها می اندازد حتی زمانی که — وجود داشته باشد، بنابراین اگر همتای واقعی در زمان `import()` وجود نداشته باشد، کارگر باز هم باز می شود.

## خطوط لوله انباشته شده

حالت Stacked مراحل خط لوله را به ترتیب اجرا می کند. پیش فرض این است:

```txt
rtk -> caveman
```

از این برای جلسات عامل کدنویسی استفاده کنید که در آن یک دستور خروجی دستور را با نثر انسانی یا دستی ترکیب می کند. RTK ابتدا لاگ های ابزار پر سر و صدا را کاهش می دهد، سپس Caveman زبان طبیعی باقی مانده را فشرده می کند.

مراحل خط لوله با `stackedPipeline` در تنظیمات فشرده سازی یا از طریق ترکیب های فشرده سازی پیکربندی می شوند.

هنگامی که هر دو موتور یک بار محموله واجد شرایط را کاهش می دهند، پس انداز ترکیب می شود:

```txt
combined = 1 - (1 - RTK savings) * (1 - Caveman input savings)
average  = 1 - (1 - 0.80) * (1 - 0.46) = 89.2%
range    = 1 - (1 - 0.60..0.90) * (1 - 0.46) = 78.4-94.6%
```

## فیلتر درخت دسترسی MCP

فیلتر هوشمند دسترسی به درخت MCP یک لایه فشرده سازی پس از اجرا است که روی MCP اجرا می شود.** نتایج ابزار** ، نه در دستورات یا زمینه. این درخت دسترسی پرمخاطب و بارهای عکس فوری مرورگر را هدف قرار می دهد که توسط ابزارهایی مانند Playwright، استفاده از رایانه و سرورهای MCP اتوماسیون مرورگر بازگردانده می شوند.

### کاری که انجام می دهد

1. **حذف نویز** — ورودی های خالی generic/text را حذف می کند (`- generic:`، `- text: ""`)
2. **سقوط خواهر و برادر** — هنگامی که خطوط متوالی ≥ `collapseThreshold` (پیشفرض 30) تکرار ساختاری هستند، آنها را در اولین خطوط `collapseKeepHead` ( `collapseKeepTail` 10) + میکند +
3. **حفظ رفر** لنگرهای — `[ref=eXX]` مورد نیاز Playwright/computer-use هرگز لمس نمی شوند
4. **برش سخت** — اگر متن پس از جمعکردن همچنان از `maxTextChars` بیشتر باشد (پیشفرض 50000)، با یک اشاره پیمایش کوتاه میشود تا عامل بتواند به کار خود ادامه دهد.

### محل موتور

```txt
open-sse/services/compression/engines/mcpAccessibility/
  index.ts            ← smartFilterText() entry point
  collapseRepeated.ts ← sibling-collapse algorithm
  constants.ts        ← DEFAULT_MCP_ACCESSIBILITY_CONFIG
```

### پیکربندی

کنترل شده توسط `compression.mcpAccessibility` در تنظیمات جهانی (مهاجرت 056). پیکربندی پیش فرض:

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

این فیلتر فقط برای محمولههای نتیجه ابزار که `type` آنها `"text"` است و طول آنها از `minLengthToProcess` بیشتر است اعمال میشود. بر فشرده سازی سریع یا درخواست بارهای پرداخت تأثیر نمی گذارد.

### پس انداز مورد انتظار

60 تا 80 درصد در نتایج ابزار مرورگر، بسته به پیچیدگی صفحه. الگوریتم فروپاشی در تعداد خطوط O(n) است و تأخیر ناچیزی را اضافه می کند.

### این فیلتر در مقابل موتورهای تراکمی بالا

| جنبه        | غارنشین / RTK / انباشته | فیلتر دسترسی MCP                       |
| ----------- | ----------------------- | -------------------------------------- |
| هدف         | درخواستها / زمینه       | نتایج ابزار MCP                        |
| ماشه        | تنظیم حالت فشرده سازی   | `compression.mcpAccessibility.enabled` |
| دامنه       | همه پیام های SSE        | فقط نتایج ابزار                        |
| لنگرهای Ref | N/A                     | بدون قید و شرط حفظ می شود              |

---

## ترکیب های فشرده سازی

ترکیبهای فشردهسازی، پروفایلهای فشردهسازی نامیده میشوند که میتوانند به ترکیبهای مسیریابی اختصاص داده شوند:

- `compression_combos`: حالت، خط لوله، پیکربندی RTK ، پیکربندی زبان و نشانگر پیشفرض را ذخیره میکند
- `compression_combo_assignments`: یک ترکیب فشرده سازی را به یک ترکیب مسیریابی نگاشت می کند
- ادغام زمان اجرا یک ترکیب فشرده سازی اختصاص داده شده را قبل از لغو ترکیب عمومی حل می کند
- تجزیه و تحلیل شامل `compression_combo_id` و `engine` است

سطح داشبورد: `Dashboard -> Context & Cache -> Compression Combos`.

## پیش نیازها / راهنمای اپراتور (CCR & session-dedup)

CCR (`ccr`) و `session-dedup` متن را جایگزین یا حذف می کنند و a را ترک می کنند** نشانگر** پشت سر این بخش مرجع اپراتور برای سیم کشی یک کلاینت، خواندن دو نشانگر، و بازیابی یا تشخیص محتوای حذف شده است. مکانیک هر موتور در بالا پوشش داده شده است. این لایه "چگونه آن را اجرا کنم" است.

### حمل و نقل و نقاط پایانی

سرور MCP که ابزارهای CCR را در معرض دید قرار می دهد از سه راه قابل دسترسی است. پایه پیش فرض URL `http://localhost:20128` (`OMNIROUTE_BASE_URL`) است:

| حمل و نقل                        | URL / فرمان                             | یادداشت ها                                                                                                                                         |
| -------------------------------- | --------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------- |
| HTTP قابل پخش (مشتری، توصیه شده) | `http://localhost:20128/api/mcp/stream` | مشتریان فعلی MCP با نقطه پایانی صحبت می کنند.                                                                                                      |
| لگاسی SSE تن                     | `http://localhost:20128/api/mcp/sse`    | حمل و نقل تک قلوهای قدیمی. آن را** بسته می شود** جلسات قابل پخش؛ از مشتریان `streamable-http` در برابر `/api/mcp/stream` استفاده کنید، نه این یکی. |
| stdio                            | `omniroute --mcp`                       | برای پیکربندی IDE MCP که فرآیند را ایجاد می کند. هیچ پرچم `--dev` وجود ندارد. `omniroute --mcp` نقطه ورود stdio است.                               |

### سطوح ذخیره سازی (آنچه از راه اندازی مجدد جان سالم به در می برد)

CCR یک است** دو طبقه** ذخیره، نه فقط در حافظه:

- **ردیف حافظه داغ** — درپوش هر بلوک 2 MiB، هر اصل 16 MiB، جهانی 64 MiB. ورودیها بهطور پیشفرض روی 24 ساعت TTL (حداکثر 7 روز) است. بازیابی کامل MCP از حافظه 256 KiB محدود شده است. هر چیزی بزرگتر هنوز از طریق حالت های محدوده / grep قابل دسترسی است.
- **ردیف SQLite بادوام** (`ccr_blocks`، `COMPRESSION_CCR_DURABLE_STORE`، به طور پیشفرض روشن) — از ردیف حافظه پشتیبانی میکند تا یک بلوک از خروج LRU ، راهاندازی مجدد، یا بازیابی فرود در نمونهای دیگر جان سالم به در ببرد. ردیف TTL بلوک را نگه میدارد، بنابراین بلوکی که از TTL گذشته است از هر دو ردیف حذف میشود.

سه محافظ لایه بادوام محدود — حفظ میکنند، یک بلوک فقط زمانی در حافظه باقی میماند که:

1. بلوک تمام شده است** 512 KB** (`MAX_DURABLE_BLOCK_BYTES`)؛
2. زمان اجرا یک زمان اجرا ابری است (بدون دیسک محلی).
3. `COMPRESSION_CCR_DURABLE_STORE=false`.

بنابراین «بلوک ناپدید شد» یک داستان راهاندازی مجدد نیست: یک بلوک sub-512 KB در زمان اجرا محلی و غیر ابری از راهاندازی مجدد از طریق لایه بادوام تا زمانی که TTL آن تمام شود زنده میماند. برای متغیر [به مرجع محیطی](../reference/ENVIRONMENT.md) مراجعه کنید.

### دو نشانگر

| نشانگر                                | معنی                                                                                                                   | آنچه مدل باید انجام دهد                                                                                                                                                                |
| ------------------------------------- | ---------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| `[CCR retrieve hash=<24hex> chars=N]` | یک بلوک بزرگ با آدرس محتوا ذخیره شد.                                                                                   | با `omniroute_ccr_retrieve` تماس بگیرید** هش 24 هگز به کلمه کپی شده است** برای بازگرداندن متن اصلی                                                                                     |
| `[dedup:ref sha=…]`                   | متن حذف شده `session-dedup` قبلاً در نوبت قبلی همان جلسه ارسال شده بود. این یک** نگاه عمدی به عقب** ، ضرر یا خطا نیست. | انجام دهید** نه** با هر ابزاری تماس بگیرید و انجام دهید** نه** سعی کنید آن را "بازسازی" کنید. اولین رخداد متن، کپی شرعی است; نوبت فعلی هرگز بازنویسی نمی شود، در نوبت بعدی حذف می شود. |

نگاه به عقب `[dedup:ref]` یک تصمیم عمدی پروتکل است — هیچ بازسازی پیش از ارسالی وجود ندارد. با آن به عنوان "این متن دقیقاً قبلاً در این جلسه روی سیم بود" رفتار کنید.

### پیش نیازهای مشتری

- **کلید (stdio):** تماس گیرنده stdio هیچ هویتی برای هر درخواست ندارد، بنابراین با `OMNIROUTE_API_KEY` احراز هویت می شود (تنظیم شده در `env` سرور MCP ). بدون آن تماس گیرنده ناشناس است و ابزارهایی که نیاز به یک مدیر اصلی دارند ممکن است از بین بروند.
- **`tools[]` پیش شرط تزریق است.** دستورالعمل CCR retrieve-protocol (#8033) تزریق می شود** فقط** وقتی `tools[]` تبلیغ شده درخواست ثابت کند که مشتری واقعاً می تواند به `omniroute_ccr_retrieve` برسد. تطابق یک بخش انتهایی است — توسط یک جداکننده (`__` — `.` `mcp__gateway__omniroute_ccr_retrieve` `/`، `:`) محدود میشود. یک `tools[]` غایب یا غیر منطبق به این معنی است که دستورالعمل بر اساس طراحی _نه_ تزریق شده است.
- **`codemode:false` (مشتریان OpenCode ).** OpenCode به طور پیش فرض روی Code Mode قرار می گیرد که فقط ابزارهای اصلی خود را برای مدل و تبلیغ می کند** نمی کند** ابزار MCP را در لیست اصلی `tools[]` قرار دهید. `codemode: false` در ورودی سرور MCP تنظیم کنید تا ابزارهای `omniroute_ccr_*` تبلیغ شوند. این یک است** مشتری** تنظیم، نه یک OmniRoute. هنوز دستور CCR تزریق نمیشود: OpenCode ابزاری را `<server>_<tool>` نامگذاری میکند، بنابراین سروری به نام `omniroute` `omniroute_omniroute_ccr_retrieve` را آشکار میکند، و `_` یکی از جداکنندههای همسان نیست.
- **مدیران.** ذخیره سازی و بازیابی به ازای اصل تأیید شده (در هر کلید API ) جدا می شود. یک کلید فقط بلوک های خودش را می بیند.

### دامنه در هر ابزار

اجرای محدوده برای تماس گیرندگان HTTP/SSE با دامنه محدود همیشه فعال است. ابزار `omniroute_` CCR نیاز به:

| ابزار                    | دامنه               |
| ------------------------ | ------------------- |
| `omniroute_ccr_store`    | `write:compression` |
| `omniroute_ccr_delete`   | `write:compression` |
| `omniroute_ccr_retrieve` | `read:compression`  |
| `omniroute_ccr_inspect`  | `read:compression`  |
| `omniroute_ccr_list`     | `read:compression`  |
| `omniroute_ccr_stats`    | `read:compression`  |

یک محدوده از دست رفته an را برمی گرداند** نتیجه خطای ابزار MCP** (`isError: true`، نه HTTP 403 — `403 LOCAL_ONLY` یک auth محافظ مسیر حلقه بک جداگانه است): `Error: Insufficient MCP scopes for <tool>. Missing: <scope>.` یک کلید کنترل از راه دور حداقل میتواند `mcp:connect` را نگه دارد (حک زدن فقط محلی `/api/mcp/` را مجاز میکند) بهعلاوه محدوده read/write خاصی که نیاز دارد.

### ماتریس مشتری

| مشتری            | حمل و نقل                        | پیکربندی برای استفاده                                                                                                                                                                                                                                         | `tools[]` تبلیغ کرد؟ (دستورالعمل → CCR تزریق شد)                                                                                                                                            |
| ---------------- | -------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| کد Claude        | قابل جریان-http                  | `claude mcp add --transport http omniroute http://localhost:20128/api/mcp/stream`                                                                                                                                                                             | بله — MCP-قابلیت. تزریق شده است.                                                                                                                                                            |
| Cursor / Cline   | `stdio`** یا** `streamable-http` | stdio: `omniroute --mcp` با `OMNIROUTE_API_KEY` در `env`; یا یک ورودی MCP از راه دور که به `http://localhost:20128/api/mcp/stream` اشاره می کند (به [راهنمای راه اندازی → MCP پیکربندی مشتری](../guides/SETUP_GUIDE.md#mcp-client-configuration) مراجعه کنید) | بله — ابزار `omniroute_ccr_*` را تبلیغ کنید.                                                                                                                                                |
| OpenCode         | قابل جریان-http                  | `opencode mcp add omniroute --url http://localhost:20128/api/mcp/stream`، بعلاوه `codemode: false`                                                                                                                                                            | ابزار تبلیغاتی فقط با `codemode: false`; دستورالعمل هنوز تزریق نشده است، زیرا `omniroute_omniroute_ccr_retrieve` مطابقت ندارد ( [به پیش نیازهای مشتری](#client-prerequisites) مراجعه کنید). |
| سازگار با OpenAI | HTTP سازگار با OpenAI (تکمیل چت) | سرویس گیرنده استاندارد تکمیل چت در مقابل نقطه پایانی سازگار با OpenAI                                                                                                                                                                                         | **هرگز** — به یک تماسگیرنده ساده سازگار با OpenAI هرگز گفته نمیشود که ابزار را فراخوانی کند و دستورالعمل تزریق نمیشود.                                                                      |

### محدودیت های بازیابی و صفحه بندی

نتایج متن ابزار MCP در اطراف `mcpAccessibility.maxTextChars` (پیشفرض `50000`) بریده میشوند. بازیابی `full` یک بلوک روی 256 KiB — محدود شده است** هیچ بازیابی کامل نامحدودی وجود ندارد** . وقتی `chars=N` یک بلوک بزرگ است، به جای کشیدن کل چیز، آن را صفحه کنید:

- قاعده کلی:**`chars > 40000` → از `mode` استفاده کنید** ، هرگز کامل نیست.
- `mode:"grep"` — regex `pattern` خط به خط تطبیق داده می شود، تا 1000 خط منطبق (`unique: true` قطره تکرار می شود)، ارزان ترین برای "یافتن خطی که نیاز دارم."
- `mode:"lines"` — یک محدوده خط 1 نمایه شده; به `start` و `end` نیاز دارد.
- `mode:"head"` / `mode:"tail"` — first/last `n` خطوط.
- `mode:"stats"` — خط، کاراکتر و بایت بدون بدنه شمارش میشود.

`mode:"lines"` با `start`/`end` برای پیمودن یک بلوک طولانی در صفحات به جای درخواست یکباره همه چیز استفاده کنید.

### نامگذاری ابزار

ابزار بازیابی در حال حاضر `omniroute_ccr_retrieve` نام دارد (پیشوند `omniroute_` یک راه حل قدیمی برای برخورد نام بین سرورها است). یک نام ابزار پسوند محدودتر پاکتر و یک اصلاح برای MCP JSON نتایج کوتاهشده در وسط رشته بهعنوان دنبالههای بالادستی ردیابی میشوند. این صفحه فقط رفتار حمل و نقل فعلی را مستند می کند.

### چرخه عمر جلسه

جلسات Streamable-HTTP بیکار می شوند و سرور آنها را درو می کند. پنجره بیکار ثابت `MCP_SESSION_IDLE_MS` است (به نام ارجاع داده می شود، نه یک مقدار کدگذاری شده، بنابراین این صفحه هنگام تغییر تغییر نمی کند). علامت یک جلسه بدون درو، HTTP 404 با `Unknown Mcp-Session-Id` — است، راه حل این است که جلسه را دوباره وصل کنید یا دوباره راه اندازی کنید.** نه** برای چرخاندن یک کلید، تغییر دامنه یا تغییر نام یک ابزار.

## سطح API

| مسیر                                   | هدف                                                          |
| -------------------------------------- | ------------------------------------------------------------ |
| `/api/settings/compression`            | تنظیمات فشرده سازی جهانی (شامل پیکربندی `mcpAccessibility` ) |
| `/api/compression/preview`             | پیش نمایش هر حالت فشرده سازی                                 |
| `/api/compression/language-packs`      | بسته های زبان Caveman موجود را فهرست کنید                    |
| `/api/context/caveman/config`          | نام مستعار تنظیمات آدم غارنشین                               |
| `/api/context/rtk/config`              | پیش فرض ها و تنظیمات RTK                                     |
| `/api/context/rtk/filters`             | کاتالوگ فیلتر RTK                                            |
| `/api/context/rtk/test`                | نقطه پایانی RTK preview/test                                 |
| `/api/context/rtk/raw-output/[id]`     | بازیابی خروجی خام احراز هویت شده                             |
| `/api/context/combos`                  | ترکیب فشرده سازی CRUD                                        |
| `/api/context/combos/[id]/assignments` | تخصیص مسیریابی-کمبو CRUD                                     |
| `/api/context/analytics`               | نام مستعار تجزیه و تحلیل فشرده سازی                          |

مسیرهای مدیریتی به احراز هویت مدیریت یا بررسی خط مشی کلید API نیاز دارند.

## ابزار MCP

فشرده سازی پنج ابزار MCP را نشان می دهد:

| ابزار                               | دامنه               | هدف                                      |
| ----------------------------------- | ------------------- | ---------------------------------------- |
| `omniroute_compression_status`      | `read:compression`  | تنظیمات، تجزیه و تحلیل، آمار حافظه پنهان |
| `omniroute_compression_configure`   | `write:compression` | تنظیمات جهانی را به روز کنید             |
| `omniroute_set_compression_engine`  | `write:compression` | تنظیم حالت و خط لوله اختیاری             |
| `omniroute_list_compression_combos` | `read:compression`  | ترکیبات فشرده سازی را فهرست کنید         |
| `omniroute_compression_combo_stats` | `read:compression`  | تجزیه و تحلیل combo/engine را بخوانید    |

## محدوده و استثنائات

**جاسازی ها هرگز فشرده نمی شوند.** `open-sse/handlers/embeddings.ts` هرگز هیچ موتور تراکمی را — نمینامد. بدنههای request/response مستقیماً دست نخورده به مجری منتقل میشوند. امروزه این ساختاری است (جاسازیها و تکمیلهای چت، کنترلکنندههای مجزا هستند)، یک بررسی زمان اجرا نیست، اما به این معنی است که نگرانی بردار-اعوجاج در #8034 هیچ سطح نوردهی در مسیر جاسازیها ندارد.

**فیلتر حذف Per-model/endpoint (#8034).** برای تکمیل چت، یک اپراتور میتواند شناسههای مدل / اهداف `provider/model` را نامگذاری کند که هرگز نباید فشرده شوند — اگر فشردهسازی بعداً به مسیر جاسازیهای مجاور نزدیکتر شود، مفید است و به طور کلی برای هر مدلی که دقیق بایت به بایت آن اهمیت دارد (Evals قطعی، cache-sens، و غیره) مفید است.

- فیلد تنظیمات: `exclusions?: string[]` در پیکربندی فشرده سازی جهانی (`GET`/`PUT /api/settings/compression`)، از طریق فضای نام فشرده سازی موجود `key_value` (`src/lib/db/compression.ts`) — بدون جدول جدید باقی ماند.
- برگه داشبورد:** داشبورد → فشرده سازی → استثناها** (`/dashboard/compression/exclusions`).
- نحو الگو: `*` تنها علامت عام است. هر متاکاراکتر regex دیگر در یک الگو قبل از تطبیق خارج می شود، بنابراین `gpt-5.6` فقط با رشته تحت اللفظی مطابقت دارد، هرگز `gpt-5x6` (ReDoS امن، محدود، بدون کمیت ساز تو در تو). الگوها با هر دو id مدل خالی و ترکیب `provider/model` — `gpt-5-6`، `openai/gpt-5-6` و `openai/*` همگی با حروف بزرگ مطابقت دارند و `*` به تنهایی هر مدلی را حذف میکند.
- تطبیق: `isCompressionExcluded()` / `normalizeCompressionExclusions()` در `open-sse/services/compression/exclusions.ts`. `chatCore.ts` هدف حذف شده را درست پس از رفع تنظیمات فشرده سازی بررسی می کند.** قبل از اینکه هر موتوری کار کند** ، و مطابقت را دقیقاً مانند فشرده سازی می کند که — صورت سراسری غیرفعال شده است. رد شدن از طریق `writeCompressionSkip(..., "excluded")` برای مشاهده تجزیه و تحلیل ثبت می شود.
- پیشفرض ( لیست empty/absent ): مشابه رفتار pre-#8034 — هیچ چیز مستثنی نمیشود.

## محدودیت های شناخته شده

- **LLMLingua-2 (SLM) به عمقهای اختیاری همکم نیاز دارد.** کارگر تنها زمانی در یک ساختمان تولیدی اجرا میشود که همتایان `@atjsh/llmlingua-2` + در `dist/node_modules` قرار گرفته باشند (به `scripts/build/colocateOptionals.mjs`، #4286 مراجعه کنید). بدون آنها، موتور باز می شود (متن اصلی را برمی گرداند). وضوح کارگر دیگر به `import.meta.url` بستگی ندارد (در بستهای مستقل میمیرد) — روی زمان اجرا cwd/ `argv[1]` لنگر میاندازد.
- **بسته های زبان غارنشین `de` / `fr` / `ja` جزئی هستند.** آنها قوانین `context` + `filler` + را ارسال می کنند اما بسته های `dedup` / `ultra` `structural` ارسال نمی کنند، بنابراین شدت `ultra` برای آن زبان ها قوی تر از `full` نیست (آنها فقط از قوانین خودشان استفاده می کنند — هیچ بازگشتی بی صدا به قوانین `dedup`/`ultra` انگلیسی وجود ندارد که متن خارجی را مخدوش می کند). `en` / `es` / `id` / `pt-BR` کامل هستند. کمک های `dedup.json` + `ultra.json` برای بسته های جزئی استقبال می شود.
- **تله متری انباشته فقط موتورهایی را که فشرده شده اند فهرست می کند.** یک پله انباشته خط لوله که موتور آن کار می کرد اما 0 درصد صرفه جویی ایجاد می کرد `stats:null` برمی گرداند و بنابراین در `engineBreakdown` — غیرقابل تشخیص از مرحله ای که نادیده گرفته شده است ظاهر نمی شود. تمایز "ران، 0٪" از "پرش" نیاز به تغییر مدل تفکیک دارد و به تعویق می افتد.

## اعتبار سنجی

دروازه های متمرکز برای این منطقه عبارتند از:

```bash
node --import tsx/esm --test tests/unit/compression/rtk-*.test.ts tests/unit/compression/pipeline-integration.test.ts tests/unit/compression/context-compression-api.test.ts
node --import tsx/esm --test tests/unit/compression/*.test.ts tests/golden-set/*.test.ts tests/integration/compression-pipeline.test.ts tests/unit/api/compression/compression-api.test.ts
node --import tsx/esm --test tests/unit/compression/mcpAccessibility*.test.ts
npm run typecheck:core
```
