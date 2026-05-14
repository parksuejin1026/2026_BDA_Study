# 2026 Big Data Analysis Study

빅데이터 분석 프로그래밍 수업 내용을 주차별로 정리한 저장소입니다. Python 기초부터 NumPy, Pandas, Matplotlib 기반 데이터 분석과 시각화까지 실습 노트북을 중심으로 구성되어 있습니다.

## 사용 기술

- Python
- Jupyter Notebook / Google Colab
- NumPy
- Pandas
- Matplotlib
- Seaborn
- pydataset

## 주차별 수업 내용 요약

| 주차 | 주요 내용 | 관련 파일 |
| --- | --- | --- |
| 1주차 | 강의 소개와 데이터 분석 개발 환경을 준비했습니다. Colab/Jupyter 사용법, Python 라이브러리 설치, Matplotlib을 활용한 간단한 시각화와 한글 폰트 설정을 다뤘습니다. | `Week1/01w_init_bigdata.ipynb` |
| 2주차 | Python 기초 문법과 자료구조를 학습했습니다. 변수, 날짜/시간, 리스트·딕셔너리 등 기본 자료형을 다루고 `pydataset`을 활용해 예제 데이터를 불러오는 방법을 연습했습니다. | `Week2/02w_python_basic.ipynb` |
| 3주차 | 과학 계산 라이브러리 NumPy의 기본 사용법을 학습했습니다. 배열 생성, 차원과 형태 확인, 인덱싱·슬라이싱, 기본 연산을 실습했습니다. | `Week3/Week3_BDA.ipynb` |
| 4주차 | NumPy 다차원 배열의 결합과 분리를 다뤘습니다. `vstack`, `hstack`, `row_stack`, `column_stack`, `split`, `hsplit`, `vsplit` 등을 이용해 배열 구조를 변환했습니다. | `Week4/2026_BDA_Week4.ipynb` |
| 5주차 | Matplotlib 기반 데이터 시각화 기초를 학습했습니다. 선 그래프, 산점도, 그래프 제목·축·범례 설정, 여러 그래프를 배치하는 subplot 사용법을 연습했습니다. | `Week5/matplotlib.ipynb`, `Week5/05w_matplotlib_subplot_B.ipynb` |
| 6주차 | Pandas 데이터프레임의 기본 구조와 정보 확인 방법을 학습했습니다. DataFrame 생성, 행과 열 선택, `head`, `tail`, `info`, `describe` 등을 활용한 데이터 탐색을 실습했습니다. | `Week6/06w_dataframe_B.ipynb` |
| 7주차 | `pydataset`의 다양한 데이터셋을 Pandas로 불러와 분석했습니다. 데이터프레임 검색, 조건 필터링, 컬럼 선택, 기초 통계 확인을 중심으로 실습했습니다. | `Week7/BDA_week7.ipynb` |
| 8주차 | Pandas 데이터 전처리 치트시트를 기반으로 데이터 조작 기능을 정리했습니다. 데이터프레임 생성, 정렬, 컬럼명 변경, 중복 제거, 샘플링, `loc`/`iloc` 선택 등을 연습했습니다. | `Week8/08w_Pandas_Cheat_Sheet_Practice.ipynb` |
| 9주차 | 데이터 시각화 실습을 확장했습니다. Pandas 데이터와 Matplotlib/Seaborn을 함께 사용해 변수 간 관계, 분포, 범주별 비교를 시각적으로 확인했습니다. | `Week9/09w_data_vis_B.ipynb` |
| 10주차 | 다양한 데이터셋을 활용해 시각화 분석을 반복 실습했습니다. 그래프 유형별 표현 방식, 여러 데이터프레임 비교, 한글 시각화 설정, 시각화 결과 해석을 다뤘습니다. | `Week10/10w_data_vis_B.ipynb` |
| 11주차 | Pandas의 그룹화와 병합 기능을 학습했습니다. `groupby`를 이용한 집계, 그룹별 통계 계산, 데이터프레임 결합과 `merge`를 활용한 데이터 통합을 실습했습니다. | `Week11/11w_ch06_dataframe_group_merge.ipynb` |

## 폴더 구조

```text
2026_BDA_Study/
├── Week1/    # 개발 환경, 강의 소개, 시각화 준비
├── Week2/    # Python 기초와 자료구조
├── Week3/    # NumPy 기초
├── Week4/    # NumPy 배열 결합과 분리
├── Week5/    # Matplotlib 시각화 기초
├── Week6/    # Pandas 데이터프레임 기초
├── Week7/    # pydataset과 데이터프레임 검색
├── Week8/    # Pandas 데이터 전처리 연습
├── Week9/    # 데이터 시각화 실습
├── Week10/   # 데이터 시각화 심화 실습
├── Week11/   # 데이터프레임 그룹화와 병합
└── 수업자료/  # 강의 PDF 자료
```

## 참고

- 각 주차 폴더에는 수업 실습용 Jupyter Notebook 파일이 포함되어 있습니다.
- `수업자료/` 폴더에는 강의 PDF와 시험 관련 자료가 정리되어 있습니다.
