サイバーパンク・ネオン雨 (Neon Rain)

概要

サイバーパンク風のネオン雨が降るデモページです。
Googleクロール向けに最適化されており、構造化データ（JSON-LD）やSEO向けメタタグを備えています。

デモ
	•	ページ内の h1 と p にテキストを残しており、Googlebotが内容を理解しやすい
	•	ネオン雨の演出は CSS と JavaScript で実装
	•	雨の数はクロール負荷を考慮して軽量化済み

ファイル構成

neon-rain/
├─ index.html
├─ README.md
├─ css/style.css  (任意)
└─ js/rain.js    (任意)

使い方
	1.	リポジトリをクローン
git clone https://github.com/USERNAME/neon-rain.git
	2.	index.html をブラウザで開く

カスタマイズ
	•	雨の数、色、速度は rain.js 内の numDrops や CSS の linear-gradient を変更
	•	タイトルや説明文は index.html の title と meta で変更可能

ライセンス

MIT License

⸻

GitHubに追加する手順
	1.	GitHubでリポジトリ作成
	2.	ローカルでリポジトリ初期化
git init
git add .
git commit -m “初回コミット: サイバーパンク・ネオン雨クロールページ”
git branch -M main
git remote add origin https://github.com/USERNAME/neon-rain.git
git push -u origin main
	3.	ブラウザで確認（GitHub Pagesに公開も可能）
