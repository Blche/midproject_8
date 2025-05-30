# midproject_8
## Git 워크플로우 순서
1️⃣ 원격 변경사항 반영

```git pull```

<br>
2️⃣ 로컬 변경사항 staged

```git add -A```

<br>
3️⃣ 커밋 (메시지를 구체적으로)

```git commit -m "설명"```

<br>
4️⃣ 푸시

```git push```
<br>

> pull이나 push에서 오류가 난다면 ```git push origin main```의 형태로 입력

<br>

## 컬럼명
- 원래 사용하던 데이터셋은 1부터 인덱스가 들어가 있습니다.

| 원본파일       | 원래 컬럼명                        | 변경 컬럼명               |
|----------------|---------------------------------|-------------------------|
| 1              | customerID                      | 고객ID                   |
| 2              | gender                          | 성별                     |
| 3              | SeniorCitizen                   | 고령자여부                 |
| 4              | Partner                         | 배우자여부                 |
| 5              | Dependents                      | 부양가족여부               |
| 6              | tenure                          | 가입개월수                 |
| 7              | PhoneService                    | 전화서비스가입여부           |
| 8              | MultipleLines                   | 복수회선여부               |
| 9              | InternetService                 | 인터넷서비스유형             |
| 10             | OnlineSecurity                  | 온라인보안서비스여부          |
| 11             | OnlineBackup                    | 온라인백업서비스여부          |
| 12             | DeviceProtection                | 기기보호서비스여부           |
| 13             | TechSupport                     | 기술지원서비스여부           |
| 14             | StreamingTV                     | TV스트리밍이용여부           |
| 15             | StreamingMovies                 | 영화스트리밍이용여부          |
| 16             | Contract                        | 계약기간유형               |
| 17             | PaperlessBilling                | 전자청구서이용여부           |
| 18             | PaymentMethod                   | 결제방법                  |
| 19             | MonthlyCharges                  | 월요금                   |
| 20             | TotalCharges                    | 총요금                   |
| 21             | Churn                           | 이탈여부                  |
| 22             |                                 | 인터넷서비스가입여부          |
| New_churn      | Country                         | 나라                     |
|                | State                           | 주                      |
|                | City                            | 도시                     |
|                | Zip Code                        | 우편번호                   |
|                | Lat Long                        | 위경도                    |
|                | Latitude                        | 위도                     |
|                | Longitude                       | 경도                     |
|                | Churn Label                     | 이탈여부                  |
|                | Churn Value                     | 이탈여부(bool)             |
|                | Churn Score                     | 이탈점수                   |
|                | CLTV                            | 고객생애가치                |
|                | Churn Reason                    | 이탈이유                   |
| demographics   | Age                             | 나이                     |
|                | Under 30                        | 30세미만여부                |
|                | Married                         | 결혼여부                   |
|                | Number of Dependents            | 부양가족수                  |
| population     | population                      | 지역인구수                  |
| services       | Referred a Friend               | 친구추천여부                 |
|                | Number of Referrals             | 친구추천횟수                 |
|                | Tenure in Months                | 가입개월수2                 |
|                | Offer                           | 가입혜택                   |
|                | Avg Monthly Long Distance Charges | 장거리통화요금              |
|                | Avg Monthly GB Download         | 월평균다운로드용량(GB)        |
|                | Premium Tech Support            | 프리미엄기술지원여부           |
|                | Unlimited Data                  | 무제한데이터이용여부          |
|                | Paperless Billing               | 무지청구서이용여부            |
|                | Payment Method                  | 결제방법2                  |
|                | Total Charges                   | 총요금                    |
|                | Total Refunds                   | 총환불액                   |
|                | Total Extra Data Charges        | 총초과데이터요금              |
|                | Total Long Distance Charges     | 총장거리통화요금              |
|                | Total Revenue                   | 총납부금                   |
| status         | Satisfaction Score              | 만족도 점수                 |
|                | Customer Status                 | 고객상태                   |
|                | Churn Category                  | 이탈유형                   |
