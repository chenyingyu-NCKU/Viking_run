# Viking_run
This repo is for the unity homework of window programming. It is a Temple-Run-like game made with unity3D

Unity3D Homework
陳映伃 F74096247 

GitHub: https://github.com/chenyingyu-NCKU/Viking_run.git 

Environment: 開發使用 Mac (Intel chip)
本次作業我繳交了 Mac 跟 Windows 兩個版本（我只在電腦上測試過 Mac 版本的，運作上沒有問題）
Windows 我不敢確定，如過助教有發現問題，我會使用 Mac 做 Demo

Introduction:
一個類似 temple run 的小遊戲。
1. 使用上課時老師給的 package 做了大部分，音樂跟其他角色（追玩家的狼）使用 Asset Store 上的免費資源。
2. 玩家會一直跑（自動），中途可以暫停
3. 地板無限生成（有分一般地板跟跳躍地板，各有3、4種樣式，隨機生成）
4. 玩家透過吃紫色鑽石來獲得積分(coins)（並附有音效）
5. 玩家可以左右移動吃鑽石、能跳躍（不能雙跳）、能左右轉
6. 如果玩家被狼追到、或掉落地面，則死亡遊戲重來（直接重來，不會回到菜單）
7. 玩家的鑽石數以及生存時間（秒數）會顯示在螢幕最上方
8. Game Menu 菜單有三個按鈕：開始遊戲、如何遊玩、離開
9. 遊戲開始時會是時間為零、鑽石為零、角色靜止(idle)的狀態，按下空白鍵遊戲開始。中途也能按下空白鍵暫停遊戲
10. 角色在靜止、奔跑、跳躍的動畫中自由切換
11. 遊戲畫面有按鈕能回到菜單
12. 難度中（障礙物偏多）
（如果助教要從 GitHub 找 code 的話，會放在 /Asset/ Script/）


How To Play My Game:
1. 按Ａ、Ｄ向左右移動（操控角色吃鑽石）
2. 按Ｑ、Ｅ向左右轉（轉 90 度）（可以在空中轉向）
3. 按Ｗ（最好長按）跳躍，可以同時跳躍同時移動或轉向（但無法雙跳）
4. 按空白鍵能開始、暫停
（建議在 start point 先熟悉以上指令再按空白鍵開始遊戲，以免手忙腳亂）

Bonus:
1. 吃金幣音效、背景音樂（兩首）
2. 有要靠著一邊走的地板
4. 地板樣式隨機生成
3. How good my game is?
    (1) 善用 prefab 生成各種物件，Asset 中有一個 prefab 專用資料夾放置 地圖物件、鑽石等等
    (2) 地圖設計，我的地圖是方塊生成的，光是一般的地板方塊就有八種，可玩性很高
    (3) 特地去找符合遊戲的音樂以、角色（追玩家的狼）、字體，讓遊戲更美觀

FeedBack:
使用 Unity 做遊戲還是相當好入手的，debug的資源也多。
老師教得還算仔細，但是操作有點快，講得也偏快，前幾堂沒有老師的 code 在手上起來會有些吃力。
不過好在有錄影可以事後複習。
老師教的操作都是比較易懂的，這點我覺得很好。bug 抵起來比較不辛苦。
以上。
