# Solizon - 未来を創造するテクノロジーカンパニー

Solizonは、ITの力で企業の課題を解決する革新的なテクノロジーパートナーです。  
このリポジトリは、Solizonのランディングページ（LP）をホスティング・管理するためのものです。

---

## 📌 概要

本LPは以下のセクションから構成されています：

- ヒーローセクション（キャッチコピー＋CTA）
- Solizonの強み
- 提供サービス一覧
- サービス導入の流れ
- 下部CTA（無料相談）
- お問い合わせフォーム
- 会社情報・フッター

全て **HTML・CSS・JavaScript** を1ファイルにまとめた静的サイト形式です。

---

## 🔧 使用技術

- **HTML5**：ページ構造
- **CSS3**：レスポンシブデザイン、アニメーション含むスタイリング
- **JavaScript**：ナビゲーションのスムーズスクロール、メニューのトグルなどの動作制御

---

## 🚀 公開方法

### 1. Netlify を使ったデプロイ（おすすめ）

1. [Netlify](https://www.netlify.com/) にサインアップ
2. 「New Site from Git」で本リポジトリを選択
3. Build Command：**なし**、Publish Directory：**/** を指定
4. 自動デプロイされ、`https://your-site-name.netlify.app` にて公開完了！

### 2. GitHub Pages（無料・シンプル）

1. 本リポジトリを GitHub にプッシュ
2. リポジトリの Settings > Pages を開く
3. 「Source: `main` branch / root」を選択して保存
4. 数分後、`https://ユーザー名.github.io/リポジトリ名/` でアクセス可能

---

## 📝 ファイル構成

solizon-landing/
├── index.html        ← 本LPの全コードが集約されたファイル
├── README.md         ← このファイル

---

## ✨ カスタマイズポイント

- `index.html` 内の `<title>` や `<meta>` を変更してSEO対策
- お問い合わせフォームの送信処理を実装したい場合は Netlify Forms や Google Forms の連携が可能です（必要に応じてサポート可）

---

## ©️ ライセンス

本コードは Solizon LP用途のための専用テンプレートです。  
商用利用・カスタマイズはご自由にどうぞ。  
（公開・販売される場合はクレジットの表記をお願いします）
