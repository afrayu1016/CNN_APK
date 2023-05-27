# CNN_APK

## Learn
* 處理檔案和路徑
* 將特徵轉為向量，再轉為圖片
* Model : CNN , Random Forest , SVM
* 二元分類

## Context
Extract the original apk to predict wheather the Android app is a malware.
## Dataset
* Dataset : Total_feature.csv
* Index : apk filename
* Column:
  - features
  - label : 0 is benign, 1 is malicious
## Data Preprocessing
* Extract the users-permission features from .xml
* 若此apk擁有該特徵，則將該特徵的欄位在此筆資料設為1，反之則設為0
* 將轉為0和1的特徵向量轉為 256 * 256黑白圖片

## Predict
![image](https://github.com/afrayu1016/CNN_ART/blob/a9d78a7e317bf8d1a035c8de92bbf7964d5b073e/comparision.png)
