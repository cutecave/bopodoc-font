Bopo RubyOnly IVS Font 博璞純注音字型
========================================

本專案是利用程式將多款開源字型的注音符號，組裝成具體拼音的開源注音字型集。
IVS 發音與編碼方式皆遵從「注音IVS字型規格」的讀音表規則，使得使用者在多種
IVS 字體之間切換時，能夠得到一致的發音結果。


字型列表
--------

| 字型                                     | 來源字型                          | 授權        |
| 博璞黑體純注音 (BopoSansRubyOnlyIVS)    | Noto Sans TC (Google/Adobe)       | SIL OFL 1.1 |
| 博璞宋體純注音 (BopoSerifRubyOnlyIVS)   | Noto Serif TC (Google/Adobe)      | SIL OFL 1.1 |
| 博璞圓體純注音 (BopoRoundRubyOnlyIVS)   | 昭源環方 Chiron GoRound TC (Tamcy)| SIL OFL 1.1 |


組裝方式
--------

以上三種注音字型，分別從各來源字型的多種字重取出注音符號重組合而成，避免注音
字體過細。聲調符號經過特殊處理，放大聲調符號使其更易於閱讀。並微調二聲落筆方
向為從左而右，以符合台灣人習慣。


安裝方式
--------

Windows：雙擊 .ttf 檔案，點選「安裝」
macOS：雙擊 .ttf 檔案，在字體簿中點選「安裝字體」
Linux：將 .ttf 檔案複製到 ~/.fonts/ 或 /usr/share/fonts/


線上編輯器
----------

免安裝使用字型請至 波波注音 https://bopodoc.com


授權
----

本字型依 SIL Open Font License 1.1 授權釋出。
詳見 LICENSE.txt

來源字型的著作權屬於原作者：
- Noto Sans TC / Noto Serif TC: https://github.com/notofonts/noto-cjk
- 昭源環方 Chiron GoRound TC: https://github.com/chiron-fonts/chiron-go-round-tc

IVS 讀音表來源：
- 注音 IVS 字型規格 BpmfVS: https://github.com/ButTaiwan/bpmfvs
