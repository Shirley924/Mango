# Mango
A contest for mango sorting
1.	Model：
  i.	Architecture

![image](https://user-images.githubusercontent.com/58549322/112744493-249be500-8fd3-11eb-9dd0-0d270c1189f0.png)

2.	Preprocessing：
  i.	Method:
  (i) 我把所有的圖片resize成相同大小(200 X 200)s，因為是彩色圖片，所以維度為3，再加上label，故input為：(200,200,3,X)
  (ii) 接著利用特徵增強將resize過的圖片做變化
  (iii) 放入模型當中等訓練結果
  (iiii) 最後拿訓練過的模型對test data進行測試
  
  ii.   Example：
  * 第一張圖片處理前後結果  
  處理前  <img src="https://user-images.githubusercontent.com/58549322/112744660-a80a0600-8fd4-11eb-8ea2-161e01954fcf.png" width="300"/> 處理後![image](https://user-images.githubusercontent.com/58549322/112744853-2c10bd80-8fd6-11eb-9fab-2af0c5f02618.png)


  * 第二張圖片處理前後結果
  
   處理前  <img src="https://user-images.githubusercontent.com/58549322/112744793-aab92b00-8fd5-11eb-9b23-e47c322a0720.png" width="300"/>  處理後![image](https://user-images.githubusercontent.com/58549322/112744841-113e4900-8fd6-11eb-8166-d43535b5cfa1.png)

