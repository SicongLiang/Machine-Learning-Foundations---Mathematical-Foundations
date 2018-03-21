Definition:improving some performance measure with experience computed from data

![PPT1](https://github.com/SicongLiang/Machine-Learning-Foundations---Mathematical-Foundations/blob/master/week1/3.JPG)

PS：KDDCup数据挖掘比赛

Application in Entertainment:Recommender System 
eg. viewer and movie都描绘成一串特征数字做乘法得到分数
pattern：rating <-- viewer/movie factors
learning：known rating
       -->learned factors
       -->unknown rating prediction

BASIC Notations:
(1)input x ∈ X(customer application)
(2)output y ∈ Y(good/bad after approving credit card)
(3)unknown pattern to be learned <--> target function:
 f: X --> Y(ideal credit approval formula)
(4)data <--> training examples: D = {(x1,y1),(x2,y2),...,(xn,yn)}(historical records in bank)
(5)hypothesis(假说) <--> skill with hopefully good performance:
 g: X--> Y('learned' formula to be used)
(6){(xn,yn)} from f --> ML --> g
(7)target f unknown(i.e. no programmable definition)
   hypothesis g hopefully ≈ f but possibly different from f (perfection 'impossible' when f unknown)
(8)assume g ∈ H = {hk},i.e. approving if
   h1:annual salary > NTD 800,000
   h2:debt > NTD 100,000(really?)
   h3:year in job ≤ 2(really?)
(9)hypothesis set H:
   can contain good or bad hypotheses
   up to A to pick the 'best' one as g
☆ learning model = A and H
(10)Practical Definition of Machine Learning: use data to compute hypothesis g that approximates target f
(11)relative fields:
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
1 When Can Machines Learn?
    Lecture 1: The Learning Problem
      •Course Introduction 
              foundation oriented and story-like
       •What is Machine Learning
              use data to approximate target
       •Applications of Machine Learning
              almost everywhere
       •Components of Machine Learning
              A takes D and H to get g
       •Machine Learning and Other Fields
              related to DM, AI and Stats

  •next: a simple and yet useful learning model (H and A)
2 Why Can Machines Learn?
3 How Can Machines Learn?
4 How Can Machines Learn Better?
