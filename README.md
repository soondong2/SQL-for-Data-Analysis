# SQL for Data Analysis
![image](https://user-images.githubusercontent.com/100760303/210536699-5918281b-a4aa-44d6-9791-9ab4633ccbd1.png)

<br>

## 책 소개
- 데이터 준비부터 분석을 통한 인사이트 도출까지
- 데이터를 인사이트로 바꾸는 SQL 활용법
<br>

분석에 앞서 데이터를 준비하는 과정부터 실무에서 가장 활용도 높은 시계열, 코호트, 리텐션 분석 등 다양한 분석법을 알려준다.<br>
실제 데이터셋을 사용해 흥미로운 예제를 실습해보며 실전에 가까운 분석 경험을 쌓아보자.

<br>

## SQL 실습 환경 구축
- [PostgreSQL 설치 및 실행](https://github.com/soondong2/SQL_for_Data_Analysis/blob/main/PostgreSQL%20%EC%84%A4%EC%B9%98%20%EB%B0%8F%20%EC%8B%A4%ED%96%89.md)
## 데이터 준비
- [데이터 생성 코드](https://github.com/soondong2/SQL_for_Data_Analysis/blob/main/2%EC%9E%A5%20%EB%8D%B0%EC%9D%B4%ED%84%B0%20%EC%A4%80%EB%B9%84/date_dim.sql)
## 시계열 분석
- [데이터 생성](https://github.com/soondong2/SQL_for_Data_Analysis/blob/main/3%EC%9E%A5%20%EC%8B%9C%EA%B3%84%EC%97%B4%20%EB%B6%84%EC%84%9D/1.%20%EB%8D%B0%EC%9D%B4%ED%84%B0%20%EC%83%9D%EC%84%B1.md)
- 트렌드 분석
  - [간단한 트렌드 분석](https://github.com/soondong2/SQL_for_Data_Analysis/blob/main/3%EC%9E%A5%20%EC%8B%9C%EA%B3%84%EC%97%B4%20%EB%B6%84%EC%84%9D/2-1.%20%EA%B0%84%EB%8B%A8%ED%95%9C%20%ED%8A%B8%EB%A0%8C%EB%93%9C%20%EB%B6%84%EC%84%9D.md)
  - [요소 비교](https://github.com/soondong2/SQL-for-Data-Analysis/blob/main/3%EC%9E%A5%20%EC%8B%9C%EA%B3%84%EC%97%B4%20%EB%B6%84%EC%84%9D/2-2.%20%EC%9A%94%EC%86%8C%20%EB%B9%84%EA%B5%90.md)
  - [전체 대비 비율](https://github.com/soondong2/SQL-for-Data-Analysis/blob/main/3%EC%9E%A5%20%EC%8B%9C%EA%B3%84%EC%97%B4%20%EB%B6%84%EC%84%9D/2-3.%20%EC%A0%84%EC%B2%B4%20%EB%8C%80%EB%B9%84%20%EB%B9%84%EC%9C%A8.md)
- 시간 윈도우 롤링
  - [시계열 데이터 변화 이해를 위한 인덱싱](https://github.com/soondong2/SQL-for-Data-Analysis/blob/main/3%EC%9E%A5%20%EC%8B%9C%EA%B3%84%EC%97%B4%20%EB%B6%84%EC%84%9D/3-1.%20%EC%8B%9C%EA%B3%84%EC%97%B4%20%EB%8D%B0%EC%9D%B4%ED%84%B0%20%EB%B3%80%ED%99%94%20%EC%9D%B4%ED%95%B4%EB%A5%BC%20%EC%9C%84%ED%95%9C%20%EC%9D%B8%EB%8D%B1%EC%8B%B1.md)
  - [롤링 계산](https://github.com/soondong2/SQL-for-Data-Analysis/blob/main/3%EC%9E%A5%20%EC%8B%9C%EA%B3%84%EC%97%B4%20%EB%B6%84%EC%84%9D/3-2.%20%EB%A1%A4%EB%A7%81%20%EA%B3%84%EC%82%B0.md)
  - [희소 데이터와 시간 윈도우 롤링](https://github.com/soondong2/SQL-for-Data-Analysis/blob/main/3%EC%9E%A5%20%EC%8B%9C%EA%B3%84%EC%97%B4%20%EB%B6%84%EC%84%9D/3-3.%20%ED%9D%AC%EC%86%8C%20%EB%8D%B0%EC%9D%B4%ED%84%B0%EC%99%80%20%EC%8B%9C%EA%B0%84%20%EC%9C%88%EB%8F%84%EC%9A%B0%20%EB%A1%A4%EB%A7%81.md)
  - [누적값 계산](https://github.com/soondong2/SQL-for-Data-Analysis/blob/main/3%EC%9E%A5%20%EC%8B%9C%EA%B3%84%EC%97%B4%20%EB%B6%84%EC%84%9D/3-4.%20%EB%88%84%EC%A0%81%EA%B0%92%20%EA%B3%84%EC%82%B0.md)
- 계절성 분석
  - [구간 비교](https://github.com/soondong2/SQL-for-Data-Analysis/blob/main/3%EC%9E%A5%20%EC%8B%9C%EA%B3%84%EC%97%B4%20%EB%B6%84%EC%84%9D/4-1.%20%EA%B5%AC%EA%B0%84%20%EB%B9%84%EA%B5%90.md)
  - [작년과 올해 비교](https://github.com/soondong2/SQL-for-Data-Analysis/blob/main/3%EC%9E%A5%20%EC%8B%9C%EA%B3%84%EC%97%B4%20%EB%B6%84%EC%84%9D/4-2.%20%EC%9E%91%EB%85%84%EA%B3%BC%20%EC%98%AC%ED%95%B4%20%EB%B9%84%EA%B5%90.md)
  - [다중 구간 비교](https://github.com/soondong2/SQL-for-Data-Analysis/blob/main/3%EC%9E%A5%20%EC%8B%9C%EA%B3%84%EC%97%B4%20%EB%B6%84%EC%84%9D/4-3.%20%EB%8B%A4%EC%A4%91%20%EA%B5%AC%EA%B0%84%20%EB%B9%84%EA%B5%90.md)
## 코호트 분석
- [데이터 생성](https://github.com/soondong2/SQL-for-Data-Analysis/blob/main/4%EC%9E%A5%20%EC%BD%94%ED%98%B8%ED%8A%B8%20%EB%B6%84%EC%84%9D/1.%20%EB%8D%B0%EC%9D%B4%ED%84%B0%20%EC%83%9D%EC%84%B1.md)
- 리텐션 분석
  - [기본 리텐션 커브를 위한 SQL](https://github.com/soondong2/SQL-for-Data-Analysis/blob/main/4%EC%9E%A5%20%EC%BD%94%ED%98%B8%ED%8A%B8%20%EB%B6%84%EC%84%9D/2-1.%20%EA%B8%B0%EB%B3%B8%20%EB%A6%AC%ED%85%90%EC%85%98%20%EC%BB%A4%EB%B8%8C%EB%A5%BC%20%EC%9C%84%ED%95%9C%20SQL.md)
  - [리텐션 정확도 향상을 위한 시계열 조절](https://github.com/soondong2/SQL-for-Data-Analysis/blob/main/4%EC%9E%A5%20%EC%BD%94%ED%98%B8%ED%8A%B8%20%EB%B6%84%EC%84%9D/2-2.%20%EB%A6%AC%ED%85%90%EC%85%98%20%EC%A0%95%ED%99%95%EB%8F%84%20%ED%96%A5%EC%83%81%EC%9D%84%20%EC%9C%84%ED%95%9C%20%EC%8B%9C%EA%B3%84%EC%97%B4%20%EC%A1%B0%EC%A0%88.md)
  - [시계열 데이터에서 코호트 ](https://github.com/soondong2/SQL-for-Data-Analysis/blob/main/4%EC%9E%A5%20%EC%BD%94%ED%98%B8%ED%8A%B8%20%EB%B6%84%EC%84%9D/2-3.%20%EC%8B%9C%EA%B3%84%EC%97%B4%20%EB%8D%B0%EC%9D%B4%ED%84%B0%EC%97%90%EC%84%9C%20%EC%BD%94%ED%98%B8%ED%8A%B8%20%EB%B6%84%EC%84%9D%ED%95%98%EA%B8%B0.md)
  - [다른 테이블의 속성으로 코호트 분석](https://github.com/soondong2/SQL-for-Data-Analysis/blob/main/4%EC%9E%A5%20%EC%BD%94%ED%98%B8%ED%8A%B8%20%EB%B6%84%EC%84%9D/2-4.%20%EB%8B%A4%EB%A5%B8%20%ED%85%8C%EC%9D%B4%EB%B8%94%EC%9D%98%20%EC%86%8D%EC%84%B1%EC%9C%BC%EB%A1%9C%20%EC%BD%94%ED%98%B8%ED%8A%B8%20%EB%B6%84%EC%84%9D.md)
  - [희소 코호트 다루기](https://github.com/soondong2/SQL-for-Data-Analysis/blob/main/4%EC%9E%A5%20%EC%BD%94%ED%98%B8%ED%8A%B8%20%EB%B6%84%EC%84%9D/2-5.%20%ED%9D%AC%EC%86%8C%20%EC%BD%94%ED%98%B8%ED%8A%B8%20%EB%8B%A4%EB%A3%A8%EA%B8%B0.md)
  - [처음 날짜 대신 다른 날자를 기준으로 코호트 정의하기](https://github.com/soondong2/SQL-for-Data-Analysis/blob/main/4%EC%9E%A5%20%EC%BD%94%ED%98%B8%ED%8A%B8%20%EB%B6%84%EC%84%9D/2-6.%20%EC%B2%98%EC%9D%8C%20%EB%82%A0%EC%A7%9C%20%EB%8C%80%EC%8B%A0%20%EB%8B%A4%EB%A5%B8%20%EB%82%A0%EC%A7%9C%EB%A5%BC%20%EA%B8%B0%EC%A4%80%EC%9C%BC%EB%A1%9C%20%EC%BD%94%ED%98%B8%ED%8A%B8%20%EC%A0%95%EC%9D%98.md)
- 관련 코호트 분석
  - [생존자](https://github.com/soondong2/SQL-for-Data-Analysis/blob/main/4%EC%9E%A5%20%EC%BD%94%ED%98%B8%ED%8A%B8%20%EB%B6%84%EC%84%9D/3-1.%20%EC%83%9D%EC%A1%B4%EC%9E%90.md)
  - [리턴십 (반복 구매 행동)](https://github.com/soondong2/SQL-for-Data-Analysis/blob/main/4%EC%9E%A5%20%EC%BD%94%ED%98%B8%ED%8A%B8%20%EB%B6%84%EC%84%9D/3-2.%20%EB%A6%AC%ED%84%B4%EC%8B%AD(%EB%B0%98%EB%B3%B5%20%EA%B5%AC%EB%A7%A4%20%ED%96%89%EB%8F%99).md)
  - [누적 계산](https://github.com/soondong2/SQL-for-Data-Analysis/blob/main/4%EC%9E%A5%20%EC%BD%94%ED%98%B8%ED%8A%B8%20%EB%B6%84%EC%84%9D/3-3.%20%EB%88%84%EC%A0%81%20%EA%B3%84%EC%82%B0.md)
## 텍스트 분석
- [데이터 생성](https://github.com/soondong2/SQL-for-Data-Analysis/blob/main/5%EC%9E%A5%20%ED%85%8D%EC%8A%A4%ED%8A%B8%20%EB%B6%84%EC%84%9D/1.%20%EB%8D%B0%EC%9D%B4%ED%84%B0%20%EC%83%9D%EC%84%B1.md)
- [텍스트 파싱](https://github.com/soondong2/SQL-for-Data-Analysis/blob/main/5%EC%9E%A5%20%ED%85%8D%EC%8A%A4%ED%8A%B8%20%EB%B6%84%EC%84%9D/2.%20%ED%85%8D%EC%8A%A4%ED%8A%B8%20%ED%8C%8C%EC%8B%B1.md)
- [텍스트 변환](https://github.com/soondong2/SQL-for-Data-Analysis/blob/main/5%EC%9E%A5%20%ED%85%8D%EC%8A%A4%ED%8A%B8%20%EB%B6%84%EC%84%9D/3.%20%ED%85%8D%EC%8A%A4%ED%8A%B8%20%EB%B3%80%ED%99%98.md)
- 대규모 텍스트에서 문자열 찾기
  - [와일드카드 매칭(LIKE, ILIKE)](https://github.com/soondong2/SQL-for-Data-Analysis/blob/main/5%EC%9E%A5%20%ED%85%8D%EC%8A%A4%ED%8A%B8%20%EB%B6%84%EC%84%9D/4-1.%20%EB%8C%80%EA%B7%9C%EB%AA%A8%20%ED%85%8D%EC%8A%A4%ED%8A%B8%EC%97%90%EC%84%9C%20%EB%AC%B8%EC%9E%90%EC%97%B4%20%EC%B0%BE%EA%B8%B0%20-%20LIKE%2C%20ILIKE.md)
  - [정확한 매칭(IN, NOT IN)](https://github.com/soondong2/SQL-for-Data-Analysis/blob/main/5%EC%9E%A5%20%ED%85%8D%EC%8A%A4%ED%8A%B8%20%EB%B6%84%EC%84%9D/4-2.%20%EB%8C%80%EA%B7%9C%EB%AA%A8%20%ED%85%8D%EC%8A%A4%ED%8A%B8%EC%97%90%EC%84%9C%20%EB%AC%B8%EC%9E%90%EC%97%B4%20%EC%B0%BE%EA%B8%B0%20-%20IN%2C%20NOT%20IN.md)
- 정규 표현식
  - 정규 표현식을 활용한 패턴 매칭과 대체
- 텍스트 구성과 형태 변환
  - 문자열 연결
  - 텍스트 형태 변환
## 이상 탐지
- 정렬을 활용한 이상 탐지
- 백분위수와 표준편차를 활용한 이상 탐지
- 그래프를 활용한 이상 탐지
- 이상값의 형태
  - 예외적인 값
  - 예외적인 개수 또는 빈도
  - 데이터 결측으로 인한 이상값
- 이상값 처리
  - 삭제
  - 다른 값으로 대체
  - 리스케일
## 실험 분석
## 복잡한 데이터셋 생성
## 결론
