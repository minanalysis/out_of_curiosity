### 오늘의 궁금증 해결

- [판다스] 함수와 attributes의 차이

       [attributes는 값을 받고 싶을 때 사용 / 함수는 어떠한 parameter에 대한 값을 받고 싶을 때 사용]

      함수는 ()를 써주는데, attributes는 속성값을 전체출력하는 것이기 때문에 괄호를 쓰지 않는다. 

      함수의 경우 ()안에 특정 옵션을 지정할 수 있음. 
     [시리즈 attributes](https://pandas.pydata.org/docs/reference/series.html)

     [데이터프레임 attributes](https://pandas.pydata.org/docs/reference/frame.html?highlight=attributes)

     출처: 판다스 공식사이트 https://pandas.pydata.org/docs/index.html](https://pandas.pydata.org/docs/index.html)

- 매개변수와 인수

  매개변수는 함수에 입력으로 전달된 값을 받는 변수를 의미하고 인수는 함수를 호출할 때 전달하는 입력값을 의미한다.

  ```
  def add(a, b):  # a, b는 매개변수
  return a+b

  print(add(3, 4))  # 3, 4는 인수
  ```
  출처: 점프투파이썬 [https://wikidocs.net/24](https://wikidocs.net/24)


- [판다스] loc 이용해서 필터한 칼럼Series 출력하기

      예시} 'fare'가 500보다 큰 값을 출력하시오. 

      내가 풀었던 방식 → df[df['fare']>500]['fare']

      강사님이 사용하신 방식 → df.loc[df["fare"]>500, "fare"]

### 오늘의 데이터공부 일기

파이썬 1회차 수업 때보다는 수업내용을 알아들을 수 있어서 좋다. 100%를 수업시간에 내꺼로 만들진 못하지만, 복습하면서 온전히 나의 것으로 만드는 것도 뿌듯하다🙂 

강사님께서 과제를 리뷰해주셨는데, 내가 사용한 방식이 아닌 새로운 방식으로 더 효율적으로 데이터를 출력할 수 있다는 것이 놀라웠다. 

내 방식만이 정답이라는 생각은 정말 하지 말어야지. '커뮤니케이션 역량이 중요합니다.' 항상 두루뭉퉁하게만 다가왔던 이 문장이 분석을 배우면서 왜 중요하다는 지 체감해 가는 중이다. 

-민아는 발전중 😛
