# Lire les kanji du JLPT N5

Module de formation à distance pour apprendre à **lire** les 105 kanji de base du japonais (niveau JLPT N5) : les reconnaître, comprendre leur sens et les lire dans les mots de tous les jours, sur des documents proches du réel.

Le lien vers la version en ligne se trouve dans la section *About* du dépôt (à droite).

## Public et objectifs

- **Public** : adultes francophones débutants, qui lisent déjà les hiragana et les katakana.
- **Format** : à distance, asynchrone, sans durée imposée ; le module se suit seul, à son rythme.
- **Objectif** : lire et comprendre les 105 kanji du module dans des situations réelles (prix, horaires, panneaux, menus, messages).

## Organisation

Chaque unité comprend un livre interactif **Comprendre** (cartes avec le son, activités de vérification, documents réels) et un quiz **S'entraîner** (12 questions tirées au hasard, objectif 80 %). Les unités 4 et 9 se terminent par une **mission** en scénario à embranchements. Le module se conclut par une **évaluation finale**, « Une journée au Japon », et sa correction commentée.

| Unité | Thème | Kanji | Activités |
| --- | --- | --- | --- |
| 1 | Nombres et argent | 一 二 三 四 五 六 七 八 九 十 百 千 万 円 | [Comprendre](activites/unite-01-nombres-et-argent/comprendre.html) · [S'entraîner](activites/unite-01-nombres-et-argent/s-entrainer.html) |
| 2 | Temps et calendrier | 日 月 火 水 木 金 土 年 今 時 分 半 毎 | [Comprendre](activites/unite-02-temps-et-calendrier/comprendre.html) · [S'entraîner](activites/unite-02-temps-et-calendrier/s-entrainer.html) |
| 3 | Personnes et corps | 人 男 女 子 父 母 友 目 耳 口 手 足 | [Comprendre](activites/unite-03-personnes-et-corps/comprendre.html) · [S'entraîner](activites/unite-03-personnes-et-corps/s-entrainer.html) |
| 4 | Directions | 上 下 左 右 中 外 前 後 東 西 南 北 | [Comprendre](activites/unite-04-directions/comprendre.html) · [S'entraîner](activites/unite-04-directions/s-entrainer.html) · [Mission : Retrouver ゆき](activites/unite-04-directions/mission-retrouver-yuki.html) |
| 5 | Nature et climat | 山 川 田 天 気 雨 花 空 | [Comprendre](activites/unite-05-nature-et-climat/comprendre.html) · [S'entraîner](activites/unite-05-nature-et-climat/s-entrainer.html) |
| 6 | Adjectifs | 大 小 高 安 新 古 長 多 少 白 赤 青 | [Comprendre](activites/unite-06-adjectifs/comprendre.html) · [S'entraîner](activites/unite-06-adjectifs/s-entrainer.html) |
| 7 | Verbes d'action | 行 来 帰 会 食 飲 見 聞 読 書 話 買 出 入 立 休 | [Comprendre (1re partie)](activites/unite-07-verbes-d-action/comprendre-partie-1.html) · [S'entraîner (1re partie)](activites/unite-07-verbes-d-action/s-entrainer-partie-1.html) · [Comprendre (2e partie)](activites/unite-07-verbes-d-action/comprendre-partie-2.html) · [S'entraîner (2e partie)](activites/unite-07-verbes-d-action/s-entrainer-partie-2.html) |
| 8 | École et savoir | 学 校 先 生 語 本 文 字 | [Comprendre](activites/unite-08-ecole-et-savoir/comprendre.html) · [S'entraîner](activites/unite-08-ecole-et-savoir/s-entrainer.html) |
| 9 | Société et lieux | 車 電 駅 国 社 店 道 門 名 何 | [Comprendre](activites/unite-09-societe-et-lieux/comprendre.html) · [S'entraîner](activites/unite-09-societe-et-lieux/s-entrainer.html) · [Mission : De la gare au restaurant](activites/unite-09-societe-et-lieux/mission-de-la-gare-au-restaurant.html) |
| — | Évaluation finale | les 105 kanji | [Évaluation](activites/evaluation-finale/evaluation.html) · [Correction](activites/evaluation-finale/correction.html) |

## Choix pédagogiques

- **Cognitivisme et enseignement explicite** : double codage forme, sens et son, clés des kanji, exemples résolus, rappel actif, révisions espacées.
- **Béhaviorisme** : quiz avec retour immédiat et seuil de maîtrise à 80 %.
- **Perspective actionnelle** : documents réels, missions et évaluation en situation : l'apprenant lit pour agir.

## Organisation du dépôt

```
index.html              page d'accueil du module
activites/
  unite-01-nombres-et-argent/   comprendre.html, s-entrainer.html
  …                             (un dossier par unité ; missions dans les unités 4 et 9)
  unite-07-verbes-d-action/     deux parties : comprendre-partie-1.html, s-entrainer-partie-1.html, …
  evaluation-finale/            evaluation.html, correction.html
assets/
  fonts/                polices (WOFF2) et leur licence
  motifs/               motifs japonais des unités
```

Chaque activité est un fichier HTML autonome (export H5P « un seul fichier ») : il fonctionne sans serveur ni connexion à une plateforme. Version de démonstration : les résultats ne sont pas enregistrés. Dans Moodle, le même module enregistre les tentatives et les notes de chaque apprenant.

## Accessibilité

Page d'accueil structurée par titres, lien d'évitement, contrastes vérifiés, navigation au clavier, textes des liens explicites, langue du document déclarée (avec le japonais balisé), images décoratives ignorées par les lecteurs d'écran. Chaque activité a un titre de page et un lien de retour au sommaire.

## Crédits et licences

- **Voix de synthèse** : VOICEVOX:玄野武宏
- **Polices** : Klee One (Fontworks) et Zen Kaku Gothic New, sous licence SIL Open Font License 1.1
- **Activités** : créées avec Lumi (logiciel libre, licence AGPL) et le format H5P (bibliothèques sous licence MIT)
- **Textes, images et documents** : créés pour le module, avec l'aide d'une IA générative

Les contenus du module (textes, images, activités) sont protégés par le droit d'auteur. Les composants tiers ci-dessus restent sous leur propre licence.
