# SnowPlus Pre-Season Mobile Web App

這是一個可直接部署的手機版 Web App / PWA，包含三個版本：

- `/open-cute/` — Open Edition Cover A：可愛版
- `/open-real/` — Open Edition Cover B：真人版
- `/coach-plus/` — Coach Plus：進階教練版

## 最快部署：Netlify Drop

1. 解壓縮 `snowplus-preseason-webapp-final.zip`。
2. 到 Netlify Drop。
3. 把整個 `snowplus-preseason-webapp-final` 資料夾拖上去。
4. Netlify 會產生公開網址。

## 本機預覽

```bash
cd snowplus-preseason-webapp-final
python3 -m http.server 8000
```

打開：

```text
http://localhost:8000
```

## 行銷連結建議

- 大眾行銷 / IG / LINE：`/open-real/`
- 可愛版 A/B test：`/open-cute/`
- 教練培訓或內部使用：`/coach-plus/`
- 官網資源頁：首頁 `/`

## 注意

Open Edition 兩版內容一致，只有封面不同。Coach Plus 為進階版。此版本不包含 LP / 力板 / 生物力學數據報告內容。
