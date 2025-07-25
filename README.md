# 🎓 EduLms - 統合型学習管理システム：体系的な教育と品質実践のために

**EduLms** は、ISO 9001 / ISO 14001 に基づく品質・環境教育をはじめ、QCツール、教育訓練、FSMプロセス可視化を統合した  
**教育の再利用 × 記録テンプレート × プロセス管理の見える化** を支援する、軽量かつ構造的な **LMS（Learning Management System）教材リポジトリ** です。

> 🇯🇵 このページは日本語版です ｜ 🇺🇸 [English version available here](./README_en.md)

---

### 💡 **LMSとは？**

**LMS（Learning Management System）** は、単なる教育訓練の実施ではなく、  
**教材の構成管理・訓練計画・力量記録・進捗評価** を包括する「学習の設計と運用基盤」です。  
EduLmsでは、これを **Markdown × Git × Mermaid** により構造的に表現・運用します。

---

## 📦 主な機能 / Features

- ✅ ISO 9001:2015 / ISO 14001:2015 に準拠した教材テンプレート  
- ✅ 教育訓練（7.2）・認識向上（7.3）・力量トレーサビリティの整備  
- ✅ PDCA管理テンプレート、監査・是正・校正のFSMプロセス可視化  
- ✅ Edusemi / EduMecha / EduController との再利用可能な教材連携  
- ✅ Git + Mermaid + Markdown によるバージョン管理と学習ログの記録  

---

## 📁 ディレクトリ構成

```plaintext
EduLms/
├── iso9001/              # 品質管理：PDCA、是正、校正、監査 等
├── iso14001/             # 環境管理：リスク・機会、法令順守、環境方針
├── training/             # 教育訓練・認識向上・力量記録
├── qc_tools/             # QC七つ道具（パレート図・管理図・特性要因図 等）
├── templates/            # 各種記録テンプレート・様式・PDCA管理票
├── mermaid_diagrams/     # FSM図・PDCAフローなど構造可視化ファイル群
└── ref_links/            # 他教材（Edusemi等）との接続・再利用記録
```

---

## 📂 フォルダ別リンク一覧 / Directory Links

| フォルダ名         | 内容                                       | リンク                         |
|--------------------|--------------------------------------------|------------------------------|
| `iso9001/`         | 品質管理教材（PDCA、是正、校正、監査）     | [📁 iso9001](./iso9001/)     |
| `iso14001/`        | 環境管理教材（環境方針、法令順守、リスク） | [📁 iso14001](./iso14001/)   |
| `training/`        | 教育訓練、力量評価、認識向上の教材         | [📁 training](./training/)   |
| `qc_tools/`        | QC七つ道具（パレート図、ヒストグラム 等） | [📁 qc_tools](./qc_tools/)   |
| `templates/`       | 様式テンプレート（PDCA記録、文書管理）     | [📁 templates](./templates/) |
| `mermaid_diagrams/`| FSM・PDCA・訓練フロー等の構造可視化        | [📁 mermaid_diagrams](./mermaid_diagrams/) |
| `ref_links/`       | 他教材とのリンク記録（Edusemi等）          | [📁 ref_links](./ref_links/) |

---

## 🔗 関連プロジェクト / Related Projects

| プロジェクト名 | 内容                                                         |
|----------------|--------------------------------------------------------------|
| [Edusemi-v4x](https://github.com/samizo-aitl/Edusemi-v4x)       | 半導体・材料工学の教育教材（品質管理との連携）          |
| [EduMecha](https://github.com/samizo-aitl/EduMecha)             | 測定・構造設計教育教材（校正、図面との接続）            |
| [EduController](https://github.com/samizo-aitl/EduController)   | FSM制御・AI訓練教材（プロセス管理と教育訓練の統合）     |

---

## 🧠 教育 × 構造設計の統合戦略

- **FSMによる可視化**：訓練・監査・校正などのプロセスを状態遷移で表現  
- **双方向教材リンク**：Edusemiや他教材と `ref_links/` 経由で再利用接続  
- **PDCA管理テンプレ**：是正・予防・文書改訂・力量再評価を一元管理  

---

## 📜 ライセンス / License

MIT License  
Copyright (c) 2025  
**Shinichi Samizo / Samizo-AITL**

---

## 👤 **執筆者情報 / Author**

**三溝 真一（Shinichi Samizo）**  
- **信州大学大学院 電気電子工学 修了**  
- 元 **セイコーエプソン**株式会社 技術者（1997年〜）

📌 **経験領域**：  
- **半導体デバイス（ロジック・メモリ・高耐圧混載）**  
- **インクジェット薄膜ピエゾアクチュエータ**  
- **PrecisionCoreプリントヘッド製品化・BOM管理・ISO教育**

📬 **連絡先**  
- ✉️ [shin3t72@gmail.com](mailto:shin3t72@gmail.com)  
- 🐦 [https://x.com/shin3t72](https://x.com/shin3t72)  
- 💻 [https://samizo-aitl.github.io/](https://samizo-aitl.github.io/)

---

## 💬 フィードバック募集 / We Welcome Your Feedback

**EduLms** は、教育訓練・品質管理・構造的教材管理の現場実装を支援することを目的としています。  
以下のような内容について、ご意見・ご要望を歓迎します：

- 教育訓練・監査・校正現場での具体的な活用方法  
- テンプレートやFSM図の改善提案  
- Edusemi・EduController 等との連携拡張要望  
- GitHub Pages活用や教材の構成運用に関するご相談  

👉 コメント・提案は以下の Discussion スレッドへどうぞ：  
[Discussions フィードバックスレッド](https://github.com/Samizo-AITL/EduLms/discussions)

皆さまのご意見を、教材品質の向上に活かしてまいります。

---
