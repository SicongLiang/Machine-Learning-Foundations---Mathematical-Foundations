Definition:improving some performance measure with experience computed from data

![PPT1](https://github.com/SicongLiang/Machine-Learning-Foundations---Mathematical-Foundations/blob/master/week1/3.JPG)

PS：KDDCup数据挖掘比赛

Application in Entertainment:Recommender System 
eg. viewer and movie都描绘成一串特征数字做乘法得到分数
pattern：rating <-- viewer/movie factors
learning：known rating
       -->learned factors
       -->unknown rating prediction
       
![PPT2](https://github.com/SicongLiang/Machine-Learning-Foundations---Mathematical-Foundations/blob/master/week1/4.JPG)

BASIC Notations:

![PPT3](https://github.com/SicongLiang/Machine-Learning-Foundations---Mathematical-Foundations/blob/master/week1/5.JPG)

![PPT4](https://github.com/SicongLiang/Machine-Learning-Foundations---Mathematical-Foundations/blob/master/week1/6.JPG)

![PPT5](https://github.com/SicongLiang/Machine-Learning-Foundations---Mathematical-Foundations/blob/master/week1/7.JPG)

![PPT6](https://github.com/SicongLiang/Machine-Learning-Foundations---Mathematical-Foundations/blob/master/week1/8.JPG)

Practical Definition of Machine Learning: use data to compute hypothesis g that approximates target f

relative fields:
    -Data Mining:use (huge) data to find property that is interesting
      •if ‘interesting property’ same as ‘hypothesis that approximate target’  
        — ML = DM (usually what KDDCup does)
      •if ‘interesting property’ related to ‘hypothesis that approximate target’
        — DM can help ML, and vice versa (often, but not always)
      traditional DM also focuses on efficient computation in large database
 ☆ difficult to distinguish ML and DM in reality 

   -Artificial Interlligence:compute something that shows intelligent behavior
     •g ≈ f is something that shows intelligent behavior
       — ML can realize AI, among other routes
     •e.g. chess playing
       traditional AI: game tree
       ML for AI: ‘learning from board data’
☆ ML is one possible route to realize AI

   -Statistics:use data to make inference about an unknown process
     •g is an inference outcome;f is something unknown
       — statistics can be used to achieve ML
     •traditional statistics also focus on provable results with math assumptions, and care less about computation
☆ statistics: many useful tools for ML

Summary

![PPT7](https://github.com/SicongLiang/Machine-Learning-Foundations---Mathematical-Foundations/blob/master/week1/9.JPG)

