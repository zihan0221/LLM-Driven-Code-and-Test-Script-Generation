## P0 Prompt 1
我直接把「飲料訂購系統.pdf」塞給claude
### 成果
![alt text](./images/image.png)

bug: 飲料訂購那些資訊需要塞成一個橫排的表格，如pdf中圖3-1的表格，但他沒有做到

![alt text](./images/image-1.png)

不算bug的bug: 題目會給一個csv，但我沒有丟csv給claude，所以他在js那邊模擬了一個csv，很有想法 


## P0 Prompt 2
按照成果1的bug去修，我丟給他以下截圖給的Prompt為「我希望飲料訂購部分的排版跟這個一樣，並重新給我完整的html5,css,js檔案」
![alt text](./images/image-2.png)

### 成果
基本就完成所有需求ㄌ
![alt text](./images/image-3.png)


### p1 Prompt
因為playwright他需要data-testid還有aria-label，所以重新叫Claude生了html5,css,js三個檔案，Prompt為「我想要把部分物件都加上data-testid、aria-label屬性，請重新幫我生出html5,css,js」

### 成果
跟上一個成果沒什麼不一樣

