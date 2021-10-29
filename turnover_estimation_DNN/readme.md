## Turnover estimation using DNN

**Problem explanation**\
Recently, as the number of services using big data and data science has increased, N company needs a lot of developers in the field. In response, before considering hiring additional employees from outside, it was decided to receive applications from employees who want to move to big data and data science through the in-house department movement system. However, Ms. Pine Leaf, who works for HR(Human Resource), tries to create software that predicts employees who quit their jobs and find new jobs due to low satisfaction with the current department (field, wages, colleagues, etc.). Using neural network technology, please write an artificial intelligence SW that predicts employees who want to change jobs provided as test.csv files.

**문제 설명**\
최근 N사는 빅데이터분야와 데이터사이언스분야를 활용한 서비스가 많아지면서 해당 분야 개발자가 많이 필 요해졌다. 이에 외부에서 직원을 추가 채용하는 부분을 고려하기 전 사내 부서 이동 제도를 통해 빅데이터분 야와 데이터사이언스분야로 옮기고 싶어하는 직원들의 신청을 받기로 했다. 그러나 HR(인사팀)에서 근무하는 솔잎 양은 해당 직원들의 정보가 인공지능관련 부서로의 이동뿐만 아니라, 현 부서의 만족도가 낮아(분야, 임 금, 동료, 기타 등등) 이직을 고려중인 직원으로 분류 가능하다는 분석결과를 도출하고 사내 직원들 중 현재 직장을 그만두고 새로운 일자리를 알아보는 직원을 예측하는 소프트웨어를 만들어 보려한다. 신경망 기술을 활용하여, test.csv 파일로 제공된 이직하기 희망하는 직원을 예측해주는 인공지능 SW를 작성해 주기 바란다.

**데이터 설명**
|Header|discription|
|:--:|:--|
index| 직원 개인 정보 순번
enrollee_id| 직원 고유 ID
city| 도시 코드
city_development_index| 도시 개발 지수
gender| 직원의 성별
relevent_experience| 직원의 데이터사이언스분야 관련 경험
enrolled_university| 현 대학등록여부
education_level| 학위
major_discipline| 전공
experience| 직원의 경력
company_size| 현 회사의 직원수
company_type| 고용 유형
last_new_job| 이직 회사 입사 년도
training_hours| 이수한 교육 시간
target| 이직 희망 여부
