# cafeore-gamelab.github.io（Cafeore Game Lab のサイト）の中身

ノート67の「数ページだけのサイト」。GitHub Pages のユーザーサイトとして公開する前提。

## ファイル
| ファイル | 役目 | App Store Connect のどこに入れるか |
|---|---|---|
| `index.html` | トップ（LAB の約束・ゲーム一覧・実況の方針） | マーケティング URL：`https://cafeore-gamelab.github.io/` |
| `privacy/index.html` | 全アプリ共通のプライバシーポリシー | プライバシーポリシー URL：`https://cafeore-gamelab.github.io/privacy/` |
| `support/index.html` | 問い合わせ・よくある質問 | サポート URL：`https://cafeore-gamelab.github.io/support/` |
| `app-ads.txt` | AdMob の確認用（ドメインのルートに置く必要がある） | （マーケティング URL から AdMob が見に来る） |
| `404.html`・`style.css`・`images/`・`.nojekyll` | 見た目・おまけ | — |

## 公開の手順
- 組織 `cafeore-gamelab` のリポジトリ `cafeore-gamelab.github.io`（Public）。Settings ＞ Pages で Branch を `main`・`/ (root)` にする
- 2026-11-09：旧 `cafeore56/cafeore56.github.io` から引っ越し（履歴ごと）

## 公開前に埋めるところ（`TODO` で検索）
- 運営者名（App Store の販売元名）
- ~~問い合わせ用メールアドレス~~ → gamelab.cafeore@gmail.com（2026-11-08 済）
- 実況・配信の方針でよいか
- プライバシーポリシーの制定日、使う外部サービス（AdMob 以外を使うなら表に足す）
- `app-ads.txt` の1行（AdMob に登録してから）
- ゲームを出したら、トップにカードを1枚足す
