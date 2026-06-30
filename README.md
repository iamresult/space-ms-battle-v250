# SPACE MS BATTLE 3D — Ver.2.5.2

ブラウザでそのまま遊べる3DボクセルFPS。ダウンロード不要・無料・スマホ対応。

## 構成ファイル
- `index.html` … ブリーフィングサイト（トップページ）。ゲームを内蔵し、START MISSION で起動。
- `SPACE_MS_BATTLE_3D_v252.html` … ゲーム単体（直接開いても遊べる）。
- `.nojekyll` … GitHub Pages の Jekyll 処理を無効化（静的HTMLをそのまま配信）。

## GitHub Pages での公開手順
1. このリポジトリに上記ファイルをすべてアップロード（ルート直下に配置）。
2. リポジトリの **Settings → Pages** を開く。
3. **Build and deployment → Source** で「Deploy from a branch」を選択。
4. **Branch** を `main`（または該当ブランチ）、フォルダを `/ (root)` にして Save。
5. 数分後、`https://<ユーザー名>.github.io/<リポジトリ名>/` で公開される。

## メモ
- すべて単一HTML（外部依存は Three.js を CDN から読み込むのみ）。サーバー不要。
- 音声はブラウザの仕様上、最初のタップ/クリック後に有効化される。
