# Let-s-Play-Fingerspelling
## Introduction
美國拼寫手語（ASL Fingerspelling）是利用特定手勢來表達特定的英文字母，可以補足一般手語系統中無法表示的概念，常用於表達人名、專有名詞。

現有的手語學習工具大多使用影片教學，對於學習手語拼寫的初學者而言缺少互動性和趣味性。
少數採用遊戲化的方式，卻採用「猜測圖片代表的手勢」， 缺少實際演練讓人很難提起學習興趣。  

本遊戲使用機器學習訓練的手語辨識模型來偵測玩家手勢，支援兩位玩家一同遊玩。兩位玩家根據畫面出現的英文單字，使用拼寫手語答題，透過遊玩與練習模式熟悉英文字母的手語手勢。

## Method & Library
程式介面：  
* OpenCV  
* PyQt5  
* Pygame  

手勢辨識模型：  
* MediaPipe  
* Scikit-learn  
* Google ASL Fingerspelling (Dataset)

![image](https://github.com/EmilyChang6/Let-s-Play-Fingerspelling/blob/main/Let%E2%80%99s%20Play%20Fingerspelling.PNG)
