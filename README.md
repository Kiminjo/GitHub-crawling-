# GitHub crawler

## 1. 프로젝트 소개 
- 목적 : GitHub의 repository 및 user 정보를 수집하기 위함
<br></br>
<br></br>

## 2. 수집 데이터 
|데이터        |데이터 타입|
|:---:        |:---:|
|repository 명|str|
|repository ID|int|
|owner ID|int|
|owner type|str|
|repository full name | str|
|topcis|list|
|contributors|list|
|contributor counts|int|
|stargazer counts|int|
|forker counts|int|
|created date|date|
|last updated datae|date|
|readme|str|


repository full name : "user name/repository name"
<br></br>
<br></br>

## 3. 실행 방법 
- `crawling material.py` 에서 수집하고자 하는 키워드 지정 
- `Github crawling.py` 의 main 내에서 수집하고자 하는 범위 지정 
- `python Github_crawling.py` 실행 
<br></br>
<br></br>

## 4. 구동 환경
- python >= 3.5
- PyGithub 
- pandas >= 1.0.1 
