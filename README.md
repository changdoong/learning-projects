# learning-projects
배우면서 실습한 프로젝트 코드를 정리한 레포지토리이다.

# 파일 설명
## retail_data_df
### 소매 거래 데이터를 담고 있는 csv이다.
### 기본적으로 Dataframe을 다루는 방법을 공부한다.
> 사용 함수 정리
- groupby()[]
()열을 기준으로 []열을 그룹화한다.

- pd.DataFrame()
새로운 데이터프레임을 생성하거나 데이터 구조를 변환한다.

- TransactionEncoder()
리스트 형태의 거래데이터를 원-핫 인코딩 형태로 변환한다.

- transform()
그룹화 후 각 그룹에 맞춰 계산 결과를 원래의 형태에 맞게 다시 정렬한다.

- apriori()
거래 데이터에서 최소 지지도 이상인 **빈발 항목 집합** 추출한다.   
  **빈발 항목 집합**: 거래 데이터에서 자주 함께 등장하는 항목의 조합
  - apriori() 함수로 빈발 항목집합을 찾음
  - association_rules() 함수로 연관 규칙을 만든다

- association_rules()
빈발 항목 집합에서 신뢰도 향상도 등을 기준으로 연관 규칙을 추출한다.

- sort_values()
특정 열의 값을 기준으로 데이터를 정렬한다.

## pizza_df
### 피자 주문 정보 데이터를 담고 있는 csv이다.
### 데이터프레임 전처리를 통해 insight를 추출한다.
> 사용 함수 정리
- groupby()[]
()열을 기준으로 []열을 그룹화한다.

- merge(how='', on='')
다른 데이터프레임과 병합할 때 사용한다

- rename(columns={'' : ''})
해당 컬럼의 이름을 변경한다.

- unique()
특정 열의 고유한 값을 확인한다.

- to_datetime()
특정 열의 데이터타입을 datetime으로 변경한다.
 
- sort_values(ascending=False)
열을 기준으로 내림차순 정리한다.
