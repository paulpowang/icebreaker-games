# 抽一張｜破冰遊戲 Icebreaker Games

手機就能玩的聚會破冰遊戲，中英雙語字幕，單一 HTML 檔，不需要後端。
A bilingual (Traditional Chinese / English) party game web app. One static HTML file, no backend.

## 遊戲 Games
- 💬 話題抽籤 Conversation cards（破冰、深聊、二選一、我從來沒有、戀愛）
- 🎲 真心話大冒險 Truth or dare
- 🙌 你比我猜 Charades（計時）
- 🗣️ 台語空耳 Taiwanese sound-alike
- 🤔 我是誰 Who am I?（手機舉額頭）
- 📜 紙條劇場 Slip theater（照劇本／主持人即興）
- 🕵️ 誰是臥底 Undercover（多機用房間碼，或傳一支手機）
- 🎋 抽籤 Draw lots（號碼制，可加名字、刪號碼、分組）

## 多機怎麼運作 How multi-phone works
手機之間不連線。大家輸入相同的房間碼、人數、局數，每支手機用同一個亂數種子算出一樣的結果，各自顯示自己號碼的內容。
Phones never talk to each other — the same room code seeds the same shuffle on every device.

## 部署到 GitHub Pages
1. 把 `index.html` 放在 repo 根目錄並 push。
2. Settings → Pages → Source 選 `Deploy from a branch`，Branch 選 `main`、資料夾 `/ (root)`。
3. 約一分鐘後開啟 `https://<帳號>.github.io/<repo>/`。

## 修改題庫 Editing content
題庫都在 `index.html` 的 `<script>` 開頭（`TOPICS`、`TRUTH`、`DARE`、`CHARADES`、`TAIGI`、`UNDERCOVER`、`WHOAMI`、`STORY_LINES`、`STORY_TALES`、`STORY_BRIDGES`），每筆格式為 `["中文","English"]`。

## 資料 Privacy
不收集任何資料。抽過的題目、抽籤名單、紙條只存在使用者自己的瀏覽器（localStorage）。
