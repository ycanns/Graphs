# Graphs | KRIHS Magazine

<p align="center">
  <img src="docs/KRIHS_icon/ci_14.jpg" alt="KRIHS" width="755"/>
</p>

Interactive visualizations accompanying the monthly KRIHS Magazine, created primarily with R and Python.

월간 국토의 분석 내용을 함께 살펴볼 수 있는 인터랙티브 지도와 그래프 모음입니다.

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![R](https://img.shields.io/badge/R-276DC3?logo=r&logoColor=white)
![Mapbox](https://img.shields.io/badge/Mapbox-000000?logo=mapbox&logoColor=white)
![Leaflet](https://img.shields.io/badge/Leaflet-199900?logo=leaflet&logoColor=white)

[월간 국토 관련 글 보기](https://www.krihs.re.kr/publica/periodicalList.es?mid=a10103010000&pub_kind=1&pageIndex=1&report_num_temp=&searchCondition=study_au&searchKeyword=%EC%9E%A5%EC%9A%94%ED%95%9C)

## 시각화 바로가기

아래 **열기** 링크를 누르면 GitHub 소스 파일 화면이 아닌 실제 대화형 시각화로 이동합니다.

| 주제 | 대표 시각화 | 바로가기 |
|---|---|---|
| 인구이동 통계 | 전국 시군구별 인구이동 (2022) | [열기](https://ycanns.github.io/Graphs/POP_move_Ipu_2022.html) |
| 인구이동 흐름 | 주요 전입지와 전출지의 이동 (2022) | [열기](https://ycanns.github.io/Graphs/POP_OD_2022_sub.html) |
| 인구이동 흐름 | Sankey Diagram (2022) | [열기](https://ycanns.github.io/Graphs/sankey_Pop_2022.html) |
| 네트워크 | 연도별 네트워크 선택 | [열기](https://ycanns.github.io/Graphs/forceNetwork_index.html) |
| 소득유형별 이동 | 대기업 급여소득자 기종점 변화 | [열기](https://ycanns.github.io/Graphs/BigCom_OD_1821_new.html) |
| 교육 | 학원교습소 등록 현황 — 전체연도 집계 | [열기](https://ycanns.github.io/Graphs/ACADMA_DATA.html) |
| 상권 | 음식 업종 평균 지속 영업 기간 | [열기](https://ycanns.github.io/Graphs/Ave_Survival_Duration_RSTRNT.html) |

## 월간 국토 호별 안내

각 안내에는 분석 배경과 해당 호에 수록된 시각화 링크가 정리되어 있습니다.

| 발행호 | 주제 | 안내 |
|---|---|---|
| 2023년 1월 | 소득 데이터로 인구이동 변화 읽기 | [보기](docs/2023/January/README.md) |
| 2023년 3월 | 통계청 전출입데이터로 국토 인구이동 읽기 | [보기](docs/2023/March/README.md) |
| 2023년 4월 | 국토의 사교육 관심 읽기 | [보기](docs/2023/April/README.md) |
| 2023년 9월 | 소상공인 데이터로 국토변화 읽기 | [보기](docs/2023/Sep/README.md) |
| 2023년 10월 | 민원 빅데이터와 전출입데이터로 국토이동 관심 읽기 | [보기](docs/2023/Oct/README.md) |

## 전체 시각화 목록

총 **480개 HTML 페이지**를 주제와 지역별로 정리했습니다. 시각화 선택용 페이지도 포함하며, 단순 초기 화면인 `index.html`은 제외했습니다.

- 아래 제목을 누르면 해당 목록으로 이동합니다. 목록의 **펼치기**를 클릭해 개별 시각화를 열어 주세요.
- 파일명은 원본 식별자를 유지했습니다. 약어와 세부 지표의 의미는 각 시각화 및 해당 호의 설명을 참고해 주세요.
- 용량은 저장소 파일 크기를 MB(1,000,000바이트)로 표시했습니다. 큰 파일은 처음 열 때 시간이 걸릴 수 있습니다.
- 데이터의 기준연도와 분석 범위는 시각화별로 다릅니다.

- [인구이동 통계와 네트워크 (43)](#population)
- [소득유형별 이동과 기종점 분석 (50)](#income-mobility)
- [전국 연령별 이동 (24)](#nationwide)
- [부산 연령별 이동 (24)](#region-busan)
- [대구 연령별 이동 (24)](#region-daegu)
- [대전 연령별 이동 (24)](#region-deajn)
- [광주 연령별 이동 (24)](#region-gwnju)
- [경기 연령별 이동 (24)](#region-gyngi)
- [인천 연령별 이동 (24)](#region-inchn)
- [세종 연령별 이동 (24)](#region-sejng)
- [서울 연령별 이동 (24)](#region-seoul)
- [울산 연령별 이동 (24)](#region-ulsan)
- [권역별 이동과 통행 (41)](#regional)
- [소득과 소비 및 금융 (19)](#economy)
- [사업체와 상권 (37)](#business)
- [교육 (14)](#education)
- [관광과 여가 (7)](#tourism)
- [시설과 공간 분포 (10)](#infrastructure)
- [민원과 뉴스 및 연구 동향 (13)](#text)
- [기타 시각화 (6)](#other)

<a id="population"></a>

### 인구이동 통계와 네트워크

<details>
<summary><b>펼치기 — 43개 페이지</b></summary>

| 파일명 | 바로가기 | 용량 (MB) |
|---|---|---:|
| `POP_OD_2012_sub.html` | [열기](https://ycanns.github.io/Graphs/POP_OD_2012_sub.html) | 0.04 |
| `POP_OD_2013_sub.html` | [열기](https://ycanns.github.io/Graphs/POP_OD_2013_sub.html) | 0.04 |
| `POP_OD_2014_sub.html` | [열기](https://ycanns.github.io/Graphs/POP_OD_2014_sub.html) | 0.04 |
| `POP_OD_2015_sub.html` | [열기](https://ycanns.github.io/Graphs/POP_OD_2015_sub.html) | 0.04 |
| `POP_OD_2016_sub.html` | [열기](https://ycanns.github.io/Graphs/POP_OD_2016_sub.html) | 0.04 |
| `POP_OD_2017_sub.html` | [열기](https://ycanns.github.io/Graphs/POP_OD_2017_sub.html) | 0.04 |
| `POP_OD_2018_sub.html` | [열기](https://ycanns.github.io/Graphs/POP_OD_2018_sub.html) | 0.04 |
| `POP_OD_2019_sub.html` | [열기](https://ycanns.github.io/Graphs/POP_OD_2019_sub.html) | 0.04 |
| `POP_OD_2020_sub.html` | [열기](https://ycanns.github.io/Graphs/POP_OD_2020_sub.html) | 0.04 |
| `POP_OD_2021_sub.html` | [열기](https://ycanns.github.io/Graphs/POP_OD_2021_sub.html) | 0.04 |
| `POP_OD_2022_sub.html` | [열기](https://ycanns.github.io/Graphs/POP_OD_2022_sub.html) | 0.04 |
| `POP_move_Ipu_2012.html` | [열기](https://ycanns.github.io/Graphs/POP_move_Ipu_2012.html) | 4.12 |
| `POP_move_Ipu_2013.html` | [열기](https://ycanns.github.io/Graphs/POP_move_Ipu_2013.html) | 4.12 |
| `POP_move_Ipu_2014.html` | [열기](https://ycanns.github.io/Graphs/POP_move_Ipu_2014.html) | 4.12 |
| `POP_move_Ipu_2015.html` | [열기](https://ycanns.github.io/Graphs/POP_move_Ipu_2015.html) | 4.12 |
| `POP_move_Ipu_2016.html` | [열기](https://ycanns.github.io/Graphs/POP_move_Ipu_2016.html) | 4.12 |
| `POP_move_Ipu_2017.html` | [열기](https://ycanns.github.io/Graphs/POP_move_Ipu_2017.html) | 4.12 |
| `POP_move_Ipu_2018.html` | [열기](https://ycanns.github.io/Graphs/POP_move_Ipu_2018.html) | 4.11 |
| `POP_move_Ipu_2019.html` | [열기](https://ycanns.github.io/Graphs/POP_move_Ipu_2019.html) | 4.11 |
| `POP_move_Ipu_2020.html` | [열기](https://ycanns.github.io/Graphs/POP_move_Ipu_2020.html) | 4.12 |
| `POP_move_Ipu_2021.html` | [열기](https://ycanns.github.io/Graphs/POP_move_Ipu_2021.html) | 4.11 |
| `POP_move_Ipu_2022.html` | [열기](https://ycanns.github.io/Graphs/POP_move_Ipu_2022.html) | 4.11 |
| `forceNetwork_2013.html` | [열기](https://ycanns.github.io/Graphs/forceNetwork_2013.html) | 0.27 |
| `forceNetwork_2014.html` | [열기](https://ycanns.github.io/Graphs/forceNetwork_2014.html) | 0.27 |
| `forceNetwork_2015.html` | [열기](https://ycanns.github.io/Graphs/forceNetwork_2015.html) | 0.27 |
| `forceNetwork_2016.html` | [열기](https://ycanns.github.io/Graphs/forceNetwork_2016.html) | 0.27 |
| `forceNetwork_2017.html` | [열기](https://ycanns.github.io/Graphs/forceNetwork_2017.html) | 0.27 |
| `forceNetwork_2018.html` | [열기](https://ycanns.github.io/Graphs/forceNetwork_2018.html) | 0.27 |
| `forceNetwork_2019.html` | [열기](https://ycanns.github.io/Graphs/forceNetwork_2019.html) | 0.27 |
| `forceNetwork_2020.html` | [열기](https://ycanns.github.io/Graphs/forceNetwork_2020.html) | 0.27 |
| `forceNetwork_2021.html` | [열기](https://ycanns.github.io/Graphs/forceNetwork_2021.html) | 0.27 |
| `forceNetwork_2022.html` | [열기](https://ycanns.github.io/Graphs/forceNetwork_2022.html) | 0.27 |
| `forceNetwork_index.html` | [열기](https://ycanns.github.io/Graphs/forceNetwork_index.html) | 0.00 |
| `sankey_Pop_2013.html` | [열기](https://ycanns.github.io/Graphs/sankey_Pop_2013.html) | 0.27 |
| `sankey_Pop_2014.html` | [열기](https://ycanns.github.io/Graphs/sankey_Pop_2014.html) | 0.27 |
| `sankey_Pop_2015.html` | [열기](https://ycanns.github.io/Graphs/sankey_Pop_2015.html) | 0.27 |
| `sankey_Pop_2016.html` | [열기](https://ycanns.github.io/Graphs/sankey_Pop_2016.html) | 0.27 |
| `sankey_Pop_2017.html` | [열기](https://ycanns.github.io/Graphs/sankey_Pop_2017.html) | 0.27 |
| `sankey_Pop_2018.html` | [열기](https://ycanns.github.io/Graphs/sankey_Pop_2018.html) | 0.27 |
| `sankey_Pop_2019.html` | [열기](https://ycanns.github.io/Graphs/sankey_Pop_2019.html) | 0.27 |
| `sankey_Pop_2020.html` | [열기](https://ycanns.github.io/Graphs/sankey_Pop_2020.html) | 0.27 |
| `sankey_Pop_2021.html` | [열기](https://ycanns.github.io/Graphs/sankey_Pop_2021.html) | 0.27 |
| `sankey_Pop_2022.html` | [열기](https://ycanns.github.io/Graphs/sankey_Pop_2022.html) | 0.27 |

</details>

<a id="income-mobility"></a>

### 소득유형별 이동과 기종점 분석

<details>
<summary><b>펼치기 — 50개 페이지</b></summary>

| 파일명 | 바로가기 | 용량 (MB) |
|---|---|---:|
| `BigCom_HM_1821_Dloss.html` | [열기](https://ycanns.github.io/Graphs/BigCom_HM_1821_Dloss.html) | 12.80 |
| `BigCom_HM_1821_Dnew.html` | [열기](https://ycanns.github.io/Graphs/BigCom_HM_1821_Dnew.html) | 16.79 |
| `BigCom_HM_1821_Oloss.html` | [열기](https://ycanns.github.io/Graphs/BigCom_HM_1821_Oloss.html) | 12.80 |
| `BigCom_HM_1821_Onew.html` | [열기](https://ycanns.github.io/Graphs/BigCom_HM_1821_Onew.html) | 16.79 |
| `BigCom_OD_1821_new.html` | [열기](https://ycanns.github.io/Graphs/BigCom_OD_1821_new.html) | 10.49 |
| `BigCom_OD_2118_loss.html` | [열기](https://ycanns.github.io/Graphs/BigCom_OD_2118_loss.html) | 8.01 |
| `Dist_BigCom_Destin.html` | [열기](https://ycanns.github.io/Graphs/Dist_BigCom_Destin.html) | 74.09 |
| `Dist_BigCom_Origin.html` | [열기](https://ycanns.github.io/Graphs/Dist_BigCom_Origin.html) | 74.08 |
| `Dist_ETC_Destin.html` | [열기](https://ycanns.github.io/Graphs/Dist_ETC_Destin.html) | 76.06 |
| `Dist_ETC_Origin.html` | [열기](https://ycanns.github.io/Graphs/Dist_ETC_Origin.html) | 75.77 |
| `Dist_FreeLancer_Destin.html` | [열기](https://ycanns.github.io/Graphs/Dist_FreeLancer_Destin.html) | 73.39 |
| `Dist_FreeLancer_Origin.html` | [열기](https://ycanns.github.io/Graphs/Dist_FreeLancer_Origin.html) | 73.46 |
| `Dist_SelfEmply_Destin.html` | [열기](https://ycanns.github.io/Graphs/Dist_SelfEmply_Destin.html) | 77.08 |
| `Dist_SelfEmply_Origin.html` | [열기](https://ycanns.github.io/Graphs/Dist_SelfEmply_Origin.html) | 77.08 |
| `Dist_StartUp_Destin.html` | [열기](https://ycanns.github.io/Graphs/Dist_StartUp_Destin.html) | 76.71 |
| `Dist_StartUp_Origin.html` | [열기](https://ycanns.github.io/Graphs/Dist_StartUp_Origin.html) | 76.32 |
| `ETC_HM_1821_Dloss.html` | [열기](https://ycanns.github.io/Graphs/ETC_HM_1821_Dloss.html) | 41.76 |
| `ETC_HM_1821_Dnew.html` | [열기](https://ycanns.github.io/Graphs/ETC_HM_1821_Dnew.html) | 52.36 |
| `ETC_HM_1821_Oloss.html` | [열기](https://ycanns.github.io/Graphs/ETC_HM_1821_Oloss.html) | 41.76 |
| `ETC_HM_1821_Onew.html` | [열기](https://ycanns.github.io/Graphs/ETC_HM_1821_Onew.html) | 52.36 |
| `ETC_OD_1821_new.html` | [열기](https://ycanns.github.io/Graphs/ETC_OD_1821_new.html) | 32.57 |
| `ETC_OD_2118_loss.html` | [열기](https://ycanns.github.io/Graphs/ETC_OD_2118_loss.html) | 26.03 |
| `FreeLncr_HM_1821_Dloss.html` | [열기](https://ycanns.github.io/Graphs/FreeLncr_HM_1821_Dloss.html) | 1.24 |
| `FreeLncr_HM_1821_Dnew.html` | [열기](https://ycanns.github.io/Graphs/FreeLncr_HM_1821_Dnew.html) | 1.83 |
| `FreeLncr_HM_1821_Oloss.html` | [열기](https://ycanns.github.io/Graphs/FreeLncr_HM_1821_Oloss.html) | 1.24 |
| `FreeLncr_HM_1821_Onew.html` | [열기](https://ycanns.github.io/Graphs/FreeLncr_HM_1821_Onew.html) | 1.83 |
| `FreeLncr_OD_1821_new.html` | [열기](https://ycanns.github.io/Graphs/FreeLncr_OD_1821_new.html) | 1.09 |
| `FreeLncr_OD_2118_loss.html` | [열기](https://ycanns.github.io/Graphs/FreeLncr_OD_2118_loss.html) | 0.78 |
| `JOB_BigCom_Destin.html` | [열기](https://ycanns.github.io/Graphs/JOB_BigCom_Destin.html) | 74.09 |
| `JOB_BigCom_Origin.html` | [열기](https://ycanns.github.io/Graphs/JOB_BigCom_Origin.html) | 74.08 |
| `JOB_ETC_Destin.html` | [열기](https://ycanns.github.io/Graphs/JOB_ETC_Destin.html) | 76.06 |
| `JOB_ETC_Origin.html` | [열기](https://ycanns.github.io/Graphs/JOB_ETC_Origin.html) | 75.77 |
| `JOB_FreeLancer_Destin.html` | [열기](https://ycanns.github.io/Graphs/JOB_FreeLancer_Destin.html) | 73.39 |
| `JOB_FreeLancer_Origin.html` | [열기](https://ycanns.github.io/Graphs/JOB_FreeLancer_Origin.html) | 73.46 |
| `JOB_SelfEmply_Destin.html` | [열기](https://ycanns.github.io/Graphs/JOB_SelfEmply_Destin.html) | 77.08 |
| `JOB_SelfEmply_Origin.html` | [열기](https://ycanns.github.io/Graphs/JOB_SelfEmply_Origin.html) | 77.08 |
| `JOB_StartUp_Destin.html` | [열기](https://ycanns.github.io/Graphs/JOB_StartUp_Destin.html) | 76.71 |
| `JOB_StartUp_Origin.html` | [열기](https://ycanns.github.io/Graphs/JOB_StartUp_Origin.html) | 76.32 |
| `SelfEmply_HM_1821_Dloss.html` | [열기](https://ycanns.github.io/Graphs/SelfEmply_HM_1821_Dloss.html) | 26.43 |
| `SelfEmply_HM_1821_Dnew.html` | [열기](https://ycanns.github.io/Graphs/SelfEmply_HM_1821_Dnew.html) | 40.73 |
| `SelfEmply_HM_1821_Oloss.html` | [열기](https://ycanns.github.io/Graphs/SelfEmply_HM_1821_Oloss.html) | 26.43 |
| `SelfEmply_HM_1821_Onew.html` | [열기](https://ycanns.github.io/Graphs/SelfEmply_HM_1821_Onew.html) | 40.73 |
| `SelfEmply_OD_1821_new.html` | [열기](https://ycanns.github.io/Graphs/SelfEmply_OD_1821_new.html) | 25.31 |
| `SelfEmply_OD_2118_loss.html` | [열기](https://ycanns.github.io/Graphs/SelfEmply_OD_2118_loss.html) | 16.52 |
| `StartUP_HM_1821_Dloss.html` | [열기](https://ycanns.github.io/Graphs/StartUP_HM_1821_Dloss.html) | 93.98 |
| `StartUP_HM_1821_Dnew.html` | [열기](https://ycanns.github.io/Graphs/StartUP_HM_1821_Dnew.html) | 88.76 |
| `StartUP_HM_1821_Oloss.html` | [열기](https://ycanns.github.io/Graphs/StartUP_HM_1821_Oloss.html) | 93.98 |
| `StartUP_HM_1821_Onew.html` | [열기](https://ycanns.github.io/Graphs/StartUP_HM_1821_Onew.html) | 88.76 |
| `StartUp_OD_1821_new.html` | [열기](https://ycanns.github.io/Graphs/StartUp_OD_1821_new.html) | 55.22 |
| `StartUp_OD_2118_loss.html` | [열기](https://ycanns.github.io/Graphs/StartUp_OD_2118_loss.html) | 58.67 |

</details>

<a id="nationwide"></a>

### 전국 연령별 이동

<details>
<summary><b>펼치기 — 24개 페이지</b></summary>

| 파일명 | 바로가기 | 용량 (MB) |
|---|---|---:|
| `NW_20s_CRD_Movements.html` | [열기](https://ycanns.github.io/Graphs/NW_20s_CRD_Movements.html) | 14.57 |
| `NW_20s_INC_Movements.html` | [열기](https://ycanns.github.io/Graphs/NW_20s_INC_Movements.html) | 15.05 |
| `NW_20s_Movements.html` | [열기](https://ycanns.github.io/Graphs/NW_20s_Movements.html) | 14.02 |
| `NW_20s_SPN_Movements.html` | [열기](https://ycanns.github.io/Graphs/NW_20s_SPN_Movements.html) | 15.76 |
| `NW_30s_CRD_Movements.html` | [열기](https://ycanns.github.io/Graphs/NW_30s_CRD_Movements.html) | 25.08 |
| `NW_30s_INC_Movements.html` | [열기](https://ycanns.github.io/Graphs/NW_30s_INC_Movements.html) | 24.84 |
| `NW_30s_Movements.html` | [열기](https://ycanns.github.io/Graphs/NW_30s_Movements.html) | 22.21 |
| `NW_30s_SPN_Movements.html` | [열기](https://ycanns.github.io/Graphs/NW_30s_SPN_Movements.html) | 25.15 |
| `NW_40s_CRD_Movements.html` | [열기](https://ycanns.github.io/Graphs/NW_40s_CRD_Movements.html) | 32.22 |
| `NW_40s_INC_Movements.html` | [열기](https://ycanns.github.io/Graphs/NW_40s_INC_Movements.html) | 31.43 |
| `NW_40s_Movements.html` | [열기](https://ycanns.github.io/Graphs/NW_40s_Movements.html) | 27.85 |
| `NW_40s_SPN_Movements.html` | [열기](https://ycanns.github.io/Graphs/NW_40s_SPN_Movements.html) | 31.62 |
| `NW_50s_CRD_Movements.html` | [열기](https://ycanns.github.io/Graphs/NW_50s_CRD_Movements.html) | 31.50 |
| `NW_50s_INC_Movements.html` | [열기](https://ycanns.github.io/Graphs/NW_50s_INC_Movements.html) | 30.88 |
| `NW_50s_Movements.html` | [열기](https://ycanns.github.io/Graphs/NW_50s_Movements.html) | 27.31 |
| `NW_50s_SPN_Movements.html` | [열기](https://ycanns.github.io/Graphs/NW_50s_SPN_Movements.html) | 31.04 |
| `NW_60s_CRD_Movements.html` | [열기](https://ycanns.github.io/Graphs/NW_60s_CRD_Movements.html) | 13.05 |
| `NW_60s_INC_Movements.html` | [열기](https://ycanns.github.io/Graphs/NW_60s_INC_Movements.html) | 13.13 |
| `NW_60s_Movements.html` | [열기](https://ycanns.github.io/Graphs/NW_60s_Movements.html) | 11.58 |
| `NW_60s_SPN_Movements.html` | [열기](https://ycanns.github.io/Graphs/NW_60s_SPN_Movements.html) | 13.11 |
| `NW_70s_CRD_Movements.html` | [열기](https://ycanns.github.io/Graphs/NW_70s_CRD_Movements.html) | 9.22 |
| `NW_70s_INC_Movements.html` | [열기](https://ycanns.github.io/Graphs/NW_70s_INC_Movements.html) | 9.54 |
| `NW_70s_Movements.html` | [열기](https://ycanns.github.io/Graphs/NW_70s_Movements.html) | 8.64 |
| `NW_70s_SPN_Movements.html` | [열기](https://ycanns.github.io/Graphs/NW_70s_SPN_Movements.html) | 9.60 |

</details>

<a id="region-busan"></a>

### 부산 연령별 이동

<details>
<summary><b>펼치기 — 24개 페이지</b></summary>

| 파일명 | 바로가기 | 용량 (MB) |
|---|---|---:|
| `BUSAN_20s_Movements.html` | [열기](https://ycanns.github.io/Graphs/BUSAN_20s_Movements.html) | 0.81 |
| `BUSAN_30s_Movements.html` | [열기](https://ycanns.github.io/Graphs/BUSAN_30s_Movements.html) | 1.06 |
| `BUSAN_40s_Movements.html` | [열기](https://ycanns.github.io/Graphs/BUSAN_40s_Movements.html) | 1.33 |
| `BUSAN_50s_Movements.html` | [열기](https://ycanns.github.io/Graphs/BUSAN_50s_Movements.html) | 1.44 |
| `BUSAN_60s_Movements.html` | [열기](https://ycanns.github.io/Graphs/BUSAN_60s_Movements.html) | 0.76 |
| `BUSAN_70s_Movements.html` | [열기](https://ycanns.github.io/Graphs/BUSAN_70s_Movements.html) | 0.66 |
| `BUSAN_CRD_20s_Movements.html` | [열기](https://ycanns.github.io/Graphs/BUSAN_CRD_20s_Movements.html) | 0.87 |
| `BUSAN_CRD_30s_Movements.html` | [열기](https://ycanns.github.io/Graphs/BUSAN_CRD_30s_Movements.html) | 1.22 |
| `BUSAN_CRD_40s_Movements.html` | [열기](https://ycanns.github.io/Graphs/BUSAN_CRD_40s_Movements.html) | 1.58 |
| `BUSAN_CRD_50s_Movements.html` | [열기](https://ycanns.github.io/Graphs/BUSAN_CRD_50s_Movements.html) | 1.69 |
| `BUSAN_CRD_60s_Movements.html` | [열기](https://ycanns.github.io/Graphs/BUSAN_CRD_60s_Movements.html) | 0.87 |
| `BUSAN_CRD_70s_Movements.html` | [열기](https://ycanns.github.io/Graphs/BUSAN_CRD_70s_Movements.html) | 0.72 |
| `BUSAN_INC_20s_Movements.html` | [열기](https://ycanns.github.io/Graphs/BUSAN_INC_20s_Movements.html) | 0.91 |
| `BUSAN_INC_30s_Movements.html` | [열기](https://ycanns.github.io/Graphs/BUSAN_INC_30s_Movements.html) | 1.24 |
| `BUSAN_INC_40s_Movements.html` | [열기](https://ycanns.github.io/Graphs/BUSAN_INC_40s_Movements.html) | 1.58 |
| `BUSAN_INC_50s_Movements.html` | [열기](https://ycanns.github.io/Graphs/BUSAN_INC_50s_Movements.html) | 1.70 |
| `BUSAN_INC_60s_Movements.html` | [열기](https://ycanns.github.io/Graphs/BUSAN_INC_60s_Movements.html) | 0.90 |
| `BUSAN_INC_70s_Movements.html` | [열기](https://ycanns.github.io/Graphs/BUSAN_INC_70s_Movements.html) | 0.76 |
| `BUSAN_SPN_20s_Movements.html` | [열기](https://ycanns.github.io/Graphs/BUSAN_SPN_20s_Movements.html) | 0.95 |
| `BUSAN_SPN_30s_Movements.html` | [열기](https://ycanns.github.io/Graphs/BUSAN_SPN_30s_Movements.html) | 1.25 |
| `BUSAN_SPN_40s_Movements.html` | [열기](https://ycanns.github.io/Graphs/BUSAN_SPN_40s_Movements.html) | 1.58 |
| `BUSAN_SPN_50s_Movements.html` | [열기](https://ycanns.github.io/Graphs/BUSAN_SPN_50s_Movements.html) | 1.71 |
| `BUSAN_SPN_60s_Movements.html` | [열기](https://ycanns.github.io/Graphs/BUSAN_SPN_60s_Movements.html) | 0.90 |
| `BUSAN_SPN_70s_Movements.html` | [열기](https://ycanns.github.io/Graphs/BUSAN_SPN_70s_Movements.html) | 0.76 |

</details>

<a id="region-daegu"></a>

### 대구 연령별 이동

<details>
<summary><b>펼치기 — 24개 페이지</b></summary>

| 파일명 | 바로가기 | 용량 (MB) |
|---|---|---:|
| `DAEGU_20s_Movements.html` | [열기](https://ycanns.github.io/Graphs/DAEGU_20s_Movements.html) | 0.56 |
| `DAEGU_30s_Movements.html` | [열기](https://ycanns.github.io/Graphs/DAEGU_30s_Movements.html) | 0.72 |
| `DAEGU_40s_Movements.html` | [열기](https://ycanns.github.io/Graphs/DAEGU_40s_Movements.html) | 1.01 |
| `DAEGU_50s_Movements.html` | [열기](https://ycanns.github.io/Graphs/DAEGU_50s_Movements.html) | 1.12 |
| `DAEGU_60s_Movements.html` | [열기](https://ycanns.github.io/Graphs/DAEGU_60s_Movements.html) | 0.51 |
| `DAEGU_70s_Movements.html` | [열기](https://ycanns.github.io/Graphs/DAEGU_70s_Movements.html) | 0.40 |
| `DAEGU_CRD_20s_Movements.html` | [열기](https://ycanns.github.io/Graphs/DAEGU_CRD_20s_Movements.html) | 0.60 |
| `DAEGU_CRD_30s_Movements.html` | [열기](https://ycanns.github.io/Graphs/DAEGU_CRD_30s_Movements.html) | 0.82 |
| `DAEGU_CRD_40s_Movements.html` | [열기](https://ycanns.github.io/Graphs/DAEGU_CRD_40s_Movements.html) | 1.19 |
| `DAEGU_CRD_50s_Movements.html` | [열기](https://ycanns.github.io/Graphs/DAEGU_CRD_50s_Movements.html) | 1.32 |
| `DAEGU_CRD_60s_Movements.html` | [열기](https://ycanns.github.io/Graphs/DAEGU_CRD_60s_Movements.html) | 0.58 |
| `DAEGU_CRD_70s_Movements.html` | [열기](https://ycanns.github.io/Graphs/DAEGU_CRD_70s_Movements.html) | 0.44 |
| `DAEGU_INC_20s_Movements.html` | [열기](https://ycanns.github.io/Graphs/DAEGU_INC_20s_Movements.html) | 0.62 |
| `DAEGU_INC_30s_Movements.html` | [열기](https://ycanns.github.io/Graphs/DAEGU_INC_30s_Movements.html) | 0.84 |
| `DAEGU_INC_40s_Movements.html` | [열기](https://ycanns.github.io/Graphs/DAEGU_INC_40s_Movements.html) | 1.19 |
| `DAEGU_INC_50s_Movements.html` | [열기](https://ycanns.github.io/Graphs/DAEGU_INC_50s_Movements.html) | 1.33 |
| `DAEGU_INC_60s_Movements.html` | [열기](https://ycanns.github.io/Graphs/DAEGU_INC_60s_Movements.html) | 0.60 |
| `DAEGU_INC_70s_Movements.html` | [열기](https://ycanns.github.io/Graphs/DAEGU_INC_70s_Movements.html) | 0.47 |
| `DAEGU_SPN_20s_Movements.html` | [열기](https://ycanns.github.io/Graphs/DAEGU_SPN_20s_Movements.html) | 0.65 |
| `DAEGU_SPN_30s_Movements.html` | [열기](https://ycanns.github.io/Graphs/DAEGU_SPN_30s_Movements.html) | 0.85 |
| `DAEGU_SPN_40s_Movements.html` | [열기](https://ycanns.github.io/Graphs/DAEGU_SPN_40s_Movements.html) | 1.20 |
| `DAEGU_SPN_50s_Movements.html` | [열기](https://ycanns.github.io/Graphs/DAEGU_SPN_50s_Movements.html) | 1.33 |
| `DAEGU_SPN_60s_Movements.html` | [열기](https://ycanns.github.io/Graphs/DAEGU_SPN_60s_Movements.html) | 0.60 |
| `DAEGU_SPN_70s_Movements.html` | [열기](https://ycanns.github.io/Graphs/DAEGU_SPN_70s_Movements.html) | 0.47 |

</details>

<a id="region-deajn"></a>

### 대전 연령별 이동

<details>
<summary><b>펼치기 — 24개 페이지</b></summary>

| 파일명 | 바로가기 | 용량 (MB) |
|---|---|---:|
| `DEAJN_20s_Movements.html` | [열기](https://ycanns.github.io/Graphs/DEAJN_20s_Movements.html) | 0.49 |
| `DEAJN_30s_Movements.html` | [열기](https://ycanns.github.io/Graphs/DEAJN_30s_Movements.html) | 0.70 |
| `DEAJN_40s_Movements.html` | [열기](https://ycanns.github.io/Graphs/DEAJN_40s_Movements.html) | 0.86 |
| `DEAJN_50s_Movements.html` | [열기](https://ycanns.github.io/Graphs/DEAJN_50s_Movements.html) | 0.73 |
| `DEAJN_60s_Movements.html` | [열기](https://ycanns.github.io/Graphs/DEAJN_60s_Movements.html) | 0.30 |
| `DEAJN_70s_Movements.html` | [열기](https://ycanns.github.io/Graphs/DEAJN_70s_Movements.html) | 0.24 |
| `DEAJN_CRD_20s_Movements.html` | [열기](https://ycanns.github.io/Graphs/DEAJN_CRD_20s_Movements.html) | 0.52 |
| `DEAJN_CRD_30s_Movements.html` | [열기](https://ycanns.github.io/Graphs/DEAJN_CRD_30s_Movements.html) | 0.82 |
| `DEAJN_CRD_40s_Movements.html` | [열기](https://ycanns.github.io/Graphs/DEAJN_CRD_40s_Movements.html) | 1.02 |
| `DEAJN_CRD_50s_Movements.html` | [열기](https://ycanns.github.io/Graphs/DEAJN_CRD_50s_Movements.html) | 0.86 |
| `DEAJN_CRD_60s_Movements.html` | [열기](https://ycanns.github.io/Graphs/DEAJN_CRD_60s_Movements.html) | 0.34 |
| `DEAJN_CRD_70s_Movements.html` | [열기](https://ycanns.github.io/Graphs/DEAJN_CRD_70s_Movements.html) | 0.26 |
| `DEAJN_INC_20s_Movements.html` | [열기](https://ycanns.github.io/Graphs/DEAJN_INC_20s_Movements.html) | 0.55 |
| `DEAJN_INC_30s_Movements.html` | [열기](https://ycanns.github.io/Graphs/DEAJN_INC_30s_Movements.html) | 0.82 |
| `DEAJN_INC_40s_Movements.html` | [열기](https://ycanns.github.io/Graphs/DEAJN_INC_40s_Movements.html) | 1.02 |
| `DEAJN_INC_50s_Movements.html` | [열기](https://ycanns.github.io/Graphs/DEAJN_INC_50s_Movements.html) | 0.87 |
| `DEAJN_INC_60s_Movements.html` | [열기](https://ycanns.github.io/Graphs/DEAJN_INC_60s_Movements.html) | 0.35 |
| `DEAJN_INC_70s_Movements.html` | [열기](https://ycanns.github.io/Graphs/DEAJN_INC_70s_Movements.html) | 0.28 |
| `DEAJN_SPN_20s_Movements.html` | [열기](https://ycanns.github.io/Graphs/DEAJN_SPN_20s_Movements.html) | 0.57 |
| `DEAJN_SPN_30s_Movements.html` | [열기](https://ycanns.github.io/Graphs/DEAJN_SPN_30s_Movements.html) | 0.83 |
| `DEAJN_SPN_40s_Movements.html` | [열기](https://ycanns.github.io/Graphs/DEAJN_SPN_40s_Movements.html) | 1.02 |
| `DEAJN_SPN_50s_Movements.html` | [열기](https://ycanns.github.io/Graphs/DEAJN_SPN_50s_Movements.html) | 0.87 |
| `DEAJN_SPN_60s_Movements.html` | [열기](https://ycanns.github.io/Graphs/DEAJN_SPN_60s_Movements.html) | 0.35 |
| `DEAJN_SPN_70s_Movements.html` | [열기](https://ycanns.github.io/Graphs/DEAJN_SPN_70s_Movements.html) | 0.28 |

</details>

<a id="region-gwnju"></a>

### 광주 연령별 이동

<details>
<summary><b>펼치기 — 24개 페이지</b></summary>

| 파일명 | 바로가기 | 용량 (MB) |
|---|---|---:|
| `GWNJU_20s_Movements.html` | [열기](https://ycanns.github.io/Graphs/GWNJU_20s_Movements.html) | 0.36 |
| `GWNJU_30s_Movements.html` | [열기](https://ycanns.github.io/Graphs/GWNJU_30s_Movements.html) | 0.50 |
| `GWNJU_40s_Movements.html` | [열기](https://ycanns.github.io/Graphs/GWNJU_40s_Movements.html) | 0.72 |
| `GWNJU_50s_Movements.html` | [열기](https://ycanns.github.io/Graphs/GWNJU_50s_Movements.html) | 0.67 |
| `GWNJU_60s_Movements.html` | [열기](https://ycanns.github.io/Graphs/GWNJU_60s_Movements.html) | 0.25 |
| `GWNJU_70s_Movements.html` | [열기](https://ycanns.github.io/Graphs/GWNJU_70s_Movements.html) | 0.22 |
| `GWNJU_CRD_20s_Movements.html` | [열기](https://ycanns.github.io/Graphs/GWNJU_CRD_20s_Movements.html) | 0.39 |
| `GWNJU_CRD_30s_Movements.html` | [열기](https://ycanns.github.io/Graphs/GWNJU_CRD_30s_Movements.html) | 0.58 |
| `GWNJU_CRD_40s_Movements.html` | [열기](https://ycanns.github.io/Graphs/GWNJU_CRD_40s_Movements.html) | 0.85 |
| `GWNJU_CRD_50s_Movements.html` | [열기](https://ycanns.github.io/Graphs/GWNJU_CRD_50s_Movements.html) | 0.80 |
| `GWNJU_CRD_60s_Movements.html` | [열기](https://ycanns.github.io/Graphs/GWNJU_CRD_60s_Movements.html) | 0.29 |
| `GWNJU_CRD_70s_Movements.html` | [열기](https://ycanns.github.io/Graphs/GWNJU_CRD_70s_Movements.html) | 0.24 |
| `GWNJU_INC_20s_Movements.html` | [열기](https://ycanns.github.io/Graphs/GWNJU_INC_20s_Movements.html) | 0.40 |
| `GWNJU_INC_30s_Movements.html` | [열기](https://ycanns.github.io/Graphs/GWNJU_INC_30s_Movements.html) | 0.59 |
| `GWNJU_INC_40s_Movements.html` | [열기](https://ycanns.github.io/Graphs/GWNJU_INC_40s_Movements.html) | 0.85 |
| `GWNJU_INC_50s_Movements.html` | [열기](https://ycanns.github.io/Graphs/GWNJU_INC_50s_Movements.html) | 0.79 |
| `GWNJU_INC_60s_Movements.html` | [열기](https://ycanns.github.io/Graphs/GWNJU_INC_60s_Movements.html) | 0.30 |
| `GWNJU_INC_70s_Movements.html` | [열기](https://ycanns.github.io/Graphs/GWNJU_INC_70s_Movements.html) | 0.25 |
| `GWNJU_SPN_20s_Movements.html` | [열기](https://ycanns.github.io/Graphs/GWNJU_SPN_20s_Movements.html) | 0.42 |
| `GWNJU_SPN_30s_Movements.html` | [열기](https://ycanns.github.io/Graphs/GWNJU_SPN_30s_Movements.html) | 0.59 |
| `GWNJU_SPN_40s_Movements.html` | [열기](https://ycanns.github.io/Graphs/GWNJU_SPN_40s_Movements.html) | 0.85 |
| `GWNJU_SPN_50s_Movements.html` | [열기](https://ycanns.github.io/Graphs/GWNJU_SPN_50s_Movements.html) | 0.80 |
| `GWNJU_SPN_60s_Movements.html` | [열기](https://ycanns.github.io/Graphs/GWNJU_SPN_60s_Movements.html) | 0.30 |
| `GWNJU_SPN_70s_Movements.html` | [열기](https://ycanns.github.io/Graphs/GWNJU_SPN_70s_Movements.html) | 0.25 |

</details>

<a id="region-gyngi"></a>

### 경기 연령별 이동

<details>
<summary><b>펼치기 — 24개 페이지</b></summary>

| 파일명 | 바로가기 | 용량 (MB) |
|---|---|---:|
| `GYNGI_20s_Movements.html` | [열기](https://ycanns.github.io/Graphs/GYNGI_20s_Movements.html) | 3.07 |
| `GYNGI_30s_Movements.html` | [열기](https://ycanns.github.io/Graphs/GYNGI_30s_Movements.html) | 5.38 |
| `GYNGI_40s_Movements.html` | [열기](https://ycanns.github.io/Graphs/GYNGI_40s_Movements.html) | 6.65 |
| `GYNGI_50s_Movements.html` | [열기](https://ycanns.github.io/Graphs/GYNGI_50s_Movements.html) | 6.31 |
| `GYNGI_60s_Movements.html` | [열기](https://ycanns.github.io/Graphs/GYNGI_60s_Movements.html) | 2.41 |
| `GYNGI_70s_Movements.html` | [열기](https://ycanns.github.io/Graphs/GYNGI_70s_Movements.html) | 1.54 |
| `GYNGI_CRD_20s_Movements.html` | [열기](https://ycanns.github.io/Graphs/GYNGI_CRD_20s_Movements.html) | 3.37 |
| `GYNGI_CRD_30s_Movements.html` | [열기](https://ycanns.github.io/Graphs/GYNGI_CRD_30s_Movements.html) | 6.32 |
| `GYNGI_CRD_40s_Movements.html` | [열기](https://ycanns.github.io/Graphs/GYNGI_CRD_40s_Movements.html) | 7.96 |
| `GYNGI_CRD_50s_Movements.html` | [열기](https://ycanns.github.io/Graphs/GYNGI_CRD_50s_Movements.html) | 7.53 |
| `GYNGI_CRD_60s_Movements.html` | [열기](https://ycanns.github.io/Graphs/GYNGI_CRD_60s_Movements.html) | 2.82 |
| `GYNGI_CRD_70s_Movements.html` | [열기](https://ycanns.github.io/Graphs/GYNGI_CRD_70s_Movements.html) | 1.72 |
| `GYNGI_INC_20s_Movements.html` | [열기](https://ycanns.github.io/Graphs/GYNGI_INC_20s_Movements.html) | 3.46 |
| `GYNGI_INC_30s_Movements.html` | [열기](https://ycanns.github.io/Graphs/GYNGI_INC_30s_Movements.html) | 6.33 |
| `GYNGI_INC_40s_Movements.html` | [열기](https://ycanns.github.io/Graphs/GYNGI_INC_40s_Movements.html) | 7.89 |
| `GYNGI_INC_50s_Movements.html` | [열기](https://ycanns.github.io/Graphs/GYNGI_INC_50s_Movements.html) | 7.51 |
| `GYNGI_INC_60s_Movements.html` | [열기](https://ycanns.github.io/Graphs/GYNGI_INC_60s_Movements.html) | 2.87 |
| `GYNGI_INC_70s_Movements.html` | [열기](https://ycanns.github.io/Graphs/GYNGI_INC_70s_Movements.html) | 1.79 |
| `GYNGI_SPN_20s_Movements.html` | [열기](https://ycanns.github.io/Graphs/GYNGI_SPN_20s_Movements.html) | 3.64 |
| `GYNGI_SPN_30s_Movements.html` | [열기](https://ycanns.github.io/Graphs/GYNGI_SPN_30s_Movements.html) | 6.42 |
| `GYNGI_SPN_40s_Movements.html` | [열기](https://ycanns.github.io/Graphs/GYNGI_SPN_40s_Movements.html) | 7.95 |
| `GYNGI_SPN_50s_Movements.html` | [열기](https://ycanns.github.io/Graphs/GYNGI_SPN_50s_Movements.html) | 7.55 |
| `GYNGI_SPN_60s_Movements.html` | [열기](https://ycanns.github.io/Graphs/GYNGI_SPN_60s_Movements.html) | 2.88 |
| `GYNGI_SPN_70s_Movements.html` | [열기](https://ycanns.github.io/Graphs/GYNGI_SPN_70s_Movements.html) | 1.82 |

</details>

<a id="region-inchn"></a>

### 인천 연령별 이동

<details>
<summary><b>펼치기 — 24개 페이지</b></summary>

| 파일명 | 바로가기 | 용량 (MB) |
|---|---|---:|
| `INCHN_20s_Movements.html` | [열기](https://ycanns.github.io/Graphs/INCHN_20s_Movements.html) | 0.56 |
| `INCHN_30s_Movements.html` | [열기](https://ycanns.github.io/Graphs/INCHN_30s_Movements.html) | 0.94 |
| `INCHN_40s_Movements.html` | [열기](https://ycanns.github.io/Graphs/INCHN_40s_Movements.html) | 1.22 |
| `INCHN_50s_Movements.html` | [열기](https://ycanns.github.io/Graphs/INCHN_50s_Movements.html) | 1.31 |
| `INCHN_60s_Movements.html` | [열기](https://ycanns.github.io/Graphs/INCHN_60s_Movements.html) | 0.55 |
| `INCHN_70s_Movements.html` | [열기](https://ycanns.github.io/Graphs/INCHN_70s_Movements.html) | 0.34 |
| `INCHN_CRD_20s_Movements.html` | [열기](https://ycanns.github.io/Graphs/INCHN_CRD_20s_Movements.html) | 0.61 |
| `INCHN_CRD_30s_Movements.html` | [열기](https://ycanns.github.io/Graphs/INCHN_CRD_30s_Movements.html) | 1.10 |
| `INCHN_CRD_40s_Movements.html` | [열기](https://ycanns.github.io/Graphs/INCHN_CRD_40s_Movements.html) | 1.45 |
| `INCHN_CRD_50s_Movements.html` | [열기](https://ycanns.github.io/Graphs/INCHN_CRD_50s_Movements.html) | 1.55 |
| `INCHN_CRD_60s_Movements.html` | [열기](https://ycanns.github.io/Graphs/INCHN_CRD_60s_Movements.html) | 0.64 |
| `INCHN_CRD_70s_Movements.html` | [열기](https://ycanns.github.io/Graphs/INCHN_CRD_70s_Movements.html) | 0.38 |
| `INCHN_INC_20s_Movements.html` | [열기](https://ycanns.github.io/Graphs/INCHN_INC_20s_Movements.html) | 0.63 |
| `INCHN_INC_30s_Movements.html` | [열기](https://ycanns.github.io/Graphs/INCHN_INC_30s_Movements.html) | 1.10 |
| `INCHN_INC_40s_Movements.html` | [열기](https://ycanns.github.io/Graphs/INCHN_INC_40s_Movements.html) | 1.44 |
| `INCHN_INC_50s_Movements.html` | [열기](https://ycanns.github.io/Graphs/INCHN_INC_50s_Movements.html) | 1.55 |
| `INCHN_INC_60s_Movements.html` | [열기](https://ycanns.github.io/Graphs/INCHN_INC_60s_Movements.html) | 0.65 |
| `INCHN_INC_70s_Movements.html` | [열기](https://ycanns.github.io/Graphs/INCHN_INC_70s_Movements.html) | 0.39 |
| `INCHN_SPN_20s_Movements.html` | [열기](https://ycanns.github.io/Graphs/INCHN_SPN_20s_Movements.html) | 0.66 |
| `INCHN_SPN_30s_Movements.html` | [열기](https://ycanns.github.io/Graphs/INCHN_SPN_30s_Movements.html) | 1.12 |
| `INCHN_SPN_40s_Movements.html` | [열기](https://ycanns.github.io/Graphs/INCHN_SPN_40s_Movements.html) | 1.45 |
| `INCHN_SPN_50s_Movements.html` | [열기](https://ycanns.github.io/Graphs/INCHN_SPN_50s_Movements.html) | 1.56 |
| `INCHN_SPN_60s_Movements.html` | [열기](https://ycanns.github.io/Graphs/INCHN_SPN_60s_Movements.html) | 0.66 |
| `INCHN_SPN_70s_Movements.html` | [열기](https://ycanns.github.io/Graphs/INCHN_SPN_70s_Movements.html) | 0.40 |

</details>

<a id="region-sejng"></a>

### 세종 연령별 이동

<details>
<summary><b>펼치기 — 24개 페이지</b></summary>

| 파일명 | 바로가기 | 용량 (MB) |
|---|---|---:|
| `SEJNG_20s_Movements.html` | [열기](https://ycanns.github.io/Graphs/SEJNG_20s_Movements.html) | 0.11 |
| `SEJNG_30s_Movements.html` | [열기](https://ycanns.github.io/Graphs/SEJNG_30s_Movements.html) | 0.23 |
| `SEJNG_40s_Movements.html` | [열기](https://ycanns.github.io/Graphs/SEJNG_40s_Movements.html) | 0.26 |
| `SEJNG_50s_Movements.html` | [열기](https://ycanns.github.io/Graphs/SEJNG_50s_Movements.html) | 0.17 |
| `SEJNG_60s_Movements.html` | [열기](https://ycanns.github.io/Graphs/SEJNG_60s_Movements.html) | 0.05 |
| `SEJNG_70s_Movements.html` | [열기](https://ycanns.github.io/Graphs/SEJNG_70s_Movements.html) | 0.03 |
| `SEJNG_CRD_20s_Movements.html` | [열기](https://ycanns.github.io/Graphs/SEJNG_CRD_20s_Movements.html) | 0.13 |
| `SEJNG_CRD_30s_Movements.html` | [열기](https://ycanns.github.io/Graphs/SEJNG_CRD_30s_Movements.html) | 0.27 |
| `SEJNG_CRD_40s_Movements.html` | [열기](https://ycanns.github.io/Graphs/SEJNG_CRD_40s_Movements.html) | 0.31 |
| `SEJNG_CRD_50s_Movements.html` | [열기](https://ycanns.github.io/Graphs/SEJNG_CRD_50s_Movements.html) | 0.20 |
| `SEJNG_CRD_60s_Movements.html` | [열기](https://ycanns.github.io/Graphs/SEJNG_CRD_60s_Movements.html) | 0.06 |
| `SEJNG_CRD_70s_Movements.html` | [열기](https://ycanns.github.io/Graphs/SEJNG_CRD_70s_Movements.html) | 0.04 |
| `SEJNG_INC_20s_Movements.html` | [열기](https://ycanns.github.io/Graphs/SEJNG_INC_20s_Movements.html) | 0.13 |
| `SEJNG_INC_30s_Movements.html` | [열기](https://ycanns.github.io/Graphs/SEJNG_INC_30s_Movements.html) | 0.26 |
| `SEJNG_INC_40s_Movements.html` | [열기](https://ycanns.github.io/Graphs/SEJNG_INC_40s_Movements.html) | 0.30 |
| `SEJNG_INC_50s_Movements.html` | [열기](https://ycanns.github.io/Graphs/SEJNG_INC_50s_Movements.html) | 0.20 |
| `SEJNG_INC_60s_Movements.html` | [열기](https://ycanns.github.io/Graphs/SEJNG_INC_60s_Movements.html) | 0.06 |
| `SEJNG_INC_70s_Movements.html` | [열기](https://ycanns.github.io/Graphs/SEJNG_INC_70s_Movements.html) | 0.04 |
| `SEJNG_SPN_20s_Movements.html` | [열기](https://ycanns.github.io/Graphs/SEJNG_SPN_20s_Movements.html) | 0.13 |
| `SEJNG_SPN_30s_Movements.html` | [열기](https://ycanns.github.io/Graphs/SEJNG_SPN_30s_Movements.html) | 0.27 |
| `SEJNG_SPN_40s_Movements.html` | [열기](https://ycanns.github.io/Graphs/SEJNG_SPN_40s_Movements.html) | 0.30 |
| `SEJNG_SPN_50s_Movements.html` | [열기](https://ycanns.github.io/Graphs/SEJNG_SPN_50s_Movements.html) | 0.20 |
| `SEJNG_SPN_60s_Movements.html` | [열기](https://ycanns.github.io/Graphs/SEJNG_SPN_60s_Movements.html) | 0.06 |
| `SEJNG_SPN_70s_Movements.html` | [열기](https://ycanns.github.io/Graphs/SEJNG_SPN_70s_Movements.html) | 0.04 |

</details>

<a id="region-seoul"></a>

### 서울 연령별 이동

<details>
<summary><b>펼치기 — 24개 페이지</b></summary>

| 파일명 | 바로가기 | 용량 (MB) |
|---|---|---:|
| `SEOUL_20s_Movements.html` | [열기](https://ycanns.github.io/Graphs/SEOUL_20s_Movements.html) | 2.49 |
| `SEOUL_30s_Movements.html` | [열기](https://ycanns.github.io/Graphs/SEOUL_30s_Movements.html) | 3.64 |
| `SEOUL_40s_Movements.html` | [열기](https://ycanns.github.io/Graphs/SEOUL_40s_Movements.html) | 3.60 |
| `SEOUL_50s_Movements.html` | [열기](https://ycanns.github.io/Graphs/SEOUL_50s_Movements.html) | 3.03 |
| `SEOUL_60s_Movements.html` | [열기](https://ycanns.github.io/Graphs/SEOUL_60s_Movements.html) | 1.59 |
| `SEOUL_70s_Movements.html` | [열기](https://ycanns.github.io/Graphs/SEOUL_70s_Movements.html) | 1.63 |
| `SEOUL_CRD_20s_Movements.html` | [열기](https://ycanns.github.io/Graphs/SEOUL_CRD_20s_Movements.html) | 2.65 |
| `SEOUL_CRD_30s_Movements.html` | [열기](https://ycanns.github.io/Graphs/SEOUL_CRD_30s_Movements.html) | 4.22 |
| `SEOUL_CRD_40s_Movements.html` | [열기](https://ycanns.github.io/Graphs/SEOUL_CRD_40s_Movements.html) | 4.24 |
| `SEOUL_CRD_50s_Movements.html` | [열기](https://ycanns.github.io/Graphs/SEOUL_CRD_50s_Movements.html) | 3.55 |
| `SEOUL_CRD_60s_Movements.html` | [열기](https://ycanns.github.io/Graphs/SEOUL_CRD_60s_Movements.html) | 1.82 |
| `SEOUL_CRD_70s_Movements.html` | [열기](https://ycanns.github.io/Graphs/SEOUL_CRD_70s_Movements.html) | 1.79 |
| `SEOUL_INC_20s_Movements.html` | [열기](https://ycanns.github.io/Graphs/SEOUL_INC_20s_Movements.html) | 2.78 |
| `SEOUL_INC_30s_Movements.html` | [열기](https://ycanns.github.io/Graphs/SEOUL_INC_30s_Movements.html) | 4.27 |
| `SEOUL_INC_40s_Movements.html` | [열기](https://ycanns.github.io/Graphs/SEOUL_INC_40s_Movements.html) | 4.25 |
| `SEOUL_INC_50s_Movements.html` | [열기](https://ycanns.github.io/Graphs/SEOUL_INC_50s_Movements.html) | 3.58 |
| `SEOUL_INC_60s_Movements.html` | [열기](https://ycanns.github.io/Graphs/SEOUL_INC_60s_Movements.html) | 1.88 |
| `SEOUL_INC_70s_Movements.html` | [열기](https://ycanns.github.io/Graphs/SEOUL_INC_70s_Movements.html) | 1.89 |
| `SEOUL_SPN_20s_Movements.html` | [열기](https://ycanns.github.io/Graphs/SEOUL_SPN_20s_Movements.html) | 2.92 |
| `SEOUL_SPN_30s_Movements.html` | [열기](https://ycanns.github.io/Graphs/SEOUL_SPN_30s_Movements.html) | 4.32 |
| `SEOUL_SPN_40s_Movements.html` | [열기](https://ycanns.github.io/Graphs/SEOUL_SPN_40s_Movements.html) | 4.28 |
| `SEOUL_SPN_50s_Movements.html` | [열기](https://ycanns.github.io/Graphs/SEOUL_SPN_50s_Movements.html) | 3.60 |
| `SEOUL_SPN_60s_Movements.html` | [열기](https://ycanns.github.io/Graphs/SEOUL_SPN_60s_Movements.html) | 1.88 |
| `SEOUL_SPN_70s_Movements.html` | [열기](https://ycanns.github.io/Graphs/SEOUL_SPN_70s_Movements.html) | 1.91 |

</details>

<a id="region-ulsan"></a>

### 울산 연령별 이동

<details>
<summary><b>펼치기 — 24개 페이지</b></summary>

| 파일명 | 바로가기 | 용량 (MB) |
|---|---|---:|
| `ULSAN_20s_Movements.html` | [열기](https://ycanns.github.io/Graphs/ULSAN_20s_Movements.html) | 0.37 |
| `ULSAN_30s_Movements.html` | [열기](https://ycanns.github.io/Graphs/ULSAN_30s_Movements.html) | 0.68 |
| `ULSAN_40s_Movements.html` | [열기](https://ycanns.github.io/Graphs/ULSAN_40s_Movements.html) | 0.87 |
| `ULSAN_50s_Movements.html` | [열기](https://ycanns.github.io/Graphs/ULSAN_50s_Movements.html) | 0.96 |
| `ULSAN_60s_Movements.html` | [열기](https://ycanns.github.io/Graphs/ULSAN_60s_Movements.html) | 0.42 |
| `ULSAN_70s_Movements.html` | [열기](https://ycanns.github.io/Graphs/ULSAN_70s_Movements.html) | 0.19 |
| `ULSAN_CRD_20s_Movements.html` | [열기](https://ycanns.github.io/Graphs/ULSAN_CRD_20s_Movements.html) | 0.40 |
| `ULSAN_CRD_30s_Movements.html` | [열기](https://ycanns.github.io/Graphs/ULSAN_CRD_30s_Movements.html) | 0.79 |
| `ULSAN_CRD_40s_Movements.html` | [열기](https://ycanns.github.io/Graphs/ULSAN_CRD_40s_Movements.html) | 1.04 |
| `ULSAN_CRD_50s_Movements.html` | [열기](https://ycanns.github.io/Graphs/ULSAN_CRD_50s_Movements.html) | 1.14 |
| `ULSAN_CRD_60s_Movements.html` | [열기](https://ycanns.github.io/Graphs/ULSAN_CRD_60s_Movements.html) | 0.49 |
| `ULSAN_CRD_70s_Movements.html` | [열기](https://ycanns.github.io/Graphs/ULSAN_CRD_70s_Movements.html) | 0.21 |
| `ULSAN_INC_20s_Movements.html` | [열기](https://ycanns.github.io/Graphs/ULSAN_INC_20s_Movements.html) | 0.42 |
| `ULSAN_INC_30s_Movements.html` | [열기](https://ycanns.github.io/Graphs/ULSAN_INC_30s_Movements.html) | 0.80 |
| `ULSAN_INC_40s_Movements.html` | [열기](https://ycanns.github.io/Graphs/ULSAN_INC_40s_Movements.html) | 1.03 |
| `ULSAN_INC_50s_Movements.html` | [열기](https://ycanns.github.io/Graphs/ULSAN_INC_50s_Movements.html) | 1.14 |
| `ULSAN_INC_60s_Movements.html` | [열기](https://ycanns.github.io/Graphs/ULSAN_INC_60s_Movements.html) | 0.50 |
| `ULSAN_INC_70s_Movements.html` | [열기](https://ycanns.github.io/Graphs/ULSAN_INC_70s_Movements.html) | 0.22 |
| `ULSAN_SPN_20s_Movements.html` | [열기](https://ycanns.github.io/Graphs/ULSAN_SPN_20s_Movements.html) | 0.43 |
| `ULSAN_SPN_30s_Movements.html` | [열기](https://ycanns.github.io/Graphs/ULSAN_SPN_30s_Movements.html) | 0.80 |
| `ULSAN_SPN_40s_Movements.html` | [열기](https://ycanns.github.io/Graphs/ULSAN_SPN_40s_Movements.html) | 1.03 |
| `ULSAN_SPN_50s_Movements.html` | [열기](https://ycanns.github.io/Graphs/ULSAN_SPN_50s_Movements.html) | 1.14 |
| `ULSAN_SPN_60s_Movements.html` | [열기](https://ycanns.github.io/Graphs/ULSAN_SPN_60s_Movements.html) | 0.50 |
| `ULSAN_SPN_70s_Movements.html` | [열기](https://ycanns.github.io/Graphs/ULSAN_SPN_70s_Movements.html) | 0.22 |

</details>

<a id="regional"></a>

### 권역별 이동과 통행

<details>
<summary><b>펼치기 — 41개 페이지</b></summary>

| 파일명 | 바로가기 | 용량 (MB) |
|---|---|---:|
| `BS_DG_KS_HM.html` | [열기](https://ycanns.github.io/Graphs/BS_DG_KS_HM.html) | 49.92 |
| `BS_DG_KS_HM_by_Age.html` | [열기](https://ycanns.github.io/Graphs/BS_DG_KS_HM_by_Age.html) | 85.03 |
| `BS_DG_KS_WK.html` | [열기](https://ycanns.github.io/Graphs/BS_DG_KS_WK.html) | 49.55 |
| `BS_DG_KS_WK_by_Age.html` | [열기](https://ycanns.github.io/Graphs/BS_DG_KS_WK_by_Age.html) | 88.23 |
| `Bus_Tel_2018_2021.html` | [열기](https://ycanns.github.io/Graphs/Bus_Tel_2018_2021.html) | 4.88 |
| `CC_SJ_DJ_HM.html` | [열기](https://ycanns.github.io/Graphs/CC_SJ_DJ_HM.html) | 25.92 |
| `CC_SJ_DJ_HM_by_Age.html` | [열기](https://ycanns.github.io/Graphs/CC_SJ_DJ_HM_by_Age.html) | 42.90 |
| `CC_SJ_DJ_WK.html` | [열기](https://ycanns.github.io/Graphs/CC_SJ_DJ_WK.html) | 25.65 |
| `CC_SJ_DJ_WK_by_Age.html` | [열기](https://ycanns.github.io/Graphs/CC_SJ_DJ_WK_by_Age.html) | 45.02 |
| `GJ_CN_JJ_HM.html` | [열기](https://ycanns.github.io/Graphs/GJ_CN_JJ_HM.html) | 53.03 |
| `GJ_CN_JJ_HM_by_Age.html` | [열기](https://ycanns.github.io/Graphs/GJ_CN_JJ_HM_by_Age.html) | 71.50 |
| `GJ_CN_JJ_WK.html` | [열기](https://ycanns.github.io/Graphs/GJ_CN_JJ_WK.html) | 53.02 |
| `GJ_CN_JJ_WK_by_Age.html` | [열기](https://ycanns.github.io/Graphs/GJ_CN_JJ_WK_by_Age.html) | 72.92 |
| `GW_HM.html` | [열기](https://ycanns.github.io/Graphs/GW_HM.html) | 11.88 |
| `GW_HM_by_Age.html` | [열기](https://ycanns.github.io/Graphs/GW_HM_by_Age.html) | 18.02 |
| `GW_WK.html` | [열기](https://ycanns.github.io/Graphs/GW_WK.html) | 11.93 |
| `GW_WK_by_Age.html` | [열기](https://ycanns.github.io/Graphs/GW_WK_by_Age.html) | 18.47 |
| `SL_KK_INC_HM.html` | [열기](https://ycanns.github.io/Graphs/SL_KK_INC_HM.html) | 39.56 |
| `SL_KK_INC_HM_by_Age.html` | [열기](https://ycanns.github.io/Graphs/SL_KK_INC_HM_by_Age.html) | 89.78 |
| `SL_KK_INC_WK.html` | [열기](https://ycanns.github.io/Graphs/SL_KK_INC_WK.html) | 38.54 |
| `SL_KK_INC_WK_by_Age.html` | [열기](https://ycanns.github.io/Graphs/SL_KK_INC_WK_by_Age.html) | 92.36 |
| `Tel_Proportaion_by_year.html` | [열기](https://ycanns.github.io/Graphs/Tel_Proportaion_by_year.html) | 4.88 |
| `Tel_STAT_All_Busan.html` | [열기](https://ycanns.github.io/Graphs/Tel_STAT_All_Busan.html) | 12.05 |
| `Tel_STAT_All_ChnRa.html` | [열기](https://ycanns.github.io/Graphs/Tel_STAT_All_ChnRa.html) | 16.77 |
| `Tel_STAT_All_ChngChng.html` | [열기](https://ycanns.github.io/Graphs/Tel_STAT_All_ChngChng.html) | 6.49 |
| `Tel_STAT_All_GWD.html` | [열기](https://ycanns.github.io/Graphs/Tel_STAT_All_GWD.html) | 4.01 |
| `Tel_STAT_All_Seoul.html` | [열기](https://ycanns.github.io/Graphs/Tel_STAT_All_Seoul.html) | 9.64 |
| `Trips_by_purpose_Busan.html` | [열기](https://ycanns.github.io/Graphs/Trips_by_purpose_Busan.html) | 23.74 |
| `Trips_by_purpose_ChoongChung.html` | [열기](https://ycanns.github.io/Graphs/Trips_by_purpose_ChoongChung.html) | 12.49 |
| `Trips_by_purpose_ChunNam.html` | [열기](https://ycanns.github.io/Graphs/Trips_by_purpose_ChunNam.html) | 31.05 |
| `Trips_by_purpose_GanWon.html` | [열기](https://ycanns.github.io/Graphs/Trips_by_purpose_GanWon.html) | 6.65 |
| `Trips_by_purpose_Seoul.html` | [열기](https://ycanns.github.io/Graphs/Trips_by_purpose_Seoul.html) | 18.69 |
| `m_POP_BUSAN_Movement.html` | [열기](https://ycanns.github.io/Graphs/m_POP_BUSAN_Movement.html) | 6.69 |
| `m_POP_DAEGU_Movement.html` | [열기](https://ycanns.github.io/Graphs/m_POP_DAEGU_Movement.html) | 4.73 |
| `m_POP_DAEJN_Movement.html` | [열기](https://ycanns.github.io/Graphs/m_POP_DAEJN_Movement.html) | 3.57 |
| `m_POP_GWNJU_Movement.html` | [열기](https://ycanns.github.io/Graphs/m_POP_GWNJU_Movement.html) | 2.92 |
| `m_POP_GYNGI_Movement.html` | [열기](https://ycanns.github.io/Graphs/m_POP_GYNGI_Movement.html) | 27.58 |
| `m_POP_INCHN_Movement.html` | [열기](https://ycanns.github.io/Graphs/m_POP_INCHN_Movement.html) | 5.40 |
| `m_POP_SEJNG_Movement.html` | [열기](https://ycanns.github.io/Graphs/m_POP_SEJNG_Movement.html) | 0.90 |
| `m_POP_SEOUL_Movement.html` | [열기](https://ycanns.github.io/Graphs/m_POP_SEOUL_Movement.html) | 17.57 |
| `m_POP_ULSAN_Movement.html` | [열기](https://ycanns.github.io/Graphs/m_POP_ULSAN_Movement.html) | 3.79 |

</details>

<a id="economy"></a>

### 소득과 소비 및 금융

<details>
<summary><b>펼치기 — 19개 페이지</b></summary>

| 파일명 | 바로가기 | 용량 (MB) |
|---|---|---:|
| `KCB_3D_AGE.html` | [열기](https://ycanns.github.io/Graphs/KCB_3D_AGE.html) | 14.04 |
| `KCB_3D_JOB.html` | [열기](https://ycanns.github.io/Graphs/KCB_3D_JOB.html) | 13.64 |
| `KCB_3D_POP.html` | [열기](https://ycanns.github.io/Graphs/KCB_3D_POP.html) | 13.90 |
| `KCB_3D_Sido.html` | [열기](https://ycanns.github.io/Graphs/KCB_3D_Sido.html) | 13.59 |
| `KCB_3D_SidoGroup.html` | [열기](https://ycanns.github.io/Graphs/KCB_3D_SidoGroup.html) | 13.59 |
| `KCB_INCOME.html` | [열기](https://ycanns.github.io/Graphs/KCB_INCOME.html) | 5.08 |
| `KCB_INCOME_by_AGE.html` | [열기](https://ycanns.github.io/Graphs/KCB_INCOME_by_AGE.html) | 5.06 |
| `KCB_INCOME_by_Quantile.html` | [열기](https://ycanns.github.io/Graphs/KCB_INCOME_by_Quantile.html) | 5.07 |
| `KCB_NationWide_Trends.html` | [열기](https://ycanns.github.io/Graphs/KCB_NationWide_Trends.html) | 5.05 |
| `KCB_SPENDING.html` | [열기](https://ycanns.github.io/Graphs/KCB_SPENDING.html) | 5.08 |
| `KCB_SPENDING_by_AGE.html` | [열기](https://ycanns.github.io/Graphs/KCB_SPENDING_by_AGE.html) | 5.06 |
| `KCB_SPENDING_by_Quantile.html` | [열기](https://ycanns.github.io/Graphs/KCB_SPENDING_by_Quantile.html) | 5.07 |
| `KCB_TOTAL_DEBTS.html` | [열기](https://ycanns.github.io/Graphs/KCB_TOTAL_DEBTS.html) | 5.08 |
| `KCB_TOTAL_DEBTS_by_AGE.html` | [열기](https://ycanns.github.io/Graphs/KCB_TOTAL_DEBTS_by_AGE.html) | 5.06 |
| `KCB_TOTAL_DEBTS_by_Quantile.html` | [열기](https://ycanns.github.io/Graphs/KCB_TOTAL_DEBTS_by_Quantile.html) | 5.07 |
| `MON_INC_Map_202212.html` | [열기](https://ycanns.github.io/Graphs/MON_INC_Map_202212.html) | 54.59 |
| `MON_SPN_CARDAMT_Map_202212.html` | [열기](https://ycanns.github.io/Graphs/MON_SPN_CARDAMT_Map_202212.html) | 54.48 |
| `TOT_LNAMT_Map_202212.html` | [열기](https://ycanns.github.io/Graphs/TOT_LNAMT_Map_202212.html) | 52.73 |
| `TOT_LN_DLQAMT_202212.html` | [열기](https://ycanns.github.io/Graphs/TOT_LN_DLQAMT_202212.html) | 46.86 |

</details>

<a id="business"></a>

### 사업체와 상권

<details>
<summary><b>펼치기 — 37개 페이지</b></summary>

| 파일명 | 바로가기 | 용량 (MB) |
|---|---|---:|
| `Ave_Survival_Duration.html` | [열기](https://ycanns.github.io/Graphs/Ave_Survival_Duration.html) | 88.42 |
| `Ave_Survival_Duration_EDCTN.html` | [열기](https://ycanns.github.io/Graphs/Ave_Survival_Duration_EDCTN.html) | 79.47 |
| `Ave_Survival_Duration_LDGNG.html` | [열기](https://ycanns.github.io/Graphs/Ave_Survival_Duration_LDGNG.html) | 79.98 |
| `Ave_Survival_Duration_LSR.html` | [열기](https://ycanns.github.io/Graphs/Ave_Survival_Duration_LSR.html) | 79.03 |
| `Ave_Survival_Duration_RLST.html` | [열기](https://ycanns.github.io/Graphs/Ave_Survival_Duration_RLST.html) | 79.73 |
| `Ave_Survival_Duration_RSTRNT.html` | [열기](https://ycanns.github.io/Graphs/Ave_Survival_Duration_RSTRNT.html) | 83.65 |
| `Ave_Survival_Duration_RTL.html` | [열기](https://ycanns.github.io/Graphs/Ave_Survival_Duration_RTL.html) | 85.15 |
| `Ave_Survival_Duration_SPRT.html` | [열기](https://ycanns.github.io/Graphs/Ave_Survival_Duration_SPRT.html) | 78.80 |
| `Ave_Survival_Duration_SRVC.html` | [열기](https://ycanns.github.io/Graphs/Ave_Survival_Duration_SRVC.html) | 81.90 |
| `Business_A.html` | [열기](https://ycanns.github.io/Graphs/Business_A.html) | 0.38 |
| `Business_ALL.html` | [열기](https://ycanns.github.io/Graphs/Business_ALL.html) | 0.39 |
| `Business_B.html` | [열기](https://ycanns.github.io/Graphs/Business_B.html) | 0.38 |
| `Business_C.html` | [열기](https://ycanns.github.io/Graphs/Business_C.html) | 0.39 |
| `Business_D.html` | [열기](https://ycanns.github.io/Graphs/Business_D.html) | 0.38 |
| `Business_E.html` | [열기](https://ycanns.github.io/Graphs/Business_E.html) | 0.39 |
| `Business_F.html` | [열기](https://ycanns.github.io/Graphs/Business_F.html) | 0.39 |
| `Business_G.html` | [열기](https://ycanns.github.io/Graphs/Business_G.html) | 0.39 |
| `Business_H.html` | [열기](https://ycanns.github.io/Graphs/Business_H.html) | 0.39 |
| `Business_I.html` | [열기](https://ycanns.github.io/Graphs/Business_I.html) | 0.38 |
| `Business_J.html` | [열기](https://ycanns.github.io/Graphs/Business_J.html) | 0.39 |
| `Business_K.html` | [열기](https://ycanns.github.io/Graphs/Business_K.html) | 0.38 |
| `Business_L.html` | [열기](https://ycanns.github.io/Graphs/Business_L.html) | 0.38 |
| `Business_M.html` | [열기](https://ycanns.github.io/Graphs/Business_M.html) | 0.39 |
| `Business_N.html` | [열기](https://ycanns.github.io/Graphs/Business_N.html) | 0.39 |
| `Business_O.html` | [열기](https://ycanns.github.io/Graphs/Business_O.html) | 0.38 |
| `Business_P.html` | [열기](https://ycanns.github.io/Graphs/Business_P.html) | 0.38 |
| `Business_Q.html` | [열기](https://ycanns.github.io/Graphs/Business_Q.html) | 0.39 |
| `Business_R.html` | [열기](https://ycanns.github.io/Graphs/Business_R.html) | 0.38 |
| `Business_S.html` | [열기](https://ycanns.github.io/Graphs/Business_S.html) | 0.39 |
| `Local_Business_GapMinder.html` | [열기](https://ycanns.github.io/Graphs/Local_Business_GapMinder.html) | 4.29 |
| `Major_KED_clustering_SGG.html` | [열기](https://ycanns.github.io/Graphs/Major_KED_clustering_SGG.html) | 77.48 |
| `Major_KED_clustering_SIDO.html` | [열기](https://ycanns.github.io/Graphs/Major_KED_clustering_SIDO.html) | 32.17 |
| `Ty1A_Ave_Dist_Map_1.html` | [열기](https://ycanns.github.io/Graphs/Ty1A_Ave_Dist_Map_1.html) | 91.41 |
| `Ty1A_Ave_Dist_Map_2.html` | [열기](https://ycanns.github.io/Graphs/Ty1A_Ave_Dist_Map_2.html) | 98.68 |
| `Ty1B_Ave_Dist_Map.html` | [열기](https://ycanns.github.io/Graphs/Ty1B_Ave_Dist_Map.html) | 86.22 |
| `Ty2_Ave_Dist_Map.html` | [열기](https://ycanns.github.io/Graphs/Ty2_Ave_Dist_Map.html) | 79.45 |
| `Ty3_Ave_Dist_Map.html` | [열기](https://ycanns.github.io/Graphs/Ty3_Ave_Dist_Map.html) | 81.48 |

</details>

<a id="education"></a>

### 교육

<details>
<summary><b>펼치기 — 14개 페이지</b></summary>

| 파일명 | 바로가기 | 용량 (MB) |
|---|---|---:|
| `ACADMA_DATA.html` | [열기](https://ycanns.github.io/Graphs/ACADMA_DATA.html) | 17.76 |
| `ACADMA_DATA_10.html` | [열기](https://ycanns.github.io/Graphs/ACADMA_DATA_10.html) | 5.13 |
| `ACADMA_DATA_11.html` | [열기](https://ycanns.github.io/Graphs/ACADMA_DATA_11.html) | 0.61 |
| `ACADMA_DATA_12.html` | [열기](https://ycanns.github.io/Graphs/ACADMA_DATA_12.html) | 0.57 |
| `ACADMA_DATA_13.html` | [열기](https://ycanns.github.io/Graphs/ACADMA_DATA_13.html) | 0.61 |
| `ACADMA_DATA_14.html` | [열기](https://ycanns.github.io/Graphs/ACADMA_DATA_14.html) | 0.74 |
| `ACADMA_DATA_15.html` | [열기](https://ycanns.github.io/Graphs/ACADMA_DATA_15.html) | 0.83 |
| `ACADMA_DATA_16.html` | [열기](https://ycanns.github.io/Graphs/ACADMA_DATA_16.html) | 1.00 |
| `ACADMA_DATA_17.html` | [열기](https://ycanns.github.io/Graphs/ACADMA_DATA_17.html) | 1.10 |
| `ACADMA_DATA_18.html` | [열기](https://ycanns.github.io/Graphs/ACADMA_DATA_18.html) | 1.18 |
| `ACADMA_DATA_19.html` | [열기](https://ycanns.github.io/Graphs/ACADMA_DATA_19.html) | 1.35 |
| `ACADMA_DATA_20.html` | [열기](https://ycanns.github.io/Graphs/ACADMA_DATA_20.html) | 1.14 |
| `ACADMA_DATA_21.html` | [열기](https://ycanns.github.io/Graphs/ACADMA_DATA_21.html) | 1.51 |
| `ACADMA_DATA_22.html` | [열기](https://ycanns.github.io/Graphs/ACADMA_DATA_22.html) | 1.73 |

</details>

<a id="tourism"></a>

### 관광과 여가

<details>
<summary><b>펼치기 — 7개 페이지</b></summary>

| 파일명 | 바로가기 | 용량 (MB) |
|---|---|---:|
| `Leisure_Compare_by_Age.html` | [열기](https://ycanns.github.io/Graphs/Leisure_Compare_by_Age.html) | 65.59 |
| `Shop_Compare_by_Age.html` | [열기](https://ycanns.github.io/Graphs/Shop_Compare_by_Age.html) | 13.35 |
| `Tour_COM_Trends.html` | [열기](https://ycanns.github.io/Graphs/Tour_COM_Trends.html) | 3.87 |
| `Tour_Compare_by_Age.html` | [열기](https://ycanns.github.io/Graphs/Tour_Compare_by_Age.html) | 53.46 |
| `Tour_DATA_MAP.html` | [열기](https://ycanns.github.io/Graphs/Tour_DATA_MAP.html) | 31.37 |
| `Tour_DATA_MAP_by_Yr.html` | [열기](https://ycanns.github.io/Graphs/Tour_DATA_MAP_by_Yr.html) | 33.67 |
| `Tour_Lodging_Trends.html` | [열기](https://ycanns.github.io/Graphs/Tour_Lodging_Trends.html) | 3.88 |

</details>

<a id="infrastructure"></a>

### 시설과 공간 분포

<details>
<summary><b>펼치기 — 10개 페이지</b></summary>

| 파일명 | 바로가기 | 용량 (MB) |
|---|---|---:|
| `Cmmrcial_NE_by_Urban_Map.html` | [열기](https://ycanns.github.io/Graphs/Cmmrcial_NE_by_Urban_Map.html) | 87.70 |
| `Emergency_Shelter_n_Water.html` | [열기](https://ycanns.github.io/Graphs/Emergency_Shelter_n_Water.html) | 19.36 |
| `Home_NE_by_Urban_Map.html` | [열기](https://ycanns.github.io/Graphs/Home_NE_by_Urban_Map.html) | 87.70 |
| `Industry_NE_by_Urban_Map.html` | [열기](https://ycanns.github.io/Graphs/Industry_NE_by_Urban_Map.html) | 87.70 |
| `Logistic_Facility_STAT.html` | [열기](https://ycanns.github.io/Graphs/Logistic_Facility_STAT.html) | 4.92 |
| `Logistic_Locations_doc_v2.html` | [열기](https://ycanns.github.io/Graphs/Logistic_Locations_doc_v2.html) | 0.59 |
| `Logistic_Locations_v2.html` | [열기](https://ycanns.github.io/Graphs/Logistic_Locations_v2.html) | 0.66 |
| `Logistic_NE_by_Urban_Map.html` | [열기](https://ycanns.github.io/Graphs/Logistic_NE_by_Urban_Map.html) | 87.70 |
| `Logistic_OD_Visual_v2.html` | [열기](https://ycanns.github.io/Graphs/Logistic_OD_Visual_v2.html) | 0.08 |
| `Public_NE_by_Urban_Map.html` | [열기](https://ycanns.github.io/Graphs/Public_NE_by_Urban_Map.html) | 87.70 |

</details>

<a id="text"></a>

### 민원과 뉴스 및 연구 동향

<details>
<summary><b>펼치기 — 13개 페이지</b></summary>

| 파일명 | 바로가기 | 용량 (MB) |
|---|---|---:|
| `BigKinds_Metaverse.html` | [열기](https://ycanns.github.io/Graphs/BigKinds_Metaverse.html) | 3.98 |
| `DBRIA_over_years.html` | [열기](https://ycanns.github.io/Graphs/DBRIA_over_years.html) | 5.86 |
| `DBRIA_over_years_new.html` | [열기](https://ycanns.github.io/Graphs/DBRIA_over_years_new.html) | 6.35 |
| `DBRIA_over_years_new_v2.html` | [열기](https://ycanns.github.io/Graphs/DBRIA_over_years_new_v2.html) | 6.52 |
| `DBRIA_trends_2018_2021.html` | [열기](https://ycanns.github.io/Graphs/DBRIA_trends_2018_2021.html) | 5.07 |
| `Google_Trends_n_YouTube.html` | [열기](https://ycanns.github.io/Graphs/Google_Trends_n_YouTube.html) | 3.66 |
| `IT_by_year.html` | [열기](https://ycanns.github.io/Graphs/IT_by_year.html) | 3.71 |
| `NRC_Metaverse.html` | [열기](https://ycanns.github.io/Graphs/NRC_Metaverse.html) | 3.68 |
| `NRC_Metaverse_Emotion.html` | [열기](https://ycanns.github.io/Graphs/NRC_Metaverse_Emotion.html) | 3.71 |
| `NRC_Metaverse_Emotion_pie.html` | [열기](https://ycanns.github.io/Graphs/NRC_Metaverse_Emotion_pie.html) | 3.66 |
| `Public_Asking.html` | [열기](https://ycanns.github.io/Graphs/Public_Asking.html) | 3.88 |
| `Public_Asking_by_ratio.html` | [열기](https://ycanns.github.io/Graphs/Public_Asking_by_ratio.html) | 3.89 |
| `metaverse_news.html` | [열기](https://ycanns.github.io/Graphs/metaverse_news.html) | 0.00 |

</details>

<a id="other"></a>

### 기타 시각화

<details>
<summary><b>펼치기 — 6개 페이지</b></summary>

| 파일명 | 바로가기 | 용량 (MB) |
|---|---|---:|
| `Daeduck.html` | [열기](https://ycanns.github.io/Graphs/Daeduck.html) | 0.29 |
| `Donggu.html` | [열기](https://ycanns.github.io/Graphs/Donggu.html) | 0.29 |
| `Figure24.html` | [열기](https://ycanns.github.io/Graphs/Figure24.html) | 2.55 |
| `Joonggu.html` | [열기](https://ycanns.github.io/Graphs/Joonggu.html) | 0.29 |
| `Seogu.html` | [열기](https://ycanns.github.io/Graphs/Seogu.html) | 0.29 |
| `Yousunggu.html` | [열기](https://ycanns.github.io/Graphs/Yousunggu.html) | 0.29 |

</details>

---

원본 HTML 파일은 [`docs/`](docs/)에서 확인할 수 있습니다.
