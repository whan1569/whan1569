# 이동환 | Donghwan Lee

개인 학습, 실무 기록, 프로토타입, 보류된 실험을 목적별로 정리한 프로젝트 아카이브입니다.

이 README는 자기소개서가 아니라, 제가 어떤 목적을 가지고 어떤 프로젝트를 수행했는지 정리한 기술 창고입니다.  
각 프로젝트는 완성도보다 **사용 성격**과 **수행 목적**을 기준으로 분류했습니다.

---

## Project Classification

| 구분 | 의미 |
|---|---|
| 실사용 / 실무 기록 | 실제 회사 업무, 교육 과정 산출물, 직접 사용하거나 운영한 프로젝트 |
| 학습 / 구조 실험 | 기술 학습, 구조 설계, 기능 구현 연습을 목적으로 만든 프로젝트 |
| 보류 / 중단 / 검토 완료 | 기술 가능성은 확인했으나 비용, 효율, 시간, 방향성 문제로 멈춘 프로젝트 |
| 기록 저장소 | 코드보다 활동, 문서, 경험 기록을 정리한 저장소 |

---

## 1. 실사용 / 실무 기록

실제 환경에서 사용되었거나, 외부 요구·현장 문제·교육 과정 산출물과 연결된 프로젝트입니다.

### [Woojin_works](https://github.com/whan1569/Woojin_works)

**목적**  
실제 산업 장비 제어 과정에서 발생한 PLC/C 기반 장비 제어, I/O 매핑, 상태 전이, 출력 제어, 현장 디버깅, SVN 분기 관리 이슈를 기록하기 위한 실무 저장소입니다.

**분야**  
`PLC` `C` `B&R Automation Studio` `Industrial Machine Control` `I/O Mapping` `State Logic` `SVN`

**주요 내용**
- B&R PLC / Automation Studio 기반 장비 제어 작업
- C 기반 사출기 제어 로직 분석 및 수정
- MHC Interface / InterfaceCyclic 관련 작업
- 장비 출력 제어, 코어풀, 냉각수 밸브, I/O 매핑, 상태 전이 로직 개선
- SVN 유지보수 이력 및 신규 분기 관리 가이드라인
- Logical / Physical 배치, APJ, PKG, 라이브러리 관리 범위 정리

**상태**  
실무 기록 / 문서화 중심

---

### [college_career](https://github.com/whan1569/college_career)

**목적**  
대학교 산학실습, 포럼, 교육 과정, 사회 경험 등 학교와 사회 경험을 정리한 기록 저장소입니다.

**분야**  
`Career Record` `Education` `Project History` `Activity Archive`

**주요 내용**
- 대학교 산학회사 실습
- Android + OpenCV 기반 차량 번호판 인식 프로젝트
- 부산정보정책네트워크 포럼 참석
- 고등학교 재능기부 / 알고리즘 조교 경험
- LG헬로비전 DX DATA 교육 이수
- 창업 및 가게 운영 경험

**상태**  
활동 기록 저장소

---

### [team3_web / VODiscovery](https://github.com/whan1569/team3_web)

**목적**  
LG헬로비전 DX DATA 교육 과정에서 실제 VOD 데이터를 활용해 맞춤형 추천 플랫폼을 구현한 팀 프로젝트입니다.

**분야**  
`React` `Node.js` `Express` `MySQL` `JWT` `Recommendation` `VectorDB`

**주요 내용**
- React/Vite 프론트엔드 구현
- Node.js/Express/MySQL 백엔드 구현
- JWT 인증
- 사용자 시청 이력 기반 장르 통계
- 시청 패턴 분석 API
- 콘텐츠 임베딩과 VectorDB 기반 추천 전략
- AWS 배포 및 시연

**상태**  
교육 과정 산출물 / 팀 프로젝트 / 시연 완료

---

### [Team3](https://github.com/whan1569/Team3)

**목적**  
VOD 추천 프로젝트의 기획, 데이터 분석, 추천 전략, VectorDB 전략 등을 정리한 산출물 저장소입니다.

**분야**  
`Planning` `Data Analysis` `Recommendation Strategy` `VectorDB`

**주요 내용**
- VOD 추천 프로젝트 기획
- 데이터 분석
- 줄거리 기반 추천 전략
- VectorDB 기반 Cold Start 완화 전략
- 팀 프로젝트 산출물 정리

**상태**  
교육 과정 문서 / 프로젝트 산출물

---

## 2. 개인 사용 / 시스템 구축형 프로젝트

개인적으로 실제 사용하거나, 반복 사용 가능한 시스템 구조를 만들기 위해 진행한 프로젝트입니다.

### [fund_data_collector](https://github.com/whan1569/fund_data_collector)

**목적**  
주식, 원자재, 채권, 외환, 암호화폐, 부동산 등 여러 자산군 데이터를 안정적으로 수집하고 저장하기 위한 데이터 파이프라인입니다.

**분야**  
`Python` `Data Pipeline` `Parquet` `Logging` `Multi-Asset Data` `Finance Data`

**주요 내용**
- 자산군별 fetch 모듈 분리
- Parquet 기반 데이터 저장
- 수집 상태 추적
- 로그 및 리포트 구조
- 재시작 가능한 수집 구조

**상태**  
개인 시스템 실험 / 데이터 수집 구조화

---

### [TradingBot](https://github.com/whan1569/TradingBot)

**목적**  
거래 전략, 실행, 거래소 인터페이스, 리스크 관리, 테스트/실거래 모드를 분리한 트레이딩 시스템 구조 실험입니다.

**분야**  
`Python` `Trading System` `Binance API` `Strategy` `Execution` `Risk Control`

**주요 내용**
- exchange / execution / strategy / config / model / dashboard / test 모듈 분리
- Binance API 기반 워크플로우 구성
- 리스크 관리 구조
- 시그널 생성 구조
- 테스트 모드와 실거래 모드 분리

**상태**  
시스템 아키텍처 실험 / 개인 분석 도구

---

### [UN_Comtrade_Collector](https://github.com/whan1569/UN_Comtrade_Collector)

**목적**  
UN Comtrade API를 활용해 국가, HS Code, 운송 방식 기준의 수출입 데이터를 수집하고 분석하기 위한 프로젝트입니다.

**분야**  
`Python` `UN Comtrade API` `Trade Data` `Streamlit` `CSV Cache`

**주요 내용**
- 국가/HS Code/운송 방식 기준 데이터 수집
- 수집 완료 기간 스킵
- CSV 캐싱
- API 제한 대응 구조
- 무역 금액, 수량, 단가, 항공/해상 비율 분석
- Streamlit 대시보드 구성

**상태**  
데이터 수집 / 분석 도구

---

### [nara](https://github.com/whan1569/nara)

**목적**  
나라장터 입찰 데이터를 자동화와 OCR을 통해 수집하고 구조화하기 위한 프로젝트입니다.

**분야**  
`Python` `Selenium` `PyAutoGUI` `OCR` `Google Vision` `MySQL`

**주요 내용**
- Selenium, PyAutoGUI 기반 브라우저/화면 자동화
- Google Vision OCR 기반 이미지 텍스트 추출
- 입찰 관련 비정형 데이터 구조화
- MySQL 저장 구조

**상태**  
자동화 / OCR 기반 데이터 추출 실험

---

## 3. 학습 / 구조 실험 프로젝트

특정 기술, 구조, 프레임워크, 데이터 처리 방식을 학습하거나 검증하기 위한 프로젝트입니다.

### [StepTrace_Android](https://github.com/whan1569/StepTrace_Android)

**목적**  
Android 디바이스의 센서 데이터를 수집하고 기록하는 구조를 실험하기 위한 만보기/위치 기록 앱입니다.

**분야**  
`Android` `Java` `SensorManager` `TYPE_STEP_COUNTER` `GPS` `JSON Logging`

**주요 내용**
- Android Step Counter 센서 활용
- SensorManager / SensorEventListener 기반 센서 이벤트 처리
- Activity 생명주기에 따른 센서 리스너 등록/해제
- 일정 걸음 수마다 GPS 위치 정보 기록
- JSON 형태 데이터 저장 구조

**상태**  
학습용 프로토타입 / Android 센서 구조 실험

---

### [ChatApp](https://github.com/whan1569/ChatApp)

**목적**  
C# WinForms 환경에서 TCP/IP 기반 클라이언트-서버 채팅 구조를 학습하기 위한 프로젝트입니다.

**분야**  
`C#` `WinForms` `TCP/IP` `Socket Programming`

**주요 내용**
- 클라이언트-서버 소켓 통신
- 다중 사용자 채팅 구조
- 애플리케이션 레벨 네트워크 통신 학습

**상태**  
학습용 네트워크 애플리케이션

---

### [C--MySql-connect](https://github.com/whan1569/C--MySql-connect)

**목적**  
C++ 애플리케이션과 MySQL 데이터베이스를 연동하는 구조를 학습하기 위한 실험입니다.

**분야**  
`C++` `MySQL` `Database Connection`

**주요 내용**
- C++ 애플리케이션과 MySQL 연결
- DB 연동 구조 학습
- 저수준 애플리케이션과 데이터 저장소 연결 실습

**상태**  
학습용 DB 연동 실험

---

### [aws_study](https://github.com/whan1569/aws_study)

**목적**  
AWS 배포와 인프라 구성을 학습하기 위한 저장소입니다.

**분야**  
`AWS` `EC2` `Deployment` `Infra Study`

**주요 내용**
- 클라우드 배포 학습
- 인프라 구성 실습
- 환경 설정 및 배포 흐름 정리

**상태**  
학습 기록

---

### [AI_training](https://github.com/whan1569/AI_training)

**목적**  
AI / 머신러닝 모델 학습과 데이터 처리 실습을 기록하기 위한 노트북 저장소입니다.

**분야**  
`Python` `Jupyter Notebook` `Machine Learning` `Data Processing`

**주요 내용**
- 모델 학습 실습
- 데이터 처리 실험
- 머신러닝 학습 기록

**상태**  
학습 노트북

---

## 4. AI / 비전 / 실험 자동화 프로젝트

모델을 단순히 학습시키는 것보다, 반복 실험과 평가가 가능한 구조를 만들기 위해 진행한 프로젝트입니다.

### [car_parts_scan](https://github.com/whan1569/car_parts_scan)

**목적**  
YOLOv8 기반 자동차 부품 세그멘테이션 모델을 학습하고 결과를 추적하기 위한 프로젝트입니다.

**분야**  
`YOLOv8` `Computer Vision` `Segmentation` `Model Training`

**주요 내용**
- 자동차 부품 데이터 기반 YOLOv8 세그멘테이션 실험
- 반복 학습 및 epoch별 결과 추적
- mAP, precision, loss 등 성능 지표 분석
- GPU 확인, 모델 경량화, 결과 비교 스크립트 구성

**상태**  
AI 비전 학습 / 실험 자동화

---

### [car_parts_scan-AutoML-MLflow-](https://github.com/whan1569/car_parts_scan-AutoML-MLflow-)

**목적**  
MLflow를 활용해 YOLO 학습 실험을 추적하고, 재현 가능한 모델 학습 워크플로우를 구성하기 위한 프로젝트입니다.

**분야**  
`MLflow` `Optuna` `YOLO` `Experiment Tracking` `AutoML`

**주요 내용**
- MLflow 기반 실험 기록
- Optuna 기반 하이퍼파라미터 최적화 구조 검토
- 파라미터, 메트릭, 아티팩트 관리
- early stopping 관리
- 재현 가능한 모델 학습 워크플로우 구성

**상태**  
AI 실험 추적 구조 실험

---

## 5. 보류 / 중단 / 검토 완료 프로젝트

기술 가능성은 확인했지만, 비용 대비 효율, 구현 난이도, 시간, 방향성 문제로 멈춘 프로젝트입니다.

### [VisionDrive_Risk](https://github.com/whan1569/VisionDrive_Risk)

**목적**  
모바일 카메라와 Optical Flow 기반 움직임 분석을 활용해 사고 전조 판단이 가능한지 검토한 프로젝트입니다.

**분야**  
`Computer Vision` `Optical Flow` `React Native` `Expo` `Mobile Camera` `Risk Detection`

**주요 내용**
- 카메라 영상 기반 사고 전조 판단 가능성 검토
- Optical Flow 기반 시각적 이동 흐름 분석
- Expo / React Native 환경에서 카메라 앱 연결
- 모바일 센서 활용 가능성 확인
- 고성능 비전 모델 대비 직접 구현의 비용과 효율 검토

**상태**  
기술 검토 완료 / 보류

---

### [FairWay](https://github.com/whan1569/FairWay)

**목적**  
웹/서비스 아이디어를 초기 형태로 검토한 기획형 프로토타입입니다.

**분야**  
`Web Prototype` `Service Idea` `Planning`

**주요 내용**
- 초기 서비스 아이디어 실험
- 웹 기반 서비스 구조 검토

**상태**  
초기 아이디어 / 보류

---

### [insurance_blockchain](https://github.com/whan1569/insurance_blockchain)

**목적**  
보험 서비스와 블록체인 구조를 결합할 수 있는지 검토한 컨셉형 프로토타입입니다.

**분야**  
`Blockchain` `Insurance` `Service Concept`

**주요 내용**
- 보험과 블록체인 구조 결합 아이디어 실험
- 서비스 컨셉 구조 검토

**상태**  
컨셉 검토 / 보류

---

### [National_Fiscal_Evaluation](https://github.com/whan1569/National_Fiscal_Evaluation)

**목적**  
국가 재정과 거시경제 데이터를 활용한 평가 구조를 검토하기 위한 초기 실험입니다.

**분야**  
`Macro Data` `Fiscal Evaluation` `Economy`

**주요 내용**
- 거시경제 및 국가 재정 평가 아이디어
- 국가 단위 데이터 기반 분석 구조 검토

**상태**  
초기 아이디어 / 보류

---

## 6. 데이터 / 분석 / 시각화 실험

데이터를 수집하거나 시각화하거나, 분석 구조를 실험하기 위한 프로젝트입니다.

### [Item_listup](https://github.com/whan1569/Item_listup)

**목적**  
상품명과 검색어를 수집하고 정규화하여 상품/엔티티 분석을 위한 데이터셋을 만드는 프로젝트입니다.

**분야**  
`Python` `Web Data` `Text Processing` `CSV`

**주요 내용**
- 웹 기반 상품명 및 검색어 수집
- 검색어 정규화
- 노이즈 제거
- 상품명, 브랜드, 카테고리, 성분, 속성 분류
- CSV 출력 구조 구성

**상태**  
데이터 정제 / 엔티티 분석 실험

---

### [Nasdaq_crawler](https://github.com/whan1569/Nasdaq_crawler)

**목적**  
NASDAQ 종목, ETF, 주요 지수 데이터를 수집하고 정리하기 위한 프로젝트입니다.

**분야**  
`Python` `NASDAQ` `Yahoo Finance` `CSV` `Chart Viewer`

**주요 내용**
- NASDAQ 종목 및 ETF 데이터 수집
- Yahoo Finance 기반 데이터 수집 흐름
- 주식, ETF, 주요 지수 데이터 정리
- CSV 출력 및 차트 뷰어 실험

**상태**  
시장 데이터 수집 실험

---

### [Stock_charts](https://github.com/whan1569/Stock_charts)

**목적**  
주식 시장 데이터를 시각화하고, 트리맵 및 각도 차트 등 표현 방식을 실험하기 위한 프로젝트입니다.

**분야**  
`Python` `Stock Data` `Visualization` `Treemap`

**주요 내용**
- NASDAQ 주식/ETF 데이터 기반 시각화
- 트리맵 차트 실험
- 각도 차트 실험

**상태**  
데이터 시각화 실험

---

### [bitcoin](https://github.com/whan1569/bitcoin)

**목적**  
암호화폐 시장 데이터를 분석하고 BTC 시장 흐름을 실험적으로 해석하기 위한 저장소입니다.

**분야**  
`Python` `Crypto Data` `BTC` `Market Analysis`

**주요 내용**
- 암호화폐 데이터 분석
- BTC 및 시장 데이터 흐름 분석

**상태**  
시장 분석 실험

---

## 7. 웹 / 앱 / 서비스 프로토타입

웹, 앱, 서비스 구조를 직접 만들어보거나 UI/운영 흐름을 실험한 프로젝트입니다.

### [SkinNote_OPS](https://github.com/whan1569/SkinNote_OPS)

**목적**  
피부/제품 운영 서비스의 프론트엔드 구조와 UI 흐름을 실험한 프로젝트입니다.

**분야**  
`TypeScript` `Frontend` `Service Prototype` `UI`

**주요 내용**
- TypeScript 기반 프론트엔드 구조
- UI 및 서비스 구조 설계
- 제품/운영 서비스 흐름 실험

**상태**  
서비스 프로토타입

---

### [TOPIK](https://github.com/whan1569/TOPIK)

**목적**  
TOPIK 모의시험과 취약 유형 기반 학습 추천 구조를 구현한 프로젝트입니다.

**분야**  
`JavaScript` `Recommendation` `Education Service`

**주요 내용**
- TOPIK 문제 번호별 고정 출제 유형 활용
- 모의시험 응시 후 오답 유형 분석
- 자주 틀리는 유형과 유사한 문제 추천
- 규칙 기반 추천 구조 설계

**상태**  
교육 서비스 프로토타입

---

## Repository Map

| 성격 | Repositories |
|---|---|
| 실무 기록 | Woojin_works |
| 활동 기록 | college_career |
| 교육 과정 산출물 | team3_web, Team3, TOPIK |
| 개인 시스템 | fund_data_collector, TradingBot, UN_Comtrade_Collector |
| 데이터 수집/자동화 | nara, Item_listup, Nasdaq_crawler |
| AI/비전 실험 | car_parts_scan, car_parts_scan-AutoML-MLflow-, AI_training |
| Android/네트워크 학습 | StepTrace_Android, ChatApp |
| 보류/검토 완료 | VisionDrive_Risk, FairWay, insurance_blockchain, National_Fiscal_Evaluation |
| 서비스 프로토타입 | SkinNote_OPS |

---

## Tech Stack

### Industrial / Embedded
`C` `B&R PLC` `Automation Studio` `I/O Mapping` `Cyclic Control Logic` `SVN`

### Data / Automation
`Python` `Selenium` `PyAutoGUI` `Requests` `BeautifulSoup` `Pandas` `CSV` `Parquet` `JSON`

### AI / Vision
`YOLOv8` `OpenCV` `Optical Flow` `MLflow` `Optuna` `Jupyter Notebook`

### Backend / Frontend
`Node.js` `Express` `React` `Vite` `TypeScript` `JavaScript` `JWT` `MySQL`

### Mobile / Sensor
`Android Java` `SensorManager` `TYPE_STEP_COUNTER` `GPS` `React Native` `Expo`

### Finance / Market APIs
`Binance API` `yfinance` `FRED API` `UN Comtrade API`

---

## Archive Policy

이 저장소들은 모두 완성품만을 의미하지 않습니다.

- 실제 사용되었거나 실무와 연결된 프로젝트
- 학습을 위해 만든 프로젝트
- 구조를 검증하기 위한 프로젝트
- 기술 가능성은 확인했지만 보류한 프로젝트
- 실패하거나 중단했지만 판단 근거가 남아 있는 프로젝트

를 구분하여 보관합니다.

각 프로젝트는 이후 자기소개서, 면접, 포트폴리오 문서에서 목적에 맞게 선택적으로 꺼내기 위한 기술 기록입니다.
