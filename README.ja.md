<p align="center"><img src="./assets/banner.svg" alt="XXD Panel 041 project banner" width="1200"></p>

<div align="center">

# 🦁 XXD Panel 041

### 元写真に根差す比喩を、透明感ある等距研究図へ組み込む

[![Codex Skill](https://img.shields.io/badge/Codex-Skill-000000?style=flat-square)](./SKILL.md)
[![Modes](https://img.shields.io/badge/Modes-4-EA846F?style=flat-square)](#)
[![Output](https://img.shields.io/badge/Output-PNG-6FAEB4?style=flat-square)](#)

<a href="README.md">简体中文</a> · <a href="README.en.md">English</a> · <strong>日本語</strong> · <a href="README.ko.md">한국어</a> · <a href="README.ar.md">العربية</a>

</div>

<div>

> テーマ比喩 · 等距秩序 · 淡い手稿 · 和色の透明感 · 東洋の余白

一貫した等距モデルが元写真の同一性を守り、一つの幾何学的比喩が台座、隙間、道、囲い、負形になります。淡い研究スケッチは明るい完成形の周囲に従属する思考の跡です。

## この Skill が必要な理由

このスタイルは元写真に依存し、内容を差し替えられる装飾プリセットではありません。変換は次の因果鎖に従います：

```text
lock identity and structural axes → preserve three defining cues → rebuild with one coherent isometric grid → derive one source-earned metaphor → make the metaphor govern base, cut, path, enclosure, support, or negative space → use luminous source-derived Japanese colour and matte planes → surround with faint analytic studies → align copy to axes and construction lines
```

無関係な写真に替えても認識、構造、配置、素材、色、余白、文案が実質的に変わらないなら、本 Panel の成果ではありません。

## ビジュアル契約

- **元写真への拘束：** 元写真に根差す比喩を、透明感ある等距研究図へ組み込む
- **スタイルDNA：** テーマ比喩 · 等距秩序 · 淡い手稿 · 和色の透明感 · 東洋の余白
- **識別性：** 元写真固有の手掛かりを三つ以上保ち、無関係な写真なら構造も実質的に変わること。
- **構図：** 一つの主体または不可分の関係、元写真に根拠のある配置、能動的な余白を守ること。
- **素材と色：** 固定テンプレートではなく、写真から導き、プロジェクト固有の生成仕様に従うこと。

美的制約と拒否項目は[原文プロンプト](references/041-source.md)だけにあり、Skill とランタイムアダプターは今回の出力変数だけを扱います。 [Skill](SKILL.md) · [英語ランタイムアダプター](references/xxd-panel-041-prompt.en.md)

## 作例 · X より

> [小小東（@xiaoxiaodong01）](https://x.com/xiaoxiaodong01/status/2091001986519068891) · 2026年8月22日<br>
> GPT2 × isometric × レオナルド・ダ・ヴィンチ × 美学プロンプト<br>注：元の投稿にある「VOL.401」は番号の誤記であり、作者が本作例を XXD Panel 041 と確認しています。

<table>
  <tr>
    <td width="50%"><a href="https://x.com/xiaoxiaodong01/status/2091001986519068891"><img src="./assets/examples/sample-01.jpg" alt="XXD Panel 041 作例 1"></a></td>
    <td width="50%"><a href="https://x.com/xiaoxiaodong01/status/2091001986519068891"><img src="./assets/examples/sample-02.jpg" alt="XXD Panel 041 作例 2"></a></td>
  </tr>
  <tr>
    <td width="50%"><a href="https://x.com/xiaoxiaodong01/status/2091001986519068891"><img src="./assets/examples/sample-03.jpg" alt="XXD Panel 041 作例 3"></a></td>
    <td width="50%"><a href="https://x.com/xiaoxiaodong01/status/2091001986519068891"><img src="./assets/examples/sample-04.jpg" alt="XXD Panel 041 作例 4"></a></td>
  </tr>
</table>

<p align="center"><a href="https://x.com/xiaoxiaodong01/status/2091001986519068891">元の投稿と完全なプロンプトを見る →</a></p>

これらの作例は 041 の美的意図を示すものであり、作例の被写体、構図、配色、コピー、旧キャンバス比率が生成時の参照や現在の既定値になることはありません。

## 原文プロンプトを唯一の美的基準にする

`references/041-source.md` が、このプロジェクト唯一の創作・美的基準です。Skill は原文を要約・拡張せず、共通の配色計画、美的動機、タイトル、マイクロコピーを追加しません。色、素材、構図、余白、言葉、タイポグラフィは、GPT Image 2 が原文プロンプトの規則どおりに実行します。

モードとサイズは、原文の変換美学を変えずに、旧来の 3:4 上下出力コンテナを完全に置き換えます。各成果物では選択された一つのモード契約だけを GPT Image 2 に送り、四つの候補を一つの汎用テンプレート内で解釈させません。

## 組み合わせ可能な4つの出力

`top-bottom`、`left-right`、`design-only`、`wallpaper-pack` は単独でも複数でも選べます。複数選択時も、各モードを独立したプロンプトで別々に生成します。

- `top-bottom`：現実画像を上、デザイン変換を下に置く一枚の完成キャンバス。
- `left-right`：上端から下端まで左右構造を保ち、元画像を左、デザインを右に配置します。文字もその構造内に統合し、幅は非対称でも構いません。
- `design-only`：元画像は不可視の参照に限定し、見える要素はすべて当該 Panel のデザイン変換言語に従います。
- `wallpaper-pack`：各端末用にデザイン変換のみの壁紙を独立再構成します。

境界線、中央比率、ピクセル座標は測定しません。決定論的な合成は、ユーザーが正確な分割または元写真のピクセル保持を明示した場合だけ使います。

通常サイズも複数選択できます：自動適応、元画像比率、1:1、3:4、4:3、4:5、5:4、2:3、3:2、9:16、16:9、21:9、5:7、7:5、カスタム比率／正確なピクセル。暗黙の既定サイズはありません。異なる比率は、同じ原文プロンプトから個別に再構成します。

壁紙セットは連動型または独立型。連動型は最初の一枚を基準画像とし、残りを元写真＋基準画像から各端末向けに再構成します。一枚を四サイズへ機械的に切り抜くことはありません。

各呼び出しではタスクディレクトリを一つだけ作り、最終 PNG をすべてその直下へ保存します。元画像、モード、サイズ、端末ごとのサブフォルダーは作らず、`source-01-left-right-3x2-2160x1440.png` や `source-01-wallpaper-linked-phone-1440x3200.png` のようにファイル名で識別します。

## 文字モード

生成前に次の一つを選びます。

1. **原文プロンプトに従ってモデルが文字を生成**：ユーザーは言語・地域だけを指定し、内容、量、調子、組版は GPT Image 2 が原文どおりに生成します。表示される言葉は現在の画像の内容、空気感、または暗示から生まれ、事実・資料として見える情報には、ユーザー提供・画像内で確認可能・検証済みの根拠が必要です。
2. **自分の正確な文言を使う**：一字一句そのまま渡し、書き換え・翻訳・タイトル追加をしません。組版は原文に従います。
3. **文字なし**：文字と疑似文字を厳格に禁止します。

外側の Skill はタイトルやマイクロコピーを先に書きません。出力言語は操作言語と別に確認し、人物、風景、ファイル名から推測しません。

## 完成キャンバス優先とラスター境界

画像モデルが完成画面全体の美的再構成を担当し、二連レイアウトも完成キャンバス一枚の直接生成を既定とします。`scripts/compose_panel.py` は条件付きの復旧、無劣化ピクセル調整、読み取り専用監査にだけ残し、毎回の事前計画や美的評価には使いません。

納品物はすべてPNGラスターで、呼び出しごとに `~/Desktop/xxd/` に新規タスクを作ります。設定済み画像経路は匿名化された状態だけを返し、提供元、接続先、認証情報、ヘッダー、プロンプト、応答、アカウント情報を公開しません。SVG、HTML、Canvas、図解、プログラム描画は最終作品の代替になりません。

## 宿主能力に適応する質問とインライン引数

同じ Skill が、宿主に実在する対話機能へ適応します。装飾記号をクリック可能な UI のようには見せません。

- **Claude Code に `AskUserQuestion + multiSelect: true` がある場合**：モードとサイズは本物のチェックボックス、文字方式と壁紙関係は単一選択。一般サイズは正方形・縦・横のグループに分け、選択を累積し、カスタム値は自由入力します。
- **Codex に `request_user_input` しかない場合**：文字方式や壁紙関係など、相互排他的な項目だけに使います。モードやサイズを単一選択に見せかけず、組み合わせ入力で受け取ります。
- **対話ツールがない場合**：1回目にモード、2回目にサイズ＋文字方式を入力します。偽の `- [ ]` は表示せず、フォームのためだけに Plan mode への切り替えも求めません。

2回目は最初に「自動推薦／元画像比率／一般比率／カスタム」だけを表示します。一般比率を選んだときだけ、正方形 `1:1`、縦 `3:4、4:5、2:3、9:16、5:7`、横 `4:3、5:4、3:2、16:9、21:9、7:5` を展開します。複数比率と正確なピクセルを指定できます。

すべての設定はインラインでも指定できます。

```text
/xxd-panel-041 photo.jpg --mode top-bottom,design-only --size auto,3:4,9:16 --text prompt --locale ja-JP
```

`--mode`、複数指定可能な `--size`、`--text prompt|exact|none`、`--locale`、`--copy`、`--wallpaper linked|independent`、`--wallpaper-size`、`--out` に対応します。必要な値が揃っていれば質問を省略し、不足分だけを尋ねます。

## 画像モデルの優先順位

GPT Image 2 を既定の第一候補とします。高忠実度の参照画像、生成前の完成キャンバス確認、二連モードの完成画面一括生成、条件を満たした場合だけのスクリプト合成という既存の流れは変わりません。

現在のツールまたは設定済み経路から実際に利用でき、元画像の忠実度、完成画角、対象言語の文字、連動壁紙の複数参照を満たせる場合は、Seedance 5.0 Pro、Nano Banana Pro（Gemini Image Pro）、Nano Banana 2（Gemini Image Flash）、その他の互換ビットマップモデルも利用できます。代替モデルが変更できるのは生成経路だけで、モード、画角、文案、言語、壁紙関係、完成キャンバス優先の方針は変更できません。

適切な経路がない場合は、画像生成ツールを有効にするか API Key を提供するようユーザーに案内します。ユーザーが提供した認証情報は現在のタスクで利用できますが、返信やログに再表示・記録・開示しません。明示的な依頼がない限り、長期保存やプロバイダー、アカウント、課金、グローバル経路の設定変更も行いません。

## 使い始める

```bash
git clone https://github.com/nevertoday/xxd-panel-041.git
mkdir -p ~/.codex/skills
ln -s "$(pwd)/xxd-panel-041" ~/.codex/skills/xxd-panel-041
```

Claude Code では同じフォルダを次へリンクできます： `~/.claude/skills/xxd-panel-041`. インストール後に Agent セッションを再起動してください。

```text
$xxd-panel-041
Use this photograph, ask me for the modes and copy setting, then generate fresh raster outputs.
```

完全仕様: [Skill ワークフロー](SKILL.md) · [原始スタイル資料](references/041-source.md) · [英語ランタイムアダプター](references/xxd-panel-041-prompt.en.md) · [中国語ランタイムアダプター](references/xxd-panel-041-prompt.zh-CN.md)

## XXD について

XXD は Xiaoxiaodong のブランド名略称です。作成・管理： [@xiaoxiaodong01](https://x.com/xiaoxiaodong01).

## サポートとメンバーシップ

### 個別コンサルティング · 299元／時間

Skills の使用とワークフローに関する一対一の相談です。WeChat で Xiaoxiaodong にご連絡ください。 [WeChat](https://xiaoxiaodong.pages.dev/assets/wechat-qr.png)

### Xiaoxiaodong Skills ユーザー交流グループ · 99元

一回の支払いで Skills ユーザー交流グループに参加できます。時間制の個別相談は別料金です。

### Knowledge Planet＋会員プロンプトライブラリ · 699元／年

Knowledge Planet と会員プロンプトライブラリは一つの年会です。どちらかで加入後、WeChat で連絡するともう一方も開通できます。

[Knowledge Planet](https://wx.zsxq.com/group/15554814142882) · [Member Prompt Library](https://vip.xiaoxiaodong.ai/)

<p align="center"><a href="https://xiaoxiaodong.pages.dev/assets/wechat-qr.png"><img src="https://xiaoxiaodong.pages.dev/assets/wechat-qr.png" alt="XXD WeChat" width="280"></a></p>

<div align="center"><strong>完成形と思考の痕跡が、一つの静かな場を共有する。</strong></div>

---

<div align="center">

## ☕ オープンソースを支援

中国語圏以外では Buy Me a Coffee を利用できます。支援は任意で、オープンソースへのアクセスを変えません。


<p align="center"><a href="https://github.com/nevertoday/zhongguo-traditional-colors/blob/main/docs/images/buy-me-a-coffee-qr.png?raw=true"><img src="https://github.com/nevertoday/zhongguo-traditional-colors/blob/main/docs/images/buy-me-a-coffee-qr.png?raw=true" alt="Buy Me a Coffee" width="180"></a></p>

</div>
</div>
