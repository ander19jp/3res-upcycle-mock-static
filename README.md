# 3REs Upcycle Mock（静的HTML）

このリポジトリは **Next.jsなし** の静的モックです。
Vercel は HTML/CSS/JS の静的ファイルでも公開できます。

## ルーティング（URLとフォルダの対応）
- `/` → `index.html`
- `/artist/projects` → `artist/projects/index.html`
- `/artist/apply` → `artist/apply/index.html`

※ ご提示の `https://3-r-es-mock-upworks-navy.vercel.app/artist/projects` のようなURL構造は、Next.jsでなくても「フォルダ構成」で再現できます。 citeturn0view0

## 使い方（ローカル）
- VS Codeでこのフォルダを開く
- Live Server などで `index.html` を開く（任意）

## Vercelにデプロイ（GitHub連携）
1. GitHubにこのフォルダをpush
2. Vercelで Import（Framework Presetは **Other** / Static）
3. Build Commandは空、Output Directoryは空（デフォルト）でOK

