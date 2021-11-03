# patient-analysis-repo

## 가이드

### 6개의 환자군에 대한 분석
> [extract_patient_cluster_1-6.ipynb](https://github.com/aeea-0605/patient-analysis-repo/blob/main/extract_patient_cluster_1-6.ipynb)

<br/>

#### requirement packages
- numpy
- pandas
- psycopg2
- sqlalchemy

<br/>

#### 데이터베이스 접속
> [data.ini](https://github.com/aeea-0605/patient-analysis-repo/blob/main/data.ini)
- 해당 파일에 요구되는 정보를 넣고 Notebook을 순차적으로 실행하면 됩니다.

<br/>

---

### Note에 대해 정보를 추출하고 DB에 저장
> [extract_data_to_note.ipynb](https://github.com/aeea-0605/patient-analysis-repo/blob/main/extract_data_to_note.ipynb)

<br/>

#### requirement packages
- re
- numpy
- pandas
- psycopg2
- sqlalchemy

<br/>

#### 데이터베이스 접속
> [data.ini](https://github.com/aeea-0605/patient-analysis-repo/blob/main/data.ini)
- 해당 파일에 요구되는 정보를 넣고 Notebook을 순차적으로 실행하면 됩니다.

<br/>

---
---

### 제언
- 각 Note에 대해 함수 및 클래스들에 대한 모듈 파일을 작성한다면 좀 더 깔끔한 코드를 만들 수 있다고 생각합니다.
- 시간이 촉박하여 정리하지 못한 반복되는 코드들을 함수화 한다면 좀 더 깔끔한 코드를 만들 수 있다고 생각합니다.
