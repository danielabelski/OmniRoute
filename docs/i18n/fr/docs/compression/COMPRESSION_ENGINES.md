# Compression Engines (Français)

🌐 **Languages:** 🇺🇸 [English](../../../../compression/COMPRESSION_ENGINES.md) · 🇪🇹 [am](../../../am/docs/compression/COMPRESSION_ENGINES.md) · 🇸🇦 [ar](../../../ar/docs/compression/COMPRESSION_ENGINES.md) · 🇦🇿 [az](../../../az/docs/compression/COMPRESSION_ENGINES.md) · 🇧🇬 [bg](../../../bg/docs/compression/COMPRESSION_ENGINES.md) · 🇧🇩 [bn](../../../bn/docs/compression/COMPRESSION_ENGINES.md) · 🇧🇦 [bs](../../../bs/docs/compression/COMPRESSION_ENGINES.md) · 🇨🇿 [cs](../../../cs/docs/compression/COMPRESSION_ENGINES.md) · 🇩🇰 [da](../../../da/docs/compression/COMPRESSION_ENGINES.md) · 🇩🇪 [de](../../../de/docs/compression/COMPRESSION_ENGINES.md) · 🇬🇷 [el](../../../el/docs/compression/COMPRESSION_ENGINES.md) · 🇪🇸 [es](../../../es/docs/compression/COMPRESSION_ENGINES.md) · 🇪🇪 [et](../../../et/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇷 [fa](../../../fa/docs/compression/COMPRESSION_ENGINES.md) · 🇫🇮 [fi](../../../fi/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇪 [ga](../../../ga/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [gu](../../../gu/docs/compression/COMPRESSION_ENGINES.md) · 🇳🇬 [ha](../../../ha/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇱 [he](../../../he/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [hi](../../../hi/docs/compression/COMPRESSION_ENGINES.md) · 🇭🇷 [hr](../../../hr/docs/compression/COMPRESSION_ENGINES.md) · 🇭🇺 [hu](../../../hu/docs/compression/COMPRESSION_ENGINES.md) · 🇦🇲 [hy](../../../hy/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇩 [id](../../../id/docs/compression/COMPRESSION_ENGINES.md) · 🇳🇬 [ig](../../../ig/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇹 [it](../../../it/docs/compression/COMPRESSION_ENGINES.md) · 🇯🇵 [ja](../../../ja/docs/compression/COMPRESSION_ENGINES.md) · 🇬🇪 [ka](../../../ka/docs/compression/COMPRESSION_ENGINES.md) · 🇰🇭 [km](../../../km/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [kn](../../../kn/docs/compression/COMPRESSION_ENGINES.md) · 🇰🇷 [ko](../../../ko/docs/compression/COMPRESSION_ENGINES.md) · 🇱🇹 [lt](../../../lt/docs/compression/COMPRESSION_ENGINES.md) · 🇱🇻 [lv](../../../lv/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [ml](../../../ml/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [mr](../../../mr/docs/compression/COMPRESSION_ENGINES.md) · 🇲🇾 [ms](../../../ms/docs/compression/COMPRESSION_ENGINES.md) · 🇲🇹 [mt](../../../mt/docs/compression/COMPRESSION_ENGINES.md) · 🇲🇲 [my](../../../my/docs/compression/COMPRESSION_ENGINES.md) · 🇳🇵 [ne](../../../ne/docs/compression/COMPRESSION_ENGINES.md) · 🇳🇱 [nl](../../../nl/docs/compression/COMPRESSION_ENGINES.md) · 🇳🇴 [no](../../../no/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [or](../../../or/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [pa](../../../pa/docs/compression/COMPRESSION_ENGINES.md) · 🇵🇭 [phi](../../../phi/docs/compression/COMPRESSION_ENGINES.md) · 🇵🇱 [pl](../../../pl/docs/compression/COMPRESSION_ENGINES.md) · 🇵🇹 [pt](../../../pt/docs/compression/COMPRESSION_ENGINES.md) · 🇧🇷 [pt-BR](../../../pt-BR/docs/compression/COMPRESSION_ENGINES.md) · 🇷🇴 [ro](../../../ro/docs/compression/COMPRESSION_ENGINES.md) · 🇷🇺 [ru](../../../ru/docs/compression/COMPRESSION_ENGINES.md) · 🇱🇰 [si](../../../si/docs/compression/COMPRESSION_ENGINES.md) · 🇸🇰 [sk](../../../sk/docs/compression/COMPRESSION_ENGINES.md) · 🇸🇮 [sl](../../../sl/docs/compression/COMPRESSION_ENGINES.md) · 🇷🇸 [sr](../../../sr/docs/compression/COMPRESSION_ENGINES.md) · 🇸🇪 [sv](../../../sv/docs/compression/COMPRESSION_ENGINES.md) · 🇰🇪 [sw](../../../sw/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [ta](../../../ta/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [te](../../../te/docs/compression/COMPRESSION_ENGINES.md) · 🇹🇭 [th](../../../th/docs/compression/COMPRESSION_ENGINES.md) · 🇹🇷 [tr](../../../tr/docs/compression/COMPRESSION_ENGINES.md) · 🇺🇦 [uk-UA](../../../uk-UA/docs/compression/COMPRESSION_ENGINES.md) · 🇵🇰 [ur](../../../ur/docs/compression/COMPRESSION_ENGINES.md) · 🇺🇿 [uz](../../../uz/docs/compression/COMPRESSION_ENGINES.md) · 🇻🇳 [vi](../../../vi/docs/compression/COMPRESSION_ENGINES.md) · 🇳🇬 [yo](../../../yo/docs/compression/COMPRESSION_ENGINES.md) · 🇨🇳 [zh-CN](../../../zh-CN/docs/compression/COMPRESSION_ENGINES.md) · 🇹🇼 [zh-TW](../../../zh-TW/docs/compression/COMPRESSION_ENGINES.md)

---

La compression OmniRoute est construite autour des contrats de moteur. Un mode peut exécuter un moteur directement (`caveman` ou `rtk`) ou un pipeline empilé déterministe qui exécute plusieurs moteurs dans l'ordre.

## Modes

| Mode         | Chemin du moteur                                                                          | Entrée prévue                                                       |
| ------------ | ----------------------------------------------------------------------------------------- | ------------------------------------------------------------------- |
| `off`        | aucun                                                                                     | Conservation précise et rapide                                      |
| `lite`       | Aides légères Caveman                                                                     | Nettoyage permanent à faible risque                                 |
| `standard`   | Homme des cavernes                                                                        | Condensation rapide en langage naturel                              |
| `aggressive` | Résumés Caveman + history/tool                                                            | Longues sessions de chat                                            |
| `ultra`      | Aides à l'élagage Caveman +                                                               | Récupération de limite de contexte                                  |
| `rtk`        | RTK                                                                                       | Sortie du terminal, du shell, de la construction, du test et de git |
| `omniglyph`  | OmniGlyph                                                                                 | Contexte en tant qu'image sur le fil du fournisseur natif           |
| `stacked`    | Pipeline. La requête par défaut est `session-dedup -> lite`. `rtk -> caveman` est opt-in. | Journaux d'outils mixtes et prose, économies maximales              |

### profils de compression OmniGlyph

Le moteur `omniglyph` (package `omniglyph`, 1.4.0 +) accepte un profil sémantique nommé, défini globalement via `omniglyph.profile` dans les paramètres de compression ou par étape via la configuration d'étape du pipeline empilé :

| Profil        | Limite                                                                                                              |
| ------------- | ------------------------------------------------------------------------------------------------------------------- |
| `aggressive`  | Défaut. La politique des reçus publiés a mesuré le système d'images —, les documents d'outils et l'historique dense |
| `balanced`    | Conserve l'état actif natif, protège les 8 derniers tours, réduit l'ancien historique fermé                         |
| `coding-safe` | Conserve l'autorité, les schémas d'outils et la sortie des outils en direct en natif, protège les 12 derniers tours |
| `passthrough` | Itinéraires sans transformation ; le moteur est sauté                                                               |

Le profil est un** plafond, pas un sol** : `mergeCompressionProfileOptions` dans le package refuse de laisser un appelant annuler la réouverture d'une voie avec perte que le profil a fermée, donc un `preserveSystemPrompt: false` par étape ne peut pas réactiver la compression du système sous `coding-safe`.

Mesuré sur cette base de code : `coding-safe` et `balanced` élèvent `minCompressChars` à son maximum et gardent le système, les schémas d'outils et les résultats des outils natifs, donc une session qui n'a pas encore accumulé d'historique s'arrête à `below_min_chars` et le moteur ne transforme rien. C'est pourquoi la valeur par défaut est `aggressive` plutôt que le profil le plus sûr.

Le package résout sa propre portée et son propre profil de modèle à partir de sa configuration d'environnement. OmniRoute ne délègue jamais la décision : l'adaptateur épingle la porte du modèle à la portée la plus restrictive du package, de sorte que les paramètres de l'environnement hôte ne peuvent que restreindre la liste autorisée, sans jamais l'élargir au-delà des réceptions mesurées par OmniRoute.

## Registre des moteurs

Le registre vit à `open-sse/services/compression/engines/registry.ts`. Les moteurs exposent un contrat partagé :

- `id`: identifiant de moteur stable tel que `caveman` ou `rtk`
- `apply(text, config)`: chemin d'exécution existant utilisé par les pipelines empilés
- `compress(input, config)`: chemin d'exécution principal renvoyant le texte statistiques +
- `getConfigSchema()`: renvoie la forme de type JSON-Schema d'une configuration valide
- `validateConfig(config)`: renvoie `{ valid, errors[] }`

L'inscription utilise `registerCompressionEngine(engine)` (ou `registerEngine` pour les cas avancés), qui appelle `assertValidEngine()` et `validateConfig(defaultConfig)` avant d'accepter. Utilisez `unregisterCompressionEngine(id)` pour supprimer un moteur au moment de l'exécution.

`strategySelector.ts` enregistre les moteurs intégrés avant l'exécution de la compression. Cela permet à l'aperçu, à la compression d'exécution, au mode empilé, aux tests et aux futurs moteurs d'utiliser le même chemin d'exécution.

### compression de description MCP (liée)

Un registre distinct compresse les métadonnées de description de l'outil MCP au niveau du registre — voir `open-sse/mcp-server/descriptionCompressor.ts` et [MCP-SERVER.md](../frameworks/MCP-SERVER.md). Il réutilise les règles Caveman mais fonctionne sur les métadonnées des outils, et non sur les charges utiles demandées.

### Moteurs intégrés supplémentaires

Au-delà de Caveman, RTK et LLMLingua-2, le registre contient plusieurs moteurs spécialisés sans perte/structurels (utilisés par les pipelines empilés, le terrain de jeu et les tests) :

| Moteur                | Identifiant     | Ce que ça fait                                                                                                                                                                                              |
| --------------------- | --------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| CCR                   | `ccr`           | Content-Compress-Retrieve (H4) : remplace les gros blocs de texte contigus par des références adressées au contenu, de sorte que les blocs repeated/large sont envoyés une fois et référencés par la suite. |
| hauteur sous plafond  | `headroom`      | SmartCrusher (H3 + N5) : compactage tabulaire sans perte de charges utiles homogènes de tableau JSON sous une forme `[N rows]` en colonnes.                                                                 |
| ioniseur              | `ionizer`       | échantillonnage de lignes Head/middle/tail pour de très grands blocs homogènes, stockant le milieu élidé comme référence adressée au contenu CCR.                                                           |
| session-dédoublonnage | `session-dedup` | Déduplication multi-tours adressée au contenu (inspirée de TokenMizer) : élimine le texte déjà vu dans les tours précédents de la même session.                                                             |

**Instruction de protocole de récupération CCR (#8033) :** la première fois CCR remplace le bloc ≥ 1 dans une requête, le moteur ajoute un seul message `system` idempotent (menant avec la sentinelle `[CCR protocol]` ) enseignant à l'appelant le contrat de l'outil → du marqueur : ce que signifie un marqueur `[CCR retrieve hash=<24hex> chars=N]`, que le hachage doit être copié textuellement (les 24 caractères hexadécimaux des hachages mal copiés — sont la cause probable des manques de "bloc non trouvé"), et qu'un Le marqueur `[dedup:ref sha=...]` signifie « regarder en arrière dans l'histoire », et non « appeler l'outil ». La note est injectée** seulement lorsque le `tools[]` annoncé par l'appelant prouve qu'il peut réellement atteindre `omniroute_ccr_retrieve`** (`callerSupportsCcrRetrieve()` dans `open-sse/services/compression/engines/ccr/protocolInstruction.ts`) — un appelant simple compatible OpenAI sans cet outil ne reçoit jamais d'instruction pour appeler quelque chose qu'il ne peut pas atteindre. L'idempotence est renforcée en analysant l'historique des messages à la recherche de la sentinelle avant l'injection, de sorte que les requêtes multi-tours (qui rejouent les messages précédents) n'empilent pas la note une fois par tour.

## Homme des cavernes

Le mode Caveman se concentre sur la condensation sémantique de la prose normale :

- préserve les blocs de code, URLs, JSON, les chemins et les données structurées
- supprime le remplissage, la couverture, le contexte répété et le phrasé conjonctif verbeux
- prend en charge les packs de règles de fichiers prenant en charge le langage dans `open-sse/services/compression/rules/`
- reste disponible via les anciens modes `standard`, `aggressive` et `ultra`

La surface du tableau de bord est `Dashboard -> Context & Cache -> Caveman`.

Caveman en amont rapporte moins de jetons de sortie `~75%`, des économies de sortie moyennes `65%` dans les benchmarks avec une plage `22-87%` et un outil de compression d'entrée `~46%`. OmniRoute utilise le numéro côté entrée Caveman lors de la documentation des économies prompt/context empilées ; Le mode de sortie Caveman reste une fonctionnalité de comportement de réponse distincte.

## RTK

Le mode RTK se concentre sur la sortie des commandes et des outils :

- détecte les classes de sortie telles que `git status`, `git branch`, `git diff`, Vitest/Jest/Pytest, les tests Cargo/Go, les builds TypeScript/Vite/Webpack, ESLint, npm audit/installs, les journaux Docker, le shell `find`/`grep`, les traces de pile et les journaux génériques
- applique 49 filtres JSON de `open-sse/services/compression/engines/rtk/filters/`
- prend en charge le pipeline déclaratif de style RTK : suppression ANSI, remplacement, court-circuit de sortie de correspondance, lignes strip/keep, troncature par ligne, troncature head/tail/max-line et repli à vide
- prend en charge les filtres de projet sécurisés dans `.rtk/filters.json` et les filtres globaux dans `DATA_DIR/rtk/filters.json`
- supprime les séquences ANSI, le bruit de progression, les lignes répétées et le passe-partout inutile
- préserve les échecs exploitables, les avertissements, les résumés, les fichiers modifiés et le contexte de fin
- peut éventuellement conserver la sortie brute expurgée pour recovery/debugging via des routes de gestion authentifiées

La surface du tableau de bord est `Dashboard -> Context & Cache -> RTK`.

Les détails opérationnels pour les filtres personnalisés, la confiance, la vérification et la récupération des sorties brutes sont disponibles dans [`RTK_COMPRESSION.md`](./RTK_COMPRESSION.md).

RTK en amont rapporte les économies `60-90%` pour la compression de sortie de commande. Son exemple README montre une session de code Claude de 30 minutes allant des jetons `~118,000` à `~23,900`, ou `79.7%` enregistré.

## LLMLingua-2 (élagage sémantique)

le mode LLMLingua-2 effectue** élagage des jetons sémantiques** en prose à l'aide d'un petit classificateur de jetons ONNX, complétant les moteurs Caveman et RTK basés sur des règles :

- compresse la prose dans les messages non système uniquement ; les blocs de code clôturés et autres constructions préservées ne sont jamais modifiés
- exécute le backend `@atjsh/llmlingua-2` (ONNX via `@huggingface/transformers`) dans un thread de travail, donc l'inférence de modèle ne bloque jamais la boucle d'événement de demande
- est** empilable** (`stackPriority` 35) : dans un pipeline empilé, il s'exécute après les moteurs structurels (CCR, session-dedup, headroom, Caveman) mais avant `ultra`, puisque l'élagage sémantique est plus efficace sur du texte déjà structurellement compressé — par exemple `rtk -> caveman -> llmlingua`
- **échec d'ouverture en cas d'erreur** (déps facultatifs manquants, apparition du travailleur, chargement du modèle, inférence ou délai d'attente) → le texte original est renvoyé inchangé, jamais d'erreur

Emplacement du moteur : `open-sse/services/compression/engines/llmlingua/`. La surface du tableau de bord est `Dashboard -> Context & Cache -> LLMLingua`.

### Modèles

Le modèle par défaut est**TinyBERT** (`atjsh/llmlingua-2-js-tinybert-meetingbank`, ~ 57 MB, rapide). Une plus grande précision** Base BERT** Le modèle (`Arcoldd/llmlingua4j-bert-base-onnx`, ~ 710 MB) est disponible via le champ `model` de configuration du moteur. `@huggingface/transformers` télécharge paresseusement le modèle sélectionné depuis le hub HuggingFace vers `${DATA_DIR}/models/llmlingua` lors du premier appel (`modelStore.ts`); un remplacement de configuration `modelPath` le pointe vers une copie locale à la place (installations hors ligne / avec espace vide).

### Dépendances facultatives et installation à la demande

La pile homologue d'exécution LLMLingua élagable est** facultatif** . Deux packages sont déclarés comme `optionalDependencies` dans `package.json` et conservés** externe** par la version de production (`scripts/build/prepublish.ts` ne les regroupe pas) :

| Emballer             | Version (broche) | Remarques                                         |
| -------------------- | ---------------- | ------------------------------------------------- |
| `@atjsh/llmlingua-2` | `2.0.5`          | Forfait d’entrée ; déclare les autres comme pairs |
| `js-tiktoken`        | `^1.0.20`        | Tokeniseur                                        |

`@huggingface/transformers` est épinglé sur `^4.2.0` (partagé avec le chemin d'intégration local et également tracé dans le bundle autonome) ; `@atjsh/llmlingua-2@2.0.5` s'y compare avec `"^3.5.2 || ^4.0.0"`, donc Transformers.js v3 et v4 sont pris en charge. Depuis la version 2.0.4, `@atjsh/llmlingua-2` ne nécessite plus `@tensorflow/tfjs`, ce qui a supprimé le plus grand contributeur (TensorFlow.js) de la pile SLM. Seuls les deux packages ci-dessus sont des pairs SLM élagables. Un `npm install` (dev) standard installe automatiquement la pile facultative à moins que les dépendances facultatives ne soient omises.

**Pourquoi à la demande :** le package publié par npm, le bundle autonome et l'image Docker livrée** sans** ces dépressions pour rester mince. Lorsqu'ils sont absents, la porte de dépendance du travailleur (une sonde de résolution `@atjsh/llmlingua-2` dans `worker.ts`) échoue et le moteur** échec s'ouvre silencieusement** — la sélection de LLMLingua devient un non-op (texte renvoyé inchangé, aucune erreur enregistrée). Pour l'activer dans un environnement élagué, installez la pile facultative :

```bash
# pin to the versions declared in package.json optionalDependencies
npm install @atjsh/llmlingua-2@2.0.5 js-tiktoken
```

La suppression `@tensorflow/tfjs` (2.0.4 +) élimine le contributeur ~ 800 MB précédemment dominant — l'empreinte restante est les environnements d'exécution transformers.js + onnxruntime-node, plus le modèle TinyBERT (~ 57 MB) téléchargé lors de la première utilisation (pas via npm).

Par environnement :

- **Dév/ `npm install`** — est installé automatiquement sauf si vous avez passé `--omit=optional` (ou `--no-optional`). Aucune action nécessaire.
- **NPM global (`npm i -g omniroute`) / autonome** — exécutez la commande d'installation ci-dessus dans le répertoire du package installé ou réinstallez sans omettre les dépôts facultatifs.
- **Docker** — ajoute la commande install dans une couche d'image dérivée ; l'image publiée est mince de par sa conception.
- **VPS (PM2)** — installez-le dans le `node_modules` de l'application, puis redémarrez le processus pour que le travailleur sonde à nouveau la porte.
- **Raw Next autonome (`npm run build` → `.build/next/standalone/server.js`)** — la trace autonome expédie NEITHER le travailleur ni les dépôts facultatifs, de sorte que le moteur s'ouvre silencieusement en cas d'échec. `scripts/build/colocate-standalone.mjs` réapplique les deux (le travailleur esconstruit la fermeture facultative-dep + dans l'arborescence autonome) ; il s'exécute automatiquement via le hook `postbuild` npm après chaque build. Idempotent, infaillible lorsque les députés sont absents.

**Vérifiez qu'il est actif :** avec LLMLingua sélectionné, la prose réelle rétrécit (le moteur arrête l'ouverture en cas d'échec) et la première requête déclenche le téléchargement du modèle dans `${DATA_DIR}/models/llmlingua`. La porte sonde intentionnellement uniquement `@atjsh/llmlingua-2` — les autres pairs sont uniquement ESM et `require.resolve` leur lance même lorsqu'il est présent —, de sorte que le travailleur échoue toujours si un homologue est véritablement manquant au moment `import()`.

## Pipelines empilés

Le mode empilé exécute les étapes du pipeline dans l'ordre. La valeur par défaut est :

```txt
rtk -> caveman
```

Utilisez-le pour les sessions d'agent de codage où une invite combine le résultat d'une commande avec une prose humaine ou assistante. RTK réduit d'abord les journaux d'outils bruyants, puis Caveman compresse le langage naturel restant.

Les étapes du pipeline sont configurées avec `stackedPipeline` dans les paramètres de compression ou via des combinaisons de compression.

Lorsque les deux moteurs réduisent la même charge utile éligible, les économies s’accumulent :

```txt
combined = 1 - (1 - RTK savings) * (1 - Caveman input savings)
average  = 1 - (1 - 0.80) * (1 - 0.46) = 89.2%
range    = 1 - (1 - 0.60..0.90) * (1 - 0.46) = 78.4-94.6%
```

## Filtre d'arborescence d'accessibilité MCP

Le filtre intelligent MCP Accessibility-Tree est une couche de compression post-exécution qui s'exécute sur MCP** résultats de l'outil** , pas sur les invites ou le contexte. Il cible les charges utiles détaillées de l'arborescence d'accessibilité et des instantanés de navigateur renvoyées par des outils tels que Playwright, les serveurs MCP d'utilisation informatique et d'automatisation du navigateur.

### Ce que ça fait

1. **Suppression du bruit** — supprime les entrées generic/text vides (`- generic:`, `- text: ""`)
2. **Effondrement d'un frère ou d'une sœur** — lorsque les lignes consécutives ≥ `collapseThreshold` (30 par défaut) sont des répétitions structurelles, les réduit dans les premières lignes `collapseKeepHead` (10 par défaut) + un résumé du décompte + les dernières lignes `collapseKeepTail` (5 par défaut)
3. **Conservation de la référence** les ancres — `[ref=eXX]` requises par Playwright/computer-use ne sont jamais touchées
4. **Troncature dure** — si le texte après la réduction dépasse toujours `maxTextChars` (par défaut 50 000), il est tronqué avec une indication de navigation afin que l'agent puisse continuer à travailler

### Emplacement du moteur

```txt
open-sse/services/compression/engines/mcpAccessibility/
  index.ts            ← smartFilterText() entry point
  collapseRepeated.ts ← sibling-collapse algorithm
  constants.ts        ← DEFAULT_MCP_ACCESSIBILITY_CONFIG
```

### Configuration

Contrôlé par `compression.mcpAccessibility` dans les paramètres globaux (migration 056). Configuration par défaut :

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

Le filtre s'applique uniquement aux charges utiles de résultat d'outil dont `type` est `"text"` et dont la longueur dépasse `minLengthToProcess`. Cela n’affecte pas la compression rapide ni les charges utiles des requêtes.

### Économies attendues

60 à 80 % sur les résultats de l'outil d'instantané du navigateur, en fonction de la complexité de la page. L'algorithme d'effondrement est O(n) en nombre de lignes et ajoute une latence négligeable.

### Ce filtre par rapport aux moteurs de compression ci-dessus

| Aspect              | Homme des cavernes / RTK / Empilé | filtre d'accessibilité MCP             |
| ------------------- | --------------------------------- | -------------------------------------- |
| Cible               | Demander des invites/contexte     | résultats de l'outil MCP               |
| Déclenchement       | Réglage du mode de compression    | `compression.mcpAccessibility.enabled` |
| Portée              | Tous les messages SSE             | Résultats de l'outil uniquement        |
| Ancres de référence | N/A                               | Conservé sans condition                |

---

## Combinaisons de compression

Les combos de compression sont appelés profils de compression qui peuvent être attribués aux combos de routage :

- `compression_combos`: mode de stockage, pipeline, configuration RTK, configuration de langue et marqueur par défaut
- `compression_combo_assignments`: mappe un combo de compression à un combo de routage
- l'intégration à l'exécution résout une combinaison de compression attribuée avant les remplacements de combinaison générique
- les analyses incluent `compression_combo_id` et `engine`

Surface du tableau de bord : `Dashboard -> Context & Cache -> Compression Combos`.

## Prérequis / guide de l'opérateur (CCR & session-dedup)

CCR (`ccr`) et `session-dedup` remplacent ou suppriment le texte et laissent un** marqueur** derrière. Cette section est la référence de l'opérateur pour câbler un client, lire les deux marqueurs et récupérer ou diagnostiquer le contenu élidé. La mécanique de chaque moteur est couverte ci-dessus ; c'est la couche "comment puis-je l'exécuter".

### Transports et points de terminaison

Le serveur MCP qui expose les outils CCR peut être atteint de trois manières. La base par défaut URL est `http://localhost:20128` (`OMNIROUTE_BASE_URL`) :

| Transport                            | URL / commande                          | Remarques                                                                                                                                        |
| ------------------------------------ | --------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------ |
| HTTP diffusable (client, recommandé) | `http://localhost:20128/api/mcp/stream` | Le point de terminaison auquel les clients MCP actuels parlent.                                                                                  |
| Héritage de SSE Singleton            | `http://localhost:20128/api/mcp/sse`    | Transport simple plus ancien. Il** ferme** sessions diffusables ; utilisez les clients `streamable-http` contre `/api/mcp/stream`, pas celui-ci. |
| stdio                                | `omniroute --mcp`                       | Pour la configuration IDE MCP qui génère le processus. Il n'y a pas d'indicateur `--dev` ; `omniroute --mcp` est le point d'entrée stdio.        |

### Niveaux de stockage (ce qui survit à un redémarrage)

CCR est un** à deux niveaux** stocker, pas en mémoire uniquement :

- **Niveau de mémoire chaud** — par bloc cap 2 MiB, par principal 16 MiB, global 64 MiB. Les entrées par défaut sont de 24 TTL (maximum 7 jours). La récupération complète MCP depuis la mémoire est limitée à 256 KiB; tout ce qui est plus grand est toujours accessible via les modes ranged/grep.
- **Niveau SQLite durable** (`ccr_blocks`, `COMPRESSION_CCR_DURABLE_STORE`, activé par défaut) — sauvegarde le niveau en mémoire afin qu'un bloc survive à l'expulsion LRU, à un redémarrage ou à un atterrissage de récupération sur une autre instance. La ligne conserve le TTL du bloc, donc un bloc au-delà de son TTL disparaît des deux niveaux.

Trois gardes maintiennent le niveau durable délimité — un bloc reste en mémoire uniquement lorsque :

1. le bloc est terminé** 512 KB** (`MAX_DURABLE_BLOCK_BYTES`);
2. le runtime est un runtime cloud (pas de disque local) ;
3. `COMPRESSION_CCR_DURABLE_STORE=false`.

Ainsi, « le bloc a disparu » n'est pas une histoire de redémarrage général : un bloc sub-512 KB sur un environnement d'exécution local non cloud survit à un redémarrage via le niveau durable jusqu'à ce que son TTL soit épuisé. Voir [Référence d'environnement](../reference/ENVIRONMENT.md) pour la variable.

### Les deux marqueurs

| Marqueur                              | Signification                                                                                                                                                        | Ce que le modèle doit faire                                                                                                                                                                                                        |
| ------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| `[CCR retrieve hash=<24hex> chars=N]` | Un gros bloc a été stocké avec un contenu adressé.                                                                                                                   | Appelez `omniroute_ccr_retrieve` avec le** Hachage de 24 hexadécimaux copié textuellement** pour récupérer le texte original.                                                                                                      |
| `[dedup:ref sha=…]`                   | `session-dedup` a élidé le texte déjà envoyé lors d'un tour précédent de la même session. C'est un** retour en arrière intentionnel** , pas une perte ou une erreur. | Faire** pas** appelle n'importe quel outil et fais** pas** essayez de le "reconstruire". La première occurrence du texte est la copie canonique ; le tour en cours n'est jamais réécrit, il est dédoublé lors d'un tour ultérieur. |

Le retour en arrière `[dedup:ref]` est une décision délibérée du protocole — il n'y a pas de reconstruction avant l'envoi. Traitez-le comme « ce texte exact était déjà diffusé plus tôt au cours de cette session ».

### Pré-requis clients

- **Clé (stdio) :** un appelant stdio ne porte aucune identité par requête, il s'authentifie donc avec `OMNIROUTE_API_KEY` (défini dans le `env` du serveur MCP ). Sans cela, l'appelant est anonyme et les outils qui nécessitent un principal peuvent se dégrader.
- **`tools[]` est la condition préalable à l'injection.** L'instruction de protocole de récupération CCR (#8033) est injectée** seulement** lorsque le `tools[]` annoncé dans la requête prouve que le client peut réellement atteindre `omniroute_ccr_retrieve`. La correspondance est une correspondance de segment final délimitée par un séparateur (`__`, `.`, `/`, `:`) — jamais une sous-chaîne nue — donc un nom avec espace de noms tel que `mcp__gateway__omniroute_ccr_retrieve` compte toujours. Un `tools[]` absent ou ne correspondant pas signifie que l'instruction n'est _pas_ injectée, de par sa conception.
- **`codemode:false` (clients OpenCode ).** OpenCode est par défaut en mode Code, qui annonce uniquement ses outils natifs au modèle et** ne fait pas** placez les outils MCP sur la liste `tools[]` native. Définissez `codemode: false` sur l'entrée du serveur MCP afin que les outils `omniroute_ccr_*` soient annoncés. C'est un** client** réglage, pas un OmniRoute. L'instruction CCR n'est pas encore injectée : OpenCode nomme un outil `<server>_<tool>`, donc un serveur appelé `omniroute` expose `omniroute_omniroute_ccr_retrieve`, et `_` n'est pas l'un des séparateurs correspondants.
- **Principes.** Le stockage et la récupération sont isolés par principal authentifié (par clé API ). Une clé ne voit que ses propres blocs.

### Portées par outil

L’application de la portée est toujours activée pour les appelants HTTP/SSE à portée limitée. Les outils `omniroute_` CCR nécessitent :

| Outil                    | Portée              |
| ------------------------ | ------------------- |
| `omniroute_ccr_store`    | `write:compression` |
| `omniroute_ccr_delete`   | `write:compression` |
| `omniroute_ccr_retrieve` | `read:compression`  |
| `omniroute_ccr_inspect`  | `read:compression`  |
| `omniroute_ccr_list`     | `read:compression`  |
| `omniroute_ccr_stats`    | `read:compression`  |

Une portée manquante renvoie un** résultat d'erreur de l'outil MCP** (`isError: true`, pas un HTTP 403 — le `403 LOCAL_ONLY` est l'authentification de garde de route de bouclage séparée) : `Error: Insufficient MCP scopes for <tool>. Missing: <scope>.` Une clé distante minimale peut contenir `mcp:connect` (autorise la suppression `/api/mcp/` uniquement en local) ainsi que la portée read/write spécifique dont elle a besoin.

### Matrice client

| Client            | Transport                                    | Configuration à utiliser                                                                                                                                                                                                                                        | `tools[]` annoncé ? (instruction → CCR injectée)                                                                                                                                                          |
| ----------------- | -------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Code Claude       | streamable-http                              | `claude mcp add --transport http omniroute http://localhost:20128/api/mcp/stream`                                                                                                                                                                               | Oui — compatible MCP ; injecté.                                                                                                                                                                           |
| Cursor / Cline    | `stdio`** ou** `streamable-http`             | stdio : `omniroute --mcp` avec `OMNIROUTE_API_KEY` dans `env`; ou une entrée MCP distante pointant vers `http://localhost:20128/api/mcp/stream` (voir [le Guide d'installation → MCP Client Configuration](../guides/SETUP_GUIDE.md#mcp-client-configuration) ) | Oui, — fait la publicité des outils `omniroute_ccr_*`.                                                                                                                                                    |
| OpenCode          | streamable-http                              | `opencode mcp add omniroute --url http://localhost:20128/api/mcp/stream`, plus `codemode: false`                                                                                                                                                                | Outils annoncés uniquement avec `codemode: false`; l'instruction n'est toujours pas injectée, car `omniroute_omniroute_ccr_retrieve` ne correspond pas (voir [Prérequis client](#client-prerequisites) ). |
| Compatible OpenAI | HTTP compatible OpenAI (achèvements de chat) | client de complétion de chat standard par rapport au point de terminaison compatible OpenAI                                                                                                                                                                     | **Jamais** — un appelant simple compatible OpenAI n'est jamais invité à appeler l'outil et l'instruction n'est pas injectée.                                                                              |

### Limites de récupération et pagination

Les résultats du texte de l'outil MCP sont découpés autour de `mcpAccessibility.maxTextChars` ( `50000` par défaut). Une récupération `full` d'un bloc est plafonnée à 256 KiB —** il n'y a pas de récupération complète illimitée** . Lorsque `chars=N` d'un bloc est grand, pagez-le au lieu de tout extraire :

- Règle générale :**`chars > 40000` → utiliser un `mode`** , jamais plein.
- `mode:"grep"` — regex `pattern` correspond ligne par ligne, jusqu'à 1 000 lignes correspondantes (`unique: true` supprime les répétitions), le moins cher pour "trouver la ligne dont j'ai besoin".
- `mode:"lines"` — une plage de lignes indexées à 1 ; a besoin à la fois `start` et `end`.
- Lignes `mode:"head"` / `mode:"tail"` — first/last `n`.
- `mode:"stats"` — compte les lignes, les caractères et les octets sans le corps.

Utilisez `mode:"lines"` avec `start`/`end` pour parcourir un long bloc de pages plutôt que de demander le tout en même temps.

### Dénomination des outils

L'outil de récupération s'appelle actuellement `omniroute_ccr_retrieve` (le préfixe `omniroute_` est une solution de contournement obsolète pour les collisions de noms entre serveurs). Un nom d'outil de suffixe délimité plus propre et un correctif pour les résultats MCP JSON tronqués au milieu de la chaîne sont suivis en tant que suivis en amont ; cette page documente uniquement le comportement actuel expédié.

### Cycle de vie des sessions

Les sessions HTTP diffusables s'arrêtent et le serveur les récupère ; la fenêtre inactive est la constante `MCP_SESSION_IDLE_MS` (référencée par son nom, pas par une valeur codée en dur, donc cette page ne dérive pas lorsqu'elle change). Le symptôme d'une session inactive est un HTTP 404 avec `Unknown Mcp-Session-Id` — le remède est de se reconnecter ou de redémarrer la session,** pas** pour faire pivoter une clé, modifier une portée ou renommer un outil.

## Surface API

| Itinéraire                             | But                                                                             |
| -------------------------------------- | ------------------------------------------------------------------------------- |
| `/api/settings/compression`            | Paramètres de compression globaux (inclut la configuration `mcpAccessibility` ) |
| `/api/compression/preview`             | Prévisualisez n’importe quel mode de compression                                |
| `/api/compression/language-packs`      | Liste des packs linguistiques Caveman disponibles                               |
| `/api/context/caveman/config`          | Alias des paramètres de Caveman                                                 |
| `/api/context/rtk/config`              | valeurs par défaut et paramètres RTK                                            |
| `/api/context/rtk/filters`             | catalogue de filtres RTK                                                        |
| `/api/context/rtk/test`                | point de terminaison RTK preview/test                                           |
| `/api/context/rtk/raw-output/[id]`     | Récupération de sortie brute authentifiée et expurgée                           |
| `/api/context/combos`                  | Combinaison de compression CRUD                                                 |
| `/api/context/combos/[id]/assignments` | Affectation de combo de routage CRUD                                            |
| `/api/context/analytics`               | Alias d'analyse de compression                                                  |

Les routes de gestion nécessitent une authentification de gestion ou des vérifications de stratégie de clé API.

## Outils MCP

La compression expose cinq outils MCP :

| Outil                               | Portée              | But                                         |
| ----------------------------------- | ------------------- | ------------------------------------------- |
| `omniroute_compression_status`      | `read:compression`  | Paramètres, analyses, statistiques de cache |
| `omniroute_compression_configure`   | `write:compression` | Mettre à jour les paramètres globaux        |
| `omniroute_set_compression_engine`  | `write:compression` | Mode défini et pipeline en option           |
| `omniroute_list_compression_combos` | `read:compression`  | Liste des combinaisons de compression       |
| `omniroute_compression_combo_stats` | `read:compression`  | Lire les analyses combo/engine              |

## Portée et exclusions

**Les intégrations ne sont jamais compressées.** `open-sse/handlers/embeddings.ts` n'appelle jamais aucun moteur de compression — les corps request/response passent directement à l'exécuteur testamentaire intacts. Ceci est structurel aujourd'hui (les intégrations et les complétions de chat sont des gestionnaires disjoints), pas une vérification d'exécution, mais cela signifie que le problème de distorsion vectorielle dans #8034 n'a pas de surface d'exposition dans le chemin des intégrations.

**filtre d'exclusion Per-model/endpoint (#8034).** Pour les terminaisons de chat, un opérateur peut nommer les identifiants de modèle / cibles `provider/model` qui ne doivent jamais être compressés — un garde-fou utile si la compression est un jour câblée plus près d'un chemin adjacent aux intégrations plus tard, et généralement utile pour tout modèle dont l'invite exacte octet par octet est importante (évaluations déterministes, préfixes sensibles au cache, etc.).

- Champ Paramètres : `exclusions?: string[]` sur la configuration de compression globale (`GET`/`PUT /api/settings/compression`), conservé via l'espace de noms de compression `key_value` existant (`src/lib/db/compression.ts`) — pas de nouvelle table.
- Onglet Tableau de bord :** Tableau de bord → Compression → Exclusions** (`/dashboard/compression/exclusions`).
- Syntaxe du modèle : `*` est le seul caractère générique. Tous les autres métacaractères regex d'un modèle sont échappés avant la correspondance, donc `gpt-5.6` correspond uniquement à la chaîne littérale, jamais `gpt-5x6` (sûr pour ReDoS, délimité, sans quantificateurs imbriqués). Les modèles correspondent sans tenir compte de la casse à la fois par rapport à l'identifiant du modèle nu et au composite `provider/model` — `gpt-5-6`, `openai/gpt-5-6` et `openai/*` tous fonctionnent, et `*` seul exclut tous les modèles.
- Correspondance : `isCompressionExcluded()` / `normalizeCompressionExclusions()` dans `open-sse/services/compression/exclusions.ts`. `chatCore.ts` vérifie la cible exclue juste après avoir résolu les paramètres de compression,** avant que le moteur ne tourne** , et traite une correspondance exactement comme si la compression était globalement désactivée — le corps de la requête est manifestement identique en octets. Le saut est enregistré via `writeCompressionSkip(..., "excluded")` pour la visibilité analytique.
- Par défaut (empty/absent list) : identique au comportement pré-#8034 — rien n'est exclu.

## Limites connues

- **LLMLingua-2 (SLM) nécessite des dépôts facultatifs colocalisés.** Le travailleur ne s'exécute que dans une version de production lorsque les pairs `@atjsh/llmlingua-2` + sont colocalisés dans `dist/node_modules` (voir `scripts/build/colocateOptionals.mjs`, #4286). Sans eux, le moteur s'ouvre en panne (renvoie le texte original). La résolution du travailleur ne dépend plus de `import.meta.url` (il meurt dans le bundle autonome) — il s'ancre sur le runtime cwd / `argv[1]`.
- **Les packs linguistiques Caveman `de` / `fr` / `ja` sont partiels.** Ils expédient des règles `context` + `filler` + `structural` mais pas de packs `dedup` / `ultra`, donc l'intensité `ultra` n'est pas plus forte que `full` pour ces langues (ils utilisent uniquement leurs propres règles — il n'y a pas de repli silencieux vers les règles anglaises `dedup`/`ultra`, qui détruiraient le texte étranger). `en` / `es` / `id` / `pt-BR` sont complets. Les contributions de `dedup.json` + `ultra.json` pour les packs partiels sont les bienvenues.
- **La télémétrie empilée répertorie uniquement les moteurs compressés.** Une étape de pipeline empilé dont le moteur a fonctionné mais a produit 0 % d'économies renvoie `stats:null` et n'apparaît donc pas dans `engineBreakdown` — indiscernable d'une étape qui a été ignorée. La distinction entre « exécuté, 0 % » et « ignoré » nécessiterait un changement de modèle de répartition et est différée.

## Validation

Les portes ciblées pour cette zone sont :

```bash
node --import tsx/esm --test tests/unit/compression/rtk-*.test.ts tests/unit/compression/pipeline-integration.test.ts tests/unit/compression/context-compression-api.test.ts
node --import tsx/esm --test tests/unit/compression/*.test.ts tests/golden-set/*.test.ts tests/integration/compression-pipeline.test.ts tests/unit/api/compression/compression-api.test.ts
node --import tsx/esm --test tests/unit/compression/mcpAccessibility*.test.ts
npm run typecheck:core
```
