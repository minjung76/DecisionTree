# DecisionTree
DecisionTree 결정트리 (연봉예측하기)
#장점
데이터에 대한 가정이 없는 모델입니다.
선형모델은 정규분포에 대한 가정이나 독립변수 종속변수의 선형관계를 가정으로 하는 모델인 반면 결정 트리는 데이터에 대한 가정이 없음으로 언제 어디서든지 적용할 수 있다.
아웃라이어의 영향을 거의 받지 않는다. 
트리 그패프를 통해 직과적으로 이해 설명이 가능하고 시각화에 탁월하다.
#단점
트리가 무한정 깊어지면 오버피팅 문제 발생
예측력은 떨어짐
#유용한곳
종속변수가 연속형, 범주형 모두 사용가능
모델링의 결과가 시각화할 목적이면 가장 유용
아웃라이어가 문제가 될 정도로 많으면 선형모델보다 더 좋은 대안이 됨
#데이터
연봉데이터
연봉이 50$ 이상인지 이하인지 예측 목표
종속변수는 class, 독립변수는 학력, 교육연수, 혼인상태
