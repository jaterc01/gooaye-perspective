# gooaye-perspective

股癌 Gooaye / 謝孟恭的投資、產業觀察、生活判斷與表達操作系統。

這是一個 Codex/Hermes-style skill，基於本機 EP1-EP702 逐字稿與公開資料蒸餾，用來在使用者明確要求「股癌視角」「主委會怎麼看」「Gooaye perspective」時，輸出灰階、產業鏈、部位、風險與生活配置式的判斷框架。`whatmkreallysaid.com` 公開稿目前已同步到 EP693；EP694「EP694 | 🥖」、EP695「EP695 | 🍊」、EP696「考驗接著考驗」、EP697「you shall not pass!」、EP698「我們帶了翻譯結果大家都會講英文中文」、EP699「狗吹大時代開催倒數中」、EP700「ultimate father and son relationship」、EP701「願氣氛降臨 !」與 EP702「氣氛對了真相就淡薄了」目前是 SoundOn 暫定稿：EP694-EP700 使用 `medium` CUDA `float16`，EP701-EP702 因本機沒有 CUDA 裝置改用 `medium` CPU `int8`。歷史 `.raw.*` 檔案若存在仍保留作為溯源。EP702 新增 Radiohead 抽票與信念／平靜、AI token maxing 與企業成本治理、地端／open-weight 部署、十月盤面續航，以及光模組 BOM、DSP／Driver／TIA、non-China 與 Morgan Stanley 傳聞等內容。EP694-EP702 尚未逐句人工覆核，專有名詞、英文、人名、數字、贊助詞、晶片與產品名稱、歌曲、笑話、健康、家庭與槓桿內容仍有機器轉錄風險；未來公開稿出現後應優先替換暫定稿。

## Install

Clone this repo into your skills directory:

```bash
git clone https://github.com/jaterc01/gooaye-perspective.git ~/.codex/skills/gooaye-perspective
```

For Hermes:

```bash
git clone https://github.com/jaterc01/gooaye-perspective.git ~/.hermes/skills/gooaye-perspective
```

## Usage

Trigger phrases include:

- `用股癌視角看...`
- `主委會怎麼看...`
- `Gooaye perspective`
- `gooaye-perspective`

## Notes

This skill is a simulation based on public materials and transcript analysis. It does not represent 謝孟恭本人，也不提供個人化投資建議。
