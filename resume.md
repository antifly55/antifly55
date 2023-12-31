## 연구 프로젝트

**Maximum Jaccard-Similarity Estimator (2023.06 ~ )**
-	자카드 인덱스 기반 유사 데이터 탐색을 위한 초고속/초경량 스트리밍 자료구조 개발
-	최신 기술 대비 20배 이상의 속도 효율, 50배 이상의 메모리 효율 증가
-	실제 검색 도구로 사용하기 위한 ElasticSearch Plugin 구현
-	캐싱을 통한 접근 빈도가 높은 데이터 처리 속도 개선으로 6배 이상의 속도 효율 증가

**제로데이 방어를 위한 생성형 보안기술 연구 (2022.09 ~ )**
-	과학기술정보통신부/한국연구재단/중견연구
-	초고속 데이터 스트림 클러스터링 및 공격 탐지 규칙 집합 생성 기술 개발
-	기존 클러스터링 기술 대비 100배 이상의 속도 효율, 10배 이상의 메모리 효율 증가
-	기존 공격 탐지 규칙 생성 기술 대비 20배 이상의 오탐률 감소 효과
-	USENIX Security ’23 논문 1저자 *(정보보호분야 4대 컨퍼런스) *
    -	게재 사이트: https://www.usenix.org/conference/usenixsecurity23/presentation/seo
-	Airflow 기반 실험 수행 자동/병렬화 및 수정 용이한 데이터 파이프라인 구축

**스트링 피처와 클러스터링 기반의 악성코드 XAI 분석 기술 (2023.03 ~ 2023.10)**
-	(주) 지란지교시큐리티 협업 연구
-	악성코드 파일에서 공격 행위를 유발하는 탐지 규칙 집합 생성 기술 개발
-	기존 클러스터링 기술 대비 10배 이상의 속도 효율, 20배 이상의 클러스터 순도 달성
-	아호코라식을 활용한 고속 N-gram 재결합 구현으로 분석 규칙 개수 1,000배 이상 감소
-	실제 보안 업계에서 운용하는 악성코드 데이터셋에서 99% 이상의 정확도 검증

**국제망 트래픽 분석 및 대응 기술 개발: IoT 해킹과 DDoS 탐지 (2022.03 ~ 2022.10)**
-	KT, (주) 윈스 협업 연구
-	보안관제센터에서 세부 공격 유형 분석을 위한 공격 탐지 규칙 생성 연구 및 시스템 개발
-	기존 공격 탐지 규칙 생성 연구의 문제 분석 및 해결을 통해 30배 이상의 속도 효율 증가
-	데이터 스트림 조회 API의 입력을 배치 처리로 변경하여 20배 이상의 속도 효율 증가

**차세대 SIEM 제품화를 위한 지속 학습과 분산 마이닝 핵심기술 개발 (2021.06 ~ 2022.02)**
-	과학기술정보통신부/IITP, ICT R&D 혁신 바우처 지원사업
-	SIEM에서 보안 이벤트의 정오탐 여부를 자동으로 탐지하는 지속학습 딥러닝 모델 개발
-	Elastic Weight Consolidation 공개 코드 분석 및 재학습 가중치 소실 문제 완화 기능 구현으로 정확도 30% 이상 증가
-	이분탐색 기반 IP-국가 탐색 기능을 구현하여 60배 이상의 속도 효율 증가

## 개발 프로젝트

**Paper Commenter (2023.10 ~ )**
-	논문에 대한 지식 공유 및 논의를 위한 커뮤니티 서비스
-	기술스택: FastAPI, MySQL, ElasticSearch, Redis, Airflow, Docker, AWS EC2, AWS S3
-	소스코드: github.com/antifly55/PaperCommenter-Backend
-	개발일지: velog.io/@antifly55/series/Paper-Commenter

**주요 기술적 기능**
-	ElasticSearch 및 LSH 기술을 응용한 용어 기반 고속 논문 검색엔진 구현
-	Matrix Factorization 기반 유저-논문 추천 시스템 구현 및 Airflow 기반 학습/배포 자동화
-	논문 등록 시 Maximum Jaccard-Similarity Estimator 기반 중복 탐지 기술 개발
-	기본키 예측 방지를 위해 DB 인덱스를 위한 식별자로 원본 데이터의 해시 값을 사용
-	효율적인 좋아요 개수 쿼리를 위해 Event Scheduler를 통한 주기적 컬럼 갱신 기능 구현
-	JWT를 사용한 access/refresh token 구현, Redis로 refresh token 관리
-	접근 빈도가 높은 GET API에 Redis 기반 캐싱 기능 적용

## 프로그래밍 대회 실적
- 2022년
    - ICPC Asia Seoul Regional Contest, 38th
    - ICPC Asia Korea National First Round, 50th, 교내 2등
    - 전국 대학생 프로그래밍 대회 동아리 연합 본선, 49th
    - 전국 대학생 프로그래밍 대회 동아리 연합 예선, 63rd
    - Code Jam Round 1C, 1,345th
- 2021년
    - ICPC Asia Seoul Regional Contest, 43rd
    - ICPC Asia Korea National First Round, 45th, 교내 1등
    - Code Jam Round 1C, 889th
- 2018년
    - 한국정보올림피아드 경시부문 전국대회 고등부, 동상

## 교내 활동
- 2022.03 ~ 2022.06,	국민대학교 프로그래밍 기초 조교
- 2020.09 ~ 2021.06,	국민대학교 랩애니웨어 헬퍼

## 세부 실적

### 논문
1.	Generative Intrusion Detection and Prevention on Data Stream, USENIX Security Symposium, 2023 (정보보호분야 4대 컨퍼런스, 1저자)
2.	Data Auditing for Intelligent Network Security Monitoring, IEEE Communications Magazine, 2023 (JCR 상위 5% SCIE 저널)
3.	보안관제센터 라벨링 워크로드 절감 연구, CISC-W 학회 우수논문상, 2022
4.	MaaD: 머신러닝을 이용한 보안데이터 라벨 디버거, AI+Security 우수논문 아이디어 공모전 최우수상, 2021
5.	보안관제 인공지능 모델의 신뢰성 향상 연구, 제5회 금융보안원 논문공모전 장려상, 2021
6.	SELID: Selective Event Labeling for Intrusion Detection Datasets, Sensors, 2023
7.	Maximum Jaccard-Similarity Estimator, 논문 심사중, 2023

### 국가연구/산학협력 과제
1.	제로데이 방어를 위한 생성형 보안기술 연구, 과학기술정보통신부/한국연구재단/중견연구, 2023 - 2026
2.	스트링 피처와 클러스터링 기반의 악성코드 XAI 분석 기술, (주) 지란지교시큐리티, 2023
3.	국제망 트래픽 분석 및 대응 기술 개발: IoT 해킹과 DDoS 탐지, KT, (주) 윈스, 2022
4.	인공지능 기반 보안관제 기술 개발 관련 연구용역, 금융결제원, 2021
5.	차세대 SIEM 제품화를 위한 지속 학습과 분산 마이닝 핵심기술 개발, 과학기술정보통신부/IITP, 2021 - 2022
6.	머신러닝 일반화와 딥러닝 임베딩을 활용한 보안데이터 분석 연구, 과학기술정보통신부/한국연구재단 중견연구자지원사업, 2020 - 2023
7.	보안 빅데이터 자동 분석을 위한 실시간 유사도 측정 원천 기술 연구, 과학기술정보통신부/IITP, 정보보호핵심원천기술개발사업, 2018 - 2022

### 특허
1.	10-2023-0155638, 경량 클러스터링 기반 악성코드 판단 근거 생성 기술, 2023. 11. 10
2.	10-2023-0110549, 초경량 클러스터링 기반의 생성형 침입탐지 기술, 2023. 08. 23
3.	10-2022-0148829, 패킷 클러스터링 기반의 공격탐지규칙 자동생성 기술, 2022. 11. 09
4.	10-2022-0147168, 딥러닝 이상 탐지를 위한 상대순위빈도 인코딩, 2022. 11. 07
