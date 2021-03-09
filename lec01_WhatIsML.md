# What is MachineLearning

*  ## *Machine Learing*
  
    프로그램자체가 데이터를 가지고 학습
    
    * 학습방법에따라 supervised/ Unsupervised learning으로 나뉜다.
    1. ### *Supervised Learning*

        정해져있는 데이터 이미 label들이 정해져있다 이를 트레이닝셋이라 부른다.

        ex) 사진을 보면 무엇인지 알아맞추기

        트레이닝 데이터 셋: 라벨로 학습을하면 모델이 발생 예상값을 ML이 내놓으면 그중에 답을 말해준다 ML에 넣어주는 label, data를 말한다. 

        알파고 또한 기존에 사람들이 둔 바둑들을 가지고 학습 사람들이 둔 바둑들, 데이터를 슈퍼바이져셋
        
        *Type of supervised learning* 
        1. regression

            ex) 시험성적 0~100 범위가 넓음

                x(hours) | y(score)
                ---------|---------
                10 | 90
                9 | 80
                3 | 50
                2 | 30

                x=7이면 y는 얼마인가??

        1. binary classification 
        패스하였나 안하였나 두가지로 나누어보자

            ex)

                x(hours) | y(P/F)
                ---------|---------
                10 | P
                9 | P
                3 | F
                2 | F

                결과가 등급으로 나뉨-> classification
                그중에서도 Pass/Fail 두가지로 나뉨 ->binary

        1. multi-label classification
            
            ex) 학점 ABCDE 많다.
            
                x(hours) | y(P/F)
                ---------|---------
                10 | A
                9 | B
                3 | D
                2 | F

                결과가 등급으로 나뉨-> classification
                등급이 여러개 -> multi

    2. ### *Unsupervised Learning: un-labeled data*
   
        ex) Google news grouping, Word clustering
        일일이 label을 줄수없다. 자동으로 뉴스들을 그루핑 유사한것들을 모음, 비슷한 단어들을 모음--> 데이터를 가지고 스스로 학습한다.
    
    주로 *supervised learning* 을 다룬다. 데이터를 가지고 학습
        
