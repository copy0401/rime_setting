# Mac_鼠鬚管主程式

### 安裝：

- 解壓縮 ⇨ 執行 Squirrel.pkg 安裝檔
（在預設輸入法中會有 鼠鬚管 選項，如沒有：「打開鍵盤偏好」 ⇨ 「+」「簡體中文」 ⇨ 選取 鼠鬚管 加入！）


### 安裝後建議修改：
    
- 修改 App 使 OS 默認 Squirrel 為繁體中文：
    - 於 /Library/Input Methods/Squirrel.app/Contents/Info.plist 把 Info.plist 中唯一的 \<string>zh\</string> 改成 \<string>zh-Hant\</string> ⇨ 《重開機》。

- 置換新版 librime 引擎：
    - 原 librime 在使用 lua 某些功能會產生記憶體泄漏問題，建議更換。
    - rime-with-plugins-1.7.1-osx.zip ⇨ dist ⇨ lib ⇨ 提取 librime.1.dylib ⇨ 取代 /Library/Input Methods/Squirrel.app/Contents/Frameworks/librime.1.dylib ⇨《重開機》！

### 可到官網 https://rime.im/ 下載安裝檔。

