# 📈 管理図（Control Chart）教材

本フォルダでは、QC七つ道具の一つである **管理図（Control Chart）** の教材とテンプレートを提供します。

管理図は、**工程の安定性や異常の兆候を把握するための重要な手法**であり、品質管理・統計的プロセス管理（SPC）に広く利用されます。

---

## 📌 管理図とは？

- 測定データの時系列変動をグラフ化し、**管理限界（UCL/LCL）**と照らして異常の有無を判断する図。
- 工程が「統計的に安定しているかどうか」を継続的に監視可能。
- X̄-R 管理図、p管理図、np管理図、u管理図、c管理図など、データ種類に応じた複数形式があります。

---

## 🛠️ 活用場面の例

| 活用シーン | 具体例 |
|------------|--------|
| 寸法管理 | 加工寸法のばらつきを日々記録し、外れ値や傾向を監視 |
| 工程監視 | 生産ラインの品質を定期チェックし、変動の要因を特定 |
| 校正業務 | 測定器の経時変化を管理図で可視化して校正周期判断に活用 |
| 再発防止 | 是正後の効果を継続的にモニタリングして再発防止を図る |

---

## 📁 ファイル構成

```plaintext
control_chart/
├── samples/                       # サンプル教材（PNG / Excel / Markdown）
│   ├── xbar_r_example.md          # X̄-R管理図の例（Mermaid）
│   └── control_chart_sample.xlsx  # Excelによる実データグラフ
├── templates/                     # 汎用テンプレート（Excel / CSV）
│   └── control_chart_template.xlsx
└── README.md                      # このファイル
```

### 🔗 各ファイルへのリンク

- 📄 Mermaid記法例: [`samples/xbar_r_example.md`](samples/xbar_r_example.md)  
- 📊 Excelによるサンプル管理図: [`samples/control_chart_sample.xlsx`](samples/control_chart_sample.xlsx)  
- 📝 記入用テンプレート: [`templates/control_chart_template.xlsx`](templates/control_chart_template.xlsx)  

---

## 📊 管理図の基本構成

```
    ↑
値  │                        上側管理限界（UCL）
    │        ●      ●  ●
    │     ●     ●
    │--------- 中央線（CL）
    │   ●               ●
    │        ●              ●
    │                        下側管理限界（LCL）
    └────────────────────→ 時間・ロット
```

> 📌 管理限界は「±3σ」を基準とするのが一般的です。

---

## 💡 Mermaidで描く簡易管理図（イメージ）

```mermaid
%% 簡易的な管理図（概念イメージ）
line
    title 管理図の例（簡略表示）
    x-axis ロット番号
    y-axis 寸法値
    "ロット1" : 9.98
    "ロット2" : 10.01
    "ロット3" : 10.05
    "ロット4" : 10.10
    "ロット5" : 10.08
    "ロット6" : 9.97
```

> ✳ Mermaidでは本格的な管理限界の描画は難しいため、Excelとの併用を推奨します。

---

## 🔗 関連教材リンク

- [`../`](../)：QC七つ道具のトップフォルダ  
- [`../../iso9001/`](../../iso9001/)：校正や是正後の効果監視に利用  
- [`../../training/`](../../training/)：SPC訓練や品質教育の一部として展開  

---

## 🧠 学習活用のヒント

- Excelで簡単なX̄-R管理図を描けるテンプレートを活用することで、現場応用が加速します。
- 工程能力指数（Cp, Cpk）との連携も学習対象に含めると、実務力が高まります。

---

## 📜 ライセンス

MIT License © 2025 Shinichi Samizo / Samizo-AITL
