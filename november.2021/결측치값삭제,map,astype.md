### 오늘의 궁금증 해결

- 특정 컬럼이 결측치인 값 삭제하기

       : 특정 컬럼이 결측치가 아닌 데이터 프레임 추출하는 법.

       ex) df[df['컬럼 명'].notnull()] 

       : 특정 컬럼이 결측치인 값 드랍하는 방법.

       ex) df.dropna(subset=['컬럼 명']) 

- 결측치 비율 확인

       : df.isnull().mean()*100 으로 결측치 비율을 확인하는데 비율의 의미가 헷갈렸던 부분.

       : 전체 행갯수 기준 결측치 행 갯수의 비율.

      

- map 함수

      : 예를 들어, df['a'].map(함수명) 라고 입력한다고 생각하면,

      : 'a' 컬럼의 값이 map 함수의 매개변수 속 함수명의 매개변수로 들어가서 출력되는 형태.

- astype 함수

      : 넘파이나 판다스에서 데이터프레임의 타입을 바꾸는 함수. 

      : dtype이 int인 컬럼을 str로 바꾸고 싶다면, df['컬럼명'].astype(str) 

      : 인덱싱해야하는 상황에 사용하기 좋을 것 같음.

### 오늘의 데이터공부 일기

전처리가 왜 오래걸린다는 지 알 것 같았던 하루였다. 전처리가 반드시 필요한 단계라는 것은 알겠지만, 결국은 프로젝트에서 내가 전하고 싶었던 것을 전달하는 데에 시간을 더 쓰고 싶은데.. 그럴려면 하드스킬을 더 늘리면 시간의 효율성이 성사되겠지! 

프로젝트 케이스 스터디를 하였는데, 아직은 감이 잘 안잡힌다. 항상 새로운 것을 기획하고 구현하는 쪽의 pt만 해왔어서 그런지.. 분석으로 인해 인사이트를 도출해내야하는 프로젝트는 내가 어떤 단계까지 해내야하는게 맞는건지 좀 헷갈리는 것 같다.
