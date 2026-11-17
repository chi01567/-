# 日常衣序 · Digital Wardrobe

以 React 與 Vite 製作的個人衣櫥與穿搭靈感網站。服飾資料和已儲存穿搭會保存在目前瀏覽器的 `localStorage`。

## 本機開發

```bash
npm install
npm run dev
```

## 建置

```bash
npm run build
npm run preview
```

## 部署到 Vercel

將專案推送至 GitHub，於 Vercel 匯入該 repository。Vercel 可自動偵測 Vite，或設定 Build Command 為 `npm run build`、Output Directory 為 `dist`。

## 功能

- 8 件 SVG 示意服飾、分類與風格篩選、搜尋。
- 新增單品、上傳本地照片，並設定分類、色調及風格。
- 點選單品加入畫布，支援滑鼠與觸控拖曳、縮放、圖層調整及移除。
- 一鍵從衣櫥組合穿搭，儲存至穿搭簿；另有 3 款穿搭靈感推薦。
- 服飾與穿搭保存在瀏覽器 `localStorage`；上傳圖片會縮小並以 JPEG 存入瀏覽器。

注意：`localStorage` 資料只存在使用者目前的瀏覽器，不會同步到其他裝置或帳號。
