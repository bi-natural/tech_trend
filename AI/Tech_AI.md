# AI / Deep Learing 기반 사업 방향

Deep Learning도 AI의 전체 범주에 들어가는 일부 기술이지만, 최신 AI 기술/트렌드 범주에 포함하여 간주함.

- 주요 참고문헌
  - (from Issue Paper 2016-08) 한국과학기술기획평가원
  - (from SRA MonthlySensing 2016 Year-End Review) SRA
  - 미래학자의 인공지능 시나리오 / 최윤식 지음
  - 기타

## 인공지능(AI: Artificial Intelligence) & 딥러닝(Deep Learning)

- AI 의 3대 방향 : 지능화, 자율화, 영생화
  - 지능화: SW 적인 Intelligence (인간의 지능을 대신)
  - 자율화: 자율적인 동작 (인간의 operation이 아닌 스스로의 동작) == H/W + 지능
  - 영생화: Biological, Digital적인 인간의 융합
    - enhanced human by 생물학적 진화(bio센서, bio프로세서, ...)
    - digital human. 휴먼 업로드

- AI: 기계나 소프트웨어를 이용하여 인간의 지능활동을 구현하도록 한 결과물 또는 연구분야 (협의의 AI)
  - 단기적으로는 추론(Expert System), 학습, 지식보유, 자연어 이해/구사
  - 초장기: 정보분류에 많이 사용(협의) 광고, 카테고리 분류, 검색, 페이지 링크 등 광범위한 데이터. 비정형텍스트 에 대한 분류 및 분석 (주요 알고리즘은 귀납적 학습방법, 통계/확률론 기반 Classification, ...)
  - 현재: 텍스트가 아닌 음성/영상에 대한 분석, 자동차/로봇 등 다양한 분야에 인공화된 지능을 탑재하려는 시도. 자동화(자율화) 및 최적화에 초점
  - 딥러닝(Deep Learning) : 인공신경망(ANN: Artificial Neural Network)기반의 머신러닝기반으로 기계학습에 의한 지능화 시도

- 주요 기업들의 딥러닝 활용 분야
  - 대형 IT업체 (Google, Facebook, Baidu) 등 대규모 데이터를 소유한 업체 중심으로 빅데이터 분야에서 AI 활용
  - 자동차 제조기업들의 자율주행 자동차
  - 얼굴인식, 사물인식, 자연어처리, 상품추천, 금융분석 등 ...

- 인공지능을 활용한 빅데이터 분석 관련시장은 2019년까지 486억$(57조) 규모 예상

### 딥러닝 기술 개요

- 머신러닝 vs. 딥러닝
  1. 정해진 목적을 위해 스스로 방법을 찾고 결과 도출
  2. (입력, 목표/출력)를 입력받아 스스로 프로그램을 만드는 것
  3. 주로 대량의 데이터를 학습하는 과정에서 feature들의 weight값들을 수 많은 계산(행렬계산)을 통해 반복적으로 학습 --> 방대한 연산량에 엄청난 처리용량 필요

- 딥러닝
  1. 2001년 이후 GPU 및 분산시스템 기반의 병렬처리 기술로 '엄청난 처리용량'이 가능해짐. 알파고는 1202개의 CPU와 176개의 GPU로 구성된 분산처리 시스템 기반 병렬처리 기술 사용.
  2. 대신 알고리즘은 보다 간결하게 개선 (기존 activation function보다 훨씬 간략화된 ReLU 적용, 학습중 뉴런노드를 임의로 배제하는 Dropout 방식)하여 빠르게 학습을 진행함
  3. 세부 응용분야별 연구 활발히 진행. 영상인식에는 CNN(Convolutional Neural Network), 자연어처리에는 RNN(Recurrent Neural Network) + LSTM(Long-Short Term Memory)

### 딥러닝 관련 연구개발/산업

Tractica(2015)

- 8대 기술 분야
  - 인지컴퓨팅(Cognitive Computing)
  - 머신러닝(Machine Learning)
  - 딥러닝(Deep Learning)  ****
  - 예측API (Preditive API) *
  - 자연어처리(Natural Language Processing) **
  - 이미지인식(Image Recognition) ***
  - 음성인식(Speech Recognition) **
  - 기타

- 15개 응용 영역
  - 90% 이상 (CAGR)
    - 광고, 데이터저장(Data Storage), 투자(Investment), 제조(Manufactoring), 석유가스(Oil/Gas)
  - 80% 이상
    - 소비자금융(Finance), 보건(Healthcare)
  - 70% 이상
    - 미디어(Media), 의료진단(Medical Diagnostic), 자선활동(Philanthropies)
  - 60% 이상
    - 교육(Education), 소매(Retail)
  - 60% 미만
    - 자동차(Automotive), 농업(Agriculture), 법률(Legal)

  - 매출별
    - 광고 > 자동차 > 농업 > 소비자금융 > 데이터저장 > 교육 > 투자 > 보건 > 법률 > 제조 > 미디어 > 의료진단 > 석유/가스 > 자선활동 > 소매 순

TechNavio(2015)

- 4대 응용분야
  - 전문가시스템(Expert System) : 인간전문가의 의사결정을 모사한 시스템
  - 자율로봇(Autonomous Robot) : 자율주행차, 제조로봇 등 SW + HW
  - 지능적 가상보조시스템(Intelligent Virtual Assistants) : 기업/개인 대상의 각종 서비스, 이쪽은 Long-tail business 성격
  - 기타

### 딥러닝(혹은 AI)과 관련된 상품/서비스 시장의 성격

- 딥러닝 결과물 자체보다는 Deep Learning + 기존SW, Deep Learning + HW 융합방식을 통해 가치 제공
  - 자율형 자동차, 제조로봇
  - 광고/전문가 시스템
  - 자체적인 성능향상 뿐만 아니라 특정 HW, SW의 결합을 목표로 융합적으로 일어남
- 제조/서비스에서 맞춤형 상품제공에 따라 Long-tail business 형태를 띈다
  - 데이터에 기반한 개별적 상황에 대한 분류/예측 --> 이에 따라 결과물도 다름
  - 특정 소비자계층, 환경에 맞는 맟춤형 상품/서비스 제공으로 예상
- 학습데이터의 질이 기술의 성능을 좌우 -> 기업이 가진 데이터의 질이 상품의 경쟁력 좌우
  - 동일한 딥러닝 기술수준을 갖고 있더라도 딥러닝 네트워크의 성능을 향상시킬 수 있는 데이터를 보유했느냐가 시장 성패 좌우
- 네트워크 효과가 강하게 작용
  - 글로벌 주요기업들은 개발 플랫폼을 오픈플랫폼화 (Google Tensorflow)
  - 해당 플랫폼 중심의 생태계 구축 및 사용료 매출 기대 (? 데이터도 포함 ??)

### 딥러닝 주요 적용 분야 및 기업별 현황

- 자율 주행
  - CNN 기반의 이미지/영상 인식에 의한 자율 주행

- 자율 로봇
  - CNN 기반의 시각정보 판단에 따른 공정 자동화 (범용적, 공정 학습 -> 자율화)
  - 새로운 물체에 대한 인식과 기존에 관찰한 물체의 변화를 학습하여 작업 현장에서 범용적으로 활용가능한 신뢰성 높은 자율 로봇 개발
  - (버클리) 사람의 동작으로 기계가 인지하여 배우고 그에 따라 작업을 진행하는 등 스스로 시행착오와 학습을 하는 로봇 (BRETT)

- 이미지인식
  - 페이스북 : 얼굴인식 97.5%
  - 구글포토 : 자동인식기능
  - 이미지넷 머신러닝 컨테스트

- 자연어 처리
  - 음성합성/인식/번역 등이 기존에 각자의 고유의 알고리즘이 있었으나, 현재는 딥러닝 공통 적용...
  - 음성인식의 경우 딥러닝 적용후 크게 향상됨 (Google 92%)
  - 자연어번역의 경우 문화, 번역대상, 발화자 성향 등으로 속도가 늦는 편...

- 상품추천
  - 소비자 성향에 대한 빅데이터 기반 학습. 특정 소비자의 소비 성향 분석/예측
  - 인터넷 쇼핑몰, 음악(스트리밍), 영화

- 금융
  - 투자 자문 및 트레이딩 : 알고리즘 트레이딩 -> 딥러닝기반으로 더 방대한 데이터 분석. 기업의 부도 예측 , 주가 예측
  - 핀테크 : SNS, 모바일, 인터넷 웹 데이터를 활용한 개인 신용평가 모델
  - 온라인 거래에 대한 이상거래탐지(FDS)

- 창작
  - 그림 제작, 작곡, ...

### 기술

- AI 오픈소스 제공의 본격화
  - Google의 Tensorflow, MS의 CNTK, Facebook의 Torch, Amazon의 DSSTN
  - 주요 IT기업들이 자사의 AI API를 오픈소스로 공개하여, AI개발자 커뮤니티의 기술/애플리케이션 개발을 적극 지원

- AI 공동연구를 위한 기업 협력체 조직 활발
  - Open AI, Partnership on AI 등 설립을 통해 IP제약없는 기술 장려
  - Open AI: 가정용 로봇, 대화형 챗봇, 게임용 Intelligent Agent 개발 지원을 위한 관련 알고리즘 Toolkit 및 학습 플랫폼 제공
  - Partnership on AI : AI 관련한 인문학적 문제 해결에 주력

- 고찰
  - 상용업체는 개발자 커뮤니티와의 긴밀한 연대를 통한 AI기술/어플리케이션과 방대한 데이터를 효과적으로 확보하여 관련 업계 선점에 무게를 둠
  - Open AI는 AI의 democratization 정착을 기대

### 구글

- 클라우드형 Machine Learning 라이브러리 공개
  - 음성/문자 인식 및 변환, 이미지 인식/분류, 데이터 분석 시각화 서비스
- 수백대의 컴퓨터를 활용해 Deep Learning을 동시에 지원하는 Tensorflow 제공
  - 기존 학습시간대비 획기적으로 단축 (수주 -> 수시간)
- Neural Network Syntax Net 제공: 문자의 모호함 해결
- 3D 게임학습용 AI 플랫폼 'DeepMind Lab' 제공

### 페이스북

- Deep Learning 툴킷 'Torchnet' 제공
  - Deep Learning 모델 구축용 프레임워크 Torch
  - 신속한 AI 애플리케이션 개발 지원
- Computer Vision용 객체 분리 및 객체 식별 기술 제공
  - DeepMask, SharpMask, MultiPathNet
- GPU향 Recurrent Model 테스트용 Torch-rnnlib, Torch-cudnn 제공

### 마이크로소프트

- CNTK AI Toolkit 제공
- AI 알고리즘 테스트 SW 오픈소스화: MineCraft 게임을 테스트용 환경으로 제공
- CNTK 2.0 Toolkit 제공
  - Python 과 Reinforcement Learning 지원 강화
  - Deep Learning, Machine Learning 성능 개선

### 아마존

- Deep Learing SW 'DSSTNE' 제공
  - GPU를 데이터 학습 및 Deep Learing 애플리케이션에 적용

### IBM

- Watson Analytics 오픈소스형 베타서비스 제공
- Cloud기반 Freemium 서비스 제공

### OpenAI

- 실리콘밸리 주요 기업, 투자자들이 비영리목적의 AI 연구 수행을 위한 OpenAI 설립
- 인간의 대체 목적이 아닌 증가(Augment)형 기술 확보에 초점
- Reinforcement Learning 알고리즘 테스트 Toolkit 'Gym' 공개
- AI 학습 플랫폼 'Universe' 제공
  - 방대한 업무를 효과적으로 수행하는 방법을 학습후 다양한 업무별 적용이 가능한 범용형 AI 플랫폼

### 신 알고리즘 개발 활발

"고급 AI 기술(?)"을 이용하여 패턴 인식에 집중되었던 기존 방식을 극복하기 위한 다양한 시도가 활발

- 문맥이해, 추론 기능 강화: 상대적으로 적은 데이터 만으로 상황을 이해하고 적절한 행동을 결정/추론하는 연구 확대

- AI학습 및 행동결정과정에 인간이 적극적으로 개입(Human In The Loop)형 알고리즘 중요성 강조

- 인간 친화영 AI 개발 (일상생활 관찰을 통한 인간에 대한 이해하여 서비스 로봇에 접목)

- 실생활 애플리케이션 AI기술을 적용하기 위한 시도 증가하여 범용 AI 기술과 타겟형 AI 알고리즘 개발로 이분화
  - 다양한 서비스 지원을 위한 Super Intelligence 개발
  - 용도별 지원을 위한 Target 형 Intelligence 개발
