# MICH_VP

蔡承佑應徵 MICH 全球行銷專員，第二階段 VP 面談（2026/11/11）用的 2 頁簡報網站。
視覺刻意與 MICH_CHAR（第一次面試網站）不同：淺色底，紅、白、藍（台灣、日本、美國共有的顏色）：白底上紅、藍兩團暈開的光，重疊處融合成紫色，第 2 頁會靠攏融合，象徵合作；左右換頁。

## 檔案
- `index.html`：單一 HTML 檔，沒有建置步驟，瀏覽器直接打開。

## 改 `index.html` 的慣例
- 每頁是一個 `<section class="slide" id="s-xxx" data-title="…" data-title-en="…" data-title-ja="…">`。
- 文字三語並列：`<span data-l="zh">…</span><span data-l="en">…</span><span data-l="ja">…</span>`。
- 每頁必須放得進一個畫面（約 1440×760）；內容保持精簡。
- 不要替候選人編造經歷或成果數字。
- 操作：← → 換頁、1／2 跳頁；網址加 `?lang=en` 或 `?lang=ja` 可直接切語言。
