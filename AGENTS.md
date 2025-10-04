# site-jinguji.me 向け共通指示 (2025-10-04)

- ヘッダーとフッターは Jekyll の include で共通化し、ビルド後の HTML は既存デザインを崩さないこと。
- フレームワークとして PicoCSS を読み込み、外部ライブラリを追加する場合はユーザー承認を取ること。
- 英語ページのブランド表記は `AKIRA JINGUJI` のみ、日本語ページは `神宮司明良 (AKIRA JINGUJI)` とする。
- ヒーローセクションの本文やプロフィール文は左寄せで段落幅いっぱいに表示されるよう `text-align: justify; text-align-last: left;` を維持する。
- ポートフォリオ欄のリンクラベルは「本サイト」「(株)スパイスエンジン」「シーシャ大学」「とうみん工業大学」の順序で固定する。
- 変更をプッシュした後は GitHub Actions の "pages build and deployment" 実行結果を必ず確認する。
