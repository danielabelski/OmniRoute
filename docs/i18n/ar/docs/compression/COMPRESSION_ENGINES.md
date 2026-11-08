# Compression Engines (العربية)

🌐 **Languages:** 🇺🇸 [English](../../../../compression/COMPRESSION_ENGINES.md) · 🇪🇹 [am](../../../am/docs/compression/COMPRESSION_ENGINES.md) · 🇦🇿 [az](../../../az/docs/compression/COMPRESSION_ENGINES.md) · 🇧🇬 [bg](../../../bg/docs/compression/COMPRESSION_ENGINES.md) · 🇧🇩 [bn](../../../bn/docs/compression/COMPRESSION_ENGINES.md) · 🇧🇦 [bs](../../../bs/docs/compression/COMPRESSION_ENGINES.md) · 🇨🇿 [cs](../../../cs/docs/compression/COMPRESSION_ENGINES.md) · 🇩🇰 [da](../../../da/docs/compression/COMPRESSION_ENGINES.md) · 🇩🇪 [de](../../../de/docs/compression/COMPRESSION_ENGINES.md) · 🇬🇷 [el](../../../el/docs/compression/COMPRESSION_ENGINES.md) · 🇪🇸 [es](../../../es/docs/compression/COMPRESSION_ENGINES.md) · 🇪🇪 [et](../../../et/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇷 [fa](../../../fa/docs/compression/COMPRESSION_ENGINES.md) · 🇫🇮 [fi](../../../fi/docs/compression/COMPRESSION_ENGINES.md) · 🇫🇷 [fr](../../../fr/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇪 [ga](../../../ga/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [gu](../../../gu/docs/compression/COMPRESSION_ENGINES.md) · 🇳🇬 [ha](../../../ha/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇱 [he](../../../he/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [hi](../../../hi/docs/compression/COMPRESSION_ENGINES.md) · 🇭🇷 [hr](../../../hr/docs/compression/COMPRESSION_ENGINES.md) · 🇭🇺 [hu](../../../hu/docs/compression/COMPRESSION_ENGINES.md) · 🇦🇲 [hy](../../../hy/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇩 [id](../../../id/docs/compression/COMPRESSION_ENGINES.md) · 🇳🇬 [ig](../../../ig/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇹 [it](../../../it/docs/compression/COMPRESSION_ENGINES.md) · 🇯🇵 [ja](../../../ja/docs/compression/COMPRESSION_ENGINES.md) · 🇬🇪 [ka](../../../ka/docs/compression/COMPRESSION_ENGINES.md) · 🇰🇭 [km](../../../km/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [kn](../../../kn/docs/compression/COMPRESSION_ENGINES.md) · 🇰🇷 [ko](../../../ko/docs/compression/COMPRESSION_ENGINES.md) · 🇱🇹 [lt](../../../lt/docs/compression/COMPRESSION_ENGINES.md) · 🇱🇻 [lv](../../../lv/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [ml](../../../ml/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [mr](../../../mr/docs/compression/COMPRESSION_ENGINES.md) · 🇲🇾 [ms](../../../ms/docs/compression/COMPRESSION_ENGINES.md) · 🇲🇹 [mt](../../../mt/docs/compression/COMPRESSION_ENGINES.md) · 🇲🇲 [my](../../../my/docs/compression/COMPRESSION_ENGINES.md) · 🇳🇵 [ne](../../../ne/docs/compression/COMPRESSION_ENGINES.md) · 🇳🇱 [nl](../../../nl/docs/compression/COMPRESSION_ENGINES.md) · 🇳🇴 [no](../../../no/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [or](../../../or/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [pa](../../../pa/docs/compression/COMPRESSION_ENGINES.md) · 🇵🇭 [phi](../../../phi/docs/compression/COMPRESSION_ENGINES.md) · 🇵🇱 [pl](../../../pl/docs/compression/COMPRESSION_ENGINES.md) · 🇵🇹 [pt](../../../pt/docs/compression/COMPRESSION_ENGINES.md) · 🇧🇷 [pt-BR](../../../pt-BR/docs/compression/COMPRESSION_ENGINES.md) · 🇷🇴 [ro](../../../ro/docs/compression/COMPRESSION_ENGINES.md) · 🇷🇺 [ru](../../../ru/docs/compression/COMPRESSION_ENGINES.md) · 🇱🇰 [si](../../../si/docs/compression/COMPRESSION_ENGINES.md) · 🇸🇰 [sk](../../../sk/docs/compression/COMPRESSION_ENGINES.md) · 🇸🇮 [sl](../../../sl/docs/compression/COMPRESSION_ENGINES.md) · 🇷🇸 [sr](../../../sr/docs/compression/COMPRESSION_ENGINES.md) · 🇸🇪 [sv](../../../sv/docs/compression/COMPRESSION_ENGINES.md) · 🇰🇪 [sw](../../../sw/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [ta](../../../ta/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [te](../../../te/docs/compression/COMPRESSION_ENGINES.md) · 🇹🇭 [th](../../../th/docs/compression/COMPRESSION_ENGINES.md) · 🇹🇷 [tr](../../../tr/docs/compression/COMPRESSION_ENGINES.md) · 🇺🇦 [uk-UA](../../../uk-UA/docs/compression/COMPRESSION_ENGINES.md) · 🇵🇰 [ur](../../../ur/docs/compression/COMPRESSION_ENGINES.md) · 🇺🇿 [uz](../../../uz/docs/compression/COMPRESSION_ENGINES.md) · 🇻🇳 [vi](../../../vi/docs/compression/COMPRESSION_ENGINES.md) · 🇳🇬 [yo](../../../yo/docs/compression/COMPRESSION_ENGINES.md) · 🇨🇳 [zh-CN](../../../zh-CN/docs/compression/COMPRESSION_ENGINES.md) · 🇹🇼 [zh-TW](../../../zh-TW/docs/compression/COMPRESSION_ENGINES.md)

---

يعتمد ضغط OmniRoute على عقود المحرك. يمكن للوضع تشغيل محرك واحد مباشرة (`caveman` أو `rtk`) أو خط أنابيب مكدس محدد ينفذ محركات متعددة بالترتيب.

## وسائط

| وضع          | مسار المحرك                                                                          | المدخلات المقصودة                                        |
| ------------ | ------------------------------------------------------------------------------------ | -------------------------------------------------------- |
| `off`        | لا أحد                                                                               | الحفظ الفوري الدقيق                                      |
| `lite`       | مساعدين رجل الكهف لايت                                                               | تنظيف منخفض المخاطر دائمًا                               |
| `standard`   | رجل الكهف                                                                            | تكثيف سريع باللغة الطبيعية                               |
| `aggressive` | ملخصات رجل الكهف + history/tool                                                      | جلسات محادثة طويلة                                       |
| `ultra`      | مساعدي التقليم لرجل الكهف +                                                          | استرداد حدود السياق                                      |
| `rtk`        | RTK                                                                                  | مخرجات المحطة الطرفية والصدفة والبناء والاختبار والبوابة |
| `omniglyph`  | OmniGlyph                                                                            | السياق كصورة على سلك الموفر الأصلي                       |
| `stacked`    | خط أنابيب. الطلب الافتراضي هو `session-dedup -> lite`. `rtk -> caveman` هو الاشتراك. | سجلات الأدوات المختلطة والنثر، أقصى قدر من التوفير       |

### ملفات تعريف الضغط OmniGlyph

يقبل محرك `omniglyph` (الحزمة `omniglyph`، 1.4.0 +) ملف تعريف دلالي مسمى، يتم تعيينه عالميًا من خلال `omniglyph.profile` في إعدادات الضغط أو لكل خطوة من خلال تكوين خطوة المسار المكدس:

| حساب تعريفي   | الحدود                                                                          |
| ------------- | ------------------------------------------------------------------------------- |
| `aggressive`  | تقصير. سياسة الإيصالات المنشورة تقيس نظام صور — ومستندات الأداة والتاريخ الكثيف |
| `balanced`    | يحافظ على الحالة الحية أصلية، ويحمي آخر 8 دورات، وينهار التاريخ المغلق الأقدم   |
| `coding-safe` | يحافظ على السلطة ومخططات الأدوات ومخرجات الأداة الحية أصلية، ويحمي آخر 12 دورة  |
| `passthrough` | طرق بدون تحويل؛ تم تخطي المحرك                                                  |

الملف الشخصي هو أ** السقف وليس الارض** : `mergeCompressionProfileOptions` في الحزمة يرفض السماح للمتصل بتجاوز إعادة فتح المسار المفقود الذي تم إغلاق الملف الشخصي، لذلك لا يمكن `preserveSystemPrompt: false` لكل خطوة إعادة تمكين ضغط النظام تحت `coding-safe`.

تم القياس على قاعدة التعليمات البرمجية هذه: `coding-safe` و `balanced` يرفعان `minCompressChars` إلى الحد الأقصى ويبقيان النظام ومخططات الأدوات ونتائج الأداة أصلية، لذا فإن الجلسة التي لم تتراكم محفوظات بعد تتوقف عند `below_min_chars` ولا يحول المحرك شيئًا. هذا هو السبب في أن الوضع الافتراضي هو `aggressive` وليس الملف الشخصي الأكثر أمانًا.

تقوم الحزمة بحل نطاق النموذج الخاص بها وملف التعريف الخاص بها من تكوين البيئة الخاصة بها. OmniRoute لا يفوض القرار مطلقًا: يقوم المحول بتثبيت بوابة النموذج على النطاق الأكثر تقييدًا للحزمة، لذلك يمكن لإعدادات البيئة المضيفة فقط تضييق القائمة المسموح بها، وعدم توسيعها أبدًا بما يتجاوز إيصالات OmniRoute المقاسة.

## سجل المحرك

التسجيل يعيش في `open-sse/services/compression/engines/registry.ts`. تعرض المحركات عقدًا مشتركًا:

- `id`: معرف محرك مستقر مثل `caveman` أو `rtk`
- `apply(text, config)`: مسار التنفيذ القديم الذي تستخدمه خطوط الأنابيب المكدسة
- `compress(input, config)`: مسار التنفيذ الأساسي يعرض إحصائيات + النصية
- `getConfigSchema()`: يُرجع الشكل الذي يشبه مخطط JSON للتكوين الصالح
- `validateConfig(config)`: إرجاع `{ valid, errors[] }`

يستخدم التسجيل `registerCompressionEngine(engine)` (أو `registerEngine` للحالات المتقدمة)، والذي يستدعي `assertValidEngine()` و `validateConfig(defaultConfig)` قبل القبول. استخدم `unregisterCompressionEngine(id)` لإزالة المحرك في وقت التشغيل.

يقوم `strategySelector.ts` بتسجيل المحركات المدمجة قبل تشغيل الضغط. يتيح ذلك للمعاينة وضغط وقت التشغيل والوضع المكدس والاختبارات والمحركات المستقبلية استخدام نفس مسار التنفيذ.

### ضغط وصف MCP (ذات صلة)

يقوم التسجيل المنفصل بضغط البيانات التعريفية لوصف أداة MCP على مستوى التسجيل — راجع `open-sse/mcp-server/descriptionCompressor.ts` و [MCP-SERVER.md](../frameworks/MCP-SERVER.md). فهو يعيد استخدام قواعد Caveman ولكنه يعمل على البيانات التعريفية للأداة، وليس على الحمولات المطلوبة.

### محركات مدمجة إضافية

بالإضافة إلى Caveman و RTK و LLMLingua-2، يشحن السجل العديد من المحركات الهيكلية المتخصصة التي لا تفقد البيانات (تستخدمها خطوط الأنابيب المكدسة والملعب والاختبارات):

| محرك       | بطاقة تعريف     | ماذا يفعل                                                                                                                                                     |
| ---------- | --------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| CCR        | `ccr`           | استرداد ضغط المحتوى (H4): يستبدل الكتل النصية الكبيرة المتجاورة بمراجع تتناول المحتوى، بحيث يتم إرسال كتل repeated/large مرة واحدة ويتم الرجوع إليها بعد ذلك. |
| الإرتفاع   | `headroom`      | SmartCrusher (H3 + N5): ضغط جدولي بدون فقدان لحمولات مصفوفة JSON المتجانسة في نموذج `[N rows]` عمودي.                                                         |
| المؤين     | `ionizer`       | أخذ عينات صف Head/middle/tail للكتل المتجانسة الكبيرة جدًا، وتخزين الوسط المحذوف كمرجع يتناول محتوى CCR.                                                      |
| جلسة dedup | `session-dedup` | إلغاء البيانات المكررة الموجه للمحتوى (مستوحى من TokenMizer): يحذف النص الذي تمت مشاهدته بالفعل في دورات سابقة من نفس الجلسة.                                 |

**تعليمات بروتوكول استرداد CCR (#8033):** في المرة الأولى التي تستبدل فيها CCR كتلة ≥ 1 في الطلب، يقوم المحرك بإضافة رسالة `system` فردية غير فعالة (تبدأ مع حارس `[CCR protocol]` ) لتعليم المتصل عقد أداة العلامة → : ماذا تعني علامة `[CCR retrieve hash=<24hex> chars=N]` ، أنه يجب نسخ التجزئة حرفيًا (جميع الأحرف الست عشرية الـ 24، تجزئات — المنسوخة بشكل خاطئ هي السبب المحتمل لخطأ "لم يتم العثور على الكتلة")، وأن علامة `[dedup:ref sha=...]` تعني "الرجوع إلى التاريخ"، وليس "استدعاء الأداة". يتم حقن المذكرة** فقط عندما يثبت `tools[]` المعلن عنه للمتصل أنه يمكنه الوصول بالفعل `omniroute_ccr_retrieve`** (`callerSupportsCcrRetrieve()` in `open-sse/services/compression/engines/ccr/protocolInstruction.ts`) — المتصل العادي المتوافق مع OpenAI بدون هذه الأداة لا يتلقى أبدًا تعليمات للاتصال بشيء لا يمكنه الوصول إليه. يتم فرض العجز عن طريق مسح سجل الرسائل للحارس قبل الحقن، لذلك لا تقوم الطلبات متعددة الأدوار (التي تعيد تشغيل الرسائل السابقة) بتكديس الملاحظة مرة واحدة في كل دورة.

## رجل الكهف

يركز وضع رجل الكهف على التكثيف الدلالي للنثر العادي:

- يحافظ على كتل التعليمات البرمجية و URLs و JSON والمسارات والبيانات المنظمة
- يزيل الحشو والتحوط والسياق المتكرر والصياغة الضامة المطولة
- يدعم حزم قواعد الملفات المدركة للغة في `open-sse/services/compression/rules/`
- يظل متاحًا من خلال الأوضاع القديمة `standard` و `aggressive` و `ultra`

سطح لوحة القيادة `Dashboard -> Context & Cache -> Caveman`.

يُبلغ Caveman upstream عن `~75%` عدد أقل من الرموز المميزة للمخرجات، ومتوسط توفير في المخرجات `65%` في المعايير ذات نطاق `22-87%` ، وأداة ضغط الإدخال `~46%`. يستخدم OmniRoute رقم جانب إدخال Caveman عند توثيق مدخرات prompt/context المكدسة؛ يظل وضع إخراج رجل الكهف ميزة منفصلة لسلوك الاستجابة.

## RTK

يركز وضع RTK على إخراج الأوامر والأداة:

- يكتشف فئات الإخراج مثل `git status` و `git branch` و `git diff` Vitest/Jest/PytestCargo/Go و TypeScript/Vite/Webpack builds و ESLint و npm audit/installs و Docker logs و shell `find`/`grep` وتتبعات المكدس والسجلات العامة
- يطبق 49 مرشحات JSON من `open-sse/services/compression/engines/rtk/filters/`
- يدعم خط أنابيب تعريفي على طراز RTK: تجريد ANSI ، واستبدال، ودائرة قصر لإخراج المطابقة، وخطوط strip/keep ، واقتطاع كل سطر، واقتطاع head/tail/max-line ، والاحتياطي الفارغ
- يدعم مرشحات المشروع ذات البوابات الموثوقة في `.rtk/filters.json` والمرشحات العالمية في `DATA_DIR/rtk/filters.json`
- شرائط تسلسل ANSI ، وضوضاء التقدم، والخطوط المتكررة، والنموذج النمطي غير المفيد
- يحافظ على حالات الفشل القابلة للتنفيذ، والتحذيرات، والملخصات، والملفات التي تم تغييرها، والسياق الخلفي
- يمكن اختياريًا الاحتفاظ بالمخرجات الخام المنقحة لـ recovery/debugging من خلال طرق الإدارة المعتمدة

سطح لوحة القيادة `Dashboard -> Context & Cache -> RTK`.

التفاصيل التشغيلية للمرشحات المخصصة والثقة والتحقق واسترداد المخرجات الأولية موجودة في [`RTK_COMPRESSION.md`](./RTK_COMPRESSION.md).

تقارير RTK upstream عن توفيرات `60-90%` لضغط مخرجات الأوامر. يُظهر مثال README جلسة كود Claude مدتها 30 دقيقة تنتقل من رموز `~118,000` إلى `~23,900` أو `79.7%` المحفوظة.

## LLMLingua-2 (التقليم الدلالي)

يتم تنفيذ وضع LLMLingua-2** تشذيب الرمز الدلالي** على النثر باستخدام مصنف رمزي ONNX صغير، مكملاً لمحركات Caveman و RTK القائمة على القواعد:

- يضغط النثر في الرسائل غير النظامية فقط؛ لا يتم تغيير كتل التعليمات البرمجية المسيجة والبنيات المحفوظة الأخرى أبدًا
- تشغيل الواجهة الخلفية `@atjsh/llmlingua-2` (ONNX عبر `@huggingface/transformers`) في سلسلة عمليات، لذا لا يؤدي استنتاج النموذج إلى حظر حلقة حدث الطلب أبدًا
- يكون** قابل للتكديس** (`stackPriority` 35): في خط أنابيب مكدس يتم تشغيله بعد المحركات الهيكلية (CCR، session-dedup، headroom، Caveman) ولكن قبل `ultra`، نظرًا لأن التقليم الدلالي يكون أكثر فاعلية في النص المضغوط هيكليًا بالفعل — على سبيل المثال `rtk -> caveman -> llmlingua`
- **فشل - يفتح على أي خطأ** (مفقود عمليات اختيارية أو ظهور العامل أو تحميل النموذج أو الاستدلال أو المهلة) → يتم إرجاع النص الأصلي بدون تغيير، ولا يوجد خطأ أبدًا

موقع المحرك : `open-sse/services/compression/engines/llmlingua/`. سطح لوحة القيادة هو `Dashboard -> Context & Cache -> LLMLingua`.

### نماذج

النموذج الافتراضي هو**TinyBERT** (`atjsh/llmlingua-2-js-tinybert-meetingbank`، ~ 57 MB، سريع). دقة أعلى** قاعدة بيرت** الطراز (`Arcoldd/llmlingua4j-bert-base-onnx`، ~ 710 MB) متاح عبر حقل تكوين المحرك `model`. يقوم `@huggingface/transformers` بتنزيل النموذج المحدد بتكاسل من HuggingFace Hub إلى `${DATA_DIR}/models/llmlingua` عند المكالمة الأولى (`modelStore.ts`)؛ يشير تجاوز تكوين `modelPath` إلى نسخة محلية بدلاً من ذلك (عمليات التثبيت غير المتصلة بالإنترنت/المقيدة بالهواء).

### التبعيات الاختيارية والتثبيت عند الطلب

مكدس نظير LLMLingua القابل للتشغيل هو** خياري** . تم الإعلان عن حزمتين كـ `optionalDependencies` في `package.json` والاحتفاظ بهما** خارجي** من خلال بناء الإنتاج (لا يقوم `scripts/build/prepublish.ts` بتجميعها):

| طَرد                 | الإصدار (دبوس) | ملحوظات                         |
| -------------------- | -------------- | ------------------------------- |
| `@atjsh/llmlingua-2` | `2.0.5`        | حزمة الدخول يعلن الآخرين كأقران |
| `js-tiktoken`        | `^1.0.20`      | رمز مميز                        |

يتم تثبيت `@huggingface/transformers` في `^4.2.0` (مشترك مع مسار التضمين المحلي ويتم تتبعه أيضًا في الحزمة المستقلة)؛ أقرانه `@atjsh/llmlingua-2@2.0.5` مع `"^3.5.2 || ^4.0.0"`، لذلك يتم دعم كل من Transformers.js v3 و v4. منذ الإصدار 2.0.4، لم يعد `@atjsh/llmlingua-2` يتطلب `@tensorflow/tfjs`، مما أدى إلى إزالة أكبر مساهم منفرد (TensorFlow.js) من مكدس SLM. الحزمتان المذكورتان أعلاه فقط هما نظيرات SLM القابلة للتقليم. يقوم `npm install` (dev) القياسي بتثبيت المكدس الاختياري تلقائيًا ما لم يتم حذف التبعيات الاختيارية.

**لماذا عند الطلب:** الحزمة المنشورة من قبل npm، والحزمة المستقلة، وسفينة الصور Docker** بدون** هذه الانخفاضات للبقاء ضئيلة. عند غيابهم، تفشل بوابة تبعية العامل (مسبار حل `@atjsh/llmlingua-2` في `worker.ts`) ويفشل المحرك** فشل-يفتح بصمت** — يصبح تحديد LLMLingua أمرًا محظورًا (يتم إرجاع النص دون تغيير، ولم يتم تسجيل أي خطأ). لتنشيطه في بيئة منقحة، قم بتثبيت المكدس الاختياري:

```bash
# pin to the versions declared in package.json optionalDependencies
npm install @atjsh/llmlingua-2@2.0.5 js-tiktoken
```

تؤدي إزالة `@tensorflow/tfjs` (2.0.4 +) إلى إزالة المساهم ~ 800 MB المسيطر سابقًا — والبصمة المتبقية هي أوقات تشغيل عقدة transformers.js + onnxruntime، بالإضافة إلى تنزيل نموذج TinyBERT (~ 57 MB) عند الاستخدام الأول (وليس عبر npm).

لكل بيئة:

- **ديف / `npm install`** يتم تثبيت — تلقائيًا ما لم تجتاز `--omit=optional` (أو `--no-optional`). لا حاجة لاتخاذ أي إجراء.
- **العالمية npm (`npm i -g omniroute`) / مستقل** — قم بتشغيل أمر التثبيت أعلاه داخل دليل الحزمة المثبتة، أو أعد التثبيت دون إغفال عمليات الإقلاع الاختيارية.
- **Docker** يضيف — أمر التثبيت في طبقة الصورة المشتقة؛ الصورة المنشورة تأتي ضئيلة حسب التصميم.
- **VPS (PM2)** قم بتثبيت — في `node_modules` الخاص بالتطبيق، ثم أعد تشغيل العملية حتى يقوم العامل بإعادة فحص البوابة.
- **الخام التالي المستقل (`npm run build` → `.build/next/standalone/server.js`)** — يتم شحن التتبع المستقل NEITHER العامل أو الإيقافات الاختيارية، لذلك يتم فتح المحرك بصمت. يقوم `scripts/build/colocate-standalone.mjs` بإعادة تطبيق كليهما (يقوم العامل بإنشاء إغلاق اختياري + في الشجرة المستقلة)؛ يتم تشغيله تلقائيًا عبر خطاف `postbuild` npm بعد كل إنشاء. ضعيف، ضعيف عند غياب الإعفاءات.

**التحقق من أنه نشط:** مع تحديد LLMLingua ، يتقلص النثر الحقيقي فعليًا (يتوقف المحرك عن الفتح الفاشل)، ويؤدي الطلب الأول إلى تنزيل النموذج إلى `${DATA_DIR}/models/llmlingua`. تقوم البوابة بالتحقق من `@atjsh/llmlingua-2` — فقط، أما الأقران الآخرون فهم ESM فقط ويرميهم `require.resolve` حتى عندما يكون — موجودًا، لذلك يظل العامل غير قادر على الفتح إذا كان أي نظير مفقودًا حقًا في وقت `import()`.

## خطوط الأنابيب مكدسة

يعمل الوضع المكدس على تشغيل خطوات المسار بالترتيب. الافتراضي هو:

```txt
rtk -> caveman
```

استخدم هذا لجلسات وكيل التشفير حيث يجمع الموجه بين مخرجات الأمر والنثر البشري أو المساعد. يقوم RTK بتقليل سجلات الأدوات المزعجة أولاً، ثم يقوم Caveman بضغط اللغة الطبيعية المتبقية.

يتم تكوين خطوات خط الأنابيب باستخدام `stackedPipeline` في إعدادات الضغط أو من خلال مجموعات الضغط.

عندما يقوم كلا المحركين بتقليل نفس الحمولة المؤهلة، يتضاعف التوفير:

```txt
combined = 1 - (1 - RTK savings) * (1 - Caveman input savings)
average  = 1 - (1 - 0.80) * (1 - 0.46) = 89.2%
range    = 1 - (1 - 0.60..0.90) * (1 - 0.46) = 78.4-94.6%
```

## MCP عامل تصفية شجرة إمكانية الوصول

المرشح الذكي لشجرة إمكانية الوصول MCP عبارة عن طبقة ضغط ما بعد التنفيذ يتم تشغيلها على MCP** نتائج الأداة** ، وليس على المطالبات أو السياق. وهو يستهدف شجرة إمكانية الوصول المطولة وحمولات لقطة المتصفح التي يتم إرجاعها بواسطة أدوات مثل Playwright واستخدام الكمبيوتر وخوادم MCP لأتمتة المتصفح.

### ماذا يفعل

1. **تجريد الضوضاء** — يزيل إدخالات generic/text الفارغة (`- generic:`, `- text: ""`)
2. **انهيار الأخوة** — عندما تكون الخطوط المتتالية ≥ `collapseThreshold` (الافتراضي 30) عبارة عن تكرارات هيكلية، يتم طيها في أول خطوط `collapseKeepHead` (الافتراضي 10) + a count ملخص + آخر خطوط `collapseKeepTail` (الافتراضي 5)
3. **الحفاظ على المرجع** لا يتم لمس المراسي — `[ref=eXX]` التي تتطلبها Playwright/computer-use أبدًا
4. **اقتطاع صعب** — إذا كان النص بعد الانهيار لا يزال يتجاوز `maxTextChars` (الافتراضي 50000)، فسيتم اقتطاعه باستخدام تلميح التنقل حتى يتمكن الوكيل من مواصلة العمل

### موقع المحرك

```txt
open-sse/services/compression/engines/mcpAccessibility/
  index.ts            ← smartFilterText() entry point
  collapseRepeated.ts ← sibling-collapse algorithm
  constants.ts        ← DEFAULT_MCP_ACCESSIBILITY_CONFIG
```

### إعدادات

يتم التحكم فيه بواسطة `compression.mcpAccessibility` في الإعدادات العالمية (الترحيل 056). التكوين الافتراضي:

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

يتم تطبيق المرشح فقط على الحمولات النافعة لنتائج الأداة التي تكون `type` فيها `"text"` والتي يتجاوز طولها `minLengthToProcess`. ولا يؤثر على الضغط الفوري أو طلب الحمولات.

### الادخار المتوقع

60-80% في نتائج أداة لقطة المتصفح، اعتمادًا على مدى تعقيد الصفحة. خوارزمية الانهيار هي O(n) في عدد الأسطر وتضيف زمن وصول ضئيل.

### هذا الفلتر مقابل محركات الضغط المذكورة أعلاه

| وجه            | رجل الكهف / RTK / مكدسة | مرشح إمكانية الوصول MCP                |
| -------------- | ----------------------- | -------------------------------------- |
| هدف            | مطالبات الطلب/السياق    | نتائج أداة MCP                         |
| مشغل           | إعداد وضع الضغط         | `compression.mcpAccessibility.enabled` |
| نِطَاق         | جميع رسائل SSE          | نتائج الأداة فقط                       |
| المراسي المرجع | N/A                     | الحفاظ عليها دون قيد أو شرط            |

---

## مجموعات الضغط

تُسمى مجموعات الضغط ملفات تعريف الضغط التي يمكن تخصيصها لمجموعات التوجيه:

- `compression_combos`: وضع المتاجر، وخط الأنابيب، وتكوين RTK ، وتكوين اللغة، والعلامة الافتراضية
- `compression_combo_assignments`: يقوم بتعيين مجموعة الضغط إلى مجموعة التوجيه
- يعمل تكامل وقت التشغيل على حل مجموعة الضغط المعينة قبل تجاوز التحرير والسرد العام
- تشمل التحليلات `compression_combo_id` و `engine`

سطح لوحة القيادة: `Dashboard -> Context & Cache -> Compression Combos`.

## المتطلبات الأساسية / دليل المشغل (CCR وsession-dedup)

CCR (`ccr`) و `session-dedup` يستبدلان النص أو يحذفانه ويتركان a** علامة** خلف. هذا القسم هو مرجع المشغل لتوصيل العميل وقراءة العلامتين واسترداد المحتوى المحذوف أو تشخيصه. تمت تغطية آليات كل محرك أعلاه؛ هذه هي طبقة "كيف يمكنني تشغيلها".

### وسائل النقل ونقاط النهاية

يمكن الوصول إلى خادم MCP الذي يكشف عن أدوات CCR بثلاث طرق. القاعدة الافتراضية URL هي `http://localhost:20128` (`OMNIROUTE_BASE_URL`):

| ينقل                                  | URL / الأمر                             | ملحوظات                                                                                                                |
| ------------------------------------- | --------------------------------------- | ---------------------------------------------------------------------------------------------------------------------- |
| HTTP القابلة للتدفق (العميل، موصى به) | `http://localhost:20128/api/mcp/stream` | نقطة النهاية التي يتحدث إليها عملاء MCP الحاليون.                                                                      |
| تراث SSE المفرد                       | `http://localhost:20128/api/mcp/sse`    | النقل المفرد الأقدم. هو - هي** يغلق** جلسات قابلة للبث؛ استخدم عملاء `streamable-http` ضد `/api/mcp/stream`، وليس هذا. |
| com.stdio                             | `omniroute --mcp`                       | لتكوين IDE MCP الذي يولد العملية. لا يوجد علم `--dev`. `omniroute --mcp` هي نقطة دخول stdio.                           |

### طبقات التخزين (ما يبقى بعد إعادة التشغيل)

CCR هو أ** ذو مستويين** تخزين، وليس في الذاكرة فقط:

- **الطبقة الساخنة في الذاكرة** — لكل كتلة الحد الأقصى 2 MiB، لكل مدير 16 MiB، العالمي 64 MiB. الإدخالات الافتراضية هي 24 ساعة TTL (بحد أقصى 7 أيام). يبلغ الحد الأقصى لاسترجاع MCP الكامل من الذاكرة 256 KiB؛ لا يزال من الممكن الوصول إلى أي شيء أكبر من خلال أوضاع Ranged/grep.
- **طبقة SQLite متينة** (`ccr_blocks`, `COMPRESSION_CCR_DURABLE_STORE`, on بشكل افتراضي) يدعم — طبقة الذاكرة الداخلية بحيث تنجو الكتلة من إخلاء LRU ، أو إعادة التشغيل، أو هبوط الاسترداد في مثيل آخر. يحتفظ الصف TTL الخاص بالكتلة، لذا فإن الكتلة التي تتجاوز TTL ستختفي من كلا المستويين.

ثلاثة حراس يحافظون على الطبقة المتينة المقيدة بـ — وتبقى الكتلة في الذاكرة فقط عندما:

1. انتهت الكتلة** 512 KB** (`MAX_DURABLE_BLOCK_BYTES`)؛
2. وقت التشغيل هو وقت تشغيل سحابي (لا يوجد قرص محلي)؛
3. `COMPRESSION_CCR_DURABLE_STORE=false`.

لذا فإن "اختفاء الكتلة" ليس قصة إعادة تشغيل شاملة: فكتلة sub-512 KB الموجودة في وقت تشغيل محلي غير سحابي تبقى على قيد الحياة عند إعادة التشغيل عبر الطبقة المتينة حتى نفاد TTL الخاص بها. راجع [مرجع البيئة](../reference/ENVIRONMENT.md) للمتغير.

### العلامتين

| علامة                                 | معنى                                                                                                                               | ما يجب أن يفعله النموذج                                                                                                                                                      |
| ------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| `[CCR retrieve hash=<24hex> chars=N]` | تم تخزين كتلة كبيرة من المحتوى.                                                                                                    | اتصل بـ `omniroute_ccr_retrieve` مع** 24- تجزئة سداسية منقولة حرفيا** لاستعادة النص الأصلي.                                                                                  |
| `[dedup:ref sha=…]`                   | `session-dedup` حذف النص الذي تم إرساله بالفعل في دورة سابقة من نفس الجلسة. هذا هو** نظرة متعمدة إلى الوراء** ، وليس خسارة أو خطأ. | يفعل** لا** استدعاء أي أداة والقيام به** لا** حاول "إعادة بنائه". أول ظهور للنص هو النسخة الأساسية؛ لا يتم إعادة كتابة المنعطف الحالي مطلقًا، بل يتم استخلاصه في منعطف لاحق. |

إن مراجعة `[dedup:ref]` هي قرار بروتوكول متعمد — ولا يوجد إعادة بناء مسبقة. تعامل معه على أنه "كان هذا النص الدقيق موجودًا بالفعل في وقت سابق من هذه الجلسة."

### متطلبات العميل

- **المفتاح (ستوديو):** لا يحمل المتصل stdio هوية لكل طلب، لذلك يتم المصادقة باستخدام `OMNIROUTE_API_KEY` (المحدد في `env` لخادم MCP ). بدونها يكون المتصل مجهولاً وقد تتدهور الأدوات التي تتطلب مديرًا.
- **`tools[]` هو الشرط المسبق للحقن.** يتم حقن تعليمات بروتوكول الاسترداد CCR (#8033).** فقط** عندما يثبت `tools[]` المعلن عنه للطلب أن العميل يمكنه بالفعل الوصول إلى `omniroute_ccr_retrieve`. المطابقة عبارة عن مطابقة مقطع لاحقة يحدها فاصل (`__`, `.`, `/`, `:`) — لا تحتوي أبدًا على سلسلة فرعية مجردة — لذلك لا يزال الاسم ذو مساحة الاسم مثل `mcp__gateway__omniroute_ccr_retrieve` مهمًا. غياب `tools[]` أو عدم التطابق يعني أنه لم يتم إدخال التعليمات حسب التصميم.
- **`codemode:false` (عملاء OpenCode ).** يتم تعيين OpenCode افتراضيًا على وضع Code Mode، الذي يعلن فقط عن أدواته الأصلية للنموذج و** لا** ضع أدوات MCP في قائمة `tools[]` الأصلية. قم بتعيين `codemode: false` على إدخال خادم MCP حتى يتم الإعلان عن أدوات `omniroute_ccr_*`. هذا هو** عميل** الإعداد، وليس واحد OmniRoute. لم يتم إدخال تعليمات CCR بعد: OpenCode يسمي الأداة `<server>_<tool>`، لذا فإن خادمًا يسمى `omniroute` يعرض `omniroute_omniroute_ccr_retrieve`، و `_` ليس أحد الفواصل المتطابقة.
- **مدراء المدارس.** يتم عزل التخزين والاسترجاع لكل مدير مصادق عليه (لكل مفتاح API ). يرى المفتاح الكتل الخاصة به فقط.

### نطاقات لكل أداة

يكون تطبيق النطاق قيد التشغيل دائمًا لمتصلي HTTP/SSE ذوي النطاق الضيق. تتطلب أدوات `omniroute_` CCR ما يلي:

| أداة                     | نِطَاق              |
| ------------------------ | ------------------- |
| `omniroute_ccr_store`    | `write:compression` |
| `omniroute_ccr_delete`   | `write:compression` |
| `omniroute_ccr_retrieve` | `read:compression`  |
| `omniroute_ccr_inspect`  | `read:compression`  |
| `omniroute_ccr_list`     | `read:compression`  |
| `omniroute_ccr_stats`    | `read:compression`  |

يُرجع النطاق المفقود ملفًا** نتيجة خطأ أداة MCP** (`isError: true`، وليس HTTP 403 — فإن `403 LOCAL_ONLY` هو مصادقة حماية مسار الاسترجاع المنفصلة): `Error: Insufficient MCP scopes for <tool>. Missing: <scope>.` يمكن أن يحتوي الحد الأدنى من المفتاح البعيد على `mcp:connect` (يسمح باقتطاع `/api/mcp/` محليًا فقط) بالإضافة إلى نطاق read/write المحدد الذي يحتاجه.

### مصفوفة العميل

| عميل             | ينقل                                    | التكوين للاستخدام                                                                                                                                                                                                                   | `tools[]` المعلن عنها؟ (حقن تعليمات → CCR )                                                                                                                                           |
| ---------------- | --------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| كود Claude       | قابل للبث-http                          | `claude mcp add --transport http omniroute http://localhost:20128/api/mcp/stream`                                                                                                                                                   | نعم — MCP-قادر؛ حقن.                                                                                                                                                                  |
| Cursor / Cline   | `stdio`** أو** `streamable-http`        | stdio: `omniroute --mcp` مع `OMNIROUTE_API_KEY` في `env`؛ أو إدخال MCP عن بعد يشير إلى `http://localhost:20128/api/mcp/stream` (راجع [دليل الإعداد → MCP Client Configuration](../guides/SETUP_GUIDE.md#mcp-client-configuration) ) | نعم — أعلن عن أدوات `omniroute_ccr_*`.                                                                                                                                                |
| OpenCode         | قابل للبث-http                          | `opencode mcp add omniroute --url http://localhost:20128/api/mcp/stream` بالإضافة إلى `codemode: false`                                                                                                                             | الأدوات المعلن عنها فقط مع `codemode: false`; لم يتم إدخال التعليمات بعد، لأن `omniroute_omniroute_ccr_retrieve` غير متطابق (راجع [متطلبات العميل الأساسية](#client-prerequisites) ). |
| متوافق مع OpenAI | HTTP المتوافق مع OpenAI (إكمال الدردشة) | عميل إكمال الدردشة القياسي مقابل نقطة النهاية المتوافقة مع OpenAI                                                                                                                                                                   | **أبداً** — لا يُطلب من المتصل العادي المتوافق مع OpenAI أبدًا الاتصال بالأداة، ولا يتم إدخال التعليمات.                                                                              |

### حدود الاسترجاع وترقيم الصفحات

يتم قص النتائج النصية لأداة MCP حول `mcpAccessibility.maxTextChars` ( `50000` الافتراضي). الحد `full` للكتلة هو 256 KiB —** لا يوجد استرداد كامل غير محدود** . عندما تكون `chars=N` للكتلة كبيرة، قم بصفحتها بدلاً من سحب كل شيء:

- القاعدة الأساسية:**`chars > 40000` → استخدم `mode`** ، أبدا عارية كاملة.
- `mode:"grep"` — regex `pattern` مطابق سطرًا تلو الآخر، ما يصل إلى 1000 سطر مطابق (يتكرر إسقاط `unique: true` )، أرخص عبارة عن "العثور على السطر الوحيد الذي أحتاجه."
- `mode:"lines"` — نطاق خط مفهرس 1؛ يحتاج إلى كل من `start` و `end`.
- خطوط `mode:"head"` / `mode:"tail"` — first/last `n`.
- `mode:"stats"` — عدد السطر والحرف والبايت بدون النص.

استخدم `mode:"lines"` مع `start`/`end` للتنقل في كتلة طويلة من الصفحات بدلاً من طلب الأمر برمته مرة واحدة.

### تسمية الأداة

تُسمى أداة الاسترداد حاليًا `omniroute_ccr_retrieve` (تعد البادئة `omniroute_` حلاً قديمًا لتضاربات الأسماء عبر الخادم). يتم تعقب اسم أداة اللاحقة المحددة وإصلاح نتائج MCP JSON المقطوعة في منتصف السلسلة كمتابعة أولية؛ توثق هذه الصفحة السلوك الحالي الذي تم شحنه فقط.

### دورة حياة الجلسة

جلسات Streamable-HTTP في وضع الخمول ويحصدها الخادم؛ النافذة الخاملة هي ثابت `MCP_SESSION_IDLE_MS` (يُشار إليه بالاسم، وليس بقيمة مشفرة، لذلك لا تنحرف هذه الصفحة عندما تتغير). أعراض الجلسة الخاملة هي HTTP 404 مع `Unknown Mcp-Session-Id` — العلاج هو إعادة الاتصال أو إعادة تشغيل الجلسة،** لا** لتدوير مفتاح، أو تغيير نطاق، أو إعادة تسمية أداة.

## سطح API

| طريق                                   | غاية                                                   |
| -------------------------------------- | ------------------------------------------------------ |
| `/api/settings/compression`            | إعدادات الضغط العامة (تتضمن تكوين `mcpAccessibility` ) |
| `/api/compression/preview`             | معاينة أي وضع الضغط                                    |
| `/api/compression/language-packs`      | قائمة حزم اللغات المتاحة لرجل الكهف                    |
| `/api/context/caveman/config`          | إعدادات رجل الكهف الاسم المستعار                       |
| `/api/context/rtk/config`              | الإعدادات الافتراضية والإعدادات RTK                    |
| `/api/context/rtk/filters`             | كتالوج مرشح RTK                                        |
| `/api/context/rtk/test`                | نقطة النهاية RTK preview/test                          |
| `/api/context/rtk/raw-output/[id]`     | تمت المصادقة على استرداد المخرجات الأولية المنقحة      |
| `/api/context/combos`                  | التحرير والسرد ضغط CRUD                                |
| `/api/context/combos/[id]/assignments` | تعيين التوجيه والسرد CRUD                              |
| `/api/context/analytics`               | الاسم المستعار لتحليلات الضغط                          |

تتطلب مسارات الإدارة مصادقة الإدارة أو عمليات التحقق من سياسة مفتاح API.

## أدوات MCP

يكشف الضغط عن خمس أدوات MCP :

| أداة                                | نِطَاق              | غاية                                                |
| ----------------------------------- | ------------------- | --------------------------------------------------- |
| `omniroute_compression_status`      | `read:compression`  | الإعدادات والتحليلات وإحصائيات ذاكرة التخزين المؤقت |
| `omniroute_compression_configure`   | `write:compression` | تحديث الإعدادات العالمية                            |
| `omniroute_set_compression_engine`  | `write:compression` | ضبط الوضع وخط الأنابيب الاختياري                    |
| `omniroute_list_compression_combos` | `read:compression`  | قائمة مجموعات الضغط                                 |
| `omniroute_compression_combo_stats` | `read:compression`  | قراءة تحليلات combo/engine                          |

## النطاق والاستثناءات

**لا يتم ضغط التضمينات أبدًا.** `open-sse/handlers/embeddings.ts` لا يستدعي أبدًا أي محرك ضغط — تمر أجسام request/response مباشرة إلى المنفذ دون أن يمسها أحد. يعد هذا أمرًا هيكليًا اليوم (التضمينات وإكمال الدردشة عبارة عن معالجات منفصلة)، وليس فحصًا لوقت التشغيل، ولكنه يعني أن مشكلة تشويه المتجهات في #8034 ليس لها سطح تعرض في مسار التضمينات.

**مرشح استبعاد Per-model/endpoint (#8034).** بالنسبة لاستكمالات الدردشة، يمكن للمشغل تسمية معرفات النماذج / أهداف `provider/model` التي لا يجب ضغطها مطلقًا — حاجز الحماية مفيدًا إذا تم توصيل الضغط بالقرب من مسار مجاور للتضمينات لاحقًا، ومفيد بشكل عام لأي نموذج تكون مطالبة البايت مقابل البايت به مهمة (التقييمات الحتمية، والبادئات الحساسة لذاكرة التخزين المؤقت، وما إلى ذلك).

- حقل الإعدادات: `exclusions?: string[]` في تكوين الضغط العام (`GET`/`PUT /api/settings/compression`)، واستمر عبر مساحة اسم الضغط `key_value` الموجودة (`src/lib/db/compression.ts`) — ولا يوجد جدول جديد.
- علامة التبويب لوحة القيادة:** لوحة القيادة → ضغط استبعادات →** (`/dashboard/compression/exclusions`).
- بناء جملة النمط: `*` هو حرف البدل الوحيد. يتم الهروب من كل حرف تعريف عادي آخر في النمط قبل المطابقة، لذلك يطابق `gpt-5.6` السلسلة الحرفية فقط، ولا يطابق `gpt-5x6` أبدًا (ReDoS-safe، محدد، بدون محددات كمية متداخلة). تتطابق الأنماط بشكل غير حساس لحالة الأحرف مع كل من معرف النموذج المجرد و `provider/model` المركب — `gpt-5-6` و `openai/gpt-5-6` و `openai/*` كلها تعمل، ويستبعد `*` وحده كل نموذج.
- المطابقة: `isCompressionExcluded()` / `normalizeCompressionExclusions()` في `open-sse/services/compression/exclusions.ts`. يقوم `chatCore.ts` بالتحقق من الهدف المستبعد مباشرة بعد حل إعدادات الضغط،** قبل تشغيل أي محرك** ، ويتعامل مع المطابقة تمامًا مثل تعطيل الضغط عالميًا — ومن المحتمل أن يكون نص الطلب متطابقًا مع البايت. يتم تسجيل التخطي عبر `writeCompressionSkip(..., "excluded")` لرؤية التحليلات.
- الافتراضي (قائمة empty/absent ): مطابق لسلوك ما قبل #8034 — ولا يتم استبعاد أي شيء.

## القيود المعروفة

- **يتطلب LLMLingua-2 (SLM) تواجدًا اختياريًا مشتركًا.** يعمل العامل فقط في بناء الإنتاج عندما يتواجد أقران `@atjsh/llmlingua-2` + في `dist/node_modules` (راجع `scripts/build/colocateOptionals.mjs` و #4286). بدونها، يفشل المحرك في الفتح (إرجاع النص الأصلي). لم تعد دقة العامل تعتمد على `import.meta.url` (تموت في الحزمة المستقلة) — بل يتم تثبيتها في وقت التشغيل cwd / `argv[1]`.
- **حزم لغات رجل الكهف `de` / `fr` / `ja` جزئية.** إنهم يشحنون قواعد `context` + `filler` + `structural` ولكن لا توجد حزم `dedup` / `ultra` ، لذا فإن كثافة `ultra` ليست أقوى من `full` لتلك اللغات (يستخدمون قواعدهم الخاصة فقط — ولا يوجد تراجع صامت إلى قواعد `dedup`/`ultra` الإنجليزية، والتي من شأنها تشويه النص الأجنبي). `en` / `es` / `id` / `pt-BR` كاملة. نرحب بمساهمات `dedup.json` + `ultra.json` للحزم الجزئية.
- **يسرد القياس عن بعد المكدس فقط المحركات المضغوطة.** خطوة خط الأنابيب المكدسة التي يعمل محركها ولكنها تنتج توفيرًا بنسبة 0٪ تُرجع `stats:null` وبالتالي لا تظهر في `engineBreakdown` — بشكل لا يمكن تمييزه عن الخطوة التي تم تخطيها. قد يتطلب التمييز بين "تشغيل، 0%" و"تخطي" تغيير نموذج الانهيار ويتم تأجيله.

## تصديق

والبوابات المركزة لهذه المنطقة هي:

```bash
node --import tsx/esm --test tests/unit/compression/rtk-*.test.ts tests/unit/compression/pipeline-integration.test.ts tests/unit/compression/context-compression-api.test.ts
node --import tsx/esm --test tests/unit/compression/*.test.ts tests/golden-set/*.test.ts tests/integration/compression-pipeline.test.ts tests/unit/api/compression/compression-api.test.ts
node --import tsx/esm --test tests/unit/compression/mcpAccessibility*.test.ts
npm run typecheck:core
```
