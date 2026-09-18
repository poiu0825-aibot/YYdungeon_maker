# YYdungeon_maker

Dungeon Maker 的線上測試與版本封存 Repository。

## Live build

GitHub Pages 啟用後，固定測試網址：

https://poiu0825-aibot.github.io/YYdungeon_maker/

每次新版確認要上網測試時，直接更新根目錄的 `index.html`，網址不變。

## Version management

- `index.html`：目前線上最新版本。
- `versions/`：每個版本的永久封存，例如 `versions/v6.0.0.html`。
- `CHANGELOG.md`：記錄每次版本更新內容。
- Git commit history：可用來比較、追蹤或回復任何一次更新。

### 建議更新流程

1. 完成新版 HTML 並測試基本功能。
2. 將新版另存到 `versions/vX.Y.Z.html`。
3. 用同一份內容更新 `index.html`。
4. 更新 `CHANGELOG.md`。
5. Commit message 使用例如：`Publish v6.1.0 - <功能名稱>`。

這樣線上測試網址永遠不需要改，而舊版本也可以保留。

## Current live version

**v6.0.0 — VFX / Atmosphere Polish**
