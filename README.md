# social-anxiety-VR
設計減緩社交焦慮情緒之虛擬實境遊戲系統
作者:劉靖絹、林旻萱、馮雅婕

此 project限CUTY lab成員觀看禁止分享。
包含整個研究的系統實作、實驗流程、實驗數據。部分治療流程參考至其他研究。
reference 請到論文裡面用 Ctrl+F 尋找。

## 動機
實驗動機及研究問題請參閱國科會結案報告。

## 系統實作
- 確立任務的設計及遊戲的背景
* 五項任務設計：參照事前問卷的結果進行設計
+ 遊戲背景：使用奇幻世界設定增加遊戲化程度，提高使用意願
### VRChat 
- 免費大型多人線上虛擬實境遊戲平台，
* 支援虛擬實境頭戴式顯示器，也可以使用PC設備達成跨平台的連線
+ 大型開放的平台使尋找互動者變得更加容易，降低使用者的使用成本
+ 對於連線與設備的要求並不高
+ 使用 VRCHAT Creator Companion 創建專案進行開發
### Unity
- 層級式的綜合開發環境、視覺化編輯、動態的遊戲預覽
- 龐大的素材庫，遊戲場景的搭建以免費素材完成

### 使用 c# 進行遊戲腳本的撰寫
- 以 First-person perspective設計：FPSDisplay.cs
- 搭配使用udon programs撰寫 Triggers，讓玩家角色可以與遊戲世界的物件互動，讓系統設計更加遊戲化
- 任務進行時可以拾起場景內的物件與其他角色互動


任務完成時則透過提示音的響起及任務成就的達成清單


### 非玩家角色（Non-Player Character）塑造
- 使用Readyplayer.me製作角色模型
  https://readyplayer.me/?slug=avatars
- 使用Blender將角色模型微調以及轉換檔案
- 將角色模型匯入maximo.com中，輸出角色動畫
  https://www.mixamo.com/#/
- 於unity中利用Animator Controller融合模型及動畫

### 使用者實驗
- 投放事前問卷：使用Liebowitz社交焦慮量表（LSAS）作為資料收集用途，數據用於得知系統需實作哪些情境，以及得知群眾之焦慮程度分布。

於系統完成後開始進行使用者實驗，實驗流程參閱實驗說明簡報。



數據分析 質化量化



主題式分析：https://miro.com/app/board/uXjVNIfWKlw=/?share_link_id=526362842827

vrchat世界網址:
https://vrch.at/jq4hqd3d

實驗說明：
https://www.canva.com/design/DAFwMIFgE6g/Q3QDVjyX9dCsOXAsRDNx3w/edit?utm_content=DAFwMIFgE6g&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton

心理教育：
https://www.canva.com/design/DAFwdlSZHTk/jgRsHepNFLOjEKaQY2a0WA/edit?utm_content=DAFwdlSZHTk&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton

