# NOTE GROWTH Dashboard

初版のローカルWebアプリです。

## 使い方
1. `index.html` をダブルクリックしてブラウザで開きます。
2. 月を選び、YouTube / Instagram / X / Substack / note の数字を入力します。
3. 「保存」を押すと、ブラウザ内（localStorage）に保存されます。
4. 月を切り替えると前月比が表示されます。
5. 「AI分析用」タブの文章をChatGPTやClaudeに貼り付けて分析できます。
6. 「JSONを書き出す」でバックアップできます。

## 初期データ
添付Excel `SNS_note_分析シート_入力済 (10).xlsx` から、2026年9月の入力済み範囲を反映しています。
- note記事: 21本
- note累計PV: 1,099
- noteスキ: 35
- YouTube: 1投稿 / 120表示・再生 / 5反応 / note流入1

## 次の開発候補
- YouTube Data API / Analytics APIとの自動連携
- Instagram / X / Substack の取得方式を各公式仕様に合わせて追加
- note流入用の計測リンク
- OpenAI API / Anthropic APIを組み込んだ自動月次分析
- クラウドDB化（Supabase等）
