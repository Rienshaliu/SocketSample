103062205 劉凌君 assignment8

1.一開始進入輸入ip的頁面然後輸入正確的ip之後，就會跟server連接，我把原本助教
給的submit按鈕刪掉，然後將原本的onclick留到計算去做，此時直接加入client start
，然後就跟server連接。
2.計算的部分寫在onclick()裡，在要跳到下一個頁面時，會傳送答案給server。將原本
寫在run()的out，把它變成global然後寫在這裡，傳送要server顯示的訊息。
3.顯示result的頁面

The problem I encoutered:
在一開始一直想不出來怎麼把submit改掉，變成案OK就可以連接，後來在研究一下，觀察
助教的code，有發現何時開始client的thread，進而解決了問題。