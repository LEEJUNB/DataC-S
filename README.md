# DataCrawlingScrapping
## 프로젝트의 목표
- 1. 다양한 사이트의 데이터를 효과적으로 수집
- 2. 수집한 데이터를 전처리
- 3. 엑셀 파일로 저장하는 방법을 익힘
- 4. WordCloud, Map, plot 등으로 시각화
- 5. (각 변수들 간의 상관관계를 파악)

## 데이터 수집 대상
- 네이버 주식, 인스타, 다나와 쇼핑, 코로나 통계, 인터넷 강의 댓글, 청와대 국민청원 등
- 인공지능, 빅데이터 키워드를 가진 뉴스, 레포트
- 교육, 채용 정보

## 환경
- IDE : JupyterNotebook
- 언어 : Python3
- 라이브러리1 : BeautifulSoup(HTML 태그에서 필요한 정보 추출), webdriver(Selenium 라이브러리_크롬 웹브라우저 제어)

## 주의사항
특정사이트에서 짧은 시간 동안 많은 데이터를 수집할시 디도스 공격 등으로 감지되거나 웹 서버에 무리를 줄 수 있음.
