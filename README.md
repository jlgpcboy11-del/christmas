# 陽光明信片｜Christmas Edition

以陽光草地為主題的繁體中文明信片作品展示網站，加入聖誕紅、松針綠、奶油白與金色的節慶視覺，適合桌面與手機瀏覽。

## 內容

網站展示 `postcard.jpg` 完成品，提供下載按鈕、作品規格，以及從原始風景圖裁切、調整尺寸、套用模糊與銳化濾鏡、加入繁體中文文字的製作流程說明。

## 本機預覽

這是一個不需要額外套件的靜態網站。可在專案根目錄執行：

```bash
python3 -m http.server 3000 --bind 0.0.0.0 --directory public
```

接著開啟 `http://localhost:3000/`。

## 檔案結構

- `public/index.html`：網站頁面與內容
- `public/styles.css`：聖誕節視覺、響應式版面與動畫
- `public/script.js`：年份更新與簡單互動
- `public/postcard.jpg`：800×600 明信片成品
- `public/manus-routes.json`：網站路由宣告
- `create_postcard.py`：產生明信片的 Pillow 程式
