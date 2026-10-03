# 工作階段記憶（2026-10-03）

## 本次異動（由舊到新）
1. `56f58d0` feat：特約／共購入口改指 hub 統一入口（`?entry=%2Fstores`／`?entry=%2Fcoop`）
2. `351fa26` feat：入口整併為單一「社員服務入口」→ `https://special-stores-hub.web.app/#/`，移除特約／共購直連
   - 搜尋關鍵字保留特約／共購／團購／遊戲／點數星球，打字照樣找得到
   - GitHub Pages push 後 1–2 分鐘自動生效

## 關聯（另一 repo：Line ai 聊天機器人，分支 `feat/merged-app`）
- 地圖圖磚：OSM 403 → CARTO → Esri 免費免 key（`3c70a38`、`9c7b719`），舊站＋hub 皆已部署

## 操作經驗
- 驗正式站用無痕視窗或 `Ctrl+F5`，避開瀏覽器快取誤判
