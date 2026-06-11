# フォルダ構成

privateリポジトリの構成を、公開可能な範囲で整理したものです。この公開リポジトリには、実際のソースコードやビルド可能なファイルは含めていません。

```text
shortcut-launcher/
├─ ShortcutLauncher.py
├─ ShortcutLauncher.spec
├─ requirements.txt
├─ app.ico
├─ readme.md
├─ .gitignore
├─ .vscode/
├─ user_data/
│  ├─ items.json
│  └─ icons/
├─ dist/
└─ build/
```

## 実行時に生成・利用される構成

```text
user_data/
├─ items.json
└─ icons/
   └─ {アプリ名}.png
```

`user_data/` はアプリケーション起動時に存在しない場合、自動的に作成されます。`items.json` が存在しない場合は、空の配列として初期化されます。

