# Baccarat V4 Android｜自動學習分析版

## 功能
- 莊／閒牌面輸入
- 自動計算百家樂結果
- 自動保存歷史局
- 簡化路單顯示
- 莊／閒／和統計
- 線上自動學習：每局結算後更新模型權重
- 預測前的模型機率
- 總命中率、最近100局命中率
- 本機 SharedPreferences 保存資料
- GitHub Actions 自動編譯 APK

## 重要限制
這不是可以保證預知下一局結果的系統。百家樂結果具有隨機性；「自動學習」只是讓模型根據已輸入的歷史資料調整統計權重。命中率可能隨樣本、牌靴與隨機波動改變。

## GitHub 編譯
1. 建立 GitHub Repository
2. 上傳整個專案
3. Actions -> Build Baccarat V4 APK
4. 完成後在 Artifacts 下載 `BaccaratV4-debug`

## 輸入格式
莊：K 8
閒：7 2

也可使用 A、2~9、10、J、Q、K。
