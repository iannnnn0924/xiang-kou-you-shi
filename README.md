# 巷口有事

以台南中西區為靈感的第三人稱街區遊戲原型。玩家扮演在地人阿翊，在家齊高中與五妃街周邊探索、接委託、騎機車並賺取任務酬勞。

## 試玩

網站發布後可從 GitHub Pages 網址遊玩。遊戲目前是持續開發中的原型，街區配置與人物皆為簡化模型。

## 操作

- **WASD**：移動
- **滑鼠拖曳**：轉動第三人稱鏡頭
- **Shift**：快跑
- **E**：靠近任務標記完成委託；靠近機車時騎乘／下車

## 本機預覽

直接以瀏覽器開啟 `index.html`。頁面使用 Three.js CDN 載入 3D 引擎，預覽時需要網路連線。

## 發布

推送到 `main` 分支後，`.github/workflows/pages.yml` 會使用 GitHub Actions 將網站發布至 GitHub Pages；也可從 Actions 頁面手動執行。

## 專案規劃

願景、目前狀態與後續路線圖請看 [`knowledge/plan.md`](knowledge/plan.md)。
