# LyriFlow

A minimal lyrics teleprompter web app for vocalists. Navigate through your setlist hands-free using a Bluetooth foot pedal on iPad (or any browser).

**Live Demo:** https://s00048ri.github.io/lyriflow/

## Features

- **Slide-based display** — One lyrics section per screen, not scrolling
- **Seamless song transitions** — Pressing "next" on the last slide automatically advances to the next song (the killer feature)
- **Foot pedal support** — PageDown/Up, Arrow keys, Space all work as navigation
- **Setlist management** — Add multiple songs, reorder with drag & drop (touch supported)
- **Dark theme** — Stage-friendly dark background that won't interfere with lighting
- **Auto font fitting** — CJK-aware algorithm adjusts font size to fill the screen
- **Adjustable font size** — Manual font size control with persistent settings
- **Wake Lock** — Prevents screen from sleeping during performance
- **Import/Export** — Save and load setlists as JSON files
- **Single HTML file** — No build step, no dependencies, no server required

## Usage

1. Open the app in your browser
2. Add songs and paste lyrics into the editor
3. Lyrics are automatically split into slides at blank lines
4. Arrange songs in your desired setlist order
5. Tap **Perform** to enter performance mode
6. Use your foot pedal (or keyboard) to navigate slides

### Keyboard Shortcuts (Performance Mode)

| Key | Action |
|---|---|
| `PageDown` / `→` / `↓` / `Space` | Next slide |
| `PageUp` / `←` / `↑` | Previous slide |
| `Escape` | Exit performance mode |

## Deployment

The app is a single `index.html` file. Host it anywhere:

- **GitHub Pages** — Push and enable Pages
- **Cloudflare Pages** — Deploy the `dist/` folder
- **Local** — Just open `index.html` in a browser

## Tech Stack

- Vanilla HTML / CSS / JavaScript (single file)
- Google Fonts: Noto Sans JP + Outfit
- Web APIs: Wake Lock, Fullscreen, File API
- iPad Safari optimized (`apple-mobile-web-app-capable`)

## License

MIT

---

# LyriFlow（日本語）

バンドのボーカリスト向け歌詞テレプロンプターWebアプリ。iPadのブラウザ上でBluetoothペダルを使い、ハンズフリーでセットリストを通せます。

**デモ:** https://s00048ri.github.io/lyriflow/

## 特徴

- **スライド表示** — 1画面に1セクション、スクロールではなくスライド式
- **シームレスな曲間遷移** — 最後のスライドで「次」を押すと自動的に次の曲へ（最重要機能）
- **フットペダル対応** — PageDown/Up、矢印キー、Spaceで操作可能
- **セットリスト管理** — 複数曲の登録、ドラッグ＆ドロップで並べ替え（タッチ対応）
- **ダークテーマ** — ステージ照明に干渉しない暗い背景
- **フォント自動調整** — CJK文字幅を考慮した自動フィットアルゴリズム
- **フォントサイズ調整** — 手動でのサイズ変更、設定は保持
- **Wake Lock** — 演奏中に画面がスリープしない
- **インポート/エクスポート** — セットリストをJSONファイルで保存・読み込み
- **単一HTMLファイル** — ビルド不要、依存なし、サーバー不要

## 使い方

1. ブラウザでアプリを開く
2. 曲を追加し、歌詞をエディタに貼り付ける
3. 空行で区切られたブロックが自動的にスライドに分割される
4. 曲順をドラッグで並べ替える
5. **Perform** ボタンで演奏モードに入る
6. フットペダル（またはキーボード）でスライドを送る

### キーボード操作（演奏モード）

| キー | 動作 |
|---|---|
| `PageDown` / `→` / `↓` / `Space` | 次のスライド |
| `PageUp` / `←` / `↑` | 前のスライド |
| `Escape` | 演奏モードを終了 |

## デプロイ

単一の `index.html` ファイルなので、どこでもホスト可能です：

- **GitHub Pages** — プッシュしてPagesを有効化
- **Cloudflare Pages** — `dist/` フォルダをデプロイ
- **ローカル** — `index.html` をブラウザで直接開く

## 技術スタック

- 素のHTML / CSS / JavaScript（単一ファイル）
- Google Fonts: Noto Sans JP + Outfit
- Web API: Wake Lock、Fullscreen、File API
- iPad Safari最適化（`apple-mobile-web-app-capable`）

## ライセンス

MIT
