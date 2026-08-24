# 天赦天堂官網 — 專案品牌規範

> 本站由「噬魂天堂」複製為模板，換膚為「肅殺鐵灰・赦印朱紅」。CSS 變數名沿用噬魂骨架，只換 :root 色值＝全站換膚。

## 品牌資訊
- 名稱：天赦天堂 TIAN SHE · LINEAGE
- 版本：3.81
- 風格：肅殺鐵灰 × 赦印朱紅、庚金淬火、帝王赦令
- 標語：天赦臨世 ✦ 赦令天下
- 開服：8/21（四）20:00

## 色系（嚴格遵守 style.css :root 變數）
- 背景：#0a0c0e ~ #14181d（冷鐵灰黑）
- 冷鋼銀（原「金」槽位）：#9aa6b0（主色）/ #d8e0e6（亮銀）/ #5a636b（暗鋼）
- 赦印朱紅（原「紅」槽位，主角色）：#d43a2a / #ff5238（亮）/ #8a1e12（暗）
- 冷鐵青（原 soul 第三色）：#3f7d8a / #6fb3c0（亮）
- 文字亮色：#eef3f6（標題）/ #c4ccd2（正文）
- 文字暗色：#8a949c（次要）/ #565f66（最暗，僅用於極次要提示）

## 字體
- 中文標題：Noto Serif TC（900 weight）
- 英文裝飾：Cinzel（serif）
- NEVER 使用 Inter、Roboto、sans-serif 等現代無襯線字體

## 設計禁令
- NEVER 使用白色或淺色背景
- NEVER 使用圓角卡片（border-radius 最大 4px）
- NEVER 使用可愛、卡通、扁平風格
- NEVER 在深色背景上用 --text-muted(#5a4020) 當主要文字
- 背景區塊必須實色，禁止低 opacity 透明背景（最低 0.8）
- 新增 CSS 類別名稱必須加前綴，避免與 style.css 衝突

## 生圖鐵律（LOGO／圖片，未來一律遵守）
- **禁止** Gemini 生成任何看不懂的假經文、假盧恩、亂碼文字、裝飾性外文字母
- 圖上**唯一允許的文字＝指定的正確中文**（如「天赦天堂」「赦」印），其餘一律不要文字
- 環狀／邊框裝飾帶一律改用**純圖騰紋樣**（祥雲、龍紋、花紋），不得出現任何字符
- 每份提詞務必附 negative：NO fake runes, NO gibberish glyphs, NO random letters, NO decorative inscriptions, NO unreadable script

## 視覺元素
- 邊框：金紅漸層線條
- 光效：金色/紅色/紫色 glow、text-shadow
- 裝飾：◆ 菱形符號、✦ 分隔符、盧恩文字風
- 卡片：#120e24 → #0c0818 漸層背景 + #1e1630 邊框
- 按鈕：斜切 clip-path 造型

## 素材位置
- Logo：assets/images/logo-circle.jpg
- 英雄橫幅：assets/images/hero-banner.jpg
- 品牌設計稿：天赦天堂-設計稿/ 資料夾（沿用噬魂立繪，待換天赦專屬視覺）
- 道具圖檔：桌面/道具圖檔2/{編碼}.png（共 10,502 張，檔名=圖片編碼）
- 引用方式：複製到 assets/images/item-{編碼}.png，HTML 用 `<img src="../assets/images/item-{編碼}.png">`
- 編碼來源：桌面/天堂更新檔/ 修改歷程 txt

## 頁面結構
- 首頁：index.html
- 子頁面：pages/ 資料夾
- 共用 CSS：assets/css/style.css
- 共用 JS：assets/js/main.js
- 子頁面引用路徑用 ../assets/

## 參考競品風格
- 神說天堂 godhash.vip — 設計感最好，金黑配色+影片背景+沉浸式
- 曜舞天堂 — 影片背景 Hero、職業輪播、效能優化意識好
- 普遍私服官網 — 深色+金色主調、卡片式排版、固定導航

## 未來官網方向（參考 maplestory113.com 活動頁風格）
- **內容呈現**：用大張設計圖+遊戲截圖說明，不要純文字表格
- **活動/公告頁排版**：全幅設計圖 Banner → 簡短文字說明 → 圖片展示獎勵內容
- **圖片優先**：道具、NPC、地圖截圖直接嵌入，搭配簡短文字，讓玩家一眼看懂
- **icon 全用遊戲素材圖**：從 桌面/道具圖檔2/ 抓對應編碼圖片，不用 emoji 或符號字元
- **風格關鍵字**：圖文並茂、視覺導向、玩家友善、像遊戲內公告的延伸

## 寵物系統 icon
- 項圈：item-1617.png（已備好，等寵物頁面更新時使用）

---

## 影片專案（souldevourer-promo）

### 路徑
- Remotion 專案：`Desktop\souldevourer-promo\`
- 影片定案：`Desktop\克勞德影片生成定案\噬魂天堂-影片系列\`
- 文宣/提詞：`Desktop\噬魂文宣\`
- 詳細規範：`Desktop\souldevourer-promo\CLAUDE.md`

### 角色 IP（4 角色）
| 角色 | 定位 | 閉嘴/張嘴/特殊 |
|------|------|----------------|
| 衰仔 | 被電被坑受害者 | char-loser / char-loser-talk / char-loser-down |
| 怒哥 | 暴怒掀桌人體炸彈 | char-angry / char-angry-rage / char-angry-flip |
| 無嗑 | 噬魂代言Chad嗆人 | char-chad / char-chad-talk / char-chad-point |
| GM 闇 | 裁決者中二傲嬌 | char-gm / char-gm-talk / char-gm-ban |

### 製作規範速查
- 格式：16:9（1920x1080）
- 時長：10s / 15s / 20s / 短劇25-40s
- Pika LOGO：`frames-logo-fix/`（678x544，contain）
- 語音：Gemini TTS，衰仔Orus/怒哥Fenrir/無嗑Charon/GM Kore，抱怨角色1.25x加速
- 特效：閃光≤0.4、文字縮放≤2x、不旋轉、震動≤0.3s
- 文案：聳動中二白話嗆人
- **角色演出規則：角色先出現→文字才出現、文字不重疊、誰講話誰動嘴、一次只一人說話**

### 遊戲修改歷程
- 路徑：`Desktop\天堂更新檔\TEST2030修改歷程.txt`
- 格式規則：見 memory `reference_lineage_notepad_format.md`
