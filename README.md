# cafeore56.github.io（カフェオレGAME LAB のサイト）の中身

ノート67の「数ページだけのサイト」。GitHub Pages のユーザーサイトとして公開する前提。

## ファイル
| ファイル | 役目 | App Store Connect のどこに入れるか |
|---|---|---|
| `index.html` | トップ（LAB の約束・ゲーム一覧・実況の方針） | マーケティング URL：`https://cafeore56.github.io/` |
| `privacy/index.html` | 全アプリ共通のプライバシーポリシー | プライバシーポリシー URL：`https://cafeore56.github.io/privacy/` |
| `support/index.html` | 問い合わせ・よくある質問 | サポート URL：`https://cafeore56.github.io/support/` |
| `app-ads.txt` | AdMob の確認用（ドメインのルートに置く必要がある） | （マーケティング URL から AdMob が見に来る） |
| `404.html`・`style.css`・`images/`・`.nojekyll` | 見た目・おまけ | — |

## 公開の手順（ユーザーの操作）
1. GitHub で **`cafeore56.github.io`** という名前のリポジトリを作る（**Public**。無料プランでは Pages は公開リポジトリのみ）
2. このフォルダの中身をそのリポジトリに入れる（Claude のセッションに add_repo で足せば、Claude が入れられる）
3. リポジトリの Settings ＞ Pages で、Branch を `main`・`/ (root)` にして保存。数分で `https://cafeore56.github.io/` が開く

## 公開前に埋めるところ（`TODO` で検索）
- 運営者名（App Store の販売元名）
- 問い合わせ用メールアドレス（専用のものを作る）
- 実況・配信の方針でよいか
- プライバシーポリシーの制定日、使う外部サービス（AdMob 以外を使うなら表に足す）
- `app-ads.txt` の1行（AdMob に登録してから）
- ゲームを出したら、トップにカードを1枚足す
