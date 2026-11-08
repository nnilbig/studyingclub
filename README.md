# studyingclub

AI 戰情室：用 three.js 做的等角像素風 AI 機房，五隻貓圍著中央的全息戰情桌，各自研究一個主題。畫風沿用 [alphaoffice](https://github.com/nnilbig/alphaoffice)（西區交易室）。

## 研究員

| 名字 | 貓 | 主題 | 目前對應的排程 |
| --- | --- | --- | --- |
| Nova | 暹羅貓 | AI 觀點 | 每日中文新觀點（每天 06:35） |
| Byte | 橘虎斑 | 科技新知 | 每日AI技術新知（每天 06:25） |
| Ellis | 黑貓 | 英文新聞 | 每日英文新聞（每天 06:05） |
| Page | 三花貓 | 書籍推薦 | 每日溫度小品（每天 21:23，一則跟今天日期有關的故事） |
| Coda | 藍貓 | 音樂賞析 | 尚無排程 |

排程寄到 Gmail，同時把內容寫進 `reports/`，戰情室點貓咪就能線上閱讀（「展開閱讀」可全螢幕看）。沒有排程的座位，螢幕會暗著。

## 報告資料

- `reports/index.json`：所有報告的清單（agent、date、time）
- `reports/YYYY-MM-DD/<agent>.json`：單份內容（agent：ai、tech、news、books、music）
  - 格式：`agent`、`date`、`time`、`tag`、`title`、`summary`、`sections`（每段有 `h` 標題、`p` 段落、`list` 條列）、`sources`

## 操作

- 拖曳旋轉、滾輪縮放
- 點貓咪或右側名單，看牠的主題與排程
- 「像素感」切換像素／高清渲染
