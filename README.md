# BMI 計算機 (Windows Forms 應用程式)

## 📖 專案簡介
這是一個使用 C# 與 Windows Forms (.NET Framework) 開發的 BMI (身體質量指數) 計算機。
除了具備基礎的 BMI 數值計算與體位評估功能外，還加入了輸入防呆機制，並實作了深色模式 (Dark Mode) 以提升介面質感與使用者體驗。

## ✨ 功能特色
* **基礎計算**：輸入身高 (cm) 與體重 (kg)，計算出 BMI 數值 (顯示至小數點後兩位)。
* **體位評估**：根據標準自動判斷體重狀態 (如：健康體位、輕度肥胖等)，並以不同顏色標示結果。
* **防呆機制**：自動檢查使用者是否輸入非數字或不大於零的數值，若輸入錯誤會跳出警告視窗，避免程式碼發生例外錯誤。
* **深色模式切換**：提供一鍵切換深色/淺色主題的 CheckBox，動態改變視窗與文字顏色。

## 🚀 執行說明
1. 確保電腦已安裝 Visual Studio 2022，並包含「.NET 桌面開發」工作負載。
2. 將此專案下載至本機。
3. 點擊開啟 `BMI計算機.sln` 解決方案檔。
4. 在 Visual Studio 中按下 `F5` 或點擊上方「開始」按鈕即可編譯並執行程式。

## 📸 執行截圖

**1. 正常淺色模式與計算結果**
<img width="800" height="484" alt="image" src="https://github.com/user-attachments/assets/ce734036-60a8-4eb1-aa3a-c59ae6702aac" />


**2. 深色模式 (Dark Mode) 介面**
<img width="798" height="476" alt="image" src="https://github.com/user-attachments/assets/776cfa00-0398-468b-99ab-45d43a5d3c15" />
