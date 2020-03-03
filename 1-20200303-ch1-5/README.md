# 0303 First time

- Time: 2020/03/03 (Tue) 19:30 ~ 22:00
- Location：天瓏書局 (台北市中正區重慶南路一段 105 號 )
- Signup link: https://dddtaiwan.kktix.cc/events/dddtw-2020-studygroup
- Chapters: 1 ~ 5
- 簡報： [20200303_LegacyCodeStudyGroup](./20200303_LegacyCodeStudyGroup.pdf) [slide-share](https://www.slideshare.net/FongXuanLiou/legacy-code-1st-ch1-ch5-229598275)

## Note

1. Refactor 定義: 以不能修改功能為前提做軟體結構的優化。
2. Seam Model: 如果實作程式碼已經指定型別，那就無法進行 Seam
3. DDD Repository 偽物件

## 練習題 Feedback

- 在書中提到，安全的修改事每次修改時都有測試覆蓋住，否則就是依靠 IDE 的自動化重構功能(ex: extract method, rename...)避免程式碼出錯。但有些語言及 IDE 沒有這麼完善的重構功能，這樣就很難讓每次修改被測試包住，因此這一點可以自己做衡量，如果你在做的是標準重構動作（見《重構 改善既有程式碼》)，那就可以視情況將這個規則忽略。
- 其他做法
  - 包裝成內部 method 後用子類別覆寫
  - 抽成 Interface 建立 Mock 物件
  - 替換掉物件，僅傳資料進去

### 參考：

- [GitHub Repo](https://github.com/sandromancuso/trip-service-kata)
- [yt tutorial](https://www.youtube.com/watch?v=_NnElPO5BU0)
- [blog post](http://craftedsw.blogspot.com/2011/07/testing-legacy-hard-wired-dependencies.html)

## Feedback

- 可以考慮事前依語言分組 (19:00 ~ 19:30)
- 可以考慮事前先把練習題發給參與者先看過。
