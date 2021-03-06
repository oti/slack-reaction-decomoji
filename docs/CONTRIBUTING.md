# コントリビューティングガイドライン

## リポジトリへのデコモジの追加・削除

デコモジに興味を持っていただいてありがとうございます。

デコモジ追加・削除のプルリクエストは原則として**受けつけていません。**

もしあなたが欲しいデコモジがある場合は、[decomoji-template](https://github.com/decomoji/decomoji-template)を利用しご自分で作成なさるなどしてください。

スクリプトによる自動登録時に除外したいデコモジがある場合は、`decomoji/`配下の対象ファイルを削除してから`node scripts/manager`を実行してください。

### このプロジェクトがやること

- 不定期なデコモジの追加
- 文字の色や字詰めの修正
- ファイル名やスクリプトの改修

### このプロジェクトがやらないこと

- 一度追加したデコモジの削除
- デコモジの追加・削除要望への対応

## リーダビリティに関する要望

色の変更、字詰めの変更については Issue で報告をいただければ対応を検討したいと思います。

## その他のプルリクエスト

ドキュメントテキスト、デコモジのファイル名、scripts/ 配下のファイル、スクリーンショットなどにミスを発見したり、より良い提案があればぜひプルリクエストを送ってください。
