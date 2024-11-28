# nlp2025-template_v1.zip 内のファイル

Latex版
 nlp2025.cls: latex用の文書クラス
 nlp2025-sample.tex: 原稿執筆インストラクション，および，latex用のサンプル原稿
 nlp2025-sample.pdf: nlp2025-sample.texをPDF化したもの
 j_yourrefs.bib: サンプルbibファイル

Word版
 nlp2025-wordsample.doc: Word用のサンプル原稿 (可能な限り.docxの利用を推奨）
 nlp2025-wordsample.docx: Word用のサンプル原稿 
 nlp2025-wordsample.pdf: nlp2025-wordsample.docxをPDF化したもの

参考ファイル
 LICENSE: nlp2025.cls のライセンス条項
 latexmkrc: Overleafの日本語化用設定ファイルのサンプル
 README-latex.md: nlp2025.cls に関する説明文書
 README.txt: このファイル


更新履歴

* v2025.1_0 2024.10.29: 2025年度初期バージョン

* v2024.1_0 2023.11.8: 2024年度初期バージョン

* v2023.1_0 2022.11.7: 2023年度初期バージョン

* v2022.1_1 2021.12.25: 
 - 英語対応版(English オプション)利用時の「概要」の表記を「Abstract」に変更

* v2022.1_0 2021.12.7: 2022年度版初期バージョン
 - 概要（新要素）に関する説明の追記
 - 多書体化のために jlreq-deluxe を導入
 - 謝辞を参考文献のページに含めてよい（本文とみなさない）ことの仕様変更に関する説明を追記

* v2021.3 2020.12.22:
 - latex版の参考文献のフォントサイズ指定方法の変更
 - natbibの廃止(挙動の制御が難しいため)
 - 参考文献のフォントサイズの設定コマンドを追加
   - 例：\renewcommand{\bibfont}{\footnotesize} 


* v2021.2 2020.12.18: 
 - english オプションの追加


* v2021.1 2020.12.3: 
 - 参考文献の例を \bibliographystyle{unsrt} => \bibliographystyle{junsrt} に変更
 - nlp2021-sample.tex 内の文言を一部修正（規定には影響なし）


* v20201.0 2020.12.1: 初期バージョン
