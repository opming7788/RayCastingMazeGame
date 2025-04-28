# 3D Maze Exploration Game (Raycasting)

使用 HTML、CSS、JavaScript 開發的基於 **射線投射 (Raycasting)** 技術的 3D 迷宮探索遊戲。  
玩家可以透過 **鍵盤方向鍵** 在迷宮中移動，體驗類似早期 3D 遊戲（如 Wolfenstein 3D）的第一人稱視角效果。
<a href="https://opming7788.github.io/RayCastingMazeGame/RayCasting.html">開始遊玩</a>
---

## 遊戲特色

- 🧭 2D 鳥瞰地圖在網頁左側顯示
- 🎯 3D 第一人稱視角畫面在網頁右側渲染
- 🕹️ 使用鍵盤方向鍵控制移動與轉向
- 🧱 實時射線投射，模擬牆面與深度感

---

## 使用技術

- **HTML / CSS**
  - 畫面排版與樣式設計
- **JavaScript**
  - 遊戲邏輯控制
  - 射線投射 (Raycasting) 演算法實作
- **Canvas API**
  - 繪製 2D 地圖
  - 渲染 3D 視角畫面
- **演算法**
  - 射線投射（Raycasting）
  - 數位微分分析器（DDA，Digital Differential Analyzer）
  - 向量數學運算
  - 視覺深度模擬

---

## 如何運行

1. 將專案 clone 到本地：
    ```bash
    git clone https://github.com/你的帳號/你的倉庫.git
    ```
2. 瀏覽器打開 `RayCasting.html` 即可直接在瀏覽器中遊玩。

---

## 參考技術概念

- **Raycasting 射線投射**  
  從玩家視角向前投射多條射線，利用 DDA 演算法偵測與牆體的交點，計算距離並渲染出正確比例的牆面。
  
- **DDA 數位微分分析器**  
  一種逐步推進的線段穿越演算法，用於在格子地圖上快速找到光線與牆體的交點。

---

![image](https://github.com/user-attachments/assets/9ea4bc37-8cb0-4c3b-befd-031c7832fd0b)


---

## 授權 License

本專案採用 [MIT License](LICENSE) 授權。
