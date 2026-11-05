# 騎行 3D 路線動畫

把 Bryton（或 Garmin、Strava 匯出）的 `.fit` / `.gpx` 騎行紀錄做成 3D 地形路線動畫，效果類似 Strava 付費版的 3D flyover。

**線上使用：** https://pigman1331.github.io/ride-3d/

## 功能
- 衛星影像 + 3D 地形，鏡頭跟隨騎行位置
- 即時顯示時速、距離、海拔、心率、功率、踏頻與海拔剖面
- 路線顏色：單色（可自選顏色）、依速度、依功率漸層，畫面附色階圖例
- 多段紀錄可「無縫接續」或「分段標示」（顯示中途休息時間）
- 影片長度 30 秒～2 分鐘，比例 16:9 / 9:16 / 1:1
- 「錄成影片」直接下載 mp4（Chrome / Edge）或 webm

## 使用方式
1. 從 Bryton Active App 匯出 FIT 或 GPX
2. 打開網頁，按「換檔案」或把檔案拖進畫面（多段可一次選取）
3. 調整設定，播放預覽，滿意就按「錄成影片」

檔案只在你的瀏覽器裡解析，不會上傳。

## 換預設路線
網頁開啟時播放的是 `rides.json`（已隱藏起訖點附近約 500 公尺）。

Imagery © Esri, Maxar, Earthstar Geographics · Terrain © Mapzen / AWS Terrain Tiles · 地圖引擎 MapLibre GL JS
