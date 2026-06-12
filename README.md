# Seoul After-Work Culture Map

**밤이 되면 서울의 문화지도는 줄어든다**  
An interactive data story revealing how Seoul's cultural map shrinks after dark.

`Seoul` · `Night Culture` · `Scrollytelling` · `Data Visualization` · `Public Data`

---

## English

### Overview

**Seoul After-Work Culture Map** is an interactive scrollytelling visualization about night-time cultural accessibility in Seoul.

Seoul has **1,054 registered cultural spaces**, including museums, galleries, performance venues, libraries, and other public cultural facilities. At first glance, the city appears to have abundant cultural infrastructure. However, when the map is viewed from the perspective of people trying to enjoy culture **after work or after school**, the accessible cultural map becomes much smaller.

This project asks one central question:

> Does the number of cultural spaces truly explain the cultural experience available to citizens after dark?

The answer suggested by the data is clear:  
**Seoul's cultural bottleneck at night is not mainly cost, but time.**

### Key Findings

- Seoul has **1,054** registered cultural spaces, but they are spatially concentrated.
- The top 5 districts account for **51%** of all cultural spaces.
- Jongno-gu has **244** cultural spaces, while Jungnang-gu has **13**, a gap of **18.8x**.
- Cultural demand is strong: the 2024 direct cultural-event attendance rate reached **63.0%**.
- Seoul's public transit activity peaks on **Friday**, with an average of **10.92 million trips** per day.
- Among cultural spaces with clearly available operating hours, only **45** remain open after 19:00.
- Only **4.3%** of all registered cultural spaces are explicitly confirmed as open after 19:00.
- **68%** of cultural spaces are free, suggesting that time accessibility is a stronger bottleneck than price.

### Main Argument

The project reframes cultural accessibility as a combination of three conditions:

```text
Night-time Cultural Accessibility
= Opening Hours × Return-Home Accessibility × Cost Accessibility
```

Since many cultural spaces are already free, the key challenge is whether they are open when citizens can actually visit them, and whether people can return home safely and conveniently afterward.

### Visualization Structure

The experience is organized as a full-screen scroll-based story:

1. **Supply**: How many cultural spaces Seoul has
2. **Day Map**: Where those spaces are concentrated
3. **Demand**: Whether people actually want cultural experiences
4. **Urban Rhythm**: When Seoul moves the most
5. **Last Mile**: Why returning home matters after night-time culture
6. **Closing Time**: How many spaces close around 18:00
7. **Night Map**: How few spaces remain open after 19:00
8. **Cost**: Why price is not the main barrier
9. **Policy Evidence**: Existing night-opening policies and their limits
10. **Proposal**: How Seoul can expand night-time cultural access

### Data Sources

- Seoul Open Data Plaza: **Seoul Cultural Space Information**
- Seoul Open Data Plaza: **Public Transportation Usage Pattern Information**
- Ministry of Culture, Sports and Tourism / Korea Culture & Tourism Institute: **2024 National Culture and Arts Activity Survey**
- Seoul Metropolitan Government policy materials on night-time cultural facility opening
- Korea Tourism Organization materials on night tourism and its economic effects

### Built With

- HTML
- CSS
- JavaScript
- Public open data
- Static single-page scrollytelling design

No backend server is required.

### How to View

Clone or download this repository, then open the main HTML file in **Chrome**.

For GitHub Pages deployment, it is recommended to rename the main HTML file to:

```text
index.html
```

Then enable GitHub Pages from the repository settings.

### Notes

The operating-hour analysis is based on facilities whose hours were explicitly available in the public dataset. This limitation is part of the project's argument: if operating hours are not publicly visible, night-time cultural accessibility cannot be properly measured or experienced by citizens.

---

## 한국어

### 프로젝트 소개

**Seoul After-Work Culture Map**은 서울의 야간 문화 접근성을 다룬 인터랙티브 데이터 시각화 프로젝트입니다.

서울에는 미술관, 공연장, 박물관, 도서관 등 **1,054개**의 문화공간이 등록되어 있습니다. 숫자만 보면 서울은 이미 충분히 문화 인프라가 많은 도시처럼 보입니다. 하지만 관점을 바꿔서 **퇴근 후, 또는 수업이 끝난 뒤의 시민**이 실제로 갈 수 있는 공간을 보면 서울의 문화지도는 훨씬 작아집니다.

이 프로젝트는 하나의 질문에서 출발합니다.

> 문화공간의 개수는 정말 시민의 저녁 문화생활을 설명할 수 있을까?

데이터가 보여주는 결론은 명확합니다.  
**서울의 밤 문화에서 가장 큰 병목은 비용보다 시간입니다.**

### 핵심 발견

- 서울에는 **1,054개**의 문화공간이 있지만, 공간적으로 고르게 분포되어 있지 않습니다.
- 상위 5개 구가 전체 문화공간의 **51%**를 차지합니다.
- 종로구는 **244곳**, 중랑구는 **13곳**으로 두 지역의 차이는 **18.8배**입니다.
- 문화 수요는 충분합니다. 2024년 문화예술행사 직접 관람률은 **63.0%**입니다.
- 서울의 대중교통 통행량은 **금요일**에 가장 높고, 하루 평균 **1,092만 건**을 기록합니다.
- 운영시간이 명시된 문화공간 중 19시 이후에도 열려 있는 곳은 **45곳**뿐입니다.
- 전체 1,054곳 기준으로 보면 19시 이후 개방이 확인되는 공간은 **4.3%**입니다.
- 서울 문화공간의 **68%**는 무료입니다. 따라서 가격보다 시간이 더 큰 장벽으로 나타납니다.

### 핵심 주장

이 프로젝트는 야간 문화 접근성을 다음과 같이 정의합니다.

```text
야간 문화 접근성
= 개방 시간 × 귀가 접근성 × 비용 접근성
```

이미 많은 문화공간이 무료라면, 더 중요한 질문은 시민이 실제로 갈 수 있는 시간에 열려 있는지, 그리고 문화생활 이후 집으로 돌아갈 수 있는지입니다.

### 시각화 구성

전체 화면 스크롤 방식의 데이터 스토리로 구성되어 있습니다.

1. **공급**: 서울에는 문화공간이 얼마나 많은가
2. **낮의 지도**: 문화공간은 어느 구에 집중되어 있는가
3. **수요**: 시민들은 문화생활을 원하고 있는가
4. **도시의 리듬**: 서울은 언제 가장 크게 움직이는가
5. **귀가**: 밤 문화 이후 집으로 돌아가는 조건은 어떤가
6. **마감 시간**: 문화공간은 몇 시에 문을 닫는가
7. **밤의 지도**: 19시 이후에도 불이 켜진 공간은 얼마나 남는가
8. **비용**: 가격이 정말 핵심 장벽인가
9. **정책 검증**: 서울의 야간개방 정책은 어디까지 와 있는가
10. **제안**: 서울의 밤 문화 접근성을 어떻게 넓힐 수 있는가

### 사용 데이터

- 서울열린데이터광장: **서울시 문화공간 정보**
- 서울열린데이터광장: **서울시 대중교통 이용패턴 정보**
- 문화체육관광부·한국문화관광연구원: **2024 국민문화예술활동조사**
- 서울특별시 야간 문화시설 개방 관련 정책자료
- 한국관광공사 야간관광 관련 자료

### 사용 기술

- HTML
- CSS
- JavaScript
- 공공데이터 전처리
- 정적 단일 페이지 기반 스크롤텔링 디자인

별도의 백엔드 서버 없이 실행할 수 있습니다.

### 실행 방법

레포지토리를 다운로드하거나 클론한 뒤, 메인 HTML 파일을 **Chrome**에서 열면 됩니다.

GitHub Pages로 배포하려면 메인 HTML 파일명을 다음과 같이 바꾸는 것을 추천합니다.

```text
index.html
```

그 다음 GitHub 저장소 설정에서 GitHub Pages를 활성화하면 됩니다.

### 해석상 유의점

운영시간 분석은 공공데이터에서 운영시간이 명시적으로 확인되는 시설을 기준으로 진행했습니다. 이는 분석의 한계이면서 동시에 프로젝트의 중요한 문제의식입니다. 운영시간이 공개되어 있지 않다면, 시민 입장에서는 그 공간이 밤에 열려 있는지 알 수 없고, 야간 문화 접근성도 정확히 측정하기 어렵습니다.

---

## Project Message

> Seoul's night is not open to everyone yet.  
> But it can be opened.

> 서울의 밤은 아직 모두에게 열려 있지 않습니다.  
> 그러나, 열 수 있습니다.
