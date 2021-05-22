1. 練習使用一個民生物聯網 API，例如空氣、地震等感測站所回傳的紀錄資料。
參考資料網址： https://ci.taiwan.gov.tw/dsp/environmental.aspx

[中央氣象局地震監測站 SensorThings API 服務網址](https://sta.ci.taiwan.gov.tw/STA_Earthquake_v2/v1.0/Things?$filter=substringof(%27%E8%99%9F%E5%9C%B0%E9%9C%87%27,name)&$count=true)
圖片中可以看到資料格式是json，可以用python讀取後，再去進行之後的資料處理或分析
![image](https://user-images.githubusercontent.com/28143255/119228708-d9bbcb00-bb46-11eb-9e7f-435449739966.png)

2. 練習操作 OGC SensorThings API，將環保局測站位置的資料抓取下來，並且觀察下載資料的內容。
參考網址：https://sta.ci.taiwan.gov.tw/STA_AirQuality_EPAIoT/v1.0/Things



3. 依據作業 2 所下載的各個環保局測站感測器的描述資料，進一步點選 Datastreams、Locations，以及 Datastreams 點選進入後，點選 Observations 的 URL，觀察所下載到的資料內容，其中 Observations 內部是否包含個別感測器紀錄的資料。
