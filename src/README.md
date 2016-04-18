# Rust 程式語言

歡迎光臨！本書將會讓你學會 [Rust 程式語言][rust]。
Rust 是專注在安全、速度、及並行（concurrency）等三項目標的系統程式語言。
它無需透過垃圾回收機制便可達成以上目標，也因此在其他語言所不擅長的領域（例如嵌入其他語言、在特定時間空間的限制下撰寫程式、撰寫硬體驅動、作業系統之類的底層程式碼等），Rust 也能大展身手。
相較於其他有相同目標的語言，Rust 更透過一些編譯期安全檢查，在不造成執行期額外負擔的情形下消除所有資料競爭（data races）問題。
Rust 同時也旨在實現「無成本抽象化」（zero-cost abstractions），雖然有些抽象化使其看起來像是高階語言，但 Rust 仍允許像低階語言一樣進行精確控制。

[rust]: https://www.rust-lang.org

《Rust 程式語言》被分為數個章節。
本簡介只是個開始，
後續還有：

* [準備][gs] - 替你的電腦設定 Rust 開發環境。
* [教學：猜謎遊戲][gg] - 透過一個小專案學習 Rust。
* [語法及語意][ss] - 將 Rust 細分為各個小部分。
* [Effective Rust][er] - 撰寫優良的 Rust 程式碼的高階概念。
* [Nightly Rust][nr] - 在穩定版中還沒有的最新功能。
* [詞彙表][gl] - 本書中所使用到的術語。
* [參考文獻][bi] - 關於 Rust 的文獻及論文。

[gs]: getting-started.html
[gg]: guessing-game.html
[er]: effective-rust.html
[ss]: syntax-and-semantics.html
[nr]: nightly-rust.html
[gl]: glossary.html
[bi]: bibliography.html

## 貢獻

用以產生本書的原始檔可以在 [GitHub][book] 找到。

[book]: https://github.com/rust-lang/rust/tree/master/src/doc/book

> 譯註：正體中文的翻譯原始檔位於此 [GitHub][book-zh-TW]，如有錯誤歡迎協助修正。
> 目前仍持續翻譯中⋯

[book-zh-TW]: https://github.com/askeing/rust-book


> *commit 3a6dbb3*
