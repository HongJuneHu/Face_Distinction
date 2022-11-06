# Face_Distinction
## 프로젝트 팀 이름 : NimBird
## 프로젝트 제목 : 얼굴 사진 분류 봇
## 프로젝트 내용 : input으로 사람의 얼굴 사진을 넣어주면 닮은 연예인을 알려준다.
## 프로젝트 개발 툴 : pytorch, python, Discord
## 개발 일정 : 디스코드 봇 제작(완료) -> 데이터 수집(완료) -> 데이터 전처리 및 수정(진행중) -> 모델 학습 -> 세부 조정 -> 테스트

### 2022/10/29 수정

### 현재 디스코드 봇은 준비가 되었다.
### 데이터는 구글 크롤링을 통해 수집했다.
### 데이터 전처리 및 수정은 크롤링한 데이터에는 한명의 얼굴만이 아닌 다른 사람과 같이 찍힌 사진, 각도가 틀어진 사진, 사진의 크기, 얼굴만 인식할 수 있게 얼굴만 잘라낸 데이터를 사용할 예정이다.
### 모델은 CNN 계열의 VGG라는 모델을 사용할 것이다.
### 모델 학습 후 테스트를 진행하고 Fine Tuning을 한 다음 다시 테스트를 진행할 예정이다.

### 2022/11/01 수정

### 성이 ㄱ~ㅁ 인 사람들의 1차 데이터 처리 완료

### 2022/11/05 수정

### 성이 ㄱ~ㅂ인 사람들의 1차 데이터 처리 완료

### 2022/11/06 수정

### 성이 ㄱ~ㅈ인 사람들의 1차 데이터 처리 완료