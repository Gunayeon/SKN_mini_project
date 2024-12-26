## ⭐️ 1st Project ⭐️

### 🔍 전국 자동차 등록 현황 및 기업 FAQ 조회 시스템 🔍
<br>
<h4>📌 설명</h4> 

이 프로젝트는 웹 크롤링과 open api를 활용하여 전국 자동차 등록 데이터와 기업 FAQ 정보를 조회할 수 있는 웹 애플리케이션이다.<br>
사용자들이 Streamlit 기반의 직관적인 UI를 통해 데이터를 탐색하고, 필요한 정보를 손쉽게 확인 가능하도록 개발하였다.

<br>

#### 📌 개발 기간
 2024.07.24 ~ 2024.07.25 

<br>

#### 📌 프로젝트 주요 내용
⓵ **자동차 등록 현황 조회 시스템**
> 전국 자동차 분포 현황과, 전국 자동차 등록 개수, 지역별 차량 등력 현황을 시각화하여 사용자에게 제공<br>
> 위의 정보를 제공함으로서 시장연구, 경쟁사 분석, SNS 트렌드 파악 등 다양한 분야에 활용이 가능하며, 의사결정에 활용하는데 도움을 줄 수 있음

⓶ **상위 차량 기업 FAQ 조회 시스템**
> 2개의 국내 차량 상위기업의 FAQ정보를 사용자에게 제공합니다.<br>
> FAQ 제공 시스템은 사용자들이 필요한 정보를 빠르고 간편하게 얻을 수 있도록 도와주며, 고객 만족도를 높이는 데 기여<br>
> 더 나아가 단순한 정보 전달을 넘어, 자동차 산업의 정보 접근성을 높이고 고객과 기업 모두에게 실질적인 이익을 제공하는 중요한 도구가 될 수 있음

<br>

#### 📌 프로젝트 주요 사용기술
⓵ 데이터 수집
> **웹 크롤링** : 기업 FAQ 수집
> - `BeautifulSoup`, `Selenium`
> 
> **api** : 전국 자동차 등록 현황 데이터를 수집하고 지역, 휘발유차 현황, 경유차 현황, LPG 현황, 전기차 현황을 주요 column으로 지정하여 저장

⓶ 데이터베이스
> `MySQL`을 사용하여 **ERD 설계** 및 저장

⓷ 웹 프레임워크
> `Streamlit` 활용

⓸ 데이터 처리 및 시각화
> `Pandas`, `Matplotlib/Plotly` 활용

<br> 

#### 📚 프로젝트 결과

| 기업 FAQ | 전국 자동차 분포 현황 | 
|--|--|
| ![image](https://github.com/SKNETWORKS-FAMILY-AICAMP/SKN03-1st-4Team/blob/main/image-10.png) | ![image](https://github.com/SKNETWORKS-FAMILY-AICAMP/SKN03-1st-4Team/blob/main/image-11.png) |
| 전국 자동차 등록 개수 | 차량 별 등록 현황 |
| ![image](https://github.com/SKNETWORKS-FAMILY-AICAMP/SKN03-1st-4Team/blob/main/image-11.png) | ![image](https://github.com/SKNETWORKS-FAMILY-AICAMP/SKN03-1st-4Team/blob/main/image-13.png)

<br>

#### 🎯 프로젝트 주요 가치 및 활용점
> 이 시스템은 단순히 데이터를 제공하는 데 그치지 않고, 다양한 이해관계자(정부, 기업, 개인)에게 의사결정을 지원하고, 사회적, 경제적, 환경적 문제 해결에 기여할 수 있는 중요한 도구로 활용될 수 있음<br><br>
> 나 개인적으로도 이 프로젝트를 개발하면서 데이터 수집 및 분석, 웹 구현 기술을 실무적으로 활용해 볼 수 있는 경험이 되었고, 팀원들과 **의사소통**을 통해 프로젝트를 함께 기획하고 **효율적인 협업방식**으로 이틀이라는 짧은 기간에도 불구하고 프로젝트를 완료할 수 있었다.<br><br>
> 이를 통해 개인적으로는 **개발 경험**과 **자신감**을, 팀으로서는 공동 목표를 함께 이루어나가는 점에서 팀의 **시너지 효과**와 **공동 성취감**을 얻을 수 있었던 소중한 기회라고 생각 되었음