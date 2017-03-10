#1.說明 Ruby 跟 Rails 有什麼不同?
A：
Ruby是一個程式語言，Rails是一個開發框架，裡面有很多套件可以使用。Ruby可以在Rails上開發。

#2.說明 Rails 裡的 MVC 大概是怎麼運作的？
A：
M為Model、V為View、C為Controller。
由route路徑對照表載入後，進入Controller進行比對，並找出相對Action執行。
當Action需要查閱細項時，會要求Model幫忙轉成SQL到資料庫裡要資料，取得想要查詢的資料後，送回Controller/Action的手上。
Controllr/Action要到資料後，跟View借畫面，讓資料轉成使用者易讀模式，呈現給使用者。
