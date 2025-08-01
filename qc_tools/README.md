# 🛠️ QCツール教材集 / QC Seven Tools Materials

本フォルダは、品質管理の基礎として広く用いられる **QC七つ道具** および拡張ツール（FMEA等）を学習・実践するための教材・図例・テンプレートを収録しています。

QCツールは、問題解決・工程改善・是正処置など、**ISO 9001や教育訓練の現場**でも活用可能です。

---

## 📦 収録予定のQCツール一覧

| ツール名         | 説明例 | リンク |
|------------------|--------|--------|
| パレート図       | 不良・原因の優先順位を視覚化し、重要項目を特定 | [📁 pareto](./pareto/) |
| 特性要因図       | 問題の「なぜ」を洗い出すフィッシュボーン図（因果関係分析） | [📁 cause_effect](./cause_effect/) |
| 管理図           | 工程の安定性や異常傾向を把握する折れ線グラフ | [📁 control_chart](./control_chart/) |
| チェックシート   | データの記録・分類を容易にする記入用テンプレート | [📁 check_sheet](./check_sheet/) |
| ヒストグラム     | 測定値やばらつきの分布を視覚的に分析 | [📁 histogram](./histogram/) |
| 散布図           | 2変数の相関関係を視覚化し、因果関係を探索 | [📁 scatter_plot](./scatter_plot/) |
| 層別             | データをグループごとに分けて分析する手法（例：班・ライン別） | [📁 stratification](./stratification/) |
| FMEA             | 故障モードごとに影響度を評価し、リスクの優先度に基づく対策を決定 | [📁 fmea](./fmea/) |

> 📁 各ツールは Markdown、Mermaid、Excel テンプレートで提供予定です。

---

## 📁 ディレクトリ構成

```plaintext
qc_tools/
├── pareto/             # パレート図教材・テンプレート
├── cause_effect/       # 特性要因図（フィッシュボーン）
├── control_chart/      # 管理図テンプレート
├── check_sheet/        # チェックシート例
├── histogram/          # ヒストグラム教材
├── scatter_plot/       # 散布図サンプル
├── stratification/     # 層別の手法と事例
├── fmea/               # FMEA（故障モード影響解析）教材
└── README.md           # このファイル
```

---

## 🔗 他教材との接続

- [`iso9001/`](../iso9001/)：是正処置・内部監査でのツール活用事例に接続
- [`training/`](../training/)：品質教育や新入社員訓練での基礎教材として活用
- [`mermaid_diagrams/`](../mermaid_diagrams/)：一部ツールの構造可視化をMermaidで図示

---

## 🧠 学習活用のヒント

- Mermaid記法やExcelで視覚化し、PDCAや教育訓練と連動させましょう。
- 各ツールに「使いどころ」や「分析の流れ」も記載することで、実務応用力が高まります。
- FMEAは設計・製造・サービスの各段階での**リスクマネジメント教育**に最適です。

---

## 📜 ライセンス

MIT License © 2025 Shinichi Samizo / Samizo-AITL
