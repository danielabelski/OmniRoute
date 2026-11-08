# Compression Engines (עברית)

🌐 **Languages:** 🇺🇸 [English](../../../../compression/COMPRESSION_ENGINES.md) · 🇪🇹 [am](../../../am/docs/compression/COMPRESSION_ENGINES.md) · 🇸🇦 [ar](../../../ar/docs/compression/COMPRESSION_ENGINES.md) · 🇦🇿 [az](../../../az/docs/compression/COMPRESSION_ENGINES.md) · 🇧🇬 [bg](../../../bg/docs/compression/COMPRESSION_ENGINES.md) · 🇧🇩 [bn](../../../bn/docs/compression/COMPRESSION_ENGINES.md) · 🇧🇦 [bs](../../../bs/docs/compression/COMPRESSION_ENGINES.md) · 🇨🇿 [cs](../../../cs/docs/compression/COMPRESSION_ENGINES.md) · 🇩🇰 [da](../../../da/docs/compression/COMPRESSION_ENGINES.md) · 🇩🇪 [de](../../../de/docs/compression/COMPRESSION_ENGINES.md) · 🇬🇷 [el](../../../el/docs/compression/COMPRESSION_ENGINES.md) · 🇪🇸 [es](../../../es/docs/compression/COMPRESSION_ENGINES.md) · 🇪🇪 [et](../../../et/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇷 [fa](../../../fa/docs/compression/COMPRESSION_ENGINES.md) · 🇫🇮 [fi](../../../fi/docs/compression/COMPRESSION_ENGINES.md) · 🇫🇷 [fr](../../../fr/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇪 [ga](../../../ga/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [gu](../../../gu/docs/compression/COMPRESSION_ENGINES.md) · 🇳🇬 [ha](../../../ha/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [hi](../../../hi/docs/compression/COMPRESSION_ENGINES.md) · 🇭🇷 [hr](../../../hr/docs/compression/COMPRESSION_ENGINES.md) · 🇭🇺 [hu](../../../hu/docs/compression/COMPRESSION_ENGINES.md) · 🇦🇲 [hy](../../../hy/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇩 [id](../../../id/docs/compression/COMPRESSION_ENGINES.md) · 🇳🇬 [ig](../../../ig/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇹 [it](../../../it/docs/compression/COMPRESSION_ENGINES.md) · 🇯🇵 [ja](../../../ja/docs/compression/COMPRESSION_ENGINES.md) · 🇬🇪 [ka](../../../ka/docs/compression/COMPRESSION_ENGINES.md) · 🇰🇭 [km](../../../km/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [kn](../../../kn/docs/compression/COMPRESSION_ENGINES.md) · 🇰🇷 [ko](../../../ko/docs/compression/COMPRESSION_ENGINES.md) · 🇱🇹 [lt](../../../lt/docs/compression/COMPRESSION_ENGINES.md) · 🇱🇻 [lv](../../../lv/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [ml](../../../ml/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [mr](../../../mr/docs/compression/COMPRESSION_ENGINES.md) · 🇲🇾 [ms](../../../ms/docs/compression/COMPRESSION_ENGINES.md) · 🇲🇹 [mt](../../../mt/docs/compression/COMPRESSION_ENGINES.md) · 🇲🇲 [my](../../../my/docs/compression/COMPRESSION_ENGINES.md) · 🇳🇵 [ne](../../../ne/docs/compression/COMPRESSION_ENGINES.md) · 🇳🇱 [nl](../../../nl/docs/compression/COMPRESSION_ENGINES.md) · 🇳🇴 [no](../../../no/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [or](../../../or/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [pa](../../../pa/docs/compression/COMPRESSION_ENGINES.md) · 🇵🇭 [phi](../../../phi/docs/compression/COMPRESSION_ENGINES.md) · 🇵🇱 [pl](../../../pl/docs/compression/COMPRESSION_ENGINES.md) · 🇵🇹 [pt](../../../pt/docs/compression/COMPRESSION_ENGINES.md) · 🇧🇷 [pt-BR](../../../pt-BR/docs/compression/COMPRESSION_ENGINES.md) · 🇷🇴 [ro](../../../ro/docs/compression/COMPRESSION_ENGINES.md) · 🇷🇺 [ru](../../../ru/docs/compression/COMPRESSION_ENGINES.md) · 🇱🇰 [si](../../../si/docs/compression/COMPRESSION_ENGINES.md) · 🇸🇰 [sk](../../../sk/docs/compression/COMPRESSION_ENGINES.md) · 🇸🇮 [sl](../../../sl/docs/compression/COMPRESSION_ENGINES.md) · 🇷🇸 [sr](../../../sr/docs/compression/COMPRESSION_ENGINES.md) · 🇸🇪 [sv](../../../sv/docs/compression/COMPRESSION_ENGINES.md) · 🇰🇪 [sw](../../../sw/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [ta](../../../ta/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [te](../../../te/docs/compression/COMPRESSION_ENGINES.md) · 🇹🇭 [th](../../../th/docs/compression/COMPRESSION_ENGINES.md) · 🇹🇷 [tr](../../../tr/docs/compression/COMPRESSION_ENGINES.md) · 🇺🇦 [uk-UA](../../../uk-UA/docs/compression/COMPRESSION_ENGINES.md) · 🇵🇰 [ur](../../../ur/docs/compression/COMPRESSION_ENGINES.md) · 🇺🇿 [uz](../../../uz/docs/compression/COMPRESSION_ENGINES.md) · 🇻🇳 [vi](../../../vi/docs/compression/COMPRESSION_ENGINES.md) · 🇳🇬 [yo](../../../yo/docs/compression/COMPRESSION_ENGINES.md) · 🇨🇳 [zh-CN](../../../zh-CN/docs/compression/COMPRESSION_ENGINES.md) · 🇹🇼 [zh-TW](../../../zh-TW/docs/compression/COMPRESSION_ENGINES.md)

---

דחיסת OmniRoute בנויה סביב חוזי מנוע. מצב יכול להפעיל מנוע אחד ישירות (`caveman` או `rtk`) או צינור מוערם דטרמיניסטי שמפעיל מספר מנועים לפי הסדר.

## מצבים

| מצב          | נתיב מנוע                                                                              | קלט מיועד                                |
| ------------ | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| `off`        | אַף לֹא אֶחָד                                                                          | שימור מהיר בדיוק                         |
| `lite`       | עוזרי מערות לייט                                                                       | ניקוי תמידי בסיכון נמוך                  |
| `standard`   | איש מערות                                                                              | עיבוי מהירה בשפה הטבעית                  |
| `aggressive` | איש המערות + history/tool מסכמים                                                       | מפגשי צ'אט ארוכים                        |
| `ultra`      | עוזרי + איש מערות זקה                                                                  | שחזור הגבלת הקשר                         |
| `rtk`        | RTK                                                                                    | Terminal, shell, build, test ו-git פלט   |
| `omniglyph`  | OmniGlyph                                                                              | הקשר כתמונה על חוט הספק המקומי           |
| `stacked`    | צינור. ברירת המחדל של הבקשה היא `session-dedup -> lite`. `rtk -> caveman` היא הצטרפות. | יומני כלים ופרוזה מעורבים, חסכון מקסימלי |

### פרופילי דחיסה OmniGlyph

מנוע `omniglyph` (חבילת `omniglyph`, 1.4.0 +) מקבל פרופיל סמנטי בעל שם, המוגדר באופן גלובלי דרך `omniglyph.profile` בהגדרות הדחיסה או לכל שלב דרך תצורת הצעד של הצינור המוערם:

| פּרוֹפִיל     | גְבוּל                                                                                    |
| ------------- | ----------------------------------------------------------------------------------------- |
| `aggressive`  | בְּרִירַת מֶחדָל. המדיניות שהקבלות שפורסמו מדדה מערכת תמונות —, מסמכי כלי והיסטוריה צפופה |
| `balanced`    | שומר על מצב חי, מגן על 8 הפניות האחרונות, ממוטט היסטוריה סגורה ישנה יותר                  |
| `coding-safe` | שומר על סמכות, סכימות כלים ופלט כלים חי מקורי, מגן על 12 הסיבובים האחרונים                |
| `passthrough` | מסלולים ללא שינוי; המנוע נדלג                                                             |

הפרופיל הוא א** תקרה, לא רצפה** : `mergeCompressionProfileOptions` בחבילה מסרב לתת למתקשר לעקוף מחדש נתיב אובדן שהפרופיל נסגר, כך ש- `preserveSystemPrompt: false` לפי שלב לא יכול להפעיל מחדש את דחיסת המערכת תחת `coding-safe`.

נמדד על בסיס קוד זה: `coding-safe` ו- `balanced` מעלים `minCompressChars` למקסימום ושומרים על מערכת, סכימות כלים ותוצאות הכלים מקוריות, כך שהפעלה שעדיין לא צברה היסטוריה נעצרת ב- `below_min_chars` והמנוע לא הופך דבר. לכן ברירת המחדל היא `aggressive` ולא הפרופיל הבטוח ביותר.

החבילה פותרת את היקף המודל והפרופיל שלה מתוך תצורת הסביבה שלה. OmniRoute אף פעם לא מאציל את ההחלטה: המתאם מצמיד את שער הדגם להיקף המגביל ביותר של החבילה, כך שהגדרות סביבת המארח יכולות רק לצמצם את רשימת ההיתרים, לעולם לא להרחיב אותה מעבר לקבלות הנמדדות של OmniRoute.

## רישום מנוע

הרישום מתגורר `open-sse/services/compression/engines/registry.ts`. מנועים חושפים חוזה משותף:

- `id`: מזהה מנוע יציב כגון `caveman` או `rtk`
- `apply(text, config)`: נתיב ביצוע מדור קודם בשימוש על ידי צינורות מוערמים
- `compress(input, config)`: נתיב ביצוע ראשי המחזיר טקסט + סטטיסטיקות
- `getConfigSchema()`: מחזיר את הצורה דמוית JSON-Schema של תצורה חוקית
- `validateConfig(config)`: מחזיר `{ valid, errors[] }`

ההרשמה משתמשת `registerCompressionEngine(engine)` (או `registerEngine` למקרים מתקדמים), הקוראת `assertValidEngine()` ול- `validateConfig(defaultConfig)` לפני הקבלה. השתמש `unregisterCompressionEngine(id)` כדי להסיר מנוע בזמן ריצה.

`strategySelector.ts` רושם את המנועים המובנים לפני ריצת הדחיסה. זה מאפשר תצוגה מקדימה, דחיסה בזמן ריצה, מצב מוערם, בדיקות ומנועים עתידיים להשתמש באותו נתיב ביצוע.

### דחיסת תיאור MCP (קשורה)

רישום נפרד דוחס מטא נתונים של תיאור כלי MCP ברמת הרישום — ראה `open-sse/mcp-server/descriptionCompressor.ts` ו- [MCP-SERVER.md](../frameworks/MCP-SERVER.md). הוא עושה שימוש חוזר בכללי Caveman אך פועל על מטא נתונים של הכלים, לא על מטעני בקשה.

### מנועים מובנים נוספים

מעבר ל-Caveman, RTK ו- LLMLingua-2, הרישום שולח מספר מנועים מיוחדים ללא הפסדים / מבניים (בשימוש על ידי צינורות מוערמים, מגרש המשחקים ובדיקות):

| מָנוֹעַ   | תְעוּדַת זֶהוּת | מה זה עושה                                                                                                                                              |
| --------- | --------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------- |
| CCR       | `ccr`           | Content-Compress-Retrieve (H4): מחליף בלוקי טקסט רציפים גדולים בהפניות כתובות בתוכן, כך שבלוקים repeated/large נשלחים פעם אחת ומתייחסים אליהם לאחר מכן. |
| מרווח ראש | `headroom`      | SmartCrusher (H3 + N5): דחיסה טבלאית ללא הפסדים של מטענים הומוגניים של מערך JSON לצורת `[N rows]` עמודית.                                               |
| מיינן     | `ionizer`       | דגימת שורת Head/middle/tail עבור בלוקים הומוגניים גדולים מאוד, מאחסנת את האמצע הגלום כהפניה לתוכן CCR.                                                  |
| סשן-dedup | `session-dedup` | מניעת כפילויות של פניות צולבות כתובות בתוכן (בהשראת TokenMizer): מסירה טקסט שכבר נראה בפניות קודמות של אותה הפעלה.                                      |

**הוראת פרוטוקול אחזור CCR (#8033):** בפעם הראשונה CCR מחליף ≥ 1 בלוק בבקשה, המנוע מציג הודעת `system` יחידה ואימתנית (המובילה עם ה- `[CCR protocol]` sentinel) מלמדת את המתקשר את חוזה הכלי → : מה המשמעות של סמן `[CCR retrieve hash=<24hex> chars=N]`, שיש להעתיק את ה-hash מילה במילה (כל 24 תווי ה-hex — הם כנראה גורם לפספוסים של החסימה) סמן `[dedup:ref sha=...]` פירושו "הסתכל אחורה בהיסטוריה", לא "קרא לכלי". הפתק מוזרק** רק כאשר `tools[]` המפורסם של המתקשר מוכיח שהוא באמת יכול להגיע `omniroute_ccr_retrieve`** (`callerSupportsCcrRetrieve()` in `open-sse/services/compression/engines/ccr/protocolInstruction.ts`) — מתקשר רגיל תואם OpenAI ללא הכלי הזה לעולם לא מקבל הוראה להתקשר למשהו שהוא לא יכול להגיע אליו. אימפוטנציה נאכפת על ידי סריקת היסטוריית ההודעות עבור הזקיף לפני ההזרקה, כך שבקשות ריבוי פניות (המשמיעות שוב הודעות קודמות) אינן עורמות את הפתק פעם אחת בכל תור.

## איש מערות

מצב איש מערות מתמקד בעיבוי סמנטי של פרוזה רגילה:

- שומר על בלוקי קוד, URLs, JSON, נתיבים ונתונים מובנים
- מסיר חומר מילוי, גידור, הקשר חוזר וניסוח חיבור מילולי
- תומך בחבילות כללי קבצים מודעים לשפה ב- `open-sse/services/compression/rules/`
- נשאר זמין דרך מצבי `standard`, `aggressive` ו- `ultra` מדור קודם

משטח לוח המחוונים הוא `Dashboard -> Context & Cache -> Caveman`.

Caveman במעלה הזרם מדווח `~75%` פחות אסימוני פלט, חיסכון בתפוקה ממוצעת `65%` במדדים עם טווח `22-87%`, וכלי דחיסה של קלט `~46%`. OmniRoute משתמש במספר צד הקלט של Caveman בעת תיעוד חיסכון מוערם prompt/context ; מצב פלט איש מערות נשאר תכונה נפרדת של תגובה-התנהגות.

## RTK

מצב RTK מתמקד בפלט פקודה וכלי:

- מזהה מחלקות פלט כגון `git status`, `git branch`, `git diff`, Vitest/Jest/Pytest, Cargo/Go tests, TypeScript/Vite/Webpack builds, ESLint, npm audit/installs, Docker logs, shell `find`/`grep`, עקבות מחסנית ויומנים גנריים
- מחיל 49 מסנני JSON מ- `open-sse/services/compression/engines/rtk/filters/`
- תומך בצינור ההצהרתי בסגנון RTK: הפשטת ANSI, החלפה, התאמה לקצר פלט, קווי strip/keep, חיתוך לכל קו, חיתוך head/tail/max-line ו-terpty fallback
- תומך במסנני פרויקטים בעלי אמון ב- `.rtk/filters.json` ובמסננים גלובליים ב- `DATA_DIR/rtk/filters.json`
- מסיר רצפי ANSI, רעש התקדמות, שורות חוזרות ונשנות ולוח לא מועיל
- שומר על כשלים שניתנים לפעולה, אזהרות, סיכומים, קבצים שהשתנו והקשר זנב
- אופציונלי יכול לשמור על פלט גולמי שהותקן עבור recovery/debugging באמצעות מסלולי ניהול מאומתים

משטח לוח המחוונים הוא `Dashboard -> Context & Cache -> RTK`.

פרטים תפעוליים עבור מסננים מותאמים אישית, אמון, אימות ושחזור פלט גולמי בשידור חי ב- [`RTK_COMPRESSION.md`](./RTK_COMPRESSION.md).

RTK upstream מדווח על חיסכון `60-90%` עבור דחיסת פקודה-פלט. דוגמה של README שלו מראה הפעלה של 30 דקות Claude Code שעוברת מאסימוני `~118,000` ל- `~23,900`, או `79.7%` שנשמרו.

## LLMLingua-2 (גיזום סמנטי)

מצב LLMLingua-2 מבצע** גיזום אסימון סמנטי** על פרוזה באמצעות מסווג אסימון ONNX קטן, המשלים את מנועי Caveman ו- RTK מבוססי כללים:

- דוחס פרוזה בהודעות שאינן מערכתיות בלבד; בלוקי קוד מגודרים ומבנים שמורים אחרים לעולם אינם משתנים
- מריץ את הקצה האחורי של `@atjsh/llmlingua-2` (ONNX via `@huggingface/transformers`) בשרשור עובד, כך שהסקת המודל לעולם לא חוסמת את לולאת אירוע הבקשה
- הוא** ניתן לערום** (`stackPriority` 35): בצינור מוערם הוא פועל אחרי המנועים המבניים (CCR, session-dedup, headroom, Caveman) אבל לפני `ultra`, שכן גיזום סמנטי הוא היעיל ביותר ב- — של טקסט שכבר דחוס מבחינה מבנית, למשל `rtk -> caveman -> llmlingua`
- **כשל-נפתח בכל שגיאה** (חסרים דגמים אופציונליים, השרצת עובד, טעינת מודל, הסקה או פסק זמן) → הטקסט המקורי מוחזר ללא שינוי, לעולם לא תהיה שגיאה

מיקום המנוע: `open-sse/services/compression/engines/llmlingua/`. משטח לוח המחוונים הוא `Dashboard -> Context & Cache -> LLMLingua`.

### דגמים

מודל ברירת המחדל הוא**TinyBERT** (`atjsh/llmlingua-2-js-tinybert-meetingbank`, ~ 57 MB, מהיר). דיוק גבוה יותר** בסיס BERT** הדגם (`Arcoldd/llmlingua4j-bert-base-onnx`, ~ 710 MB) זמין דרך שדה תצורת המנוע `model`. `@huggingface/transformers` מוריד את הדגם הנבחר בעצלתיים מה- HuggingFace Hub אל `${DATA_DIR}/models/llmlingua` בשיחה הראשונה (`modelStore.ts`); עקיפת תצורה `modelPath` מפנה אותו אל עותק מקומי במקום זאת (התקנות לא מקוונות / מרווחות אוויר).

### תלות אופציונלית והתקנה לפי דרישה

ערימת עמיתים ניתנת לגזירה LLMLingua היא** אופציונלי** . שתי חבילות מוכרזות כ- `optionalDependencies` ב- `package.json` ונשמרות** חִיצוֹנִי** לפי ה-production build (`scripts/build/prepublish.ts` לא מאגד אותם):

| חֲבִילָה             | גרסה (סיכה) | הערות                                |
| -------------------- | ----------- | ------------------------------------ |
| `@atjsh/llmlingua-2` | `2.0.5`     | חבילת כניסה; מכריז על האחרים כעמיתים |
| `js-tiktoken`        | `^1.0.20`   | טוקנייזר                             |

`@huggingface/transformers` מוצמד ב- `^4.2.0` (משותף עם נתיב ההטמעות המקומי וגם נמצא בצרור העצמאי); `@atjsh/llmlingua-2@2.0.5` מציץ עליו עם `"^3.5.2 || ^4.0.0"`, כך שגם Transformers.js v3 וגם v4 נתמכים. מאז 2.0.4, `@atjsh/llmlingua-2` כבר לא דורש `@tensorflow/tfjs`, מה שהסיר את התורם היחיד הגדול ביותר (TensorFlow.js) מחסנית SLM. רק שתי החבילות שלמעלה הן עמיתות SLM הניתנות לגזירה. תקן `npm install` (dev) מתקין את המחסנית האופציונלית באופן אוטומטי אלא אם הושמטו תלות אופציונלית.

**למה לפי דרישה:** החבילה שפורסמה ב-npm, החבילה העצמאית וספינת התמונות Docker** לְלֹא** המשקעים האלה כדי להישאר רזים. כשהם נעדרים, שער התלות של העובד (בדיקת `@atjsh/llmlingua-2` resolve probe ב- `worker.ts`) נכשל והמנוע** כשל-נפתח בשקט** בחירה ב- — LLMLingua הופכת ל-no-op (טקסט הוחזר ללא שינוי, ללא שגיאה מתועדת). כדי להפעיל אותו בסביבה גזומה, התקן את המחסנית האופציונלית:

```bash
# pin to the versions declared in package.json optionalDependencies
npm install @atjsh/llmlingua-2@2.0.5 js-tiktoken
```

הסרת `@tensorflow/tfjs` (2.0.4 +) מבטלת את תורם ~ 800 MB הדומיננטי בעבר — טביעת הרגל הנותרת היא זמני הריצה transformers.js + onnxruntime-node, בתוספת מודל TinyBERT (~ 57 MB) שהורדו בשימוש הראשון (לא דרך npm).

לכל סביבה:

- **Dev / `npm install`** — מותקן באופן אוטומטי אלא אם עברת `--omit=optional` (או `--no-optional`). אין צורך בפעולה.
- **npm גלובלי (`npm i -g omniroute`) / עצמאי** — הפעל את פקודת ההתקנה שלמעלה בתוך ספריית החבילות המותקנות, או התקן מחדש מבלי להשמיט הגדרות אופציונליות.
- **Docker** — הוסף את פקודת ההתקנה בשכבת תמונה נגזרת; התמונה שפורסמה נשלחת רזה בעיצובה.
- **VPS (PM2)** התקן — ב- `node_modules` של האפליקציה, ולאחר מכן הפעל מחדש את התהליך כך שהעובד יבדוק מחדש את השער.
- **Raw Next עצמאי (`npm run build` → `.build/next/standalone/server.js`)** המעקב העצמאי — NEITHER העובד וגם לא את המעמקים האופציונליים, כך שהמנוע נכשל בשקט ונפתח. `scripts/build/colocate-standalone.mjs` מחיל מחדש את שניהם (עובד esbuild + אופציונלי-dep סגירה לתוך העץ העצמאי); הוא פועל אוטומטית באמצעות ה- `postbuild` npm hook לאחר כל בנייה. אימפוטנטי, רך לכשל כאשר חסרים מחלקות.

**ודא שהוא פעיל:** כאשר LLMLingua נבחר, הפרוזה האמיתית למעשה מתכווצת (המנוע מפסיק להיפתח), והבקשה הראשונה מפעילה את הורדת הדגם ל- `${DATA_DIR}/models/llmlingua`. השער חוקר בכוונה רק `@atjsh/llmlingua-2` — שאר העמיתים הם ESM בלבד ו- `require.resolve` זורק עליהם גם כאשר הוא קיים — כך שהעובד עדיין נכשל-נפתח אם עמית כלשהו חסר באמת בזמן `import()`.

## צינורות מוערמים

מצב מוערם מפעיל את שלבי הצינור לפי הסדר. ברירת המחדל היא:

```txt
rtk -> caveman
```

השתמש בזה עבור הפעלות של סוכן קידוד שבהם הנחיה משלבת פלט פקודה עם פרוזה אנושית או עוזרת. RTK מפחית תחילה יומני כלים רועשים, ואז Caveman דוחס את השפה הטבעית שנותרה.

שלבי צינור מוגדרים עם `stackedPipeline` בהגדרות דחיסה או באמצעות שילובי דחיסה.

כאשר שני המנועים מפחיתים את אותו מטען מתאים, תרכובת חיסכון:

```txt
combined = 1 - (1 - RTK savings) * (1 - Caveman input savings)
average  = 1 - (1 - 0.80) * (1 - 0.46) = 89.2%
range    = 1 - (1 - 0.60..0.90) * (1 - 0.46) = 78.4-94.6%
```

## מסנן עץ נגישות MCP

המסנן החכם MCP accessibility-tree הוא שכבת דחיסה לאחר ביצוע הפועלת על MCP** תוצאות הכלים** , לא בהנחות או בהקשר. הוא מכוון למטעני עץ הנגישות המילוליים ולתמונת מצב הדפדפן המוחזרים על ידי כלים כמו Playwright, שימוש במחשב ואוטומציה של שרתי MCP.

### מה זה עושה

1. **הפחתת רעש** — מסיר ערכי generic/text ריקים (`- generic:`, `- text: ""`)
2. **קריסת אחים** — כאשר ≥ `collapseThreshold` (ברירת מחדל 30) שורות עוקבות הן חזרות מבניות, מכווץ אותן לתוך השורות `collapseKeepHead` הראשונות (ברירת מחדל 10) + סיכום ספירה + השורות האחרונות `collapseKeepTail` (5 ברירת מחדל)
3. **שימור רפ** לעולם לא נוגעים בעוגני — `[ref=eXX]` הנדרשים על ידי Playwright/computer-use
4. **חיתוך קשה** — אם הטקסט לאחר הכיווץ עדיין עולה על `maxTextChars` (ברירת מחדל 50,000), נחתך עם רמז ניווט כדי שהסוכן יוכל להמשיך לעבוד

### מיקום המנוע

```txt
open-sse/services/compression/engines/mcpAccessibility/
  index.ts            ← smartFilterText() entry point
  collapseRepeated.ts ← sibling-collapse algorithm
  constants.ts        ← DEFAULT_MCP_ACCESSIBILITY_CONFIG
```

### תְצוּרָה

נשלט על ידי `compression.mcpAccessibility` בהגדרות גלובליות (הגירה 056). תצורת ברירת מחדל:

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

המסנן מוחל רק על עומסי תוצאת כלים שה- `type` שלהם הוא `"text"` ואורכם עולה על `minLengthToProcess`. זה לא משפיע על דחיסה מהירה או על עומסי בקשות.

### חיסכון צפוי

60-80% על תוצאות כלי תצלום הדפדפן, תלוי במורכבות הדף. אלגוריתם הקריסה הוא O(n) בספירת השורות ומוסיף חביון זניח.

### מסנן זה לעומת מנועי הדחיסה שלמעלה

| אַספֶּקט   | איש מערות / RTK / מוערם | מסנן נגישות MCP                        |
| ---------- | ----------------------- | -------------------------------------- |
| יַעַד      | בקשת הנחיות / הקשר      | תוצאות כלי MCP                         |
| לְהַפְעִיל | הגדרת מצב דחיסה         | `compression.mcpAccessibility.enabled` |
| תְחוּם     | כל הודעות SSE           | תוצאות הכלים בלבד                      |
| עוגני ריף  | N/A                     | נשמר ללא תנאי                          |

---

## שילובי דחיסה

שילובי דחיסה נקראים פרופילי דחיסה שניתן להקצות לשילובי ניתוב:

- `compression_combos`: מאחסן מצב, צינור, תצורת RTK, תצורת שפה וסמן ברירת מחדל
- `compression_combo_assignments`: ממפה שילוב דחיסה לשילוב ניתוב
- אינטגרציה בזמן ריצה פותרת שילוב של דחיסה שהוקצתה לפני עקיפת שילוב גנרי
- אנליטיקה כוללת `compression_combo_id` ו- `engine`

משטח לוח המחוונים: `Dashboard -> Context & Cache -> Compression Combos`.

## דרישות מוקדמות / מדריך למפעיל (CCR & session-dedup)

CCR (`ccr`) ו- `session-dedup` מחליפים או מחיקים טקסט ומשאירים א** סַמָן** מֵאָחוֹר. סעיף זה הוא ההפניה למפעיל עבור חיווט לקוח, קריאת שני הסמנים, ואחזור או אבחון של התוכן שנמחק. מכניקה של כל מנוע מכוסה לעיל; זוהי שכבת "איך אני מפעיל את זה".

### הובלות ונקודות קצה

ניתן להגיע לשרת MCP שחושף את כלי CCR בשלוש דרכים. ברירת המחדל של הבסיס URL הוא `http://localhost:20128` (`OMNIROUTE_BASE_URL`):

| תַחְבּוּרָה                    | URL / פקודה                             | הערות                                                                                                                     |
| ------------------------------ | --------------------------------------- | ------------------------------------------------------------------------------------------------------------------------- |
| HTTP ניתן להזרמה (לקוח, מומלץ) | `http://localhost:20128/api/mcp/stream` | נקודת הקצה הנוכחית שלקוחות MCP מדברים איתה.                                                                               |
| מורשת SSE singleton            | `http://localhost:20128/api/mcp/sse`    | הובלה יחידנית ישנה יותר. זֶה** נסגר** הפעלות ניתנות להזרמה; השתמש בלקוחות `streamable-http` נגד `/api/mcp/stream`, לא זה. |
| stdio                          | `omniroute --mcp`                       | עבור IDE MCP config שמוליד את התהליך. אין דגל `--dev` ; `omniroute --mcp` היא נקודת הכניסה של stdio.                      |

### שכבות אחסון (מה ששורד הפעלה מחדש)

CCR הוא א** דו קומתי** חנות, לא בזיכרון בלבד:

- **שכבת זיכרון לוהטת** — לכל בלוק כובע 2 MiB, לכל עיקרי 16 MiB, גלובלי 64 MiB. ברירת המחדל של ערכים היא 24 h TTL (מקסימום 7 ימים). אחזור MCP מלא מהזיכרון מוגבל ל-256 KiB; כל דבר גדול יותר עדיין נגיש דרך מצבי טווח / grep.
- **שכבת SQLite עמידה** (`ccr_blocks`, `COMPRESSION_CCR_DURABLE_STORE`, מופעל כברירת מחדל) — מגבה את שכבת הזיכרון כך שבלוק ישרוד פינוי LRU, הפעלה מחדש או נחיתה אחזור במופע אחר. השורה שומרת על TTL של הבלוק, כך שבלוק מעבר TTL שלו נעלם משני השכבות.

שלושה שומרים שומרים על השכבה העמידה מוגבלת — בלוק נשאר זיכרון רק כאשר:

1. הבלוק נגמר** 512 KB** (`MAX_DURABLE_BLOCK_BYTES`);
2. זמן הריצה הוא זמן ריצה בענן (ללא דיסק מקומי);
3. `COMPRESSION_CCR_DURABLE_STORE=false`.

אז "הבלוק נעלם" הוא לא סיפור הפעלה מחדש כללי: בלוק sub-512 KB בזמן ריצה מקומי ללא ענן שורד הפעלה מחדש דרך הרובד העמיד עד TTL שלו נגמר. ראה [התייחסות לסביבה](../reference/ENVIRONMENT.md) עבור המשתנה.

### שני הסמנים

| סַמָן                                 | מַשְׁמָעוּת                                                                                                       | מה הדגם צריך לעשות                                                                                                                                                                |
| ------------------------------------- | ----------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| `[CCR retrieve hash=<24hex> chars=N]` | בלוק גדול אוחסן בכתובת תוכן.                                                                                      | התקשר ל- `omniroute_ccr_retrieve` עם** 24-hex hash מועתק מילה במילה** כדי להחזיר את הטקסט המקורי.                                                                                 |
| `[dedup:ref sha=…]`                   | `session-dedup` elided טקסט כבר נשלח בסיבוב מוקדם יותר של אותה הפעלה. זהו** מבט מכוון לאחור** , לא הפסד או שגיאה. | לַעֲשׂוֹת** לֹא** להתקשר לכל כלי ולעשות** לֹא** לנסות "לשחזר" את זה. ההופעה הראשונה של הטקסט היא העותק הקנוני; התור הנוכחי אף פעם לא נכתב מחדש, הוא מונע מומים בסיבוב מאוחר יותר. |

המבט האחורי של `[dedup:ref]` הוא החלטה פרוטוקול מכוונת. — אין שחזור שליחה מראש. התייחס לזה כאל "הטקסט המדויק הזה כבר היה על החוט מוקדם יותר בפגישה הזו."

### דרישות מוקדמות ללקוח

- **מפתח (סטדיו):** מתקשר מסוג stdio אינו נושא זהות לפי בקשה, ולכן הוא מאמת עם `OMNIROUTE_API_KEY` (מוגדר ב- `env` של שרת MCP ). בלעדיו המתקשר אנונימי וכלים הדורשים מנהל עלולים לדרדר.
- **`tools[]` הוא התנאי המקדים להזרקה.** הוראת פרוטוקול האחזור CCR (#8033) מוזרקת** רַק** כאשר ה- `tools[]` המפורסם של הבקשה מוכיח שהלקוח באמת יכול להגיע `omniroute_ccr_retrieve`. ההתאמה היא התאמה של קטע נגרר התחום על ידי מפריד (`__`, `.`, `/`, `:`) — אף פעם לא תת-מחרוזת חשופה — אז שם עם רווח שמות כגון `mcp__gateway__omniroute_ccr_retrieve` עדיין נחשב. `tools[]` חסר או לא תואם פירושו שההוראה _לא_ מוזרקת, לפי התכנון.
- **`codemode:false` (לקוחות OpenCode ).** ברירת המחדל OpenCode היא מצב Code, המפרסם רק את הכלים המקוריים שלו למודל ו** לא** שים את כלי MCP ברשימת `tools[]` הילידים. הגדר `codemode: false` בערך השרת MCP כך שכלי `omniroute_ccr_*` יפורסמו. זהו א** לָקוּחַ** הגדרה, לא של OmniRoute. הוא עדיין לא מקבל את הוראת CCR : OpenCode שם לכלי `<server>_<tool>`, אז שרת שנקרא `omniroute` חושף `omniroute_omniroute_ccr_retrieve`, ו- `_` אינו אחד מהמפרידים התואמים.
- **מנהלים.** אחסון ושליפה מבודדים לפי מנהל אימות (למפתח API ). מפתח רואה את הבלוקים שלו בלבד.

### היקפים לכל כלי

אכיפת היקף מופעלת תמיד עבור מתקשרי HTTP/SSE בעלי היקף צר. כלי `omniroute_` CCR דורשים:

| כְּלִי                   | תְחוּם              |
| ------------------------ | ------------------- |
| `omniroute_ccr_store`    | `write:compression` |
| `omniroute_ccr_delete`   | `write:compression` |
| `omniroute_ccr_retrieve` | `read:compression`  |
| `omniroute_ccr_inspect`  | `read:compression`  |
| `omniroute_ccr_list`     | `read:compression`  |
| `omniroute_ccr_stats`    | `read:compression`  |

היקף חסר מחזיר את an** תוצאת שגיאת כלי MCP** (`isError: true`, לא HTTP 403 — ה- `403 LOCAL_ONLY` הוא ה-Loopback הנפרד של route-guard auth): `Error: Insufficient MCP scopes for <tool>. Missing: <scope>.` מפתח מרחוק מינימלי יכול להכיל `mcp:connect` (מאשר את ה- `/api/mcp/` local-only carve-out) בתוספת ה- read/write scope הספציפי שהוא צריך.

### מטריצת לקוח

| לָקוּחַ        | תַחְבּוּרָה                       | תצורה לשימוש                                                                                                                                                                                                                     | `tools[]` פורסם? (הוזרקה הוראת → CCR )                                                                                                                                  |
| -------------- | --------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| קוד Claude     | זרם-http                          | `claude mcp add --transport http omniroute http://localhost:20128/api/mcp/stream`                                                                                                                                                | כן עם יכולת MCP — ; מוזרק.                                                                                                                                              |
| Cursor / Cline | `stdio`** אוֹ** `streamable-http` | stdio: `omniroute --mcp` עם `OMNIROUTE_API_KEY` ב- `env`; או ערך MCP מרוחק המצביע על `http://localhost:20128/api/mcp/stream` (ראה [מדריך ההתקנה → MCP Client Configuration](../guides/SETUP_GUIDE.md#mcp-client-configuration) ) | כן — לפרסם את הכלים `omniroute_ccr_*`.                                                                                                                                  |
| OpenCode       | זרם-http                          | `opencode mcp add omniroute --url http://localhost:20128/api/mcp/stream`, פלוס `codemode: false`                                                                                                                                 | כלים המפורסמים רק עם `codemode: false`; ההוראה עדיין לא מוזרקת, כי `omniroute_omniroute_ccr_retrieve` לא תואמת (ראה [דרישות מוקדמות של הלקוח](#client-prerequisites) ). |
| תואם OpenAI    | HTTP תואם OpenAI (השלמות של צ'אט) | לקוח סטנדרטי של השלמות צ'אט מול נקודת הקצה התואמת OpenAI                                                                                                                                                                         | **לְעוֹלָם לֹא** — למתקשר רגיל תואם OpenAI אף פעם לא נאמר להתקשר לכלי, וההוראה לא מוזרקת.                                                                               |

### מגבלות שליפה ועימוד

תוצאות הטקסט של כלי MCP נחתכות סביב `mcpAccessibility.maxTextChars` (ברירת מחדל `50000`). אחזור `full` של בלוק מוגבל ל-256 KiB —** אין אחזור מלא בלתי מוגבל** . כאשר `chars=N` של בלוק גדול, דפדפו אותו במקום למשוך את כל העניין:

- הֲלָכָה לְמַעֲשֶׂה:**`chars > 40000` → השתמש ב- `mode`** , אף פעם לא מלא חשוף.
- `mode:"grep"` — regex `pattern` תואם שורה אחר שורה, עד 1,000 שורות תואמות (`unique: true` יורד חזרות), הכי זול עבור "מצא את השורה האחת שאני צריך".
- `mode:"lines"` — טווח קו עם 1 אינדקס; צריך גם `start` וגם `end`.
- `mode:"head"` / `mode:"tail"` — first/last `n`.
- `mode:"stats"` — ספירת שורות, תו וביתים ללא הגוף.

השתמש `mode:"lines"` עם `start`/`end` כדי לעבור בלוק ארוך בדפים במקום לבקש את כל העניין בבת אחת.

### מתן שם לכלי

כלי האחזור נקרא כרגע `omniroute_ccr_retrieve` (הקידומת `omniroute_` היא פתרון מיושן להתנגשויות שמות חוצות שרתים). שם כלי נקי יותר עם סיומת מוגבלת ותיקון לתוצאות של MCP JSON קטוע אמצע מחרוזת עוקבים כמעקבים במעלה הזרם; דף זה מתעד את ההתנהגות הנוכחית, הנשלחת בלבד.

### מחזור החיים של הפגישה

הפעלות ניתנות להזרמה-HTTP מתבטלות והשרת קוצר אותן; חלון הסרק הוא קבוע `MCP_SESSION_IDLE_MS` (מוזכר בשם, לא ערך מקודד קשה, כך שהדף הזה לא נסחף כשהוא משתנה). הסימפטום של הפעלה שקצרה בטלה הוא HTTP 404 עם `Unknown Mcp-Session-Id` — התרופה היא להתחבר מחדש או להפעיל מחדש את ההפעלה,** לֹא** כדי לסובב מפתח, לשנות טווח או לשנות שם של כלי.

## משטח API

| מַסלוּל                                | מַטָרָה                                                |
| -------------------------------------- | ------------------------------------------------------ |
| `/api/settings/compression`            | הגדרות דחיסה גלובליות (כולל `mcpAccessibility` config) |
| `/api/compression/preview`             | תצוגה מקדימה של כל מצב דחיסה                           |
| `/api/compression/language-packs`      | רשימת חבילות השפה הזמינות של Caveman                   |
| `/api/context/caveman/config`          | כינוי הגדרות איש מערות                                 |
| `/api/context/rtk/config`              | ברירת המחדל וההגדרות RTK                               |
| `/api/context/rtk/filters`             | קטלוג סינון RTK                                        |
| `/api/context/rtk/test`                | נקודת RTK preview/test                                 |
| `/api/context/rtk/raw-output/[id]`     | שחזור פלט גולמי מאומת                                  |
| `/api/context/combos`                  | משולבת דחיסה CRUD                                      |
| `/api/context/combos/[id]/assignments` | הקצאת ניתוב-קומבו CRUD                                 |
| `/api/context/analytics`               | כינוי לניתוח דחיסה                                     |

נתיבי ניהול דורשים אימות ניהול או בדיקות מדיניות של מפתח API.

## MCP כלים

דחיסה חושפת חמישה כלי MCP :

| כְּלִי                              | תְחוּם              | מַטָרָה                         |
| ----------------------------------- | ------------------- | ------------------------------- |
| `omniroute_compression_status`      | `read:compression`  | הגדרות, ניתוח, סטטיסטיקות מטמון |
| `omniroute_compression_configure`   | `write:compression` | עדכן הגדרות גלובליות            |
| `omniroute_set_compression_engine`  | `write:compression` | הגדר מצב וצינור אופציונלי       |
| `omniroute_list_compression_combos` | `read:compression`  | רשום שילובי דחיסה               |
| `omniroute_compression_combo_stats` | `read:compression`  | קרא אנליטיקס combo/engine       |

## היקף ואי הכללות

**הטבעות לעולם אינן דחוסות.** `open-sse/handlers/embeddings.ts` אף פעם לא קורא לאף מנוע דחיסה — גופי request/response עוברים ישר אל המבצע ללא פגע. זה מבני היום (הטמעות והשלמות צ'אט הן מטפלים לא משותפים), לא בדיקת זמן ריצה, אבל זה אומר שלדאגה של עיוות וקטור ב- #8034 אין משטח חשיפה בנתיב ההטמעות.

**מסנן אי הכללה של Per-model/endpoint (#8034).** עבור השלמות צ'אט, מפעיל יכול למנות מודלים של מזהים / `provider/model` יעדים שאסור לדחוס אותם — מעקה בטיחות שימושי אם הדחיסה תהיה מחוברת אי פעם קרוב יותר לנתיב סמוך להטמעות מאוחר יותר, ובדרך כלל שימושית עבור כל מודל שההנחיה המדויקת של בייט-עבור-byte שלו חשובה (השוואות דטרמיניסטיות, קידומות רגישות למטמון וכו').

- שדה הגדרות: `exclusions?: string[]` בתצורת הדחיסה הגלובלית (`GET`/`PUT /api/settings/compression`), נמשך דרך מרחב השמות הקיים של דחיסה `key_value` (`src/lib/db/compression.ts`) — אין טבלה חדשה.
- כרטיסיית לוח המחוונים:** דשבורד → דחיסה → אי הכללות** (`/dashboard/compression/exclusions`).
- תחביר דפוס: `*` הוא התו הכללי היחיד. כל מטא-תו אחר של ביטוי רגולרי בדפוס עובר אסקייפ לפני ההתאמה, כך ש- `gpt-5.6` תואם למחרוזת המילולית בלבד, לעולם לא `gpt-5x6` (ReDoS-safe, bounded, no quantifiers מקוננים). תבניות תואמות ללא רגישות רישיות הן למזהה המודל החשוף והן ל- `provider/model` המרוכב — `gpt-5-6`, `openai/gpt-5-6` ו- `openai/*` כולם עובדים, ו- `*` לבדו אינו כולל כל דגם.
- התאמה: `isCompressionExcluded()` / `normalizeCompressionExclusions()` ב- `open-sse/services/compression/exclusions.ts`. `chatCore.ts` בודק את היעד שלא נכלל מיד לאחר פתרון הגדרות הדחיסה,** לפני שמנוע כלשהו פועל** , ומתייחס להתאמה בדיוק כמו שדחיסה מושבתת באופן גלובלי — הבקשה הוא זהה לביטים. הדילוג מוקלט באמצעות `writeCompressionSkip(..., "excluded")` עבור נראות אנליטית.
- ברירת מחדל ( רשימת empty/absent ): זהה להתנהגות שלפני #8034 — שום דבר אינו נכלל.

## מגבלות ידועות

- **LLMLingua-2 (SLM) דורש מחלקות אופציונליות במיקום משותף.** העובד רץ ב-build ייצור רק כאשר עמיתים `@atjsh/llmlingua-2` + ממוקמים ב- `dist/node_modules` (ראה `scripts/build/colocateOptionals.mjs`, #4286). בלעדיהם המנוע כשל-נפתח (מחזיר את הטקסט המקורי). רזולוציית העובד כבר לא תלויה ב- `import.meta.url` (הוא מת בחבילה העצמאית) — it עוגן ב-cwd / `argv[1]` של זמן הריצה.
- **חבילות השפה של איש המערות `de` / `fr` / `ja` הן חלקיות.** הם שולחים כללי `context` + `filler` + `structural` אבל אין חבילות `dedup` / `ultra`, כך שעוצמת `ultra` אינה חזקה יותר מ- `full` עבור השפות הללו (הם משתמשים רק בכללים שלהם — אין נפילה שקטה לכללי `dedup`/`ultra` באנגלית, דבר שיפגע בטקסט זר). `en` / `es` / `id` / `pt-BR` הושלמו. תרומות של `dedup.json` + `ultra.json` עבור החבילות החלקיות יתקבלו בברכה.
- **טלמטריה מוערמת מפרטת רק מנועים שנדחסו.** צעד צינור מוערם שהמנוע שלו פעל אך הפיק 0% חיסכון מחזיר `stats:null` ולכן אינו מופיע ב- `engineBreakdown` — שלא ניתן להבחין בצעד שדילג עליו. הבחנה בין "רץ, 0%" ל"דילוג" תדרוש שינוי במודל התמוטטות ונדחה.

## מַתַן תוֹקֵף

השערים הממוקדים לאזור זה הם:

```bash
node --import tsx/esm --test tests/unit/compression/rtk-*.test.ts tests/unit/compression/pipeline-integration.test.ts tests/unit/compression/context-compression-api.test.ts
node --import tsx/esm --test tests/unit/compression/*.test.ts tests/golden-set/*.test.ts tests/integration/compression-pipeline.test.ts tests/unit/api/compression/compression-api.test.ts
node --import tsx/esm --test tests/unit/compression/mcpAccessibility*.test.ts
npm run typecheck:core
```
