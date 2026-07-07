## HelloWorld

# 主要制作物
## 卒業研究
## [RAGを用いた動的チュートリアル生成](https://github.com/manato1201/DevelopmentRAGEnvironment)

## 補助ツール
## [Research-Collector](https://manato1201.github.io/Research-Collector/)
## [CADGPUInferenceModeling](https://manato1201.github.io/CADGPUInferenceModeling/)

## 学習成果物
## [LearningFluidEngine](https://github.com/manato1201/LearningFluidEngine)
## [LearningQuickDraw](https://github.com/manato1201/LearningQuickDraw)


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


# 松浦真聖 学習・制作ロードマップ

> 作成日: 2026-07-03(最終更新)
> 構成は [STUスキルセット学習ロードマップ](https://www.stu-inc.com/uploads/stu_roadmap_5374985edc.png) のスタイル(カテゴリ別スキルツリー+バッジ)を踏襲。
> **中身は自分の実績(`D:\個人\高校実習` → `D:\大学` → `GameDevelopment`)のみから構成。**

## バッジの説明(全図共通の凡例)

| バッジ | 色 | 意味 |
|---|---|---|
| 🟢 | 濃緑背景 + 白文字 | **習得済み** — 実績・成果物あり |
| 🟡 | 濃橙背景 + 黒文字 | **復習すべき** — 経験はあるが体系化・言語化が必要 |
| 🔵 | 濃青背景 + 白文字 | **今後学ぶ** — 自分の路線の延長で必要になる |
| 🟣 | 濃紫背景 + 白文字 | **応用・発展** — 既存スキルを掛け合わせて到達できる領域 |
| ⬛ | スレート背景 + 白文字 | カテゴリ見出し(分類ノード、バッジなし) |

```mermaid
%%{init: {'themeVariables': {'primaryColor':'#37474f','primaryTextColor':'#ffffff','primaryBorderColor':'#263238','lineColor':'#78909c','fontSize':'16px'}}}%%
flowchart LR
    L1[🟢 習得済み]:::done --- L2[🟡 復習]:::review --- L3[🔵 今後学ぶ]:::next --- L4[🟣 応用・発展]:::adv
    classDef done fill:#2e7d32,stroke:#1b5e20,stroke-width:2px,color:#ffffff,font-weight:bold
    classDef review fill:#f9a825,stroke:#e65100,stroke-width:2px,color:#000000,font-weight:bold
    classDef next fill:#1565c0,stroke:#0d47a1,stroke-width:2px,color:#ffffff,font-weight:bold
    classDef adv fill:#6a1b9a,stroke:#4a148c,stroke-width:2px,color:#ffffff,font-weight:bold
```

---

## 全体マップ(STUの「緑の道」に相当)

> 🕐 **時期:** 高校(2020-2023) → 大学1〜4年(2023-2026・現在)の全体像

```mermaid
%%{init: {'themeVariables': {'primaryColor':'#37474f','primaryTextColor':'#ffffff','primaryBorderColor':'#263238','lineColor':'#78909c','fontSize':'16px'}}}%%
flowchart TB
    S([高校 2020-2023]) ==> C1
    C1[1. 基本 / 開発環境] ==> C2[2. プログラミング言語]
    C2 ==> C3[3. ハードウェア基礎]
    C3 ==> C4[4. ゲーム制作]
    C4 ==> C5[5. CG数学・物理・レンダリング]
    C5 ==> C6[6. シミュレーション・流体]
    C6 ==> C7[7. DCCツール・アート]
    C7 ==> C8[8. AI・LLM・研究基盤]
    C8 ==> C9[9. ネットワーク・Web]
    C9 ==> C10[10. 企画・チーム制作]
    C10 ==> G([現在: 大学4年 卒研+就活 2026])
    G -.-> F([今後の道筋 → 章末])

    style S fill:#455a64,stroke:#263238,color:#ffffff,font-weight:bold
    style G fill:#2e7d32,stroke:#1b5e20,color:#ffffff,font-weight:bold
    style F fill:#6a1b9a,stroke:#4a148c,color:#ffffff,font-weight:bold
```

---

## 1. 基本 / 開発環境

> 🕐 **時期:** 高校(2020-2023)で基礎ツール操作を習得 → 大学〜現在まで継続的に更新
> 🎨 **凡例:** 🟢習得済み ｜ 🟡復習 ｜ 🔵今後学ぶ ｜ 🟣応用発展(詳細は冒頭バッジ表を参照)

```mermaid
%%{init: {'themeVariables': {'primaryColor':'#37474f','primaryTextColor':'#ffffff','primaryBorderColor':'#263238','lineColor':'#78909c','fontSize':'16px'}}}%%
flowchart LR
    OS[OS / 環境] --> W[🟢 Windows 11<br>PowerShell]:::done
    OS --> WSL[🟢 WSL2 + systemd<br>卒研で構築]:::done
    OS --> DK[🟢 Docker<br>pgvector運用]:::done

    IDE[エディタ / IDE] --> VS[🟢 Visual Studio<br>高校WPF〜Siv3D]:::done
    IDE --> VSC[🟢 VSCode / Rider系]:::done

    VC[バージョン管理] --> GIT[🟢 Git / GitHub]:::done
    GIT --> GA[🟢 GitHub Actions<br>FluidKit CI]:::done
    GIT --> GF[🟡 ブランチ戦略<br>チーム開発向け運用]:::review

    PKG[パッケージ管理] --> UV[🟢 uv Python]:::done
    PKG --> NG[🟢 NuGet / UPM]:::done

    AI[AI開発環境] --> CC[🟢 Claude Code / MCP<br>Blender MCP連携]:::done

    VC --> PF[🔵 Perforce等<br>大規模開発の構成管理]:::next
    DK --> IaC[🟣 CI/CDパイプライン設計<br>ビルド・テスト自動化]:::adv

    classDef done fill:#2e7d32,stroke:#1b5e20,stroke-width:2px,color:#ffffff,font-weight:bold
    classDef review fill:#f9a825,stroke:#e65100,stroke-width:2px,color:#000000,font-weight:bold
    classDef next fill:#1565c0,stroke:#0d47a1,stroke-width:2px,color:#ffffff,font-weight:bold
    classDef adv fill:#6a1b9a,stroke:#4a148c,stroke-width:2px,color:#ffffff,font-weight:bold
```

---

## 2. プログラミング言語

> 🕐 **時期:** 高校C#(2020-2023) → 大学1〜4年でC/C++/Python/JS/シェーダーへ拡大(2023-2026)
> 🎨 **凡例:** 🟢習得済み ｜ 🟡復習 ｜ 🔵今後学ぶ ｜ 🟣応用発展

```mermaid
%%{init: {'themeVariables': {'primaryColor':'#37474f','primaryTextColor':'#ffffff','primaryBorderColor':'#263238','lineColor':'#78909c','fontSize':'16px'}}}%%
flowchart LR
    CS[C#] --> CS1[🟢 WinForms / WPF<br>高校: チャット・OCR]:::done
    CS1 --> CS2[🟢 Unity C#<br>Steamリリース]:::done
    CS2 --> CS3[🟢 UdonSharp<br>VRChat]:::done
    CS2 --> CS4[🟡 非同期 / UniTask / ZString<br>パフォーマンス設計の体系化]:::review

    CPP[C / C++] --> CP1[🟢 C言語基礎<br>フレームバッファ・行列]:::done
    CP1 --> CP2[🟢 ゲームアルゴリズム<br>DotEat・3DCG]:::done
    CP2 --> CP3[🟢 Siv3D<br>3D数学課題群]:::done
    CP2 --> CP4[🟢 WASM SPH<br>外部依存ゼロC++]:::done
    CP4 --> CP5[🔵 モダンC++体系化<br>C++17/20・最適化]:::next

    PY[Python] --> PY1[🟢 numpy完全ベクトル化<br>流体ソルバー]:::done
    PY --> PY2[🟢 PyTorch<br>GNN訓練 AMP]:::done
    PY --> PY3[🟢 RAG / API開発]:::done
    PY3 --> PY4[🔵 型注釈・テスト習慣化<br>pytest]:::next

    WEBL[JS / Web系] --> JS1[🟢 HTML/CSS/JS<br>高校web課題集]:::done
    JS1 --> JS2[🟢 Three.js<br>流体ビューア]:::done
    JS2 --> JS3[🔵 TypeScript]:::next

    SH[シェーダー] --> SH1[🟢 HLSL / ShaderLab<br>HDRPブラックホール等]:::done
    SH1 --> SH2[🟡 Compute Shader<br>GPGPUの体系化]:::review
    SH2 --> SH3[🟣 WGSL / WebGPU<br>mini-renderer-gpuの発展]:::adv

    classDef done fill:#2e7d32,stroke:#1b5e20,stroke-width:2px,color:#ffffff,font-weight:bold
    classDef review fill:#f9a825,stroke:#e65100,stroke-width:2px,color:#000000,font-weight:bold
    classDef next fill:#1565c0,stroke:#0d47a1,stroke-width:2px,color:#ffffff,font-weight:bold
    classDef adv fill:#6a1b9a,stroke:#4a148c,stroke-width:2px,color:#ffffff,font-weight:bold
```

---

## 3. ハードウェア基礎

> 🕐 **時期:** 高校 工業実習・情報技術実習(2021-2023) → 大学1年 電子情報工学概論(2023) → 大学3年 ゲームハード概論(2025)
> 🎨 **凡例:** 🟢習得済み ｜ 🟡復習 ｜ 🔵今後学ぶ ｜ 🟣応用発展

```mermaid
%%{init: {'themeVariables': {'primaryColor':'#37474f','primaryTextColor':'#ffffff','primaryBorderColor':'#263238','lineColor':'#78909c','fontSize':'16px'}}}%%
flowchart LR
    RPI[組込み実習] --> RP1[🟢 Raspberry Pi GPIO制御<br>高校 工業実習]:::done
    RPI --> RP2[🟢 Raspbian環境構築<br>高校 情報技術実習]:::done
    RP2 --> RP3[🟡 Linuxコマンド運用の再確認<br>WSL2運用と接続して体系化]:::review

    EE[電子情報工学] --> EE1[🟢 電子情報工学概論<br>大学1年前期 全14回]:::done
    EE1 --> EE2[🟡 論理回路・CPU基礎の再整理<br>低レイヤー理解の土台]:::review

    GH[ゲームハード概論] --> GH1[🟢 ハードウェア史<br>コンピュータ基礎〜歴代機]:::done
    GH --> GH2[🟢 映像/音源出力の仕組み<br>特殊映像出力・デジタル音源]:::done
    GH --> GH3[🟢 プラットフォーム知識<br>入出力装置・アカウント・規約]:::done

    RP1 --> F1[🔵 組込み制御の再開<br>Arduino/RaspberryPiでの実機制御]:::next
    EE2 --> F2[🔵 コンピュータアーキテクチャ<br>低レイヤー最適化の理論的裏付け]:::next
    F1 --> F3[🟣 エッジAI<br>Raspberry Pi上でのGNN/ML推論]:::adv
    GH3 --> F4[🟣 実機ターゲット最適化<br>コンソール/モバイル知識を活かした軽量化]:::adv

    classDef done fill:#2e7d32,stroke:#1b5e20,stroke-width:2px,color:#ffffff,font-weight:bold
    classDef review fill:#f9a825,stroke:#e65100,stroke-width:2px,color:#000000,font-weight:bold
    classDef next fill:#1565c0,stroke:#0d47a1,stroke-width:2px,color:#ffffff,font-weight:bold
    classDef adv fill:#6a1b9a,stroke:#4a148c,stroke-width:2px,color:#ffffff,font-weight:bold
```

---

## 4. ゲーム制作

> 🕐 **時期:** 大学1〜4年の授業(2023-2026)、個人開発・Steamリリースは2024年〜並行
> 🎨 **凡例:** 🟢習得済み ｜ 🟡復習 ｜ 🔵今後学ぶ ｜ 🟣応用発展

```mermaid
%%{init: {'themeVariables': {'primaryColor':'#37474f','primaryTextColor':'#ffffff','primaryBorderColor':'#263238','lineColor':'#78909c','fontSize':'16px'}}}%%
flowchart LR
    ENG[ゲームエンジン] --> U[Unity]
    U --> U1[🟢 Built-in RP<br>VRChat案件]:::done
    U --> U2[🟢 URP / HDRP<br>ブラックホール表現]:::done
    U --> U3[🟢 Steamリリース<br>Qualial Nature]:::done
    U --> U4[🟢 VAT<br>AdvancedVAT]:::done
    U --> U5[🟡 SRP拡張 / RenderFeature<br>描画パイプライン自作]:::review
    ENG --> UE[Unreal Engine]
    UE --> UE1[🟡 UE基礎<br>UnrealGameで着手済]:::review
    UE1 --> UE2[🔵 Niagara / Material<br>流体アセットの持ち込み先]:::next

    FS[フルスクラッチ制作] --> F1[🟢 GP1: Tennis / Race / Effect]:::done
    FS --> F2[🟢 ShootingGame<br>+Vosk音声認識]:::done
    FS --> F3[🟢 Siv3D 3Dゲーム基盤]:::done

    GAI[ゲームAI] --> GA1[🟢 ゲームAI I<br>基礎理論・意思決定]:::done
    GAI --> GA2[🟢 ゲームAI II<br>経路探索・アクションAI・機械学習]:::done
    GAI --> GA3[🟢 PracticeGameAI 実装演習]:::done
    GA2 --> GA4[🟣 LLM駆動NPC / 生成AIゲーム<br>AIGameJamの発展]:::adv
    GA2 --> GA5[🟣 ゲームAI×流体シミュレーション<br>学習型ソルバー知見の転用]:::adv

    JAM[実践] --> J1[🟢 ゲームジャム<br>SGJ2025 / AIGameJam]:::done
    JAM --> J2[🟢 チーム制作実習]:::done
    U3 --> J3[🟣 Steam第2作<br>流体/GPU技術を主役に]:::adv

    classDef done fill:#2e7d32,stroke:#1b5e20,stroke-width:2px,color:#ffffff,font-weight:bold
    classDef review fill:#f9a825,stroke:#e65100,stroke-width:2px,color:#000000,font-weight:bold
    classDef next fill:#1565c0,stroke:#0d47a1,stroke-width:2px,color:#ffffff,font-weight:bold
    classDef adv fill:#6a1b9a,stroke:#4a148c,stroke-width:2px,color:#ffffff,font-weight:bold
```

---

## 5. CG数学・物理・レンダリング

> 🕐 **時期:** 大学1年 基礎数学(2023) → 大学3年 ゲームプログラミング2で集中的に実装(2025)
> 🎨 **凡例:** 🟢習得済み ｜ 🟡復習 ｜ 🔵今後学ぶ ｜ 🟣応用発展

```mermaid
%%{init: {'themeVariables': {'primaryColor':'#37474f','primaryTextColor':'#ffffff','primaryBorderColor':'#263238','lineColor':'#78909c','fontSize':'16px'}}}%%
flowchart LR
    M[数学] --> M1[🟢 行列 / ベクトル<br>2D行列演算〜localSpace]:::done
    M --> M2[🟡 クォータニオン<br>使えるが言語化が課題]:::review
    M --> M3[🟢 補間<br>Interpolation課題]:::done

    AN[アニメーション] --> A1[🟢 スケルタル / スキニング<br>Siv3D FBX]:::done
    AN --> A2[🟢 IK<br>Ortho_bone / IK_Skin]:::done
    AN --> A3[🟢 モーションブレンド]:::done

    PH[物理 / 衝突] --> P1[🟢 OBB / カプセル衝突]:::done
    PH --> P2[🟢 剛体 RigidRect]:::done

    FX[エフェクト] --> E1[🟢 パーティクル / ビルボード]:::done

    R[レンダリング] --> R1[🟢 mini-renderer<br>CPU / GPU]:::done
    R1 --> R2[🟡 レンダリング理論の体系化<br>パイプライン全段を説明できるレベル]:::review
    R2 --> R3[🔵 パストレーシング / GI<br>PBRT系の自作実装]:::next
    R3 --> R4[🟣 ニューラルレンダリング<br>NeRF / 3DGS ← GNN経験と接続]:::adv
    R1 --> R5[🔵 DirectX12 / Vulkan<br>生APIでの理解]:::next

    classDef done fill:#2e7d32,stroke:#1b5e20,stroke-width:2px,color:#ffffff,font-weight:bold
    classDef review fill:#f9a825,stroke:#e65100,stroke-width:2px,color:#000000,font-weight:bold
    classDef next fill:#1565c0,stroke:#0d47a1,stroke-width:2px,color:#ffffff,font-weight:bold
    classDef adv fill:#6a1b9a,stroke:#4a148c,stroke-width:2px,color:#ffffff,font-weight:bold
```

---

## 6. シミュレーション・流体(最大の独自領域)

> 🕐 **時期:** 個人R&D 2024年〜現在(大学の授業外で継続開発)
> 🎨 **凡例:** 🟢習得済み ｜ 🟡復習 ｜ 🔵今後学ぶ ｜ 🟣応用発展

```mermaid
%%{init: {'themeVariables': {'primaryColor':'#37474f','primaryTextColor':'#ffffff','primaryBorderColor':'#263238','lineColor':'#78909c','fontSize':'16px'}}}%%
flowchart LR
    SOLV[ソルバー実装] --> S1[🟢 SPH<br>空間ハッシュ近傍探索]:::done
    SOLV --> S2[🟢 FLIP ハイブリッド]:::done
    SOLV --> S3[🟢 Stable Fluids 格子法]:::done
    SOLV --> S4[🟢 再現性保証<br>SHA-256状態ハッシュ]:::done

    RT[リアルタイム化] --> RT1[🟢 WASM SPH<br>ブラウザ実行]:::done
    RT1 --> RT2[🔵 GPU流体<br>Compute Shaderソルバー]:::next

    NN[Neural Fluid] --> N1[🟢 GNN v1-v3<br>1.13Mパラメータ 訓練済]:::done
    N1 --> N2[🟣 学習型ソルバーの実用化<br>推論高速化・蒸留]:::adv

    PIPE[パイプライン] --> PP1[🟢 Blender連携<br>NPZ / MCP]:::done
    PIPE --> PP2[🟢 Houdini HDA]:::done
    PP1 --> PP3[🔵 エンジン統合<br>VAT → Niagara / VFX Graph]:::next

    S1 --> ADV1[🟣 MPM / 煙・炎など他分野<br>ソルバー横展開]:::adv
    RT2 --> ADV2[🟣 Steam第2作 / デモ作品<br>リアルタイム流体を売りに]:::adv

    classDef done fill:#2e7d32,stroke:#1b5e20,stroke-width:2px,color:#ffffff,font-weight:bold
    classDef review fill:#f9a825,stroke:#e65100,stroke-width:2px,color:#000000,font-weight:bold
    classDef next fill:#1565c0,stroke:#0d47a1,stroke-width:2px,color:#ffffff,font-weight:bold
    classDef adv fill:#6a1b9a,stroke:#4a148c,stroke-width:2px,color:#ffffff,font-weight:bold
```

---

## 7. DCCツール・アート

> 🕐 **時期:** 高校 デジタル造形(C4D, 2023) → 個人制作で継続中(2023〜現在)
> 🎨 **凡例:** 🟢習得済み ｜ 🟡復習 ｜ 🔵今後学ぶ ｜ 🟣応用発展

```mermaid
%%{init: {'themeVariables': {'primaryColor':'#37474f','primaryTextColor':'#ffffff','primaryBorderColor':'#263238','lineColor':'#78909c','fontSize':'16px'}}}%%
flowchart LR
    DCC[3D DCC] --> B[🟢 Blender<br>MCP自動化・流体ビューア]:::done
    DCC --> H[🟢 Houdini<br>HDA・卒研RAG対象]:::done
    DCC --> C4[🟢 Cinema 4D<br>デジタル造形課題]:::done
    H --> H2[🔵 PDG / プロシージャル深化<br>パイプライン自動化]:::next
    B --> B2[🔵 ジオメトリノード]:::next

    ART[2Dアート] --> I1[🟢 Clip Studio<br>イラスト多数]:::done
    ART --> I2[🟢 Aseprite<br>ドット絵]:::done
    ART --> I3[🟢 ゲーム素材制作<br>ひび割れ・血痕等]:::done

    DCC --> X1[🟣 DCC間データ交換の設計<br>FBX / USD / Alembic]:::adv
    H2 --> X2[🟣 LLM×DCC自動化<br>卒研RAG MCPの発展形]:::adv

    classDef done fill:#2e7d32,stroke:#1b5e20,stroke-width:2px,color:#ffffff,font-weight:bold
    classDef review fill:#f9a825,stroke:#e65100,stroke-width:2px,color:#000000,font-weight:bold
    classDef next fill:#1565c0,stroke:#0d47a1,stroke-width:2px,color:#ffffff,font-weight:bold
    classDef adv fill:#6a1b9a,stroke:#4a148c,stroke-width:2px,color:#ffffff,font-weight:bold
```

---

## 8. AI・LLM・研究基盤

> 🕐 **時期:** 個人R&D 2024年〜、大学4年 卒業研究として集大成(2025-2026)
> 🎨 **凡例:** 🟢習得済み ｜ 🟡復習 ｜ 🔵今後学ぶ ｜ 🟣応用発展

```mermaid
%%{init: {'themeVariables': {'primaryColor':'#37474f','primaryTextColor':'#ffffff','primaryBorderColor':'#263238','lineColor':'#78909c','fontSize':'16px'}}}%%
flowchart LR
    RAG[RAG / 検索] --> R1[🟢 mcp-rag-server<br>ローカルRAG自作]:::done
    RAG --> R2[🟢 卒研: Houdini Help RAG<br>pgvector 7810ファイル]:::done
    RAG --> R3[🟢 Research-Collector<br>NotebookLM連携]:::done

    ML[機械学習] --> M1[🟢 GNN設計・訓練<br>AMP / CosineAnnealing]:::done
    ML --> M2[🟢 3D生成推論<br>TripoSR CAD→3D]:::done
    ML --> M3[🟢 音声認識組込み<br>Vosk]:::done

    LLMAPI[LLM活用] --> L1[🟢 MCPサーバー開発]:::done
    LLMAPI --> L2[🟢 Gemini Live API検証]:::done

    R2 --> F1[🔵 評価・検索精度改善<br>卒研の完成度向上]:::next
    L1 --> F2[🟣 制作支援エージェント<br>DCC操作×RAG×MCPの統合]:::adv
    M1 --> F3[🟣 ML for CG<br>Neural Fluid → NeRF/3DGS]:::adv

    classDef done fill:#2e7d32,stroke:#1b5e20,stroke-width:2px,color:#ffffff,font-weight:bold
    classDef review fill:#f9a825,stroke:#e65100,stroke-width:2px,color:#000000,font-weight:bold
    classDef next fill:#1565c0,stroke:#0d47a1,stroke-width:2px,color:#ffffff,font-weight:bold
    classDef adv fill:#6a1b9a,stroke:#4a148c,stroke-width:2px,color:#ffffff,font-weight:bold
```

---

## 9. ネットワーク・Web

> 🕐 **時期:** 高校 チャットアプリ実習(2022-2023) → 個人API開発で継続(2024〜)
> 🎨 **凡例:** 🟢習得済み ｜ 🟡復習 ｜ 🔵今後学ぶ ｜ 🟣応用発展

```mermaid
%%{init: {'themeVariables': {'primaryColor':'#37474f','primaryTextColor':'#ffffff','primaryBorderColor':'#263238','lineColor':'#78909c','fontSize':'16px'}}}%%
flowchart LR
    NET[ネットワーク] --> N1[🟢 TCPソケット通信<br>高校チャットアプリ]:::done
    NET --> N2[🟢 HTTP / API設計<br>api.py / serve.py]:::done
    N2 --> N3[🟡 通信の体系知識<br>プロトコル・暗号化の整理]:::review

    DB[データベース] --> D1[🟢 SQLite]:::done
    DB --> D2[🟢 PostgreSQL + pgvector]:::done
    DB --> D3[🟢 EntityFramework<br>高校課題研究]:::done

    WEB[Web制作] --> W1[🟢 静的サイト<br>web課題集〜miyagisite]:::done
    W1 --> W3[🔵 モダンフロントエンド<br>フレームワーク1つ]:::next
    N1 --> W4[🟣 マルチプレイヤーゲーム通信<br>チャット経験×ゲーム制作]:::adv

    classDef done fill:#2e7d32,stroke:#1b5e20,stroke-width:2px,color:#ffffff,font-weight:bold
    classDef review fill:#f9a825,stroke:#e65100,stroke-width:2px,color:#000000,font-weight:bold
    classDef next fill:#1565c0,stroke:#0d47a1,stroke-width:2px,color:#ffffff,font-weight:bold
    classDef adv fill:#6a1b9a,stroke:#4a148c,stroke-width:2px,color:#ffffff,font-weight:bold
```

---

## 10. 企画・チーム制作

> 🕐 **時期:** 大学1〜3年の授業・実習(2023-2025)
> 🎨 **凡例:** 🟢習得済み ｜ 🟡復習 ｜ 🔵今後学ぶ ｜ 🟣応用発展

```mermaid
%%{init: {'themeVariables': {'primaryColor':'#37474f','primaryTextColor':'#ffffff','primaryBorderColor':'#263238','lineColor':'#78909c','fontSize':'16px'}}}%%
flowchart LR
    PLAN[企画 / デザイン理論] --> P1[🟢 ゲーム構成論<br>メカニクス・バランス・世界観]:::done
    PLAN --> P2[🟢 企画発想法<br>マンダラ・チェックリスト法]:::done
    PLAN --> P3[🟢 コンテンツデザイン概論]:::done
    PLAN --> P4[🟢 エンタテインメント設計]:::done
    PLAN --> P5[🟢 インターフェースデザイン<br>UI/UX理論]:::done

    TEAM[チーム経験] --> T1[🟢 ゲーム制作技術総合実習]:::done
    TEAM --> T2[🟢 地域共創デザイン実習]:::done
    TEAM --> T3[🟢 ゲームジャム複数回]:::done
    TEAM --> T4[🟢 週報 / プロジェクト運営<br>3年制作応用実習]:::done
    TEAM --> T5[🟢 コンテンツ制作マネジメント<br>2年前期]:::done
    TEAM --> T6[🟢 チームワークとリーダーシップ<br>2年後期]:::done

    BIZ[ビジネス知識] --> BZ1[🟢 知的財産権 / 企業経営<br>グローバル市場化戦略]:::done

    T4 --> F1[🟡 進行管理の言語化<br>就活で語れる形に棚卸し]:::review
    P1 --> F2[🟣 技術主導の企画<br>R&D成果を企画に変換する型]:::adv

    classDef done fill:#2e7d32,stroke:#1b5e20,stroke-width:2px,color:#ffffff,font-weight:bold
    classDef review fill:#f9a825,stroke:#e65100,stroke-width:2px,color:#000000,font-weight:bold
    classDef next fill:#1565c0,stroke:#0d47a1,stroke-width:2px,color:#ffffff,font-weight:bold
    classDef adv fill:#6a1b9a,stroke:#4a148c,stroke-width:2px,color:#ffffff,font-weight:bold
```

---

## 今後の道筋(復習 → 学習 → 応用・発展)

> 🕐 **時期:** 2026年後半(卒業まで) → 2027年(深化) → 2028年〜(応用)を想定
> 🎨 **凡例:** 🟡復習(まず言語化) ｜ 🔵今後学ぶ(既存資産の延長) ｜ 🟣応用発展(掛け合わせ)
> 自分の実績の延長線だけで組んだ優先順位。

```mermaid
%%{init: {'themeVariables': {'primaryColor':'#37474f','primaryTextColor':'#ffffff','primaryBorderColor':'#263238','lineColor':'#78909c','fontSize':'16px'}}}%%
flowchart TB
    subgraph NOW["🟡 まず復習・言語化(卒研・就活と並行)"]
        Y1[クォータニオン・座標変換の言語化]:::review
        Y2[レンダリングパイプライン全段の整理<br>mini-rendererを教材化]:::review
        Y3[Unity描画・最適化知識の体系化<br>Steam開発の経験を棚卸し]:::review
    end

    subgraph NEXT["🔵 次に学ぶ(既存資産が伸びる方向)"]
        B1[GPU流体<br>Compute Shaderソルバー]:::next
        B2[パストレーシング自作<br>mini-renderer発展]:::next
        B3[VAT→Niagara/VFX Graph統合<br>UE再開]:::next
        B4[Houdini PDG / プロシージャル深化]:::next
    end

    subgraph ADV["🟣 応用・発展(掛け合わせで独自領域へ)"]
        P1[リアルタイム流体が主役の作品<br>Steam第2作 or 技術デモ]:::adv
        P2[ML for CG<br>Neural Fluid→NeRF/3DGS]:::adv
        P3[LLM×制作パイプライン<br>卒研RAG MCP→制作支援エージェント]:::adv
        P4[マルチプレイヤー通信<br>チャット経験×ゲーム]:::adv
    end

    Y2 --> B2
    Y3 --> B1
    B1 --> P1
    B2 --> P2
    B3 --> P1
    B4 --> P3

    classDef done fill:#2e7d32,stroke:#1b5e20,stroke-width:2px,color:#ffffff,font-weight:bold
    classDef review fill:#f9a825,stroke:#e65100,stroke-width:2px,color:#000000,font-weight:bold
    classDef next fill:#1565c0,stroke:#0d47a1,stroke-width:2px,color:#ffffff,font-weight:bold
    classDef adv fill:#6a1b9a,stroke:#4a148c,stroke-width:2px,color:#ffffff,font-weight:bold
    style NOW fill:#263238,stroke:#f9a825,stroke-width:2px,color:#ffffff
    style NEXT fill:#263238,stroke:#1565c0,stroke-width:2px,color:#ffffff
    style ADV fill:#263238,stroke:#6a1b9a,stroke-width:2px,color:#ffffff
```

### 制作ロードマップ(成果物ベース)

> 🕐 **時期:** 済(2024〜) → 2026年内(卒業) → 2027年(深化) → 2028年〜(応用作品)
> 🎨 **凡例:** 🟢習得済み(完了) ｜ 🟡復習中の成果物 ｜ 🔵次の制作 ｜ 🟣到達点

```mermaid
%%{init: {'themeVariables': {'primaryColor':'#37474f','primaryTextColor':'#ffffff','primaryBorderColor':'#263238','lineColor':'#78909c','fontSize':'16px'}}}%%
flowchart LR
    G0[🟢 済: Steam<br>Qualial Nature]:::done --> G1[卒業研究完成<br>Houdini RAG MCP]:::review
    G1 --> G2[GPU流体デモ<br>WASM版のCompute Shader移植]:::next
    G2 --> G3[流体×エンジン統合<br>FluidKit→VAT→Niagara]:::next
    G3 --> G4[リアルタイム流体作品<br>Steam第2作/技術デモリール]:::adv

    classDef done fill:#2e7d32,stroke:#1b5e20,stroke-width:2px,color:#ffffff,font-weight:bold
    classDef review fill:#f9a825,stroke:#e65100,stroke-width:2px,color:#000000,font-weight:bold
    classDef next fill:#1565c0,stroke:#0d47a1,stroke-width:2px,color:#ffffff,font-weight:bold
    classDef adv fill:#6a1b9a,stroke:#4a148c,stroke-width:2px,color:#ffffff,font-weight:bold
```

---

## まとめ

- **一貫した軸**: 「動くものを作りながら低レイヤーへ潜る」— 高校: 組込み(Raspberry Pi)/アプリ(C#) → 大学: ゲームフルスクラッチ → 3D数学・ハードウェア理論 → 自作ソルバー/レンダラー → ML
- **他人と被らない資産**: ①自作流体エンジン一式(SPH/FLIP/GNN/WASM) ②LLM/RAG/MCP基盤 ③Steamリリース実績 ④高校由来の組込み/ハードウェア知識(電子情報工学概論・ゲームハード概論と地続き)。今後はこれらの**掛け合わせ**(リアルタイム流体作品、ML for CG、エッジAI、制作支援エージェント)が最も費用対効果が高い
- **弱点は「新技術」ではなく「言語化」**: 実装済みのものを説明できる形に整理することが、就活期の最優先タスク



