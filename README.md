# 20240313_log_view

Link : https://dacon.io/competitions/official/236226

## Goals
웹 로그를 기반으로 한 조회수 예측  
public score 2.9238 이상  

## Dataset
한 세션에서 발생한 다양한 정보를 기록한 웹 로그  
train.csv  
┣ sessionID : 세션 ID  
┣ userID : 사용자 ID  
┣ TARGET : 세션에서 발생한 총 조회수  
┣ browser : 사용된 브라우저  
┣ OS : 사용된 기기의 운영체제  
┣ device : 사용된 기기  
┣ new : 첫 방문 여부 (0: 첫 방문 아님, 1: 첫 방문)  
┣ quality : 세션의 질 (거래 성사를 기준으로 측정된 값, 범위: 1~100)  
┣ duration : 총 세션 시간 (단위: 초)  
┣ bounced : 이탈 여부 (0: 이탈하지 않음, 1: 이탈함)  
┣ transaction : 세션 내에서 발생의 거래의 수  
┣ transaction_revenue : 총 거래 수익  
┣ continent : 세션이 발생한 대륙  
┣ subcontinent : 세션이 발생한 하위 대륙  
┣ country : 세션이 발생한 국가  
┣ traffic_source : 트래픽이 발생한 소스  
┣ traffic_medium : 트래픽 소스의 매체  
┣ keyword : 트래픽 소스의 키워드, 일반적으로 traffic_medium이 organic, cpc인 경우에 설정  
┗ referral_path : traffic_medium이 referral인 경우 설정되는 경로
test.csv
sample_submission.csv

## 평가 방식
RMSE score

## 진행 기간
2024.03.06 ~ 2024.03.13

