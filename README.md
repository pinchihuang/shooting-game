## 射擊遊戲
#### 組員:
a班 111321007陳郁芳、 111321021黃品齊
#### 修改專案:
105321030_陳佳馨_105321036_蔡佩紘:射擊遊戲(原名：打鬥遊戲)
### 基本(原本)功能
* 這個遊戲是需要兩個玩家a、b，a、b玩家都能分別做上下左右的操作，a，b玩家各有一個攻擊鈕和防禦鈕，玩家發射一顆子彈後，直到子彈消失在邊界才能再次攻擊，打到對方可以讓對方血量減一，若對方成功防禦則血量不變，直到其中一方血量歸零,則顯示出遊戲結果(平手、綠色勝利、紅色勝利)。
### 新增功能
* 射擊打到對手成功扣血時增加逼逼聲。
* 增加雙方子彈數量限制，子彈用完無法再發射，雙方皆用完子彈，但未有一方血量歸零，則算做平手。
* 攻擊會大範圍發射子彈(1->3)。
* 為了方便觀察，操作方面將雙方的血量用紅色LED和綠色LED區分開來(FPGA選擇不同的顯示)。
* 修改成不一樣的成功顯示畫面。
1. 平手(雙方子彈都用完但仍未分出勝負時，或是血量同時用盡時)
  ![image](https://github.com/pinchihuang/shooting-game/blob/main/%E5%B9%B3%E6%89%8B.jpg)
2. 紅色勝利
  ![image](https://github.com/pinchihuang/shooting-game/blob/main/%E7%B4%85%E8%89%B2%E5%8B%9D%E5%88%A9.jpg)
3. 綠色勝利
  ![image](https://github.com/pinchihuang/shooting-game/blob/main/%E7%B6%A0%E8%89%B2%E5%8B%9D%E5%88%A9.jpg)


