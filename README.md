# TIL
## 2023-04-28
### 레브잇 그로스세션 참석
* MVP 테스트부터 시작한 빠른 실험과 피드백 루프
* 성장에 정체가 왔을 떄, 전사 지표를 재설정. 허무지표인 GMV(거래액) -> RGMV
(Recurring GMV)
* 단기 성장이 아닌 장기 성장을 위한 본질에 집중
### 동료 Business Analyst 분과 커피챗
* 한번에 너무 fit한 곳을 찾아가려하지 말고, 장기적으로 바라보자.
* 시간관리 커뮤니티 기획
## 2023-04-24
### <원인과 결과의 경제학> 8장
> **최적선**
> - 데이터 사이를 통과하면서 데이터 간의 거리의 합계가 가장 작아지도록 그은 선
> - 기울기 : 원인이 한 단위 증가했을 때 결과가 어느 정도 변화하는지지 보여주는 것 = 인과 효과

> **회귀분석** : 최적선을 긋는 방법
> - 단회귀 분석 : 두 변수의 관계를 평가하는 방법
    </br>- 교란 요인이 존재하지 않는다는 전제조건이 충족돼야 한다.
> - 중회귀 분석 : 교란 요인 값이 움직이지 않도록 고정한 다음 최적선을 긋는 방법  
     - 예 : 음주와 폐암 사이에 인과관계를 파악하려면, 흡연량이라는 교란 요인을 고려해야야 함. → 흡연량이 동일한 사람들로 한정해서(흡연량 고정) 음주량이 센 사람과 약한 사람을 비교
## 2023-04-21
### SQL 코테 문제 풀기
* 프로그래머스 - 조건에 맞는 사용자와 총 거래금액 조회하기
* 프로그래머스 - 대여 기록이 존재하는 자동차 리스트 구하기
* [프로그래머스 : 자동차 대여 기록에서 대여중 / 대여 가능 여부 구분하기](https://growing-cindy.tistory.com/17)</br>

<br> 가장 어려웠던 세 번째 문제 풀이 과정과 배운점 블로그에 정리
### <원인과 결과의 경제학> 5장
> **회귀 불연속 설계**
> - 특별한 이유 없이 자의적으로 결정된 ‘컷오프 값’을 전후로 실험군과 대조군이 갈리는 상황을 이용해 인과 효과를 추정하는 방법
> - 컷오프 값 주변에서 ‘점프’ (종속 변수의 큰 격차)가 발생한다면 이 크기가 독립 변수가 종속 변수에 미치는 인과효과라고 볼 수 있다.
> - 전제조건 : 연속 변수의 컷오프 값 주변에서 결과에 영향을 줄 만한 다른 이벤트가 발생하지 말아야 한다.

</aside>

## 2023-04-17
### <원인과 결과의 경제학> 5장
> **조작변수법**
> - 조작변수 ; 결과에는 직접 영향을 주지 않지만 원인에 영향을 줌으로써 간접적으로 결과에 영향을 주는 제3의 변수
> - 조작변수를 통해서 실험군과 대조군을 비교 가능한 상태로 만드는 방법
> - 전제조건
>   1. 원인에는 영향을 미치지만 결과에는 직접 영향을 주지 않아야 한다.
>   2. 조작 변수와 결과 모두에 영향을 줄 만한 제4의 변수가 존재하지 않아야 한다.

## 2023-04-16
### <원인과 결과의 경제학> 3장, 4장 읽기
> **이중차분법**
> - (실험군, 대조군) 각각의 개입 전후 결과의 차이
> - 실험군과 대조군의 차이
</br>이 두개의 차이로 효과를 추정하는 방법
> - ********전제조건********
> </br> 1)개입 전 결과의 ‘트렌드’가 같아야 한다. (’트렌드’가 비교 가능해야 한다.)
</br> 2)결과에 영향을 줄 만한 다른 변화가 실험군과 대조군에 별개로 발생하지 않아야 한다.

* 실제 비즈니스 현장에서 저 두가지 전제조건을 충족할 수 있는 상황이 얼마나 있을까..? 실무에서 인과관계를 파악하기 위한 통계적 기법을 어떻게 적용하고 있는지 궁금하다.
## 2023-04-13
### 프로그래머스 - 조건에 맞는 사용자 조회하기
- [문제 풀고 레슨런 정리](https://growing-cindy.tistory.com/14)

## 2023-03-09
### <그로스해킹> 책 읽기
(3.3 Retention, 3.4 Revenue, 3.5 Referral) </br>

* 한 번 떨어진 리텐션을 다시 끌어올리는 것은 매우 어렵다. 서비스 초기부터 리텐션이 떨어지지 않도록 관리해야 한다.
* 노션에서 사용자에게 에버노트 등의 경쟁 서비스에서 기존에 작성했던 메모를 자동으로 가져오게 하는 기능도 리텐션을 위한 기능으로 볼 수 있다. (리텐션 사례로 나오지만 활성화 단계로도 볼 수 있지 않을까?) 후발주자의 경우, 기존에 축적되어 있는 가치를 훼손하지 않고 이전하도록 부담을 덜어준 사례로 볼 수 있다.
* 건강하게 성장하는 서비스는 LTR(고객 생애 매출)이 CAC(고객 획득 비용)보다 충분히 커야 한다. (일반적으로는 LTR이 CAC의 5~10배는 돼야 한다고 한다.) LTR > CAC 가 되기까지의 기간이 얼마나 걸리는지도 고려해야 한다.
* 매출 데이터도 쪼개서 보면 많은 인사이트를 얻을 수 있다.
  + 아이템별로 : 개별 상품별 매출 기여도, 판매량의 변화, 카테고리별, 신상 vs 기존 상품, 자체제작 vs 사입 등등... 
  + `매출 = 결제자수 * ARPPU` </br>
  이를 다음과 같이 더 쪼갤 수 있다. `매출 = 설치 수 * 가입전환율 * 리텐션 * 결제비율 * ARPPU` </br>
  이렇게 퍼널에 따라 쪼갬으로써 매출 증가와 감소의 원인을 파악할 수 있다.
  > 전 회사에서 광고주의 매출 증감의 원인을 파악하고 이에 대한 제안 (광고의 측면으로든, 광고주 운영 전략 측면으로든)을 하는 것이 주요한 업무였다.
  -> 매출 상승이 유입이 늘어나서인가? 그렇다면 광고 유입이 늘어난 것인가 오가닉 유입이 늘어난 것인가?
  -> 구매 전환율이 좋아져서인가? 광고를 통한 구매 전환율이 좋아졌는가? 사이트 자체의 전환율이 좋아진 것인가?
  -> 고객들이 평균적으로 더 비싼제품을 사는 것인가?
  -> 평균적인 상품 단가가 올라가서인가?
  -> 사입 혹은 제작을 잘해서 상품의 매력도가 상승한 것인가?
  -> 특히 판매량이나 판매 비율이 증가한 상품은 없는가?
  등등 꼬리에 꼬리를 물고 매출을 분석해나갔다.
* 추천을 위한 대표적인 기능인 '친구 초대'기능이다. 서비스의 친구 초대에 대한 보상을 통해 CAC를 추론해 볼 수 있다.
* 추천 시스템이 잘 동작하기 위한 기본 전제는 '서비스의 완성도'이다. 즉, 활성화(Activation) 단계가 잘 구축되어 있지 않다면 역효과만 일으킬 수 있다.
* 그로스 해킹은 AARRR 모든 단계에 해당하는 활동을 통합적으로 지칭한다. 서비스 전반의 성장을 위한 모든 노력이 곧 그로스 해킹인 것 같다.
## 2022-12-02
### SQL 코딩테스트 연습문제
1. LeetCode : Rank Scores
    > SQL의 예약어를 테이블, 컬럼 등을 구분해주는 이름으로 사용할 때는 백틱(``)을 사용하여 감싸주어야 한다.
    -> [참고링크](https://dev.mysql.com/doc/refman/8.0/en/keywords.html)
    > ``` SQL
    > SELECT score,
    >   DENSE_RANK() OVER (ORDER BY score DESC) AS `rank`
    > FROM Scores
    > ORDER BY score DESC;
    > ```
    > 위의 쿼리에서 결과물 출력 시 컬럼명으로 사용하고자 한 'rank'는 예약어이기 때문에 ``로 감싸주었다.
2. SolveSQL : 지역별 주문의 특징
    > CASE문에 집계함수를 활용하는 방법!! 아래와 같은 형태를 기억하자.
    > ```SQL
    > SELECT region AS Region
    >   ,COUNT(DISTINCT CASE WHEN category = 'Furniture' THEN order_id END) AS Furniture
    >FROM records
    > GROUP BY region
3. LeetCode : Customers Who Never Order
    ``` SQL 
    SELECT name AS Customers
    FROM customers
    WHERE id IN (
        SELECT DISTINCT customers.id
        FROM customers LEFT JOIN orders ON customers.id = orders.customerId
        WHERE orders.id IS NULL
    )
      ```
    한 번도 주문하지 않은 고객을 찾아내기 위해 처음에는 위와 같이 서브쿼리에 `IN`을 이용하였다. 
    하지만 `Orders` 테이블 자체가 이미 주문한 고객의 id만 기록되어 있기 때문에, 따로 서브쿼리를 사용하지 않고 아래와 같이 훨씬 더 효율적인 쿼리를 짤 수 있다.
    ``` SQL
    SELECT name AS Customers
    FROM Customers
    WHERE id NOT IN (SELECT customerId FROM Orders)
    ```
## 2022-11-27
* 카트라이더 트랙 분석 프로젝트 raw data 파일 깃 레파지토리에 업로드
* 대용량 파일은 GIT LFS를 다운 받아서 처리해야함
  <br> [참고 자료 링크](https://velog.io/@offsujin/git-Git-LFS로-깃허브에-대용량-파일-업로드하기)
## 2022-11-26
### 화난사람들 데이터 기반 프라이싱 프로젝트
* 보고서 중 SWOT분석 파트 작성
* 변호사 광고 서비스 경쟁사 조사 및 보고서 작성
* 화난 사람들 변호사 광고 서비스 가격 제안
## 2022-11-24
카트라이더 트랙 분석 프로젝트 깃 레포지토리 정리, 위키 문서 작성
## 2022-11-23
### 1. [해커랭크 [Print Prime Numbers] 문제 풀이](https://velog.io/@goodkse7/SQL-해커랭크-Print-Prime-Numbers-Stored-Procedure-GROUPCONCAT)
> **Stored Procedure(저장 프로시저)란?**
> * Stored Procedure는 반복해서 사용하는 쿼리를 하나의 루틴으로 저장하여 사용할 수 있게 한다.
> * Function과 비슷한 역할을 하지만, Function은 어떤 값을 리턴하지만 Procedure는 단순히 리턴값 없이 쿼리를 콜한다는 점에서 다르다.
>* Procedure 내에 기본 `SELECT` 문 뿐만 아니라 `IF`, `CASE`, `WHILE` 등 다양한 구문을 활용할 수 있다.

> **GROUP_CONCAT** <br>
> `GROUP_CONCAT`은 서로 다른 행에 있는 데이터를 한 줄로 합쳐줄 때 사용한다.
>```SQL
>SELECT GROUP_CONCAT([컬럼명] separator [구분자] | ORDER BY [컬럼명])
>FROM [테이블명]
>GROUP BY [그룹명]
> ```
> * `GROUP BY` 문을 포함하면, 그룹별로 묶어서 해당하는 데이터를 한 줄로 출력해준다.
> * `GROUP BY` 문을 포함하지 않으면, 모든 데이터를 하나의 그룹으로 보고 한 줄로 출력해준다.
> * `ORDER BY` 문을 사용하면 특정 컬럼을 기준으로 정렬하여 출력할 수 있다.

### 2. 잡코리아 이력서 작성 및 지원
## 2022-11-22
### 화난사람들 데이터 기반 프라이싱 프로젝트
* 팀회의 - 개인별 세부미션 작성 내용 공유
* 신규 광고 서비스 경쟁사 가격정책 조사 및 비교분석

### SQL 코딩테스트 스터디
> 최고 혹은 최저를 찾을 때 꼭 MAX MIN을 사용하지 않아도 된다! LIMIT를 사용해 간단하게 해결할 수 있다
## 2022-11-21
### 화난사람들 데이터 기반 프라이싱 프로젝트
* 가격 전략 강의 청취
* 화난사람들 서비스 분석 및 리걸테크 시장조사
* 화난사람들 SWOT분석 진행 <br>

#### <경쟁가치 및 브랜드가치에 의한 가격 전략> 강의 청취 ####
1. 경쟁가치에 의한 가격 전략
  - SWOT분석을 통해 기업이 어느 위치에 있는지 객관적으로 봐야한다.
  - 경쟁자와 우리 기업의 가격을 비교하는 프라이싱 툴 사용
2. 브랜드가치에 의한 가격전략
  - 자기 과시적인 가치, 사회적 가치, 품질 가치, 감성 가치
  - 가치를 제공한다면 가격을 올려도 소비자가 만족할 수 있다.
## 2022-11-18
### 카트라이더 선호 트랙 분석 프로젝트 회고
#### Good
* 프로젝트 시작 전 킥오프 시간을 갖고 그라운드 룰을 정한 것. 이후 협업 간의 장애요소를 최소화할 수 있었고, 서로의 장점을 파악해 R&R을 효율적으로 분배 가능했음
* 분석 결과를 바탕으로 제안하는 정도로 끝내지 않고, 실제로 활용 가능한 아웃풋(트랙 계산기)을 만들어낸 것.
* 토의를 통해 모두가 납득하고 합의를 본 후 다음 의제로 넘어간 것. 열띤 토론이 논쟁이나 감정싸움으로 이어지지 않을 수 있었던 서로의 소프트한 커뮤니케이션 스킬.
### Poor & Need to improve
* 작은 아이디어까지 이슈를 발행해 백로그를 쌓아두고 트래킹하는 방식으로 일하지 못한 것. 기록이 남지 않다보니 실행하지 못하고 지나친 아이디어들이 있었음.<br>
  -> 지난 회사에서 일하면서도 많이 느꼈던 것. 스쳐지나가는 이야기도 가장 작은 단위로 이슈를 발행해두기
* 시간에 쫓기다보니 프로젝트 진행 단계마다 분석을 통해 풀어야하는 문제, 즉 가설을 명확하게 정리하고 분석을 진행하지 못했던 것.
  -> 분석을 위한 분석이 되지 않도록 목적과 문제 정의를 북극성으로 두고 가야 한다.
* 킥오프 때 네이밍 컨벤션과 파일 관리 방식 등 주요한 것들을 정하지 못한 것.
  -> 프로젝트가 진행될수록 서로 바쁘다보니 이런 사소한 것들을 챙기기 어려워진다. 별거 아닌 것 같아 보여도, 시작하기 전 약속하고 진행해야 한다.
### Learned
* 분석가에게는 꼼꼼함이 중요한 역량이다. 아주 새롭고 창의적인 분석 방법을 생각해내는 것보다도 수많은 변수를 놓치지 않고 분석해보고 체크하는 디테일함이 필요하다.
* 작은 것부터 실험해보는 애자일 정신. 모든 데이터를 다 모으고나서 분석하려고 하기보다, 당장 할 수 있는 작은 단위의 데이터부터 실험해보고 실행하는 것이 중요하다.
* 예상하지 못한 결과라고 무의미한 것이 아니다. 좋은 모델이 나오지 않았다면 나오지 않은 이유는 무엇인지, 우리의 예상과 다른 것은 무엇인지 관점을 달리 생각해보면 얻을 수 있는 인사이트가 반드시 있다.

## 2022-11-17
### 화난사람들 데이터 기반 프라이싱 프로젝트
* 팀 모임 후  참고 자료 바탕으로 스터디 <br>

#### <비용가치에 의한 가격 전략> 강의 청취 ####
* 강력한 브랜드는 사용자들이 가격을 인지하는 브랜드이다. 가격을 높이더라도 사용자는 해당 제품/서비스를 계속 이용할 가능성이 크다.
* 가격은 기업의 가치 그 자체이며, 사업의 목적을 위해 합리적인 방식으로 전략을 세우는 과정이 프라이싱이다.
* 프라이싱 프로세스의 첫 단계는 원가율과 마진율을 계산하는 것
  - 이익을 극대화하기 위해서는 판매가격을 조정하는 것이 가장 효과적이다. (비용을 줄이는 것은 매우 어렵기 때문)
  - 가격 설계를 잘한다는 것은 마진이 좋은 가격을 만드는 것이다.

  > 주요 계산식 <br>
  ```판매 가격 = COST(변동비) + O/H (고정비) + MG (공급자 실질 이익)``` <br>
  ```매출액 = 판매량 * 제품단가 ``` <br>
  ```매출총이익(Gross Margin) = 매출액 - 매출 원가 ``` <br>
  ```순이익율(Net Profit Margin) = (순익/매출액)*100```
## 2022-11-16
* 카트라이더 선호 트랙 분석 프로젝트 포트폴리오 정리 60% 정도 진행
## 2022-10-27
### 카트라이더 선호 트랙 분석 DAY12
1. 테스트로 추출한 3일치 데이터 통계 분석 진행
2. 팀원 각자 추출한 한달치 데이터 병합 진행

## 2022-10-19
### 카트라이더 선호 트랙 분석 DAY6
설문조사
* 카트라이더 유저가 선호하는/선호하지 않는 트랙의 특성을 알아보기 위한 설문조사 구성 및 배포
* PC카트 유저 오픈채팅방, 넥슨 홈페이지 및 디시인사이드 갤러리 등의 커뮤니티에 배포
* 설문조사 결과를 바탕으로 트랙을 분석할 정량/정성 지표를 정의할 예정

## 2022-10-10
### SQL 코딩테스트 문제 풀이
1. SQL Project Planning(해커랭크)
2. 할부는 몇 개월로 해드릴까요(SolveSQL)
3. Actors and Directors Who Coperated At Least Three Times (리트코드)<br>

배운 것
- 한 컬럼이 다른 한 컬럼에 존재하는지 확인하기 위해 IN을 사용할 수 있다.
- 조건에 맞는 컬럼을 각각 구한 후 합쳐서 프린트해주고 싶을 때, ROW_NUMBER를 사용해서 조인을 해줄 수 있다.
- ORDER BY 에서도 함수 사용이 가능하다.
- 문제를 대충 읽고 무작정 코드부터 쓰지 말고, EDA를 꼼꼼하게 하고 테이블을 파악한 후에 코드를 짜자!!!
- 어떤 조건을 가지고 데이터를 추출할 때, 꼭 서브쿼리를 사용하려 하지 말고 GROUP BY와 HAVING을 활용해보자. 쿼리의 효율성을 고민하기!
## 2022-10-07
### 데이터 리터러시란
[링크드인 최창식님의 포스트](https://www.linkedin.com/posts/changsikchoi_%EB%8D%B0%EC%9D%B4%ED%84%B0-%EB%A6%AC%ED%84%B0%EB%9F%AC%EC%8B%9C%EC%97%90-%EA%B4%80%ED%95%9C-%EC%83%9D%EA%B0%81-%EB%B6%80%EC%A0%9C-%EA%B7%B8%EA%B2%8C-%EB%AD%94%EB%8D%B0-%EC%98%A4%EB%8A%98-%EC%9D%B4%EB%9F%B0%EC%A0%80%EB%9F%B0-activity-6984002682537603072-XJDx?utm_source=share&utm_medium=member_desktop)

> 내가 생각하는 회사에(특히 스타트업) 필요한 데이터를 읽고 해석하는 능력을 쪼개보면 아래와 같다 <br>
<br> 1-1 비지니스 모델 및 서비스를 구조화 시켜 사고하는 능력
<br> 1-2 위 구조의 과거, 현재, 미래를 관측하기 위해서는 어떤 위계적 수치들을 측정해야 하는지 의사결정 할 수 있는 능력
<br> 2-1 기본적인 통계지식(AB test)
<br> 3-1 산업에 대한 도메인 지식
<br> 4-1 관측한 현실과 데이터를 해석 할 수 있는 다양한 지식 프레임 보유(경제학, 사회학..)
<br> 5-1 현상과 사고를 수식화 하는 능력

흔하게 통용되는 용어들, 그저 그대로 받아들이고 사용하는 것이 아니라 그 의미가 무엇인지 스스로 생각해보는 것이 중요한 것 같다. <br>
내가 생각하는 데이터 리터러시는 무엇인가? 내가 생각하는 데이터 분석가는 어떤 사람인가? 어떤 분석가가 좋은 분석가인가? <br>
내가 하고자 하는 일에 대해서 내 언어로 표현할 수 있어야 하지 않을까.
### 이력서, 포트폴리오 관련 강의 듣고 정리
* 나라는 사람을 어떤 사람으로 봐주면 좋겠는지 나의 컨셉을 잡아라.
* 이를 바탕으로 이력서와 포트폴리오 전체에서 일관된 메세지를 전달하라.
* 성과는 직접적인 수치가 아닌, 몇 배 성장시켰고 몇 퍼센트 개선했는지 정도면 충분하다.
### 적용할 것
* [데이터리안 보민님 깃헙](https://github.com/springkind/2019_da_head_team ) 참고해서 미니 프로젝트 코드 파일 올려두기

## 2022-10-06
### 기업분석 소모임 참석
* 2주 동안 팀별로 분석한 내용 발표
* 해당 비즈니스 : 에이블리, 지그재그, 쏘카, 채널톡, 데브시스터즈, 토스
* 적용할 것 : 분석한 내용 정리해서 블로그에 올리기, ERD까지 만들어보기, 다른 분들이 분석하신 내용도 살펴보고 내 언어로 정리해보기
### 통계 - 텍스트 분석
* 잠재 의미 분석 (Latent Sentiment Analysis)
* 단어 임베딩과 유사도
* 감성 분석
* 나이브 베이즈와 로지스틱 회귀분석
## 2022-10-05
### 경력기술서 작성
* 관련 콘텐츠 찾아보고 정리함
- 숫자로 말하라
- 직무와 관련된 내용으로 구성하라
- 채용공고와 나의 USP(Unique Selling Point)를 연결해서 내용을 구성하라
 → 나의 USP를 먼저 정리해보기
- 이력서 각 항목은 Context → Action → Result를 담고 있어야 한다.
### 에이블리 기업분석 추가 진행
* 광고 서비스가 에이블리의 중요한 BM일 것으로 판단
* 해당 BM 관련한 OMTM과 AARRR 지표들을 추측하여 정리함

## 2022-10-02
### 에이블리 기업 분석
#### 커머스 시장, 패션 커머스 플랫폼 시장 동향 조사
* 슈퍼앱은 전문성을 강화, 버티컬은 카테고리를 확장하며 경계가 허물어지고 있음
* 패션 커머스 플랫폼은 공통적으로 카테고리 및 유저 확장, 브랜드와 디자이너와의 상생, 해외 진출을 성장 전략으로 삼고 있음
#### 에이블리의 데이터
* 서비스가 수집하고 있는 데이터 파악
* 그중 OMTM 선정
### GIT 복습
* [git의 기본 개념, commit, push, pull, merge 방법 정리](https://velog.io/@goodkse7/GIT-원격저장소에-commit-push-pull하기)

## 2022-09-30
### 포트폴리오 작업
* 레퍼런스 찾아봄
* 전체 레이아웃 정리
* 프로필의 소개 문장 작성
### 포트폴리오의 역할
* 이력서는 시간순으로, 조직 중심으로 업무를 정리
* 포트폴리오는 내가 해온 일을 중심으로 일하는 나의 스토리를 소개
* 내가 생각하는 데이터분석가는 무엇이고, 나의 강점은 무엇인지 드러나도록 작성할 것

## 2022-09-21

### 리눅스 커맨드라인 기초
```
pwd //print working directory
```
```
cd //change directory
cd .. : 현재 폴더 기준으로 상위 디렉토리로 이동
```
```
ls //list
```
- ls 뒤에는 -a나 -l 옵션을 붙일 수 있음
- -a : 숨김파일도 보여줌
- -l : 상세정보를 보여줌  


### Vim 사용법 기초
#### Vim 명령어로 텍스트 파일을 만들고 수정해주자.
```
vim 123.txt // 123이 제목인 텍스트 파일을 생성
```
1. vim 에디터를 처음 키면 명령모드로 진입하기 때문에 입력을 할 수 없다. -> 입력하려면 입력모드로 바꿔야 한다.
2. 입력모드로 진입하려면 i키 (insert)등을 누른다.
3. 입력이 다 끝나고 저장 등의 명령을 컴퓨터에게 내리려면 명령모드로 다시 돌아가야 함
  - 명령모드로 바꾸려면 키보드에서 `esc`키를 누름
  - 명령모드에서 `:w`를 입력하고 `enter`키를 누르면 저장만 됨(write)
  - `:wq`를 입력하면 저장하고 에디터에서 빠져나올 수 있음(write and quit)
  - `:q`를 입력하면 에디터에서 빠져나올 수 있음(quit)

위와 같은 명령어로 텍스트 파일 뿐만 아니라 프로그래밍 언어 파일도 편집 가능하다.

### commit
#### 정의
  - The "commit" command is used to save your changes to the local repository.
  - 커밋 하나는 독립적인 버전을 나타냄
  - The git commit command captures a snapshot of the project's currently staged changes.
  - 스냅샷(사진)과 유사

#### 언제 커밋을 만드는가
  - logical한 변경이 있을때 커밋을 하나 만듬
  - 가능하면 커밋 단위는 작을 수록 좋음

### gitignore
- 프로젝트의 불필요한 환경설정 파일들이 깃에 포함되지 않도록 하는 것
- gitignore generator를 이용하여, 내가 쓴 언어와 운영체제, 텍스트 에디터 등 맞는 것을 검색해서 생성한다.
- 모든 저장소에는 gitignore 파일이 존재해야 한다!
