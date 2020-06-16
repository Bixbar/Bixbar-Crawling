# Bixbar
> Notion : https://www.notion.so/ccookncook/Bixbar-b5401104a0d64fdc838d27505fbf27b2
- **crawling**
  - main.py를 실행하여 크롤링이 실행
  - "(칵테일명).json" 파일 json 폴더 안에 생성
- **ccookncook.bixbar**
  - bixby 캡슐
- **food pair**
  - food - cocktail pair를 위한 csv

# Bixbar Interface
![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/7f70e435-9c7c-4b15-b816-438d8606d26d/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/7f70e435-9c7c-4b15-b816-438d8606d26d/Untitled.png)

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/7de232c6-4bf0-4a8f-8ab7-c850f660eb07/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/7de232c6-4bf0-4a8f-8ab7-c850f660eb07/Untitled.png)

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/74d73f59-6527-4fe5-a6a8-647723913cc0/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/74d73f59-6527-4fe5-a6a8-647723913cc0/Untitled.png)

# 주요기능

- **칵테일 제조법 전달**

  - 레시피와 재료 등의 정보를 제공

- **사용자 맞춤 칵테일 추천**

  - 사용자의 연령대, 성별 및 기본 취향을 수집하여 정확한 사용자 맞춤 추천

- **칵테일에 어울리는 안주 추천**

  - 칵테일-안주 페어링 정보에서 가장 높은 정확도를 보이는 안주 추천

# About Project

숭실대학교 소프트웨어학부 2019-2 ~ 2020-1 캡스톤디자인종합프로젝트

# 팀 구성

- **[박정아](http://github.com/co3oing)**
  - Database 설계 및 구축, Data 삽입 및 조회 구현
- **송혜령**
  - 크롤링, 크롤링한 Data를 JSON 파일로 파싱
- **임규형**
  - Bixby NLP Training, 캡슐 설계, Modeling구현, 디자인, 웹서버와의 통신 구현
- **[최민성](http://github.com/kordood)**
  - Django 웹서버 구축, Bixby와의 통신(Response) 구현
  
# Project Architecture
- 시스템 대블록 설계
![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/7c2da5fc-51e2-4b3c-bfe5-e0cc2491a168/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/7c2da5fc-51e2-4b3c-bfe5-e0cc2491a168/Untitled.png)

- Database
![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/48a24386-a001-4146-8744-2a4dcef53b78/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/48a24386-a001-4146-8744-2a4dcef53b78/Untitled.png)

- Flow Chart
![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/e8f3b73d-1cf9-4994-a3cd-2c91e7ee4a20/Bixby_FlowChart0.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/e8f3b73d-1cf9-4994-a3cd-2c91e7ee4a20/Bixby_FlowChart0.png)

# 개발환경

- **Bixby**

  - Bixby Developer Studio
  - Javascript

- **Server & DB**

  - Goorm IDE
  - Python 3.7
  - SQLite

- **Crawling**

  - Jupyter Notebook
  - Python 3.7
  - [liquor.com](http://liquor.com/)
