# 合同会社ミューソフトウェアのホームページ

## 利用ツール

* 静的サイトジェネレーター: [Jekyll](https://jekyllrb.com/)
* サイトテーマ: [Doc](https://mmistakes.github.io/minimal-mistakes/) [GitHub](https://github.com/mmistakes/minimal-mistakes)

## 利用方法

### レイアウトの変更

1. 対象のレイアウトファイル `_layout/XXX.html` を更新
2. 存在しない場合は `original_repo/_layout/XXX.html` を `_layout` にコピーして更新

### コマンド

```bash
# ローカルサーバ起動
bundle exec jekyll serve

# Gemfile を更新したあとパッケージのインストール
bundle
```
