# AWINLab_NewbieHW
新生作業
## Q1.
### 作業流程
1. 在 kaggle 裡找 most voted 的 notebook 參考寫法 <br> 
    Ref :
 [Mobile Price Prediction](https://www.kaggle.com/code/vikramb/mobile-price-prediction#Conclusion:-KNN-&-Linear-Regression-performed-the-best)、
 [Mobile Price Classification with SVM](https://www.kaggle.com/code/gulsahdemiryurek/mobile-price-classification-with-svm/notebook)
2. Read Data <br>
   Aim : 透過常見手機規格去預測手機價格(Range) <br>
   規格 ( 特徵 ) :
   * battery_power、blue、clock_speed、dual_sim、fc、four_g、int_memory、m_dep、mobile_wt、n_cores、pc、px_height、px_width、ram、sc_h、sc_w、talk_time
   、three_g、touch_screen、wifi、price_range
   * 電池充飽幾 mAh 、有無藍芽功能、clock 速度、有無雙 sim 卡功能、前鏡頭 pixel 數、4G ? 、內部記憶體空間、手機厚度、手機重量、幾核心、主鏡頭 pixel 數、解析度高、解析度寬、
   記憶體(RAM)、螢幕高度、螢幕寬度、最長使用時間、3G ? 、可觸控 ? 、有無支援 wifi 、價格帶 <br>
   
3. Date Analysis <br>
   尋找高相關性資料 : <br>
   * price range and ram 
   * 3G and 4G
   * pc(Primary Camera mega pixels) and fc(Front Camera mega pixels)
   * px_weight(Pixel Resolution Width) and px_height(Pixel Resolution Height)
   * sc_w(Screen Width of mobile in cm) and sc_h(Screen Height of mobile in cm) <br>
   
   **Feature selection** <br>
5. Model test and Performance metrics of different models ( SVM、 KNN 、 DT 、 RF )
6. Conclusion
7. Price prediction of Test.csv Using BEST model for Prediction
