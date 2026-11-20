# Shiden-BusinessCards

Shiden Cards（名刺一覧）の閲覧ページの公開ホスティング。

- 公開 URL: https://hayahide-cloud.github.io/Shiden-BusinessCards/
- このリポジトリには閲覧ページ（`index.html`・`icon.svg`）だけを置く。**名刺データは一切置かない**
- 名刺データは非公開リポジトリにあり、ページを開いた端末で「読込設定」にトークンを入れたときだけ、そのブラウザが直接読み込む。トークンはその端末のブラウザ（localStorage）にだけ保存される
- 正本は別の非公開リポジトリにある。このリポジトリのファイルは正本のミラーなので、直接編集しない
