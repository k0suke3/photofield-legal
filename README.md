# photofield-legal

PhotoField Simulator の規約・プライバシーポリシーを GitHub Pages で公開するための
**パブリックリポジトリ用フォルダ**。アプリ本体（プライベート）とは分離している。

## 公開手順
1. このフォルダの内容を新しい**パブリック**リポジトリ（例: `photofield-legal`）に push する。
2. リポジトリの **Settings → Pages → Source** を `Deploy from a branch` / `main` / `/(root)` に設定。
3. 数分後、以下で公開される:
   - `https://<ユーザー名>.github.io/photofield-legal/privacy-policy`
   - `https://<ユーザー名>.github.io/photofield-legal/terms-of-use`

## アプリ側の設定
公開後、アプリの `EXPO_PUBLIC_TERMS_URL` / `EXPO_PUBLIC_PRIVACY_URL` に上記URLを設定する。
