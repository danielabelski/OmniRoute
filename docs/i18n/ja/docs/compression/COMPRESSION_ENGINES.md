# Compression Engines (日本語)

🌐 **Languages:** 🇺🇸 [English](../../../../compression/COMPRESSION_ENGINES.md) · 🇪🇹 [am](../../../am/docs/compression/COMPRESSION_ENGINES.md) · 🇸🇦 [ar](../../../ar/docs/compression/COMPRESSION_ENGINES.md) · 🇦🇿 [az](../../../az/docs/compression/COMPRESSION_ENGINES.md) · 🇧🇬 [bg](../../../bg/docs/compression/COMPRESSION_ENGINES.md) · 🇧🇩 [bn](../../../bn/docs/compression/COMPRESSION_ENGINES.md) · 🇧🇦 [bs](../../../bs/docs/compression/COMPRESSION_ENGINES.md) · 🇨🇿 [cs](../../../cs/docs/compression/COMPRESSION_ENGINES.md) · 🇩🇰 [da](../../../da/docs/compression/COMPRESSION_ENGINES.md) · 🇩🇪 [de](../../../de/docs/compression/COMPRESSION_ENGINES.md) · 🇬🇷 [el](../../../el/docs/compression/COMPRESSION_ENGINES.md) · 🇪🇸 [es](../../../es/docs/compression/COMPRESSION_ENGINES.md) · 🇪🇪 [et](../../../et/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇷 [fa](../../../fa/docs/compression/COMPRESSION_ENGINES.md) · 🇫🇮 [fi](../../../fi/docs/compression/COMPRESSION_ENGINES.md) · 🇫🇷 [fr](../../../fr/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇪 [ga](../../../ga/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [gu](../../../gu/docs/compression/COMPRESSION_ENGINES.md) · 🇳🇬 [ha](../../../ha/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇱 [he](../../../he/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [hi](../../../hi/docs/compression/COMPRESSION_ENGINES.md) · 🇭🇷 [hr](../../../hr/docs/compression/COMPRESSION_ENGINES.md) · 🇭🇺 [hu](../../../hu/docs/compression/COMPRESSION_ENGINES.md) · 🇦🇲 [hy](../../../hy/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇩 [id](../../../id/docs/compression/COMPRESSION_ENGINES.md) · 🇳🇬 [ig](../../../ig/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇹 [it](../../../it/docs/compression/COMPRESSION_ENGINES.md) · 🇬🇪 [ka](../../../ka/docs/compression/COMPRESSION_ENGINES.md) · 🇰🇭 [km](../../../km/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [kn](../../../kn/docs/compression/COMPRESSION_ENGINES.md) · 🇰🇷 [ko](../../../ko/docs/compression/COMPRESSION_ENGINES.md) · 🇱🇹 [lt](../../../lt/docs/compression/COMPRESSION_ENGINES.md) · 🇱🇻 [lv](../../../lv/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [ml](../../../ml/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [mr](../../../mr/docs/compression/COMPRESSION_ENGINES.md) · 🇲🇾 [ms](../../../ms/docs/compression/COMPRESSION_ENGINES.md) · 🇲🇹 [mt](../../../mt/docs/compression/COMPRESSION_ENGINES.md) · 🇲🇲 [my](../../../my/docs/compression/COMPRESSION_ENGINES.md) · 🇳🇵 [ne](../../../ne/docs/compression/COMPRESSION_ENGINES.md) · 🇳🇱 [nl](../../../nl/docs/compression/COMPRESSION_ENGINES.md) · 🇳🇴 [no](../../../no/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [or](../../../or/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [pa](../../../pa/docs/compression/COMPRESSION_ENGINES.md) · 🇵🇭 [phi](../../../phi/docs/compression/COMPRESSION_ENGINES.md) · 🇵🇱 [pl](../../../pl/docs/compression/COMPRESSION_ENGINES.md) · 🇵🇹 [pt](../../../pt/docs/compression/COMPRESSION_ENGINES.md) · 🇧🇷 [pt-BR](../../../pt-BR/docs/compression/COMPRESSION_ENGINES.md) · 🇷🇴 [ro](../../../ro/docs/compression/COMPRESSION_ENGINES.md) · 🇷🇺 [ru](../../../ru/docs/compression/COMPRESSION_ENGINES.md) · 🇱🇰 [si](../../../si/docs/compression/COMPRESSION_ENGINES.md) · 🇸🇰 [sk](../../../sk/docs/compression/COMPRESSION_ENGINES.md) · 🇸🇮 [sl](../../../sl/docs/compression/COMPRESSION_ENGINES.md) · 🇷🇸 [sr](../../../sr/docs/compression/COMPRESSION_ENGINES.md) · 🇸🇪 [sv](../../../sv/docs/compression/COMPRESSION_ENGINES.md) · 🇰🇪 [sw](../../../sw/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [ta](../../../ta/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [te](../../../te/docs/compression/COMPRESSION_ENGINES.md) · 🇹🇭 [th](../../../th/docs/compression/COMPRESSION_ENGINES.md) · 🇹🇷 [tr](../../../tr/docs/compression/COMPRESSION_ENGINES.md) · 🇺🇦 [uk-UA](../../../uk-UA/docs/compression/COMPRESSION_ENGINES.md) · 🇵🇰 [ur](../../../ur/docs/compression/COMPRESSION_ENGINES.md) · 🇺🇿 [uz](../../../uz/docs/compression/COMPRESSION_ENGINES.md) · 🇻🇳 [vi](../../../vi/docs/compression/COMPRESSION_ENGINES.md) · 🇳🇬 [yo](../../../yo/docs/compression/COMPRESSION_ENGINES.md) · 🇨🇳 [zh-CN](../../../zh-CN/docs/compression/COMPRESSION_ENGINES.md) · 🇹🇼 [zh-TW](../../../zh-TW/docs/compression/COMPRESSION_ENGINES.md)

---

OmniRoute圧縮はエンジン コントラクトに基づいて構築されています。モードでは、1 つのエンジン (`caveman`または`rtk`) を直接実行することも、複数のエンジンを順番に実行する決定論的なスタック パイプラインを実行することもできます。

## モード

| モード       | エンジンの経路                                                                                         | 意図した入力                                        |
| ------------ | ------------------------------------------------------------------------------------------------------ | --------------------------------------------------- |
| `off`        | なし                                                                                                   | 正確な即時保存                                      |
| `lite`       | 穴居人のライトヘルパー                                                                                 | 低リスクの常時クリーンアップ                        |
| `standard`   | 穴居人                                                                                                 | 自然言語の即時要約                                  |
| `aggressive` | 穴居人+ history/toolサマライザー                                                                       | 長時間のチャットセッション                          |
| `ultra`      | Caveman +剪定ヘルパー                                                                                  | コンテキスト制限の回復                              |
| `rtk`        | RTK                                                                                                    | ターミナル、シェル、ビルド、テスト、および git 出力 |
| `omniglyph`  | OmniGlyph                                                                                              | ネイティブプロバイダーワイヤー上のContext-as-image  |
| `stacked`    | パイプライン。リクエストのデフォルトは`session-dedup -> lite`です。 `rtk -> caveman`はオプトインです。 | ツールのログと散文が混在し、最大限の節約が可能      |

### OmniGlyph圧縮プロファイル

`omniglyph`エンジン (パッケージ`omniglyph`、 1.4.0 +) は、圧縮設定の`omniglyph.profile`を介してグローバルに設定されるか、スタックされたパイプラインのステップ構成を介してステップごとに設定される名前付きセマンティック プロファイルを受け入れます。

| プロフィール  | 境界                                                                                                              |
| ------------- | ----------------------------------------------------------------------------------------------------------------- |
| `aggressive`  | デフォルト。公開されたレシートで測定されたポリシーは、 —画像システム、ツール ドキュメント、および緻密な履歴です。 |
| `balanced`    | ライブ状態をネイティブに維持し、最後の 8 ターンを保護し、古い閉じられた履歴を折りたたみます                       |
| `coding-safe` | 権限、ツールスキーマ、ライブツール出力をネイティブに維持し、最後の 12 ターンを保護します                          |
| `passthrough` | 変換せずにルートします。エンジンがスキップされる                                                                  |

プロフィールは、**床ではなく天井**: パッケージ内の`mergeCompressionProfileOptions`呼び出し元がプロファイルによって閉じられた損失のあるレーンを再度オーバーライドすることを拒否するため、ステップごとの`preserveSystemPrompt: false` `coding-safe`の下でシステム圧縮を再度有効にすることができません。

このコードベースで測定: `coding-safe`と`balanced` `minCompressChars`最大まで引き上げ、システム、ツール スキーマ、ツール結果をネイティブに維持するため、履歴がまだ蓄積されていないセッションは`below_min_chars`で停止し、エンジンは何も変換しません。そのため、デフォルトは最も安全なプロファイルではなく`aggressive`です。

パッケージは、環境構成から独自のモデル スコープとプロファイルを解決します。 OmniRoute決定を委任することはありません。アダプターはモデル ゲートをパッケージの最も制限されたスコープに固定するため、ホスト環境の設定はホワイトリストを狭めることしかできず、 OmniRouteの測定された受信を超えて広げることはできません。

## エンジンレジストリ

レジストリは`open-sse/services/compression/engines/registry.ts`にあります。エンジンは共有コントラクトを公開します。

- `id`: `caveman`や`rtk`などの安定したエンジン ID
- `apply(text, config)`: スタックされたパイプラインによって使用されるレガシー実行パス
- `compress(input, config)`: テキスト+統計を返すプライマリ実行パス
- `getConfigSchema()`: 有効な構成の JSON スキーマに似た形式を返します。
- `validateConfig(config)`: `{ valid, errors[] }`を返します

登録には`registerCompressionEngine(engine)` (または高度な場合は`registerEngine` ) が使用され、受け入れる前に`assertValidEngine()`および`validateConfig(defaultConfig)`が呼び出されます。 `unregisterCompressionEngine(id)`を使用して、実行時にエンジンを削除します。

`strategySelector.ts`圧縮を実行する前に組み込みエンジンを登録します。これにより、プレビュー、ランタイム圧縮、スタック モード、テスト、および将来のエンジンで同じ実行パスを使用できるようになります。

### MCP記述圧縮 (関連)

別のレジストリは、 MCPツールの説明メタデータをレジストリ レベルで圧縮します— `open-sse/mcp-server/descriptionCompressor.ts`および[MCP-SERVER.md](../frameworks/MCP-SERVER.md)参照)。 Caveman ルールを再利用しますが、リクエスト ペイロードではなくツールのメタデータを操作します。

### 追加の内蔵エンジン

Caveman、 RTK、およびLLMLingua-2以外にも、レジストリにはいくつかの特殊なロスレス / 構造エンジン (スタックされたパイプライン、プレイグラウンド、およびテストによって使用される) が同梱されています。

| エンジン           | ID              | 何をするのか                                                                                                                                                                |
| ------------------ | --------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| CCR                | `ccr`           | Content-Compress-Retrieve (H4): 大きな連続テキスト ブロックをコンテンツ アドレス指定された参照に置き換えるため、 repeated/largeブロックは一度送信され、その後参照されます。 |
| ヘッドルーム       | `headroom`      | SmartCrusher (H3 + N5): 同種の JSON 配列ペイロードを列状の`[N rows]`形式にロスレス表形式で圧縮します。                                                                      |
| イオナイザー       | `ionizer`       | 非常に大きな同種ブロックのHead/middle/tail行サンプリング。省略された中央をCCRコンテンツアドレス参照として保存します。                                                       |
| セッション重複除去 | `session-dedup` | コンテンツに対応したクロスターン重複排除 (TokenMizer からインスピレーションを得た): 同じセッションの以前のターンですでに表示されていたテキストを省略します。                |

**CCRプロトコル取得命令 (#8033):**初めてCCRリクエスト内の≥ 1 ブロックを置き換えるとき、エンジンは呼び出し元にマーカーを教える単一の冪等`system`メッセージ ( `[CCR protocol]`センチネルで始まる) を先頭に追加します。 →ツール規約: `[CCR retrieve hash=<24hex> chars=N]`マーカーの意味、ハッシュをそのままコピーする必要があること ( — 24 個の 16 進文字すべてが間違ってコピーされたハッシュは、「ブロックが見つからない」ミスの原因である可能性があります)、そして、 `[dedup:ref sha=...]`マーカーは「ツールを呼び出す」のではなく、「歴史を振り返る」ことを意味します。メモが挿入されます**呼び出し側がアドバタイズした`tools[]`が実際に`omniroute_ccr_retrieve`に到達できることが証明された場合のみ**(`callerSupportsCcrRetrieve()` in `open-sse/services/compression/engines/ccr/protocolInstruction.ts`) —そのツールを持たない単純な OpenAI 互換の呼び出し元は、到達できないものを呼び出す命令を受け取ることはありません。冪等性は、注入前にセンチネルのメッセージ履歴をスキャンすることによって強制されるため、マルチターン リクエスト (前のメッセージを再生する) では、ターンごとに 1 回メモがスタックされません。

## 穴居人

Caveman モードは、通常の散文の意味上の凝縮に重点を置いています。

- コード ブロック、 URLs、 JSON、パス、および構造化データを保持します
- フィラー、ヘッジ、繰り返される文脈、および冗長な接続句を削除します。
- `open-sse/services/compression/rules/`で言語対応ファイル ルール パックをサポートします
- 従来の`standard`、 `aggressive`、および`ultra`モードを通じて引き続き利用可能

ダッシュボード表面は`Dashboard -> Context & Cache -> Caveman`です。

Caveman アップストリームは、 `22-87%`範囲のベンチマークでの`~75%`出力トークンの減少、 `65%`平均出力の節約、および`~46%`入力圧縮ツールを報告しています。 OmniRouteスタックされたprompt/context節約を文書化するときに Caveman 入力側の数値を使用します。 Caveman 出力モードは、別個の応答動作機能のままです。

## RTK

RTKモードはコマンドとツールの出力に重点を置いています。

- `git status`、 `git branch`、 `git diff`、 Vitest/Jest/Pytest、 Cargo/Goテスト、 TypeScript/Vite/Webpackビルド、 ESLint、 npm audit/installs、 Dockerログ、シェル`find`/`grep`、スタック トレース、汎用ログなどの出力クラスを検出します。
- `open-sse/services/compression/engines/rtk/filters/`から 49 のJSONフィルターを適用します
- RTK スタイルの宣言パイプラインをサポートします: ANSIストリッピング、置換、一致出力短絡、 strip/keepライン、ラインごとの切り捨て、 head/tail/max-line切り捨て、および空のフォールバック
- `.rtk/filters.json`のトラストゲート プロジェクト フィルターと`DATA_DIR/rtk/filters.json`のグローバル フィルターをサポートします。
- ANSIシーケンス、進行ノイズ、繰り返し行、役に立たない定型文を削除します。
- 対処可能なエラー、警告、概要、変更されたファイル、および末尾のコンテキストを保持します。
- オプションで、認証された管理ルートを通じてrecovery/debuggingの編集された生の出力を保持できます

ダッシュボード表面は`Dashboard -> Context & Cache -> RTK`です。

カスタム フィルター、信頼、検証、および raw 出力リカバリの操作の詳細は、 [`RTK_COMPRESSION.md`](./RTK_COMPRESSION.md)にあります。

RTKアップストリームは、コマンド出力圧縮のための`60-90%`節約を報告します。そのREADME例は、 `~118,000`トークンから`~23,900`、または`79.7%`に保存される 30 分間のClaudeコード セッションを示しています。

## LLMLingua-2 (セマンティックプルーニング)

LLMLingua-2モードの実行**セマンティックトークンプルーニング**散文では、ルールベースの Caveman エンジンとRTKエンジンを補完する、小さなONNXトークン分類子を使用します。

- 非システム メッセージの散文のみを圧縮します。フェンスで囲まれたコード ブロックとその他の保存された構造は決して変更されません
- `@atjsh/llmlingua-2`バックエンド ( `@huggingface/transformers`経由のONNX ) をワーカー スレッドで実行するため、モデル推論がリクエスト イベント ループをブロックすることはありません
- は**積み重ね可能**(`stackPriority` 35): スタックされたパイプラインでは、構造エンジン (CCR、 session-dedup、headroom、Caveman) の後、ただし`ultra`の前に実行されます。これは、セマンティック プルーニングがすでに構造的に圧縮されているテキスト— ( `rtk -> caveman -> llmlingua`など) に対して最も効果的であるためです。
- **エラーが発生するとフェールオープンします**(オプションの deps、ワーカー スポーン、モデル ロード、推論、またはタイムアウトが欠落しています) →元のテキストが変更されずに返され、エラーは発生しません

エンジンの場所: `open-sse/services/compression/engines/llmlingua/`。ダッシュボードの表面は`Dashboard -> Context & Cache -> LLMLingua`です。

### モデル

デフォルトのモデルは**TinyBERT** (`atjsh/llmlingua-2-js-tinybert-meetingbank`、 ~ 57 MB、高速)。より高い精度**BERTベース**モデル (`Arcoldd/llmlingua4j-bert-base-onnx`、 ~ 710 MB) は、エンジン設定`model`フィールドから入手できます。 `@huggingface/transformers` 、最初の呼び出し (`modelStore.ts`) で、選択されたモデルをHuggingFaceハブから`${DATA_DIR}/models/llmlingua`に遅延ダウンロードします。 `modelPath`設定オーバーライドは、代わりにローカル コピーをポイントします (オフライン/エアギャップ インストール)。

### オプションの依存関係とオンデマンドのインストール

プルーナブルなLLMLinguaランタイム ピア スタックは次のとおりです。**オプション**。 2 つのパッケージが`package.json`で`optionalDependencies`として宣言され、保持されます。**外部の**実稼働ビルドによる (`scripts/build/prepublish.ts`はそれらをバンドルしません):

| パッケージ           | バージョン (ピン) | 注意事項                                           |
| -------------------- | ----------------- | -------------------------------------------------- |
| `@atjsh/llmlingua-2` | `2.0.5`           | エントリーパッケージ。他の人をピアとして宣言します |
| `js-tiktoken`        | `^1.0.20`         | トークナイザー                                     |

`@huggingface/transformers`は`^4.2.0`に固定されます (ローカル埋め込みパスと共有され、スタンドアロン バンドルにもトレースされます)。 `@atjsh/llmlingua-2@2.0.5` `"^3.5.2 || ^4.0.0"`とピアリングするため、 Transformers.js v3 と v4 の両方がサポートされます。 2.0.4 以降、 `@atjsh/llmlingua-2` `@tensorflow/tfjs`必要としなくなり、最大の単一貢献者 (TensorFlow.js) がSLMスタックから削除されました。上記の 2 つのパッケージのみがプルーニング可能なSLMピアです。標準の`npm install` (dev) は、オプションの依存関係が省略されない限り、オプションのスタックを自動的にインストールします。

**オンデマンドの理由:** npm で公開されたパッケージ、スタンドアロン バンドル、およびDockerイメージ シップ**それなし**スリムを維持するためのこれらのデプス。これらが存在しない場合、ワーカーの依存関係ゲート ( `worker.ts`の`@atjsh/llmlingua-2`解決プローブ) が失敗し、エンジンが**サイレントにフェールオープンします**— LLMLinguaを選択すると、操作は行われなくなります (テキストは変更されずに返され、エラーはログに記録されません)。プルーニングされた環境でアクティブ化するには、オプションのスタックをインストールします。

```bash
# pin to the versions declared in package.json optionalDependencies
npm install @atjsh/llmlingua-2@2.0.5 js-tiktoken
```

`@tensorflow/tfjs`削除 (2.0.4 +) により、以前の支配的な~ 800 MBコントリビュータ—が削除されます。残りのフットプリントは、 transformers.js + onnxruntime-node ランタイムに加え、最初の使用時に (npm 経由ではなく) ダウンロードされたTinyBERTモデル (~ 57 MB) です。

環境ごと:

- **開発 / `npm install`** `--omit=optional` (または`--no-optional`) を渡さない限り、 —自動的にインストールされます。アクションは必要ありません。
- **グローバル npm (`npm i -g omniroute`) / スタンドアロン**—インストールされたパッケージ ディレクトリ内で上記の install コマンドを実行するか、オプションの deps を省略せずに再インストールします。
- **Docker** —派生イメージ レイヤーに install コマンドを追加します。公開された画像は設計上スリムに出荷されます。
- **VPS (PM2)** —アプリの`node_modules`にインストールし、プロセスを再起動して、ワーカーがゲートを再プローブするようにします。
- **Raw Next スタンドアロン (`npm run build` → `.build/next/standalone/server.js`)** —スタンドアロン トレースにはNEITHERワーカーもオプションの deps も同梱されるため、エンジンはサイレントにフェールオープンします。 `scripts/build/colocate-standalone.mjs`両方を再適用します (ワーカーは+オプションの展開クロージャをスタンドアロン ツリーにビルドします)。これは、ビルドのたびに`postbuild` npm フックを介して自動的に実行されます。べき等であり、deps が存在しない場合はフェイルソフトです。

**アクティブであることを確認します。** LLMLinguaを選択すると、実際の散文は実際に縮小し (エンジンはフェールオープンを停止します)、最初のリクエストによって`${DATA_DIR}/models/llmlingua`へのモデルのダウンロードがトリガーされます。ゲートは意図的に`@atjsh/llmlingua-2` —のみをプローブし、他のピアは ESM 専用であり、 —存在する場合でも`require.resolve`それらにスローされるため、 `import()`時点で本当にピアが欠落している場合でもワーカーはフェールオープンします。

## スタックされたパイプライン

スタックモードでは、パイプラインステップを順番に実行します。デフォルトは次のとおりです。

```txt
rtk -> caveman
```

これは、プロンプトがコマンド出力と人間またはアシスタントの文章を組み合わせるコーディング エージェント セッションに使用します。 RTK最初にノイズの多いツール ログを削減し、次に Caveman が残りの自然言語を圧縮します。

パイプライン ステップは、圧縮設定で`stackedPipeline`を使用するか、圧縮コンボを通じて構成されます。

両方のエンジンが同じ対象ペイロードを削減すると、節約はさらに増大します。

```txt
combined = 1 - (1 - RTK savings) * (1 - Caveman input savings)
average  = 1 - (1 - 0.80) * (1 - 0.46) = 89.2%
range    = 1 - (1 - 0.60..0.90) * (1 - 0.46) = 78.4-94.6%
```

## MCPアクセシビリティ ツリー フィルター

MCPアクセシビリティ ツリー スマート フィルターは、 MCP上で実行される実行後圧縮レイヤーです。**ツールの結果**、プロンプトやコンテキストではありません。これはPlaywright、コンピュータ使用、およびブラウザ自動化MCPサーバーなどのツールによって返される詳細なアクセシビリティ ツリーとブラウザ スナップショット ペイロードをターゲットとしています。

### 何をするのか

1. **ノイズ除去**—空のgeneric/textエントリ (`- generic:`、 `- text: ""`) を削除します。
2. **兄弟崩壊**— ≥ `collapseThreshold` (デフォルト 30) 連続行が構造的繰り返しの場合、それらを最初の`collapseKeepHead` (デフォルト 10) 行に折りたたむ+カウントの概要+最後の`collapseKeepTail` (デフォルト 5) 行
3. **参照の保存**Playwright/computer-useが必要とする— `[ref=eXX]`アンカーは決して触れられません
4. **ハードトランケーション**— 、折りたたみ後のテキストがまだ`maxTextChars` (デフォルト 50,000) を超える場合、エージェントが作業を続行できるようにナビゲーション ヒントを付けて切り詰めます。

### エンジンの位置

```txt
open-sse/services/compression/engines/mcpAccessibility/
  index.ts            ← smartFilterText() entry point
  collapseRepeated.ts ← sibling-collapse algorithm
  constants.ts        ← DEFAULT_MCP_ACCESSIBILITY_CONFIG
```

### 構成

グローバル設定の`compression.mcpAccessibility`によって制御されます (移行 056)。デフォルト設定:

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

フィルターは、 `type`が`"text"`で、長さが`minLengthToProcess`を超えるツール結果ペイロードにのみ適用されます。プロンプト圧縮やリクエスト ペイロードには影響しません。

### 期待される節約額

ページの複雑さに応じて、ブラウザー スナップショット ツールの結果の 60 ～ 80%。折りたたみアルゴリズムの行数は O(n) で、追加されるレイテンシーは無視できるほどです。

### このフィルタと上記の圧縮エンジンの比較

| 側面         | 穴居人 / RTK / 積み上げ             | MCPアクセシビリティフィルター          |
| ------------ | ----------------------------------- | -------------------------------------- |
| ターゲット   | リクエストのプロンプト/コンテキスト | MCPツールの結果                        |
| トリガー     | 圧縮モードの設定                    | `compression.mcpAccessibility.enabled` |
| 範囲         | すべてのSSEメッセージ               | ツールの結果のみ                       |
| 参照アンカー | N/A                                 | 無条件に保存                           |

---

## 圧縮コンボ

圧縮コンボは、ルーティング コンボに割り当てることができる名前付き圧縮プロファイルです。

- `compression_combos`: モード、パイプライン、 RTK設定、言語設定、およびデフォルトのマーカーを保存します
- `compression_combo_assignments`: 圧縮コンボをルーティング コンボにマッピングします。
- ランタイム統合は、汎用コンボがオーバーライドされる前に、割り当てられた圧縮コンボを解決します。
- 分析には`compression_combo_id`と`engine`が含まれます

ダッシュボード表面: `Dashboard -> Context & Cache -> Compression Combos`。

## 前提条件 / オペレーターガイド (CCRおよび session-dedup)

CCR (`ccr`) および`session-dedup`テキストを置換または削除し、テキストを残します。**マーカー**後ろに。このセクションは、クライアントの接続、2 つのマーカーの読み取り、および省略されたコンテンツの取得または診断に関するオペレーターのリファレンスです。各エンジンの機構については上で説明しています。これは「実行方法」レイヤーです。

### トランスポートとエンドポイント

CCRツールを公開するMCPサーバーには 3 つの方法でアクセスできます。デフォルトのベースURLは`http://localhost:20128` (`OMNIROUTE_BASE_URL`) です。

| 輸送                                          | URL / コマンド                          | 注意事項                                                                                                                                                                  |
| --------------------------------------------- | --------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| ストリーミング可能なHTTP (クライアント、推奨) | `http://localhost:20128/api/mcp/stream` | 現在のMCPクライアントが通信するエンドポイント。                                                                                                                           |
| レガシーSSEシングルトン                       | `http://localhost:20128/api/mcp/sse`    | 古いシングルトントランスポート。それ**閉まる**ストリーミング可能なセッション。 `/api/mcp/stream`に対しては、これではなく`streamable-http`クライアントを使用してください。 |
| 標準デジタル                                  | `omniroute --mcp`                       | IDE MCPの場合、プロセスを生成する構成。 `--dev`フラグはありません。 `omniroute --mcp`は stdio エントリ ポイントです。                                                     |

### ストレージ層 (再起動後も存続するもの)

CCRは**二段**インメモリのみではなくストアします。

- **ホットインメモリ層**—ブロックごとのキャップ 2 MiB、プリンシパルごとに 16 MiB、グローバル 64 MiB。エントリのデフォルトは 24 時間のTTL (最大 7 日間) です。メモリからの完全なMCP取得は 256 KiBに制限されます。それより大きいものには、引き続き ranged/grep モードを通じてアクセスできます。
- **耐久性のあるSQLite層**(`ccr_blocks`、 `COMPRESSION_CCR_DURABLE_STORE`、デフォルトでは on) —メモリ内層をバックアップするため、ブロックはLRUエビクション、再起動、または別のインスタンスにランディングされた取得後にも存続します。行はブロックのTTL保持するため、そのTTL超えるブロックは両方の層から削除されます。

3 つのガードは、耐久性のある層の境界を維持します— 、次の場合にブロックがメモリ専用のままになります。

1. ブロックは終わりました**512 KB** (`MAX_DURABLE_BLOCK_BYTES`);
2. ランタイムはクラウド ランタイムです (ローカル ディスクはありません)。
3. `COMPRESSION_CCR_DURABLE_STORE=false`.

したがって、「ブロックが消えた」ということは包括的な再起動の話ではありません。ローカルの非クラウド ランタイム上のsub-512 KBブロックは、そのTTLがなくなるまで永続層を介して再起動しても存続します。変数については、 [「環境リファレンス」を](../reference/ENVIRONMENT.md)参照してください。

### 2つのマーカー

| マーカー                              | 意味                                                                                                                                           | モデルがやるべきこと                                                                                                                                                                                     |
| ------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| `[CCR retrieve hash=<24hex> chars=N]` | 大きなブロックがコンテンツアドレス指定されて保存されました。                                                                                   | `omniroute_ccr_retrieve`を呼び出します。** 24 進数のハッシュをそのままコピー**元のテキストを取得するには。                                                                                               |
| `[dedup:ref sha=…]`                   | `session-dedup` 、同じセッションの以前のターンですでに送信されたテキストを省略しました。これは**意図的な振り返り**損失やエラーではありません。 | する**ない**任意のツールを呼び出して実行します**ない**それを「再構築」してみてください。テキストの最初の出現は正規のコピーです。現在のターンは書き換えられることはなく、後のターンで重複が除去されます。 |

The `[dedup:ref]` look-back is a deliberate protocol decision — there is no pre-send reconstruction. Treat it as "this exact text was already on the wire earlier in this session."

### クライアントの前提条件

- **キー (stdio):** stdio 呼び出し元はリクエストごとの ID を持たないため、 `OMNIROUTE_API_KEY` ( MCPサーバーの`env`で設定) で認証します。これがないと呼び出し元は匿名になり、プリンシパルを必要とするツールの機能が低下する可能性があります。
- **`tools[]`は注入の前提条件です。** CCR検索プロトコル命令 (#8033) が挿入されます**のみ**リクエストのアドバタイズされた`tools[]`によって、クライアントが実際に`omniroute_ccr_retrieve`に到達できることが証明されたとき。一致は区切り文字 (`__`、 `.`、 `/`、 `:`) で区切られた末尾セグメントの一致です。 —裸の部分文字列—ではないため、 `mcp__gateway__omniroute_ccr_retrieve`などの名前空間付きの名前もカウントされます。 `tools[]`存在しない、または一致しない場合は、その命令が設計上「挿入されない」ことを意味します。
- **`codemode:false` (OpenCodeクライアント)。** OpenCodeデフォルトでコード モードになり、ネイティブ ツールのみをモデルにアドバタイズします。**しません**MCPツールをネイティブ`tools[]`リストに追加します。 `omniroute_ccr_*`ツールがアドバタイズされるように、 MCPサーバー エントリに`codemode: false`設定します。これは**クライアント**OmniRoute設定ではありません。 CCR命令はまだ挿入されていません。 OpenCodeツールに`<server>_<tool>`という名前を付けているため、 `omniroute`というサーバーは`omniroute_omniroute_ccr_retrieve`を公開しますが、 `_`一致する区切り文字の 1 つではありません。
- **校長先生。**保管と取得は、認証されたプリンシパルごと ( APIキーごと) に分離されます。キーはそれ自体のブロックのみを認識します。

### ツールごとのスコープ

スコープの強制は、スコープが狭いHTTP/SSE呼び出し元に対して常にオンになります。 `omniroute_` CCRツールには以下が必要です。

| 道具                     | 範囲                |
| ------------------------ | ------------------- |
| `omniroute_ccr_store`    | `write:compression` |
| `omniroute_ccr_delete`   | `write:compression` |
| `omniroute_ccr_retrieve` | `read:compression`  |
| `omniroute_ccr_inspect`  | `read:compression`  |
| `omniroute_ccr_list`     | `read:compression`  |
| `omniroute_ccr_stats`    | `read:compression`  |

スコープが見つからない場合は、**MCPツールのエラー結果**( HTTP 403 —ではなく`isError: true`、 `403 LOCAL_ONLY`は別個のループバック ルート ガード認証です): `Error: Insufficient MCP scopes for <tool>. Missing: <scope>.`最小限のリモート キーは、 `mcp:connect` ( `/api/mcp/`ローカルのみのカーブアウトを許可) に加えて、必要な特定のread/writeスコープを保持できます。

### クライアントマトリックス

| クライアント   | 輸送                               | 使用する構成                                                                                                                                                                                                                                 | `tools[]`が宣伝しましたか？ (→ CCR命令が挿入されました)                                                                                                                                     |
| -------------- | ---------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Claudeコード   | ストリーミング可能-http            | `claude mcp add --transport http omniroute http://localhost:20128/api/mcp/stream`                                                                                                                                                            | はい— MCP 対応。注射された。                                                                                                                                                                |
| Cursor / Cline | `stdio`**または**`streamable-http` | stdio: `omniroute --mcp`と`env`内の`OMNIROUTE_API_KEY` ;または、 `http://localhost:20128/api/mcp/stream`を指すリモートMCPエントリ ( [「セットアップ ガイド→ MCPクライアント設定](../guides/SETUP_GUIDE.md#mcp-client-configuration)」を参照) | はい、 — `omniroute_ccr_*`ツールを宣伝します。                                                                                                                                              |
| OpenCode       | ストリーミング可能-http            | `opencode mcp add omniroute --url http://localhost:20128/api/mcp/stream`、プラス`codemode: false`                                                                                                                                            | `codemode: false`でのみアドバタイズされるツール。 `omniroute_omniroute_ccr_retrieve`一致しないため、命令はまだ挿入されません ( [「クライアントの前提条件](#client-prerequisites)」を参照)。 |
| OpenAI対応     | OpenAI互換HTTP （チャット補完）    | OpenAI 互換エンドポイントに対する標準チャット補完クライアント                                                                                                                                                                                | **一度もない**—プレーンな OpenAI 互換呼び出し元には、ツールを呼び出すように指示されることはなく、命令は挿入されません。                                                                     |

### 取得制限とページネーション

MCPツールのテキスト結果は、 `mcpAccessibility.maxTextChars` (デフォルトでは`50000`) の周囲で切り取られます。ブロックの`full`取得は 256 KiB —に制限されます**無制限の完全取得はありません**。ブロックの`chars=N`が大きい場合は、全体をプルするのではなくページングします。

- 経験則:**`chars > 40000` → `mode`を使用する**、決してベアフルではありません。
- `mode:"grep"` — regex `pattern`は行ごとに一致し、最大 1,000 行まで一致します (`unique: true`繰り返しを削除します)。「必要な 1 行を見つける」のに最も安価です。
- `mode:"lines"` — 1 からなるインデックス付きの行範囲。 `start`と`end`両方が必要です。
- `mode:"head"` / `mode:"tail"` — first/last `n`行。
- `mode:"stats"` —本文を除いた行数、文字数、およびバイト数。

一度にすべてをリクエストするのではなく、 `mode:"lines"` `start`/`end`とともに使用して、ページ内の長いブロックを移動します。

### ツールの名前付け

現在、取得ツールの名前は`omniroute_ccr_retrieve`です ( `omniroute_`プレフィックスは、サーバー間の名前衝突に対する古い回避策です)。よりクリーンな境界サフィックス ツール名と、文字列の途中で切り詰められたMCP JSON結果の修正が上流のフォローアップとして追跡されます。このページには、出荷時の現在の動作のみが記載されています。

### セッションのライフサイクル

Streamable-HTTP セッションはアイドル状態になり、サーバーがそれを回収します。アイドル ウィンドウは`MCP_SESSION_IDLE_MS`定数です (ハードコードされた値ではなく、名前によって参照されるため、このページは変更されてもドリフトしません)。アイドルリープセッションの症状は、 `Unknown Mcp-Session-Id` —を伴うHTTP 404 です。解決策は、セッションを再接続するか再起動することです。**ない**キーを回転したり、スコープを変更したり、ツールの名前を変更したりできます。

## API表面

| ルート                                 | 目的                                                   |
| -------------------------------------- | ------------------------------------------------------ |
| `/api/settings/compression`            | グローバル圧縮設定 ( `mcpAccessibility` config を含む) |
| `/api/compression/preview`             | 圧縮モードをプレビューする                             |
| `/api/compression/language-packs`      | 利用可能な Caveman 言語パックのリストを表示する        |
| `/api/context/caveman/config`          | 穴居人の設定エイリアス                                 |
| `/api/context/rtk/config`              | RTKデフォルトと設定                                    |
| `/api/context/rtk/filters`             | RTKフィルターカタログ                                  |
| `/api/context/rtk/test`                | RTK preview/testエンドポイント                         |
| `/api/context/rtk/raw-output/[id]`     | 認証済みの編集済み生出力のリカバリ                     |
| `/api/context/combos`                  | 圧縮コンボCRUD                                         |
| `/api/context/combos/[id]/assignments` | ルーティングコンボ割り当てCRUD                         |
| `/api/context/analytics`               | 圧縮分析のエイリアス                                   |

管理ルートには、管理認証または API キー ポリシー チェックが必要です。

## MCPツール

圧縮により、次の 5 つのMCPツールが公開されます。

| 道具                                | 範囲                | 目的                                   |
| ----------------------------------- | ------------------- | -------------------------------------- |
| `omniroute_compression_status`      | `read:compression`  | 設定、分析、キャッシュ統計             |
| `omniroute_compression_configure`   | `write:compression` | グローバル設定を更新する               |
| `omniroute_set_compression_engine`  | `write:compression` | セットモードとオプションのパイプライン |
| `omniroute_list_compression_combos` | `read:compression`  | リスト圧縮コンボ                       |
| `omniroute_compression_combo_stats` | `read:compression`  | combo/engine分析を読む                 |

## 範囲と除外事項

**埋め込みは決して圧縮されません。** `open-sse/handlers/embeddings.ts`圧縮エンジン—を呼び出すことはなく、 request/responseボディはそのまま実行プログラムに直接渡されます。これは現在では構造的なものであり (埋め込みとチャット完了は独立したハンドラーです)、実行時チェックではありませんが、 #8034のベクトル歪みの問題が埋め込みパスに露出面がないことを意味します。

**Per-model/endpoint exclusion filter (#8034).** For chat completions, an operator can name model ids / `provider/model` targets that must never be compressed — a guardrail useful if compression is ever wired closer to an embeddings-adjacent path later, and generally useful for any model whose exact byte-for-byte prompt matters (deterministic evals, cache-sensitive prefixes, etc.).

- 設定フィールド: グローバル圧縮構成上の`exclusions?: string[]` (`GET`/`PUT /api/settings/compression`)、既存の`key_value`圧縮名前空間 (`src/lib/db/compression.ts`) —を介して永続化されます。新しいテーブルはありません。
- ダッシュボードタブ:**ダッシュボード→圧縮→の除外**(`/dashboard/compression/exclusions`)。
- パターン構文: `*`が唯一のワイルドカードです。パターン内の他のすべての正規表現メタ文字は一致する前にエスケープされるため、 `gpt-5.6`リテラル文字列のみに一致し、 `gpt-5x6`には一致しません (ReDoS セーフ、制限付き、ネストされた量指定子なし)。パターンは、ベア モデル ID と`provider/model`複合—両方に対して大文字と小文字を区別せずに一致します。 `gpt-5-6`、 `openai/gpt-5-6`、および`openai/*`すべて機能し、 `*`のみではすべてのモデルが除外されます。
- 一致: `open-sse/services/compression/exclusions.ts`の`isCompressionExcluded()` / `normalizeCompressionExclusions()` 。 `chatCore.ts`圧縮設定を解決した直後に除外されたターゲットをチェックします。**エンジンがかかる前に**、グローバルに無効になっている圧縮とまったく同じように一致を扱います。 — 、リクエスト本文はバイト同一であると考えられます。スキップは、分析の可視性のために`writeCompressionSkip(..., "excluded")`経由で記録されます。
- デフォルト (empty/absent list):#8034の動作と同じ—は何も除外されません。

## 既知の制限事項

- **LLMLingua-2 (SLM) には、同じ場所に配置されたオプションの deps が必要です。**ワーカーは、 `@atjsh/llmlingua-2` +ピアが`dist/node_modules`に同じ場所に配置されている場合にのみ実稼働ビルドで実行されます ( `scripts/build/colocateOptionals.mjs`、 #4286参照)。これらがないと、エンジンはフェールオープンします (元のテキストが返されます)。ワーカーの解決は`import.meta.url`に依存しなくなりました (スタンドアロン バンドルでは無効になります) —はランタイム cwd / `argv[1]`に固定されます。
- **Caveman 言語パック`de` / `fr` / `ja`は部分的です。** `context` + `filler` + `structural`ルールは同梱されていますが、 `dedup` / `ultra`パックは同梱されていないため、これらの言語では`ultra`強度は`full`よりも強力ではありません (独自のルール—のみを使用し、外国語テキストをマングルする英語の`dedup`/`ultra`ルールへのサイレント フォールバックはありません)。 `en` / `es` / `id` / `pt-BR`が完成しました。部分パックに対する`dedup.json` + `ultra.json`の貢献は歓迎されます。
- **スタックされたテレメトリには、圧縮したエンジンのみがリストされます。**エンジンは実行されたものの、節約率 0 % を生成したスタック パイプライン ステップは`stats:null`返すため、 `engineBreakdown` —には表示されず、スキップされたステップと区別できません。 「ran, 0 %」と「skipped」を区別するには、ブレークダウン モデルの変更が必要となるため、延期されます。

## 検証

このエリアで注目されているゲートは次のとおりです。

```bash
node --import tsx/esm --test tests/unit/compression/rtk-*.test.ts tests/unit/compression/pipeline-integration.test.ts tests/unit/compression/context-compression-api.test.ts
node --import tsx/esm --test tests/unit/compression/*.test.ts tests/golden-set/*.test.ts tests/integration/compression-pipeline.test.ts tests/unit/api/compression/compression-api.test.ts
node --import tsx/esm --test tests/unit/compression/mcpAccessibility*.test.ts
npm run typecheck:core
```
