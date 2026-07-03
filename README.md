## HelloWorld

# 主要制作物
## 補助ツール
## [Research-Collector](https://manato1201.github.io/Research-Collector/)
## [CADGPUInferenceModeling](https://manato1201.github.io/CADGPUInferenceModeling/)

## ゲーム作品
## [JunkShooting](https://github.com/manato1201/JunkShooting)
## [AdvancedVAT](https://github.com/manato1201/AdvancedVAT)
## [piece-peace](https://github.com/manato1201/piece-peace)


<!--
**manato1201/manato1201** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...

- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->  
![](https://raw.githubusercontent.com/manato1201/manato1201/output/github-contribution-grid-snake.svg)

<p align="left">
  <a href="https://github.com/manato1201">
    <img height="20" src="https://komarev.com/ghpvc/?username=manato1201" />
  </a>
  <a href="https://github.com/manato1201">
    <img height="20" src="https://img.shields.io/github/followers/Keichan15?label=follow&logo=github&style=flat" />
  </a>  
</p>


## Stats

- ## Skill
<img alt="language" src="https://skillicons.dev/icons?theme=dark&perline=10&i=c,cpp,cs,md,raspberrypi,cloudflare,opencv" />

- ## Tool
<img alt="language" src="https://skillicons.dev/icons?theme=dark&perline=10&i=github,visualstudio,vscode,rider,unity" /> 

- ## Learning
<img alt="language" src="https://skillicons.dev/icons?theme=dark&perline=10&i=unreal" /> 

![](http://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=manato1201&theme=gruvbox)
![](http://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=manato1201&theme=gruvbox)
![](http://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=manato1201&theme=gruvbox)
![](http://github-profile-summary-cards.vercel.app/api/cards/stats?username=manato1201&theme=gruvbox)
![](http://github-profile-summary-cards.vercel.app/api/cards/productive-time?username=manato1201&theme=gruvbox&utcOffset=9)



# 学習・制作ロードマップ

> 作成日: 2026-07-03
> 参照: [STUで求められるスキルセット 学習ロードマップ (2021年10月改定)](https://www.stu-inc.com/uploads/stu_roadmap_5374985edc.png)
> 調査対象: `D:\大学` / `D:\個人\高校実習` / `C:\Users\matuu\Desktop\GameDevelopment`

---

## 1. 現在地

- **東京国際工科専門職大学 4年**(2026年7月)— 卒業研究(Houdini Help RAG MCP)・就活期
- 目指す方向性: **テクニカルアーティスト / CGエンジニア / グラフィックスプログラマー**(STUロードマップ準拠)
- 既に **Steam でゲームをリリース済み**(Qualial Nature)。個人開発の深度は学生水準を大きく超えている

---

## 2. これまでの歩み(実績タイムライン)

```mermaid
timeline
    title 学習・制作の歩み
    section 高校(〜2023.3)
        情報系実習 : C# WinForms/WPF : TCPチャットアプリ(Client/Server) : SQLite
        課題研究 : OCR文字認識(WPF/UWP検証×3) : Web課題集(HTML/CSS/JS)
        校外 : 日立東日本ソリューションズ クラフトマン実習
    section 大学1年(2023)
        理論 : ゲーム構成論(ゲームデザイン理論) : 企画発想法 : コンテンツデザイン概論
        実装 : C言語基礎(フレームバッファ・2D行列演算)
        DCC : Cinema 4D(キャラクターアニメーション)
    section 大学2年(2024)
        C++ : ゲームアルゴリズム(DotEat・3DCG)
        ゲーム制作 : GP1(Tennis/Race/Effect) : ShootingGame+Vosk音声認識
        チーム : ゲーム制作技術総合実習 : 地域共創デザイン実習
    section 大学3年(2025)
        3D数学/物理 : Siv3Dでスケルタルアニメ・IK・スキニング : OBB/カプセル衝突・剛体 : モーションブレンド・パーティクル・ビルボード
        AI : ゲームAI I/II
        教養 : ゲームハード概論・知財・経営
    section 個人開発(2024〜現在)
        Unity : Steamリリース「Qualial Nature」 : HDRPブラックホール : VRChat UdonSharp(VRCEffectFrameWork) : AdvancedVAT
        グラフィックスR&D : 流体エンジン(SPH/FLIP/Stable Fluids) : Neural Fluid(GNN 1.13Mパラメータ) : WASMリアルタイムSPH : mini-renderer(GPU)
        AI基盤 : mcp-rag-server : Research-Collector : CAD GPU推論(TripoSR)
        アート : ClipStudioイラスト : Aseprite : Blender/Houdini
    section 大学4年(2026・現在)
        卒業研究 : Houdini RAG MCP(pgvector+Docker+WSL2)
        就活 : ポートフォリオ整備
```

---

## 3. スキル棚卸し × STUロードマップ ギャップ分析

STUロードマップの必須(❤)・推奨(✅)項目に対する現状。

### ✅ 習得済み(実績あり)

| カテゴリ | スキル | 根拠となる実績 |
|---|---|---|
| 言語 | C# | 高校WPF〜Unity/UdonSharp まで5年以上 |
| 言語 | C++ | ゲームアルゴリズム、Siv3D、WASM SPH(外部依存ゼロ実装) |
| 言語 | Python | 流体ソルバー(numpy完全ベクトル化)、RAG、uv運用 |
| 言語 | HTML/JS | 高校Web課題〜Three.jsビューア、ポートフォリオ |
| CG数学 | 三角関数・行列・クォータニオン | Siv3D課題(IK・スキニング・OBB)で実践済み |
| CG | 衝突判定・剛体・補間 | OBB/カプセル/RigidRect/Interpolation |
| ゲームエンジン | Unity(Built-in/URP/HDRP) | Steamリリース、HDRP、VAT、VRChat SDK |
| DCC | Blender / Houdini / C4D | fluid HDA、Blender MCP連携、C4D課題 |
| バージョン管理 | Git / GitHub | 全個人リポジトリ、GitHub Actions(FluidKit) |
| サーバー/仮想化 | WSL2 / Docker | 卒研(pgvector on Docker) |
| データ | JSON / SQLite / PostgreSQL | 中間フォーマット運用、卒研DB |
| ネットワーク | TCP/IP・HTTP | 高校チャットアプリ(ソケット)、APIサーバー |
| **STU範囲外の強み** | LLM/RAG/MCP・GNN・音声認識 | mcp-rag-server、Neural Fluid、Vosk — **AI×TAの差別化要素** |

### ⚠️ 復習・体系化が必要(触ってはいる)

| スキル | 現状 | やること |
|---|---|---|
| レンダリング理論 | mini-rendererで着手済みだが体系化不足 | スキャンライン→レイトレ→パストレ→GIの理論を一気通貫で整理 |
| シェーダー(HLSL) | Unityシェーダー経験あり | Compute Shader・SRP拡張まで踏み込む |
| Unreal Engine | UnrealGameフォルダあり(浅い) | STU必須の Blueprint / Material / Niagara / コンテンツパイプライン |
| 3D数学 | 授業で習得済み | クォータニオン・座標変換を「人に説明できる」レベルに再整理(就活対策) |
| CI/CD・テスト | GitHub Actions一部使用 | pytest習慣化、ビルド自動化パイプライン |
| ドキュメンテーション | README/講義資料は書ける | Doxygen/Sphinxなど生成系ツール |

### ❌ 未着手(STU必須・推奨とのギャップ)

| スキル | STU上の扱い | 優先度 |
|---|---|---|
| **Autodesk Maya + MEL/PyMEL/Python API** | 必須 | **高** — TA職の共通言語。Blender/Houdini経験があるので移行は速い |
| **Perforce** | 必須 | 中 — 概念だけ先行学習(ワークスペース/ストリーム)。実務で習得可 |
| USD / Alembic / FBX SDK | Scene Description | **高** — パイプラインTAの中核。Houdini Solarisから入ると効率的 |
| ShotGrid(+API) | 必須 | 低 — 入社後でよい。概念(工程管理)だけ把握 |
| Qt / PySide2 | 推奨 | **高** — DCCツール開発の標準。Python力があるので即戦力化しやすい |
| OpenColorIO / ACES | カラーマネジメント | 中 — HDRP経験と接続すると理解が速い |
| 文字エンコーディング | 必須 | 低 — Shift-JIS/UTF-8の実務知識を1日で整理 |
| Vulkan / DirectX 12(生API) | Graphics API | 中 — mini-renderer-gpuの発展として |

---

## 4. 今後の学習ロードマップ

```mermaid
flowchart TB
    subgraph P1["Phase 1｜今〜卒業(2026後半〜2027.3) 就活直結・復習"]
        direction TB
        A1["卒業研究の完成<br>Houdini RAG MCP"]
        A2["3D数学の再体系化<br>クォータニオン/座標変換を説明できるレベルに"]
        A3["UE5基礎<br>Blueprint / Material / Niagara"]
        A4["Maya基礎 + Python API<br>Blender経験からの移行"]
        A5["ポートフォリオ統合<br>Steam作品+流体+RAGを1本のストーリーに"]
    end

    subgraph P2["Phase 2｜深化(2027) TAとしての武器づくり"]
        direction TB
        B1["PySide2/Qtツール開発<br>DCC連携ツールを1本制作"]
        B2["USD/Alembicパイプライン<br>Houdini Solaris起点"]
        B3["HLSL深化<br>Compute Shader / SRP拡張 / GPUパーティクル"]
        B4["レンダリング理論の完走<br>パストレーサー自作(PBRT準拠)"]
        B5["Perforce/ShotGrid概念<br>+ CI/CDパイプライン構築"]
    end

    subgraph P3["Phase 3｜応用・発展(2028〜) 差別化・研究"]
        direction TB
        C1["Neural Rendering / ML for CG<br>GNN流体の延長 → NeRF/3DGS"]
        C2["流体エンジンのエンジン統合<br>VATエクスポート → Unity/UE(Niagara)"]
        C3["Houdini PDG / パイプライン自動化<br>+ LLMエージェント統合(独自領域)"]
        C4["WebGPU / Vulkan<br>mini-renderer-gpuの発展"]
        C5["分散レンダリング / Deadline<br>OpenColorIO・ACES運用"]
    end

    A2 --> B4
    A3 --> B3
    A4 --> B1
    B1 --> C3
    B2 --> C3
    B3 --> C2
    B4 --> C1
    B4 --> C4
```

### Phase 1 の優先順位(理由つき)

1. **卒業研究** — 卒業要件。RAG×Houdiniは他の学生がやっていない領域なのでそのまま就活の主砲になる
2. **3D数学の復習** — TA/グラフィックス職の面接頻出。実装経験(Siv3D課題)があるので「言語化」だけが課題
3. **UE5(Blueprint/Material/Niagara)** — STU必須で唯一の大きな空白。Unity経験があるので概念マッピングで速習可能
4. **Maya + Python API** — TA求人の必須要件筆頭。「Blenderはできます」だけだと選考で不利になりがち
5. **ポートフォリオ** — Steamリリース・流体R&D・RAG基盤を「技術で制作を支えるTA」の物語に編集する

---

## 5. 制作ロードマップ(ポートフォリオ強化)

```mermaid
flowchart LR
    G1["卒業制作<br>Houdini RAG MCP"] --> G2["TAツールリール<br>PySide製 DCC→Unity<br>自動インポートパイプライン"]
    G2 --> G3["流体×エンジン統合デモ<br>FluidKit → VAT → Niagara/VFX Graph"]
    G3 --> G4["自作パストレーサー<br>mini-renderer発展<br>PBR/GI対応"]
    G4 --> G5["ポートフォリオサイト完成<br>Web/Portfolio に全作品統合"]

    style G1 fill:#f9d67a
    style G5 fill:#8fd18f
```

| 制作物 | 使う既存資産 | 証明できるスキル |
|---|---|---|
| TAツール(PySide) | mcp-rag-server のPython力 | ツール開発・パイプライン設計 |
| 流体×Niagara統合 | FluidKit + AdvancedVAT | シミュレーション・VFX・エンジン間データ変換 |
| 自作パストレーサー | mini-renderer / mini-renderer-gpu | レンダリング理論・C++/GPU |
| LLM支援制作環境 | Houdini RAG MCP(卒研) | **独自領域: AI活用パイプライン** |

---

## 6. 学習方針(STUロードマップ備考より)

- 項目名の暗記ではなく、**各項目を自分で掘り下げて初めて知識になる** — 幸いあなたは「作って学ぶ」型が既に確立している
- 一見無関係な技術も間接的に業務で使われる — **RAG/LLM経験は現時点のSTUマップに無い将来価値**
- トレンドは変わる。技術者である限り一生勉強 — 現在のペース(授業+個人R&D並走)を維持すれば十分戦える

### 週次の目安

| 枠 | 内容 |
|---|---|
| 最優先 | 卒業研究 + 就活(ポートフォリオ) |
| 週2〜3h | Phase 1 の空白埋め(UE5 → Maya の順) |
| 隙間時間 | 3D数学の言語化(ノート化・ブログ化すると面接対策と一石二鳥) |



