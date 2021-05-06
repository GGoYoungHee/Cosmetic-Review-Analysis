# Cosmetic-Review-Analysis

- 진행날짜 : 2021.03.02 ~ (ing)

- 이번 플젝은 많은 코드를 올리지는 못할듯 싶다.
- 그래도 기본적인 모델 코드는 올려야지~
- 일단 이 플젝이 다 끝나고 올려야겠다.

</br>

- 원래 학과 수업의 일환으로 시작되었지만 어쩌다 보니 규모가 커지게 되었고 실제 데이터 분석이 기업에서 어떻게 쓰일 수 있을 것인지를 생각할 수 있는 기회가 되었다.
- 분석가의 관점뿐 만이 아니라 CEO의 관점에서 데이터 분석을 바라보는 것을 생각해보았다.
- 실제 회사에서 데이터 분석이 어떻게 쓰이는 지 경험해보고, 단순히 분석에서 끝나는 것이 아니라 분석 결과를 비즈니스 모델로 확장시킬 수 있는 지를 생각해 보았다.


</br>
- sparse한 데이터는 pca와 t-sne를 통해 차원축소로 해결하였다.

</br>

- 결국은 딥러닝 돌렸다!!
</br>


# 느낀 점

- 이번 프로젝트를 통해서 내가 뭘 좋아하는지, 어떤 데이터에 흥미있어 하는지를 좀 더 알아본것 같다.

- 이런 딥러닝을 사용한 프로젝트를 통해 도출된 결론을 가지고 남들을 설득시키는 것이 어렵다는 것을 알았고, 이 이유는 딥러닝에서 중요한 hidden layer (은닉층) 때문에 나온 블랙박스라는 딥러닝의 한계점이 있는 것 같다.

> 2020년도에 내가 가장 많이 생각했던 점이 예측만 잘 하면 되는거지 굳이 해석이 필요한가?라는 질문이다. 이 점이 아마도 머신러닝과 딥러닝의 차이점이 아닐까 싶은데 '블랙박스' 라는 특성이 왜 한계점인지를 잘 몰랐었다. 어쨋든 실제로 데이터 분석을 하는 곳에서는 예측이 목표라고 생각했던 과거의 나는 교수님한테도 물어보고, 여러 공모전도 나가면서 나름의 해답을 "설득"이라는 곳에서 찾았다. 데이터 분석 만으로 끝나는 것이 아니라 데이터 분석을 통해 매출을 증대시킨다던가, 정책 도입 등 다른 사람들이 데이터 분석의 결과를 이용하게 되는데, 이 때 정책 결정자나 회사의 CEO 등 다른 사람에게 분석 결과에 대해 설명하는데 '블랙박스'의 특성이 한계점이라고 생각했다. 이건 공모전에서 분석 결과를 파워포인트로 요약 정리 해서 발표하면서 느꼈다. 결국 데이터 분석 공모전이란, 나의 분석 결과를 심사위원들에게 설득시키는 과정이라고 느끼게 되었다. 모델구축 , 검증에서 끝나는 것이 아니라 한가지 단계가 더 남아있었던 것이다. 즉 데이터 분석의 목적은 예측 뿐 만이 아니라 예측값을 다른 사람들에게 설득시키기 위해 분석 결과에 대한 해석도 중요하다고 생각했다. 이 프로젝트에서 딥러닝을 많이 사용했는데, 다른 사람들이 은닉층에서 어떤 일이 일어나는 지를 궁금해했고, 나는 그저 "알 수 없다."라는 말 밖에 할 수가 없었다. 이 말은 받아들이는 사람도 답답해 했고, 딥러닝을 하나도 모르는 사람에게 분석 결과를 설명하면서 나도 조금 답답했다.



- 자연어 처리를 하면서 한국어가 복잡하고 신기한 언어임을 깨달았다.
- 또한 NLP가 시계열 데이터 분석과 비슷한 방향성을 가지고 분석한다는 것을 알았다.
- 단어의 순서를 시간의 변화로 보고 예측 / 분류 / 군집 등을 진행한다는 것이 정형데이터, 특히 시계열 데이터의 머신러닝 분석과 비슷한 느낌이었다.
- NLP도 딥러닝, 컴퓨터 공학이라고 생각했지만 결국 끝까지 파고 들어가면 통계가 나온다는 것을 알았다.
