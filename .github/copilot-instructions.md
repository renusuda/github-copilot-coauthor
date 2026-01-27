# Git Commit Message Guidelines

GitHub Copilotがコミットメッセージを生成、またはコミット操作を支援する際は、以下のガイドラインに従ってください。

## 1. 共同制作者（Co-authored-by）の付与

Copilotがコードの提案や修正に大きく寄与した場合は、メッセージの末尾に必ず以下のトレーラー（Footer）を追加してください。

- **記述内容:** `Co-authored-by: Copilot <175728472+Copilot@users.noreply.github.com>`
- **配置ルール:** メッセージ本文とトレーラーの間には空行を1行入れ、他の `Co-authored-by` や `Signed-off-by` がある場合はその後に続けて記述してください。

## 2. メッセージの構成例

生成するコミットメッセージは、原則として以下の構造に従ってください。

```text
<type>: <subject>

<body>

Co-authored-by: Copilot <175728472+Copilot@users.noreply.github.com>
```
