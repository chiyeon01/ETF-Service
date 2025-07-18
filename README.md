# "적립식 투자자"를 위한 전략적 ETF 투자 서비스
![image](https://github.com/user-attachments/assets/40b0d03a-3a07-4742-84ac-c497f6dcff97)
<br/><br/>

## 목차
1. **서비스 제안 배경 및 필요성**
<br/>

2. **환경 설정**
<br/>

3. **모델 설명**
<br/>

4. **프로토타입 설명**
<br/>

5. **팀 구성**
<br/><br/>

## 1. 서비스 제안 배경 및 필요성
<br/><br/>

### ▶ 지수 추종 ETF의 적립식 투자
<br/>

안정성을 추구하는 많은 투자자들이 나스닥100, S&P500, 코스피200 등과 같은 지수 추종 ETF에 투자하는 사례 증가.
적립식 투자는 일정 금액을 정기적으로 투자하므로, 고점에서 한 번에 투자하는 리스크를 줄임.
따라서 안정성을 추구하는 투자자들에게는 좋은 방식.
지수는 결국 장기적으로 우상향 하기 때문에 단기 등락보다는 장기 보유가 핵심 -> 적립식 투자
<br/><br/>

### ▶ 적립식 투자의 문제점
<br/>

❗ **지수 고평가 시점에서의 투자**<br/>
지수가 고평가된 상태일 때, 계속 적립하면 비싼 가격에 매수하게 됨. => 향후 조정이나 하락시 수익률 악화 가능성
<br/><br/>

❗ **하락장에서의 투자**<br/>
경기 침체기의 경우 기수가 계속해서 하락
하락의 원인이 구조적인 경우, 회복까지의 시간 증가 ex) 버블 붕괴, 코로나
<br/><br/>

### ▶ 솔루션
<br/>

✔ **지수 고평가 시점에서의 투자**
<br/>

* 한국은행 자료 기반 분석

* 동향에 따라 투자 비중 조정 가이드

* 글로벌 경제 뉴스 기반 분석

* 섹터/국가 리밸런싱 추천
<br/><br/>

✔ **하락장에서의 투자**
<br/>

* 한국은행 자료 기반 분석

* 하락 원인 별 전략 제시

* 글로벌 경제 뉴스 기반 분석

* 현금 비중 전략 & 리스크 경고
<br/><br/>

## 2. 환경 설정
<br/><br/>

### ▶ Chrome Browser Download
<br/>

```
wget https://storage.googleapis.com/chrome-for-testing-public/138.0.7204.92/linux64/chrome-linux64.zip
```

```
wget https://storage.googleapis.com/chrome-for-testing-public/138.0.7204.92/linux64/chromedriver-linux64.zip
```

```
unzip https://storage.googleapis.com/chrome-for-testing-public/138.0.7204.92/linux64/chrome-linux64.zip
```

```
unzip https://storage.googleapis.com/chrome-for-testing-public/138.0.7204.92/linux64/chromedriver-linux64.zip
```
<br/><br/>

### ▶ Chrome Browser 파일 경로 변경
<br/>

## 방법 1.
<br/>

아래와 같이 브라우저 및 드라이버의 경로를 바꿔야 합니다.

```
"/usr/local/bin/chromedriver"  # ChromeDriver 경로
"/usr/bin/google-chrome"  # Chrome 브라우저 경로
```
<br/><br/>

## 방법 2.
<br/>

아래와 같이 브라우저 및 드라이버를 사용자 설정에 맞게 바꿔야 합니다.
chromedriver_path, chrome_path 변수는 function.py에 존재합니다.
```
chromedriver_path = "/usr/local/bin/chromedriver"  # ChromeDriver 경로
chrome_path = "/usr/bin/google-chrome"  # Chrome 브라우저 경로
```
<br/><br/>

### ▶ APP 실행
<br/>

```
streamlit run app.py
```
<br/><br/>

## 3. **모델 설명**
<br/><br/>





