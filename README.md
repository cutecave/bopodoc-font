# BopoDoc Font 波波注音字型

波波注音編輯器使用的開源字型集。

## 字型列表

### 波波標楷 BopoKai

以全字庫正楷體（TW-Kai）為基礎，逐字手動修正重心偏移，讓直書排版更整齊。目前已手修 10,251 字。英數符號換用 Noto Serif TC。

收字以教育部正字表為主，加上字嗨補集確保向下相容，共 29,978 個漢字：

| 集合 | 字數 | 說明 |
|------|-----:|------|
| 正字表 | 29,824 | 教育部《異體字字典》甲乙丙 N 四表 |
| 字嗨 | 13,435 | BpmfZihiKaiStd 收錄的國字 |
| 正字表 ∪ 字嗨 | 29,978 | 重疊 13,281 字，字嗨獨有 154 字 |
| 全字庫涵蓋 | 29,978 | 100%，缺 0 字 |

| 字型 | 來源字型 | 授權 |
|------|---------|------|
| 波波標楷 (BopoKai) | 全字庫正楷體 TW-Kai (數位發展部) + Noto Serif TC (Google/Adobe) | SIL OFL 1.1 |

### 波波純注音 Bopo RubyOnly IVS

利用程式將多款開源字型的注音符號，組裝成具體拼音的注音字型集。
IVS 發音與編碼方式皆遵從「注音IVS字型規格」的讀音表規則，使得使用者在多種 IVS 字體之間切換時，能夠得到一致的發音結果。

| 字型 | 來源字型 | 授權 |
|------|---------|------|
| 波波黑體純注音 (BopoSansRubyOnlyIVS) | Noto Sans TC (Google/Adobe) | SIL OFL 1.1 |
| 波波宋體純注音 (BopoSerifRubyOnlyIVS) | Noto Serif TC (Google/Adobe) | SIL OFL 1.1 |
| 波波圓體純注音 (BopoRoundRubyOnlyIVS) | 昭源環方 Chiron GoRound TC (Tamcy) | SIL OFL 1.1 |

注音字型的組裝方式：分別從各來源字型的多種字重取出注音符號重組合而成，避免注音字體過細。
聲調符號經過特殊處理，放大聲調符號使其更易於閱讀。並微調二聲落筆方向為從左而右，以符合台灣人習慣。

## 線上編輯器

免安裝使用字型請至 [波波注音](https://bopodoc.com)

## 授權

本字型依 [SIL Open Font License 1.1](https://openfontlicense.org/) 授權釋出。

來源字型的著作權屬於原作者：
- [全字庫正楷體 TW-Kai](https://data.gov.tw/dataset/5961) (數位發展部)
- [Noto Sans TC / Noto Serif TC](https://github.com/notofonts/noto-cjk) (Google/Adobe)
- [昭源環方 Chiron GoRound TC](https://github.com/chiron-fonts/chiron-go-round-tc) (Tamcy)

IVS 讀音表來源：
- [注音 IVS 字型規格 BpmfVS](https://github.com/ButTaiwan/bpmfvs)
