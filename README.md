# gooaye-perspective

股癌 Gooaye / 謝孟恭的投資、產業觀察、生活判斷與表達操作系統。

這是一個 Codex/Hermes-style skill，基於本機 EP1-EP710 逐字稿與公開資料蒸餾，用來在使用者明確要求「股癌視角」「主委會怎麼看」「Gooaye perspective」時，輸出灰階、產業鏈、部位、風險與生活配置式的判斷框架。`whatmkreallysaid.com` 公開稿目前已同步到 EP702；EP703-EP707 是 SoundOn `faster-whisper-medium` CPU `int8` 暫定稿，EP708 是同模型 CUDA `float16` 暫定稿，EP709-EP710 是同模型 CPU `int8` 暫定稿，並保留各集 `EP*.raw.*` 作為溯源。EP709 新增可持續訓練、iPhone Duo 適應期、Anthropic S-1／IPO 資金與稀釋、盤中確認、short covering 與相鄰資安題材；EP710 新增居家安全與投資風控、槓桿清洗、AI 資本支出重估、預測謙卑、半導體／軟體輪動、光通整併，以及家庭、創作與時間窗口。EP703-EP710 尚未逐句人工覆核，專有名詞、英文、人名、數字、股票代號、贊助詞、音樂、笑話、健康、家庭與槓桿內容仍有機器轉錄風險；未來公開稿出現後應優先替換暫定稿。

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
