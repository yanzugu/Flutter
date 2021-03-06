# Flutter

## Flutter 在 visual studio code 上的環境架設
### 需求 : 
* [VS code](https://code.visualstudio.com)
* [Android Studio](https://developer.android.com/studio)
* [flutter SDK](https://flutter.dev/docs/get-started/install/windows)

## 步驟
### Flutter
* 1.安裝 flutter SDK 將其解壓縮至任意資料夾。
* 2.將 ~[ YOUR PATH ]\flutter\bin 路徑加至環境變數。

### Android Studio
* 1.安裝 Android Studio。
* 2.透過 SDK Manager 依照需求安裝 SDK。
* 3.透過 AVD Manager 安裝模擬器。

### VS code
* 1.安裝 Flutter Extension.
* 2.安裝 Android OS Emulator Extension.
* 3.右鍵點擊 Android iOS Emulator -> Extension settings -> Emulator Path 輸入 ~[ YOUR PATH ]\Android\Sdk\emulator
* 4.按 F1 搜尋 Flutter New Application Project 點擊以新增專案 (注意 : 專案路徑中不能含有 non-ascii 字元)。
* 5.在 terminal 中輸入 flutter doctor 檢查環境，並依照指示完成。
* 6.按 F1 搜尋 Emulator 點擊並選則模擬器 / Flutter Emulaor。
* 7.若環境及模擬器均沒有問題，則在 terminal 中輸入 flutter run / Press F5.
