## StockManager Frontend

**財務指標閲覧ツール（React製フロントエンド）**

企業名検索から財務データ表示までを行う、React + Django API連携の個人開発プロジェクトのフロントエンド部分です。

---

### 主な機能

- 企業名から銘柄コードを自動変換（OpenAI API使用）
- 財務指標の可視化表示（yfinance取得）
- ユーザー登録 / ログイン（JWTトークン連携）
- お気に入り銘柄の登録 / 閲覧
- マイページ表示

---

### 使用技術

- **React** / **React Router**
- **Axios**（バックエンドAPI通信）
- **環境変数管理**：dotenv（`.env`）
- **状態管理**：useState / useEffect ベース
- **スタイル**：CSS Modules

---

### 起動手順

```bash
# 依存インストール
npm install

# 起動
npm start
