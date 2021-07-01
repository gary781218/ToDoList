# ToDoList

這是筆者第三個Side Project, 前2個專案都使用Winform設計GUI, 想開始嘗試切版及JavaScript, 故寫了這個小專案.

因為主要是想練習切版跟取dom, 故沒有太多複雜的功能, 僅能對工作清單執行新增、修改、刪除，完成的工作, 則可以勾選完成, 並歸檔至完成區.

![image](https://user-images.githubusercontent.com/49896529/124083311-4c8e5f00-da80-11eb-8b87-e0026e2c9346.png)

</br>

## 注意事項

原本資料儲存的工作，筆者是靠Firebase完成的, 但Firebase需要申請帳號, 且要在程式碼中加入金鑰. 筆者考量個滋問題, 故建立此版本. 筆者用Array產生test1至test4的初始資料, 但所有的動作都不會真的儲存, 僅限於當次使用, 重新開啟網頁後, 就會回到原本的模樣.若想使用Firebase，請參考[ToDoList-Firebase版](https://bitbucket.org/gary781218/todolist/src/master/)

</br>

#### 亮點

- 練習照著[設計稿](https://hexschool.github.io/THE_F2E_Design/todolist/#artboard0), 使用HTML及CSS進行切版
- 使用[FontAwesome](https://fontawesome.com/start)產生Icon
- 練習JavaScript-選擇不同的nav, 畫面是使用**JavaScript**進行渲染, 故僅有一個HTML檔