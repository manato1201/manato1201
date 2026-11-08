# 松浦真聖 / manato1201

動くものを作りながら、低レイヤーへ潜る。
流体・レンダリング・RAG・開発支援ツールを、一人で設計して実装しています。

<p align="left">
  <a href="https://github.com/manato1201"><img height="20" src="https://komarev.com/ghpvc/?username=manato1201" alt="views" /></a>
  <a href="https://github.com/manato1201?tab=followers"><img height="20" src="https://img.shields.io/github/followers/manato1201?label=follow&logo=github&style=flat" alt="followers" /></a>
</p>

![](https://raw.githubusercontent.com/manato1201/manato1201/output/github-contribution-grid-snake.svg)

## 主要制作物

### 卒業研究
| 制作物 | ひとこと |
|---|---|
| [DevelopmentRAGEnvironment](https://github.com/manato1201/DevelopmentRAGEnvironment) | RAG を用いた**動的チュートリアル生成**(Houdini) |

### アプリ・Web
| 制作物 | ひとこと |
|---|---|
| [LoreDesktopAndWebSystem](https://github.com/manato1201/LoreDesktopAndWebSystem) ・ [demo](https://lore-desktop-and-web-system.vercel.app) | Lore の GUI(Web + Qt)と Rust 製 API |
| [The-Algorithm-Illustrated](https://github.com/manato1201/The-Algorithm-Illustrated) ・ [demo](https://the-algorithm-illustrated.vercel.app) | アルゴリズムの図鑑 |
| [ColorEncyclopedia](https://github.com/manato1201/ColorEncyclopedia) ・ [demo](https://color-encyclopedia.vercel.app) | 色彩検定対策を兼ねた色・図形の図鑑 |
| [FoundationsEncyclopedia](https://github.com/manato1201/FoundationsEncyclopedia) ・ [demo](https://foundations-encyclopedia.vercel.app) | 言語・IT・AI の基礎の図鑑 |
| [WeatherGeoBridge](https://github.com/manato1201/WeatherGeoBridge) ・ [demo](https://weathergeobridge.vercel.app) | 天気と地図のダッシュボード(Vercel + Cloudflare Workers) |
| [miyagisite](https://github.com/manato1201/miyagisite) ・ [demo](https://miyagisite.vercel.app) | Next.js で作った Web サイト |

### 補助ツール
| 制作物 | ひとこと |
|---|---|
| [Research-Collector](https://manato1201.github.io/Research-Collector/) | 研究情報の自動収集(NotebookLM 連携) |
| [CADGPUInferenceModeling](https://manato1201.github.io/CADGPUInferenceModeling/) | CAD から 3D を推論(TripoSR) |
| [AssetDataInsightSuite](https://github.com/manato1201/AssetDataInsightSuite) | アセット品質の取込・検出・可視化 |
| [VisualRegressionQATool](https://github.com/manato1201/VisualRegressionQATool) | スクリーンショット差分による QA |
| [ToolOrchestrationHub](https://github.com/manato1201/ToolOrchestrationHub) | ツール群の死活監視とアラートの集約 |
| [FlowchartVisualizerExtension](https://github.com/manato1201/FlowchartVisualizerExtension) | 制御フローを可視化する IDE 拡張(VSCode / Visual Studio / Rider) |
| [MagicCircleGenerator](https://github.com/manato1201/MagicCircleGenerator) | 魔法陣を動的に生成(TypeScript) |
| [DocsPipeline](https://github.com/manato1201/DocsPipeline) | docstring から API 文書を作り Confluence へ(Sphinx) |
| [ProductionTracker](https://github.com/manato1201/ProductionTracker) | 制作進行ボード(Django + React) |

### 学習成果物
| 制作物 | ひとこと |
|---|---|
| [LearningFluidEngine](https://github.com/manato1201/LearningFluidEngine) | 流体エンジン(SPH / FLIP / GNN / WASM) |
| [LearningQuickDraw](https://github.com/manato1201/LearningQuickDraw) | ミニレンダラー(C++ / SDL2)と DCC 連携 |
| [RAGReel](https://github.com/manato1201/RAGReel)(旧 LearningQt) | RAG の回答からチュートリアル動画を作る(Qt / FFmpeg) |
| [VLMAutoReplayTool](https://github.com/manato1201/VLMAutoReplayTool) | VLM でゲームを自動プレイするエージェント |
| [PracticeGameAII](https://github.com/manato1201/PracticeGameAII) ・ [PracticeGameAI3](https://github.com/manato1201/PracticeGameAI3) | ゲーム AI の学習(経路探索の 3D ゲームなど) |
| [UnityHDRPBlackHole](https://github.com/manato1201/UnityHDRPBlackHole) ・ [SpringWorks](https://github.com/manato1201/SpringWorks) | Unity のレンダリング・シェーダーの探求 |

### ゲーム
| 制作物 | ひとこと |
|---|---|
| [piece-peace](https://github.com/manato1201/piece-peace) | ゲーム依存症対策のシリアスゲーム(チーム 6 名・framework 層を担当) |
| [JunkShooting](https://github.com/manato1201/JunkShooting) | 音声認識つきのシューティング(C++ / Python・個人) |
| [AdvancedVAT](https://github.com/manato1201/AdvancedVAT) | 音声解析に反応する VAT の表現(C++ / HLSL・個人) |
| [uketorikatatoraekata](https://github.com/manato1201/uketorikatatoraekata) | 錯視・錯聴をテーマにした 2D アクション |
| [AIGameJam_1](https://github.com/manato1201/AIGameJam_1) ・ [UnityGameJam_B](https://github.com/manato1201/UnityGameJam_B) | ゲームジャムの作品 |

## 構成図

### 卒業研究: RAG を用いた動的チュートリアル生成
Houdini の公式ドキュメントを Cloudflare に索引し、Houdini パネルが検索と Claude でチュートリアルを作り、RAGReel が動画にします。

![卒業研究の全体構成](assets/diagrams/thesis-rag.svg)

<details>
<summary><b>Lore Ecosystem</b> — Web と Qt クライアントが同じ Rust API を使う</summary>

![Lore Ecosystem の構成](assets/diagrams/lore-ecosystem.svg)

</details>

<details>
<summary><b>開発支援ツール</b> — 検証・可視化の結果を Hub が集める</summary>

![開発支援ツールの構成](assets/diagrams/devtools-pipeline.svg)

</details>

## ロードマップ

学習・制作の全体(11 カテゴリ・151 項目)は **[ROADMAP.md](ROADMAP.md)** にまとめています。

| | 🟢 習得済み | 🟡 復習 | 🔵 今後学ぶ | 🟣 応用・発展 |
|---|---:|---:|---:|---:|
| 項目数 | 104 | 12 | 17 | 18 |

![今後の道筋](assets/diagrams/roadmap.svg)

## 技術

<img alt="skills" src="https://skillicons.dev/icons?theme=dark&perline=10&i=c,cpp,cs,py,ts,rust,nextjs,qt,cloudflare,vercel,docker,opencv,raspberrypi" />
<img alt="tools" src="https://skillicons.dev/icons?theme=dark&perline=10&i=github,visualstudio,vscode,rider,unity,blender" />
<img alt="learning" src="https://skillicons.dev/icons?theme=dark&perline=10&i=unreal" />

<details>
<summary>GitHub の統計</summary>

![](https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=manato1201&theme=gruvbox)
![](https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=manato1201&theme=gruvbox)
![](https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=manato1201&theme=gruvbox)
![](https://github-profile-summary-cards.vercel.app/api/cards/stats?username=manato1201&theme=gruvbox)
![](https://github-profile-summary-cards.vercel.app/api/cards/productive-time?username=manato1201&theme=gruvbox&utcOffset=9)

</details>
