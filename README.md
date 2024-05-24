# HW6

## 實驗步驟
Raspberry Pi 4 
刷機步驟：

- 下載 Raspberry Pi Imager。
  - 選擇相應的 Raspberry Pi OS（64位元）版本。
  - 將系統映像寫入 MicroSD 卡。
  - 將 MicroSD 卡插入 Raspberry Pi 4，連接電源、螢幕、鍵盤和滑鼠，開機。
  - 進行初始化設定，包括名稱、密碼、時區等。
  - 連接到網路，建議使用個人熱點以確保穩定性。

環境設定：

下載所需環境：
Arduino IDE
ESP32 Board Manager
DHT11 Library
ESP32_send_to_server.ino 範例檔案
修改 ESP32_send_to_server.ino 中的網路資訊（SSID、Password、ServerIP）。
在 Raspberry Pi 4 上安裝 Arduino IDE，可參考相關教材或使用 SetupArduinoIDE.sh 腳本。
啟動 Flask Server，執行 RESTful API。
在終端機中執行 app.py。
驗證：

從控制台中確認資料是否正確傳輸到 Raspberry Pi 4 的伺服器。
