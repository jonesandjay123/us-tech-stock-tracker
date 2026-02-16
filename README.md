# 📈 美股科技基金均線追蹤

US Tech ETF Moving Average Tracker — 一個純靜態網站，追蹤美國科技股 ETF 的均線走勢。

## 功能

- **支援標的**：QQQ、VGT、XLK、ARKK、SMH、SOXX
- **均線**：MA5 / MA10 / MA20 / MA60 / MA120 / MA240（可自由開關）
- **時間區間**：3 個月 / 6 個月 / 1 年 / 2 年
- **互動圖表**：滑鼠懸停顯示價格，響應式設計

## 使用方式

直接用瀏覽器開啟 `index.html` 即可。

> ⚠️ 資料來源為 Yahoo Finance API，瀏覽器可能因 CORS 限制無法直接存取。
> 可搭配 CORS proxy 或部署到 GitHub Pages 使用。

## 技術

- 純 HTML / CSS / JavaScript（無框架）
- [Chart.js](https://www.chartjs.org/) 繪圖
- Yahoo Finance API 取得股價資料

## 未來擴展

- [ ] 部署至 GitHub Pages
- [ ] 加入更多 ETF / 個股
- [ ] 加入成交量圖
- [ ] 支援自訂均線參數
- [ ] 加入技術指標（RSI、MACD 等）

## License

MIT
