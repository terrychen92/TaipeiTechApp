TaipeiTechApp
====

這個App從一開始只有課表查詢並且在全體學生分享Apk給大家用，到後來增加wifi自動連線、學分計算功能和上架到Play Store，是作者大四時為學習開發Android App而做，這App上架近三年來累計了7338位使用者安裝，每次看到每一個學年度開始，使用者的增加幾乎是北科一屆學生的人數，還滿開心有這麼多人使用，也認識了其他平台(Web、iOS、WinPhone)的開發者，一起討論機制怎麼登入學校網站，算是作者大學時最後的作品。

作者經過一個洗澡的時間，思考自身是社會人士，App與這個專頁都是作者自己經營，上班之餘實在無力更新和維護，沒辦法全心全意照顧各位使用者及提供更便利的服務，所以決定終止這個App的服務。

這是我自己的最後一版，歡迎有興趣的人繼續開發下去。20161120

[Play Store上的介紹](https://play.google.com/store/apps/details?id=com.taipeitech)
----

歡迎加入國立臺北科技大學！  
開始上課了，想查上課時間、地點、修課學分，這個App幫你到校園入口網站抓你想要的資訊，有任何想法都可以告訴我！

####App功能：

1.活動報報  
讓社團及系學會發布活動資訊進行宣傳

2.行事曆  
更新、離線瀏覽該學年度行事曆

3.課表查詢  
讓在校生查詢學生學期課表，並提供離線瀏覽，與Widget結合在桌面瀏覽

4.學分計算  
個人歷年學分計算及畢業學分標準查詢，提供博雅修課狀況瀏覽，可調整課程類別模擬學分數


本App非官方授權，請自行斟酌。

99 CSIE Alan Chiou 20150227

檔案介紹
----
Document資料夾內放著以下檔案

1. 過去每一版Release的Apk

2. 每次更新活動報報的檔案(圖檔和App讀取的格式)

3. App讀取的行事曆的格式

4. 學分計算與離線課表的教學圖檔

5. 各種icon的檔案

除了Ducument資料夾以外的檔案都是Android Studio Project檔案，直接下載Zip檔案大約50.8 MB。

單純程式碼的話只有1.3 MB。

已知的 Issue
----

1\. App本身在[AndroidManifest.xml](taipeiTech/src/main/AndroidManifest.xml)宣告了

`android:installLocation="auto"`

如果App被安裝到外部儲存空間，會造成部分功能無法使用，例如：課表Widget、活動報報的活動通知。

參考官方說明 https://developer.android.com/guide/topics/data/install-location.html#ShouldNot

相關連結
----

[Play Store](https://play.google.com/store/apps/details?id=com.taipeitech)

[Facebook粉絲專頁](https://www.facebook.com/TaipeiTechApp/)

[聯絡作者](mailto:ce173310@gmail.com)