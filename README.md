VS Code Remote Container で CKAN を立ち上げるための一連の設定ファイル。

## 使い方

ckan のレポジトリをプロジェクトルート (.devcontainer フォルダがあるのと同じフォルダ) にクローンする。本家のクローンするのであれば、以下の通り:

```bash
git clone https://github.com/ckan/ckan.git
```

この段階でフォルダ構成は以下の図のようになる。

```
📂 /
├─📂 .devcontainer/
└─📂 ckan/
```

この状態で VS Code でプロジェクトルート (.devcontainer フォルダがあるのと同じフォルダ) を開く。

```bash
code <プロジェクトルートのパス>
```

すると、

> Folder contains a Dev Container configuration file.

と表示されるので、"Reopen in Container" をクリックする。VS Code が再起動し、CKAN のコンテナ内のファイルを VS Code 上から編集できるようになる。
