# Usage

## - Export

```bash
code --list-extensions | tee extensions.txt
```

## - Import

1. Copy the previously exported extensions.txt file to the new machine.
2. Open Visual Studio Code on the new machine and open a terminal.
3. In the terminal, navigate to the directory where the extensions.txt file is located.
4. Paste and execute the following command in the terminal:

   ```bash
   cat extensions.txt | xargs -L 1 code --install-extension
   ```

## - List

| 拡張機能名                             | 説明                                                                                                                                                                                         |
| -------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| alefragnani.Bookmarks                  | エディタ内の位置をブックマークすることができる。                                                                                                                                             |
| astro-build.astro-vscode               | Astro と呼ばれる新しいスタティックサイトジェネレーターのサポートを追加する。                                                                                                                 |
| bradlc.vscode-tailwindcss              | Tailwind CSS フレームワークのクラス名を補完する。                                                                                                                                            |
| ChakrounAnas.turbo-console-log         | `console.log()`ステートメントを高速かつ簡単に追加する。                                                                                                                                      |
| csstools.postcss                       | PostCSS フレームワークのサポートを追加する。                                                                                                                                                 |
| dbaeumer.vscode-eslint                 | ESLint を使って、JavaScript/TypeScript ファイルの品質管理を行うことができる。                                                                                                                |
| donjayamanne.githistory                | Git の歴史やブランチ、タグなどをグラフィカルに表示することができる。                                                                                                                         |
| dsznajder.es7-react-js-snippets        | React 開発に必要なスニペットを提供する。                                                                                                                                                     |
| eamodio.gitlens                        | Git リポジトリをより直感的に管理できるようにするツール。                                                                                                                                     |
| ecmel.vscode-html-css                  | HTML/CSS をより直感的に開発できるようにするツール。                                                                                                                                          |
| esbenp.prettier-vscode                 | Prettier を使って、自動的にコードをフォーマットすることができる。                                                                                                                            |
| formulahendry.auto-rename-tag          | HTML/XML タグをリネームすることができる。                                                                                                                                                    |
| golang.go                              | Go 言語の開発をサポートする。                                                                                                                                                                |
| GraphQL.vscode-graphql                 | GraphQL のサポートを追加する。                                                                                                                                                               |
| GraphQL.vscode-graphql-syntax          | GraphQL 構文のシンタックスハイライトを提供する。                                                                                                                                             |
| hashicorp.terraform                    | Terraform コードを作成、変更、デバッグすることができる。                                                                                                                                     |
| hediet.vscode-drawio                   | Draw.io を使って、図やチャートを簡単に作成することができる。                                                                                                                                 |
| JuanBlanco.solidity                    | Solidity 言語の開発をサポートする。                                                                                                                                                          |
| glenn2223.live-sass                    | Sass ファイルを監視して自動でコンパイルが可能になる。                                                                                                                                        |
| Mariusalchimavicius.json-to-ts         | JSON から TypeScript のインターフェイスを自動生成することができる。                                                                                                                          |
| Mike-co.import-sorter                  | import 文を自動でソートすることができる。                                                                                                                                                    |
| Mohammadbaqer.better-folding           | コードブロックを折りたたむことができる。                                                                                                                                                     |
| MS-azuretools.vscode-docker            | Docker の開発ワークフローをサポートするツールキット。Dockerfile、docker-compose.yml ファイルのシンタックスハイライト、デバッグ、イメージのビルド、タグ付け、パッシングなどの機能を提供する。 |
| MS-ceintl.vscode-language-pack-ja      | Visual Studio Code の言語パック。日本語ローカライズがされている。                                                                                                                            |
| ms-python.isort                        | Python の import を整形するための拡張機能。                                                                                                                                                  |
| ms-python.python                       | Python の開発に特化した拡張機能。デバッグ、ユニットテスト、自動補完などの機能を提供する。                                                                                                    |
| ms-python.vscode-pylance               | Python 向け静的型チェックツール Pylance を使用するための拡張機能。                                                                                                                           |
| ms-toolsai.jupyter                     | Jupyter Notebook で使用できる拡張機能。Python だけでなく、R、Julia、その他の言語をサポート。ノートブックの作成、実行、デバッグなどを行うことができる。                                       |
| ms-toolsai.jupyter-keymap              | Jupyter Notebook でのキーバインディングをカスタマイズするための拡張機能。                                                                                                                    |
| ms-toolsai.jupyter-renderers           | Jupyter Notebook で、デフォルトで提供されていないファイルフォーマットのレンダリングを可能にする拡張機能。                                                                                    |
| ms-toolsai.vscode-jupyter-cell-tags    | Jupyter Notebook のセルにタグを付けることができるようになる拡張機能。タグでセルをフィルタリングできるようになる。                                                                            |
| ms-toolsai.vscode-jupyter-slideshow    | Jupyter Notebook でスライドショーを作成するための拡張機能。                                                                                                                                  |
| ms-vscode-remote.remote-containers     | Visual Studio Code で、Docker コンテナー内で開発するための拡張機能。                                                                                                                         |
| ms-vsliveshare.vsliveshare             | リモートペアプログラミングのための拡張機能。リアルタイムでコードの共同編集、デバッグ、テスト、デプロイを行うことができる。                                                                   |
| nidu.copy-json-path                    | JSON ファイル内のパスをコピーするための拡張機能。                                                                                                                                            |
| Orta.vscode-jest                       | Jest テストランナーに対する VSCode 拡張機能。                                                                                                                                                |
| PKief.material-icon-theme              | VS Code のファイルアイコンを変更する。                                                                                                                                                       |
| Prisma.prisma                          | データベースのクエリエディタとマイグレーションマネージャー。                                                                                                                                 |
| pranaygp.vscode-css-peek               | CSS ファイル内のクラスを迅速に検索してジャンプできる。                                                                                                                                       |
| richie5um2.vscode-sort-json            | JSON オブジェクト内のキーと値の順序を整理する。                                                                                                                                              |
| ritwickdey.liveserver                  | ローカルサーバーを簡単に起動できる。                                                                                                                                                         |
| Sachinsmc.turbo-fmt-println            | fmt.Print()と fmt.Printf()を自動的に変換する。                                                                                                                                               |
| seatonjiang.gitmoji-vscode             | Git コミットメッセージで絵文字を使う。                                                                                                                                                       |
| shd101wyy.markdown-preview-enhanced    | Markdown プレビューアの機能を強化する。                                                                                                                                                      |
| streetsidesoftware.code-spell-checker  | コード内のスペルミスを検出する。                                                                                                                                                             |
| tintinweb.graphviz-interactive-preview | DOT 言語で書かれたグラフのプレビューを表示する。                                                                                                                                             |
| tomoki1207.vscode-input-sequence       | キーストロークのシーケンスを記録して再生する。                                                                                                                                               |
| Unifiedjs.vscode-mdx                   | MDX ファイルをエディットしてプレビューする。                                                                                                                                                 |
| Wallabyjs.quokka-vscode                | テストを書いてコードを実行する。                                                                                                                                                             |
| withfig.fig                            | CLI ツールの自動補完を提供する。                                                                                                                                                             |
| yzhang.markdown-all-in-one             | Markdown のエディター、プレビューパネル、およびプレビュー改善機能。                                                                                                                          |
| Zignd.html-css-class-completion        | HTML / CSS クラスの自動補完を提供する。                                                                                                                                                      |
