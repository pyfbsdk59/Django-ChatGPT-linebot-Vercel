# Django-ChatGPT-linebot-Vercel
# 一個Django ChatGPT linebot快速建置於平台Vercel。


### [English](https://github.com/pyfbsdk59/Django-ChatGPT-linebot-Vercel/blob/main/README_en.md)
### [日本語](https://github.com/pyfbsdk59/Django-ChatGPT-linebot-Vercel/blob/main/README_jp.md)




#### 1. 初次上傳專案到github，請多包涵。初版沒有設置另外的.env檔案和環境變數。之後會改正。


#### 2. 本專案參考了以下前輩和官方的方案改成製作，只針對剛學習Python或Django的朋友來佈置linebot在Vercel上

https://github.com/howarder3/GPT-Linebot-python-flask-on-vercel<br><br>
https://github.com/vercel/examples/tree/main/python/django


### 3. 本以為只要把Flask的部分改為Django部分即可，但花了兩天，遇到了許多坑。主要就是因為使用Django會超過Vercel Function的50MB限制，嘗試了許多版本終於成功。主要就是裝了openapi的依賴後容量會大增。故在這版本我們只使用Django 2.0版本減少容量。我試過Django 3.2以上版本會Build失敗。若沒有其他特別需求，建議使用Django 2.0版本即可。也歡迎測試其他版本。

------
### Line和openai api設置請參考： https://github.com/howarder3/GPT-Linebot-python-flask-on-vercel
