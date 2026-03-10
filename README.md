# OSS License Simple Viewer (HTML Version)

## [日本語]

本プロジェクトは、トヨタ自動車および日立ソリューションズによって開発された [OSS License Simple Viewer (Excel版)](https://github.com/OLSV-oss/OSSLicenseSimpleViewer) の設計思想と判定ロジックをベースに、HTML/JavaScript環境向けに **再構成 (Reconstructed)** したツールです。  
日立製作所の [open-license](https://github.com/Hitachi/open-license) プロジェクトが提供するJSONデータを活用し、ブラウザ上で手軽にライセンス義務や免責事項を確認できます。

### ✨ 主な機能

* **Web UI**: インストールや専用ソフトは不要。ブラウザとJSONファイルがあれば動作します。
* **ユースケースフィルタ**:
  * 「頒布（配布）の有無」および「頒布形式（ソース/バイナリ）」による絞り込み機能を搭載。
  * アクション文中の助詞（「～から」「～を」など）を判定し、複雑なユースケースを自動的に分類・抽出します。

### ⚠️ 制約事項と免責事項

**ご利用の前に必ずお読みください：**

1. **フィルタ判定の限界**: 本ツールにおける「頒布形式」の自動フィルタリング機能は**暫定的な実装**です。日本語の表現や文脈によっては、期待とは異なるフィルタ結果になる可能性があります（表示されるべき項目が非表示になる、あるいはその逆など）。
2. **無保証 (No Warranty)**: 本ソフトウェアは「現状のまま」提供され、いかなる種類の保証も行いません。作者は、本ソフトウェアの使用に関連して生じた損害（ライセンス違反、法的紛争、業務上の損失等を含むがこれらに限定されない）について、一切の責任を負いません。
3. **最終判断の必要性**: 本ツールはライセンス・コンプライアンスの補助を目的としたものであり、法的な助言ではありません。最終的な判断にあたっては、必ずライセンス原文を確認し、必要に応じて法務専門家に相談してください。

### 🚀 使い方

1. [open-license](https://github.com/Hitachi/open-license) から `actions.json`, `conditions.json`, `licenses.json`, `notices.json` を入手します。
2. `OSSLicenseSimpleViewer.html` をブラウザで開き、上記4ファイルを一括読み込みします。
3. ライセンスとユースケースを選択して、適用される義務や免責事項を確認します。

### 📜 ライセンス / Licenses

本ソフトウェアは以下のデュアルライセンスです：

* **MIT License**
* **The Beer-ware License (Revision 42)**

詳細はルートディレクトリの `LICENSE` ファイルを参照してください。

### 🙏 謝辞 / Acknowledgments

* **Original Concept**: [OSSLicenseSimpleViewer](https://github.com/OLSV-oss/OSSLicenseSimpleViewer) (Toyota Motor Corporation / Hitachi Solutions, Ltd.)
  * 本ツールは、オリジナル版のロジックをAIによって解析・再構成した派生作品です。オリジナル版の著作権表示およびライセンス全文は `original_license/` ディレクトリに保持されています。
* **Data Source**: [open-license](https://github.com/Hitachi/open-license) (Hitachi, Ltd.)

---

## [English]

This project is a **reconstruction** of the [OSS License Simple Viewer (Excel version)](https://github.com/OLSV-oss/OSSLicenseSimpleViewer) for HTML/JavaScript, inheriting its design philosophy and logic. The original version was developed by Toyota Motor Corporation and Hitachi Solutions, Ltd.  
It utilizes JSON data from Hitachi's [open-license](https://github.com/Hitachi/open-license) project to allow easy checking of license conditions in a web browser.

### ✨ Features

* **Web UI**: No installation or dedicated software required. Works with just a browser and JSON files.
* **Use-case Filter**:
  * Filters by "Distribution (Yes/No)" and "Distribution Format (Source/Binary)."
  * Analyzes Japanese particles (e.g., "from," "the") in action descriptions to automatically classify and extract complex use-cases.

### ⚠️ Disclaimer and Limitations

**Please read the following carefully before use:**

1. **Filtering Limitations**: The automatic filtering by "Distribution Format" is a **provisional implementation**. Depending on the phrasing or context, the filter results may not be as expected (e.g., items that should be displayed may be hidden, or vice versa).
2. **No Warranty**: This software is provided "as is" without warranty of any kind. The author shall not be liable for any damages arising out of or in connection with the use of this software (including, but not limited to, license violations, legal disputes, or business losses).
3. **Requirement for Final Judgment**: This tool is intended to assist with license compliance and does not constitute legal advice. For final judgment on distribution terms, always refer to the original license text and consult with legal professionals as needed.

### 🚀 Usage

1. Obtain `actions.json`, `conditions.json`, `licenses.json`, and `notices.json` from [open-license](https://github.com/Hitachi/open-license).
2. Open `OSSLicenseSimpleViewer.html` in a browser and load these four JSON files together.
3. Select a license and use-case to review the applicable obligations and disclaimers.

### 📜 Licenses

This software is released under a dual license:

* **MIT License**
* **The Beer-ware License (Revision 42)**

See the `LICENSE` file for details.

### 🙏 Acknowledgments

* **Original Concept**: [OSSLicenseSimpleViewer](https://github.com/OLSV-oss/OSSLicenseSimpleViewer) (Toyota Motor Corporation / Hitachi Solutions, Ltd.)
  * This tool is a derivative work reconstructed using AI based on the original logic. Original license terms and copyright notices are maintained in the `original_license/` directory.
* **Data Source**: [open-license](https://github.com/Hitachi/open-license) (Hitachi, Ltd.)
