# Webdev Learning

## GitHub & Vercel URL

[Git Hub URL](https://github.com/CatsSky/1111-web-demo-410418064)

[Vercel URL](https://1111-web-demo-410418064.vercel.app/index.html)

## Hero

在Hero頁面上我將背景圖片換為我所拍攝的一張夕陽風景照，我在hero的`section`內加上一個span並透過`::after`將照片覆蓋上半透明的純色背景。

![](https://i.imgur.com/jnTrUx8.jpg)
![](https://i.imgur.com/z0HDjV6.png)

## Works

在作品集中我放上過去做過的repo，附上超連結並重新排版。

![](https://i.imgur.com/5a7wNwt.png)

## Resume

### Skills

我是以整個homepage作為自己的resume，放上了自己技能的程度敘述。

![](https://i.imgur.com/gKhNOps.png)

### Canvas

在連絡方式的地方我將背景換上類似matrix特效的動態效果，效果的實作是利用HTML5的`canvas`繪製。

![](https://i.imgur.com/R3jEDDt.png)

### Timeline

在最後時間軸的地方我利用javascript的監聽器變更`element`的`class`屬性達到滾動時觸發的淡入淡出/移動的transition。

![](https://i.imgur.com/NbWJ6q5.png)

## 心得

這次期末的開放考題我是以老師上課所教的網頁作為基礎，其中找了幾個我覺得可以再補充的地方做了修改。
大部分運用到的都是老師上課時教過的，像是hero背景的半透明mask、grid-area重新排版。Timeline的transition算是用到scroll listener和transform的tag，比較麻煩一點。
另外有趣的是matrix的canvas背景，這個部分是使用js作繪製，先根據canvas大小選擇列的數量，並從中隨機生成一批2D Point在不同座標上，然後以這些座標作為亮點的開端在後面作上漸層的trailing。

這次的作業完成度並不算太高，但是在做的過程中我還是有學到不少東西。我主要專長並不是網頁前端，也不算個富創造力、想像力的人，所以也只能照著版式修改，憑著這次的經驗與收穫，也許以後有機會要做full-stack時我也不會那麼不知所措吧！