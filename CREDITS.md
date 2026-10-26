# 聲音實驗室 Music Lab — 素材記錄

## 樂器採樣

鋼琴、小提琴、長笛、小號、木結他：Nicholaus Brosowsky 與 tonejs-instruments contributors。
來源：https://github.com/nbrosowsky/tonejs-instruments
採樣授權：Creative Commons Attribution 3.0 (CC BY 3.0)
授權全文：https://creativecommons.org/licenses/by/3.0/
上游原始來源：鋼琴、弦樂及管樂標作 VSO2（Versilian Studios）；木結他標作 Iowa（University of Iowa）。完整來源見 audio/sample-source-info.txt；上游授權說明見 audio/tonejs-instruments-README.md。

本網站以原 MP3 檔儲存，執行時以固定音量校正、最近採樣音的音高比率、短淡入淡出及循環片段作按住延音。這是採樣演奏，並非聲稱所有音域均為真實樂器可演奏音域。力度差別以獨立增益保留。教師仍需以課室設備作主觀音色及音量審聽。

小鼓：Versilian Studios LLC / Sam Gossner，Versilian Community Sample Library。
來源：https://github.com/sgossner/VCSL
素材：Membranophones/Struck Membranophones/Snare Drum, Modern 3/Snare4_HitSN_v2_rr1_Mid.wav
授權：CC0 1.0，完整條款存於 audio/VCSL-LICENSE.txt。

每一份下載檔的 URL、大小及 SHA-256 記於 audio/manifest.json。本專案沒有使用外部 CDN 執行程式，也沒有追蹤碼。

## 音樂與畫面

C 大調共同旋律、C/G/F 配置及四拍分解型取自使用者提供的 2026 年按班別及日期修訂教案。未包含教材提及歌曲的商業錄音或樂譜。
三拍根音—三音—五音為獨立編寫的練習型，須由教師試聽確認；不是改寫學生原作。
「林間的光」三格 SVG 圖像與首屏音符圖為本專案原創。

2026-10-12 長笛更新：改用 University of Iowa Electronic Music Studios / Lawrence Fritts 錄音，演奏 Sonja Feig（April 2000），Flute.nonvib.pp。官方來源 https://theremin.music.uiowa.edu/MISflute.html ；使用條件 https://theremin.music.uiowa.edu/MIS.html （可下載並用於任何項目，無限制）。從官方 ZIP 的音階錄音抽取 C4、E4、A4、C5，轉成 PCM WAV，加 12 ms 邊界淡入淡出；沒有把其他樂器模擬成長笛。裁切位置與來源在 manifest.json。原長笛 MP3 留作開發比較，不再用於播放。
六款樂器 SVG 圖卡為本專案原創繪製。

認音鍵盤（keyboard/）：使用上述 tonejs-instruments 鋼琴採樣（CC BY 3.0）C4、D♯4、F♯4、A4、C5、D♯5、F♯5、A5、C6，裁剪至 3.2 秒並加淡出，其餘音高以最近採樣變調。
