# itinerary

旅程しおりのアーカイブ。GitHub Pages で公開し、`index.html` から各旅程へリンクする構成。

## 公開URL

- トップ（一覧）: `https://katzeallergie.github.io/itinerary/`
- クリスマス旅行: `https://katzeallergie.github.io/itinerary/trips/2026-12-christmas-europe/`
- イタリア旅行: `https://katzeallergie.github.io/itinerary/trips/2026-04-italy/`

## 新しい旅程を追加する手順

1. `trips/` の下に新しいフォルダを作る（例: `trips/2027-04-italy/`）
2. その中に `index.html` としてしおりのHTMLファイルを置く
3. ルートの `index.html` を開き、`<!-- 新しい旅程を追加する場合は... -->` のコメント直後に
   `<a class="trip">` ブロックをコピーして追加（日付・タイトル・ルート・ステータスを書き換える）
4. コミットしてpush（GitHub Pagesが数分で自動反映）

## Claude / Claude Code での更新

このリポジトリをClaude Codeで開けば、しおりの中身（`trips/*/index.html` 内の `DAYS` 配列など）や
トップページの一覧を会話しながら編集 → push まで一気に進められます。
