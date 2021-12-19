# patient-analysis-repo
---

## 1. 개요

### **1-1. 프로젝트 목적**
여러 테이블로 구성된 환자 데이터를 활용해 추출하려는 목적에 따라 SQL을 통해 데이터를 추출하는 서브 프로젝트입니다.

<br/>

### **1-2. 프로젝트 목표**
- SQL 을 활용한 DB 에서의 데이터 추출
- 환자 진료노트에서의 텍스트 추출 및 DB 에 데이터 저장

<br/>

### **1-3. 기술적 summary**
- SQLAlchemy, Numpy, Pandas 를 활용한 데이터 추출 및 저장
- 정규표현식을 활용한 진료노트에서의 텍스트 추출

<br/>

### **1-4. 데이터 설명**
**<테이블 별 설명>**
- **person** : 환자에 대한 정보
- **visit_occurrence** : 환자의 방문에 대한 정보
- **condition_occurrence** : 진단(병명)에 대한 정보
- **drug_exposure** : 의약품 처방에 대한 정보
- **concept** : 병명에 대한 정보

<br/>

---
---
## 2. 결과

### **2-1. 5개의 특정 환자군에 대한 분석**
- 아래의 Notebook 에서 DB에서의 데이터 추출 및 전처리, 결과를 기록하였습니다.
> [extract_patient_cluster_1-5.ipynb](https://github.com/aeea-0605/patient-analysis-repo/blob/main/extract_patient_cluster_1-5.ipynb)

<br/>

### **2-2. 환자 진료노트에서의 데이터 추출**
- 아래의 Notebook 에서 텍스트 추출 및 전처리, DB에 데이터를 저장하는 과정을 기록하였습니다.
> [extract_data_to_note.ipynb](https://github.com/aeea-0605/patient-analysis-repo/blob/main/extract_data_to_note.ipynb)

<br/>

---
---

#### **requirement packages**
- numpy
- pandas
- psycopg2
- sqlalchemy
