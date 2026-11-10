# MICH_VP

蔡承佑應徵 MICH 全球行銷專員，第二階段 VP 面談（2026/11/11）用的 2 頁簡報網站。
視覺：日本現代主義海報風。白紙＋淡格線、第 1 頁置中文字＋淡淡的日本國旗紅圓、黑色細線；紅白藍代表台灣、日本、美國共有的顏色。兩頁原地淡入切換（手機也一樣是一頁一頁，可按箭頭或左右滑動），第 2 頁三欄由下往上進場。

## 檔案
- `index.html`：單一 HTML 檔，沒有建置步驟，瀏覽器直接打開。

## 改 `index.html` 的慣例
- 每頁是一個 `<section class="slide" id="s-xxx" data-title="…" data-title-en="…" data-title-ja="…">`。
- 文字三語並列：`<span data-l="zh">…</span><span data-l="en">…</span><span data-l="ja">…</span>`。
- 每頁必須放得進一個畫面（約 1440×760）；內容保持精簡。
- 不要替候選人編造經歷或成果數字。
- 操作：← → 換頁、1／2 跳頁；網址加 `?lang=en` 或 `?lang=ja` 可直接切語言。

## 字體（離線也能用）
- 標題的明朝體（Noto Serif TC／JP）存在 `fonts/`，只包含頁面用到的字，所以檔案很小。
- **改了任何文字之後**，執行 `python3 fonts/update_fonts.py` 重新下載字體，新加的字才會是明朝體（需要網路）。
