# T-brain 永豐AI GO競賽-攻房戰

[Competition website](https://tbrain.trendmicro.com.tw/Competitions/Details/30)

這次的競賽使用了多種模型 
1. Gradient Boosted Trees
2. Random Forest
3. Cart Model
4. XGB
5. Multi-layer perceptron (MLP)

透過 1-4 的回歸模型得出輸出結果後再接以一 MLP 得到結果

結果:
1. Gradient Boosted Trees

![image](https://github.com/david965154/T-brain_AI_house_price_prediction/assets/145984683/7828e861-3f75-4c3c-bf54-2cabb5c23011)

2. Random Forest

![image](https://github.com/david965154/T-brain_AI_house_price_prediction/assets/145984683/b491b4db-59a0-47af-97ef-c32e4519fec1)

3. Cart Model

![image](https://github.com/david965154/T-brain_AI_house_price_prediction/assets/145984683/bc943f01-9e26-4869-bca0-0bdcce924805)

4. XGB

![image](https://github.com/david965154/T-brain_AI_house_price_prediction/assets/145984683/92470ebb-ca3e-4064-9301-c2fcde6a4909)

5. Multi-layer perceptron (MLP)

![image](https://github.com/david965154/T-brain_AI_house_price_prediction/assets/145984683/18ee402f-14f2-40cb-b180-52854f0a73fa)

事實上，可以透過看到 XGB 的表現較佳，在評估方式 MAPE (Mean Absolute Percentage Error) 下

![image](https://github.com/david965154/T-brain_AI_house_price_prediction/assets/145984683/c41bed7a-35a9-4af0-a0ce-ecadc28b0d5b)

最後結果也是 XGB 達到最佳 9.40 ，而組合則是 9.52 。

