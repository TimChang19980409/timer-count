# 精美倒數計時器

這是一個具有現代化設計的網頁倒數計時器，適用於各種促銷活動、特別活動或重要日期的倒數。

## 功能特點

- 精確顯示天、時、分、秒的倒數時間
- 優雅的漸變背景設計
- 動態更新效果
- 浮動的限時特惠標籤
- 響應式設計
- 自動補零顯示（個位數前方自動添加0）

## 預覽效果

- 漸變背景：採用深藍色系漸變效果
- 半透明卡片設計
- 數字變化時的脈動動畫
- 限時特惠標籤的漂浮動畫效果

## 使用方法

1. 複製 `timer-count.html` 文件到您的專案中
2. 修改目標日期：
   ```javascript
   const targetDate = new Date('2025-02-14T17:00:00+08:00');
   ```
   將日期更改為您需要的目標時間（格式：YYYY-MM-DDTHH:mm:ss+08:00）

## 自定義設置

### 修改樣式
- 背景顏色：修改 `.countdown-container` 中的 `background` 屬性
- 卡片大小：調整 `.time-card` 中的 `padding` 和 `min-width`
- 字體大小：修改 `.number` 和 `.label` 中的 `font-size`

### 修改動畫
- 數字更新動畫：調整 `@keyframes pulse` 中的參數
- 標籤漂浮動畫：調整 `@keyframes float` 中的參數

## 瀏覽器支援

- Chrome
- Firefox
- Safari
- Edge
- 其他現代瀏覽器

## 注意事項

1. 時間設定使用 UTC+8 時區（台灣/香港/中國時間）
2. 當倒數結束時，所有數字將顯示為 "00"
3. 建議使用現代瀏覽器以獲得最佳效果

## 授權

MIT License

## 作者

Tim980409

---

歡迎提出建議和改進意見！ 