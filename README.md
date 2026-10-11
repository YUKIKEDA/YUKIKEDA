# Hi, I'm YUKIKEDA 👋

Rust / C# / Python で、数値計算・科学計算、デスクトップアプリ、グラフィックス周辺のツールを作っています。
実務で困ったことや、既存のツールに足りないものを、ライブラリやアプリとして形にするのが好きです。

## 🧰 Tech Stack

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://skillicons.dev/icons?i=rust,cs,py,cpp,c,dart,flutter,ts&theme=dark">
  <img alt="Rust, C#, Python, C++, C, Dart, Flutter, TypeScript" src="https://skillicons.dev/icons?i=rust,cs,py,cpp,c,dart,flutter,ts&theme=light">
</picture>

## 🔬 Numerical & Scientific Computing

- [convx](https://github.com/YUKIKEDA/convx)(開発中): Rust の幾何計算ライブラリ。Qhull に相当する Rust 実装が見当たらないので作っています。
- [interpx](https://github.com/YUKIKEDA/interpx)(開発中): Rust の補間ライブラリ。SciPy の `LinearNDInterpolator` のような補間を Rust から使えるようにします。
- [gprx](https://github.com/YUKIKEDA/gprx): Rust のガウス過程回帰ライブラリ。実務で GPR ライブラリを扱った経験をもとに、高速で拡張しやすい作りを目指しました。
- [trumpet-morphing](https://github.com/YUKIKEDA/trumpet-morphing): トランペットの形状をモーフィングして、CAE のサロゲート学習用データセットを生成します。
- [SimpleLinearNDInterpolator](https://github.com/YUKIKEDA/SimpleLinearNDInterpolator): Qhull を使った、C++ の N 次元線形補間ライブラリ。

## 🧱 Libraries from Real-World Problems

- [Graft](https://github.com/YUKIKEDA/Graft): WPF アプリ向けの E2E テストフレームワーク。テスト対象のアプリにエージェントを組み込み、ビジュアルツリーを直接読みます。E2E テストを AI エージェントで自動化したくて作りました。
- [Txfio](https://github.com/YUKIKEDA/Txfio): 共有フォルダ上のファイルを、コミットするまで元のファイルに触れずに書ける C# のライブラリ。クラッシュ後の復旧にも対応します。
- [AgentBridge](https://github.com/YUKIKEDA/AgentBridge): クラウド LLM の Tool Use を、.NET のデスクトップアプリに組み込むためのライブラリ。
- AuraORM(非公開・公開準備中): DrizzleORM のような軽量さで、NativeAOT でコンパイルできる C# の ORM。ほぼ書き終えたので、コードを整理しているところです。

## 🖥️ Desktop Apps

- [meshpad](https://github.com/YUKIKEDA/meshpad): Nastran と STL のファイルを、メモ帳のように素早く開くビューア。Windows 標準の STL ビューアが遅かったので作りました。
- [GIMgr](https://github.com/YUKIKEDA/GIMgr)(開発中): Tauri 製の、画像生成 AI で作った画像の管理アプリ。動きますが、不具合と機能不足が残っています。
- [flgantt](https://github.com/YUKIKEDA/flgantt)(学習): Flutter とレイヤードアーキテクチャを学ぶために作った、デスクトップ向けのガントチャート。
- wayfinder(非公開・開発中): Windows エクスプローラーの操作性に不満があって作っている、Rust 製のファイラー。
- NasCC(非公開・開発中): データを NAS に置き、手元のストレージをキャッシュとして使うためのクライアントアプリ。

## 📝 Others

- [agent-workflow](https://github.com/YUKIKEDA/agent-workflow): Cursor 向けの、開発ループ用 Agent Skills のパック。
- [DesktopAppComparison](https://github.com/YUKIKEDA/DesktopAppComparison): デスクトップアプリのフレームワークについて、リソース消費をベンチマークで比べた検証用リポジトリ。
- `GuideFor〜` のリポジトリは、学習のために AI で生成したドキュメントです。

WPF のカスタムコントロール、OxyPlot の拡張、DiffRasterCpp(Rust で書き直す予定)、github-project-metrics などは、整理して公開できる形にしたいと考えています。

## 📊 GitHub Stats

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api/top-langs/?username=YUKIKEDA&layout=compact&theme=dark">
  <img alt="Top Languages" src="https://github-readme-stats.vercel.app/api/top-langs/?username=YUKIKEDA&layout=compact">
</picture>
