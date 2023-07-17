# 외부조인, 내부조인, 셀프조인 설명
# join 이란?
### join 은 한 데이터베이스 내의 여러 테이블의 레코드를 조합하여 하나의 열로 표현한 것이다.
### 따라서 조인은 테이블로 저장되거나, 그 자체로 이용할 수 있는 결과 세트를 만들어 낸다.
### JOIN은 2개의 테이블 내에서 각각의 공통값을 이용함으로써 필드를 조합하는 수단이 된다.
# inner join 이란?
### inner join 은 내부 조인은 둘 이상의 테이블에 존재하는 공통 속성의 값이 같은 것을 결과로 추출한다.
### 외부조인 에는 3가지 유형이 존재한다.
### 왼쪽 외부 결합 : LEFT 테이블의 모든 행과 두 테이블간에 일치하는 레코드를 반환한다.
### 오른쪽 외부 결합 : RIGHT 테이블의 모든 행과 두 테이블간에 일치하는 레코드를 반환한다.
### 전체 외부 결합 : Left Outer Join과 Right Outer Join의 결과를 결합한다.
# ineer join 코딩.
![화면 캡처 2023-03-30 094828](https://user-images.githubusercontent.com/127116197/228699663-c1cb87c8-e573-4304-bc49-0204e2e43ac6.png)
## 출력
![화면 캡처 2023-03-30 095248](https://user-images.githubusercontent.com/127116197/228700221-a050e2ae-04d9-403a-b1d1-013b349a193e.png)
# outer join 이란?
### OUTER JOIN은 조인하는 여러테이블에서 한 쪽에는 데이터가 있고, 한 쪽에는 데이터가 없는 경우,
### 데이터가 있는 쪽 테이블의 내용을 모두 출력하는 것입니다.
### 즉, 조건에 맞지 않아도 해당하는 행을 출력하고 싶을 때 사용할 수 있습니다.
# outer join 종류
### (1) LEFT OUTER JOIN : 조인문의 왼쪽에 있는 테이블의 모든 결과를 가져 온 후 오른쪽 테이블의 데이터를 매칭하고, 매칭되는 데이터가 없는 경우 NULL로 표시한다.
### (2) RIGHT OUTER JOIN : 조인문의 오른쪽에 있는 테이블의 모든 결과를 가져온 후 왼쪽의 테이블의 데이터를 매칭하고, 매칭되는 데이터가 없는 경우 NULL을 표시한다.
### (3) FULL OUTER JOIN : LEFT OUTER JOIN 과 RIGHT OUTER JOIN을 합친 것으로, 양쪽 모두 조건이 일치하지 않는 것까지 모두 결합해 출력한다.
# 외부조인과 내부조인 차이점
![inner-join-vs-outer-join](https://user-images.githubusercontent.com/127116197/228697990-edeeafca-6f97-4325-969a-148cb5577764.jpg)
# self join 이란?
### SELF JOIN이란, 1개의 테이블(X)에 가상으로 x1, x2라는 별칭을 부여하여 2개의 테이블인 것처럼 간주한 뒤 JOIN하는 것입니다.
### 1개의 컬럼 내에 섞여있는 여러 레코드들을 다른 컬럼을 통해서 위계 또는 관계를 알 수 있는 모습으로 조회할 수 있습니다.
![SE-b58f1309-1d60-4b00-a853-a24d670cd1f7](https://user-images.githubusercontent.com/127116197/228699469-da29d789-735a-4bcb-b992-8dbdebd2fb7f.jpg)

