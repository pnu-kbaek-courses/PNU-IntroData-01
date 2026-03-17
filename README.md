# 데이터사이언스 입문 (부산대학교, 2026년 봄학기)

**강의자**: 백광열 교수 (Pusan National University)

> 이 repository는 GitHub Classroom을 통해 학생 개인에게 자동으로 할당됩니다. 별도 제출 무하이, 이 repository에 파일을 저장하면 제출로 간주됩니다.

---

## 파일 구성

### 학습 자료 (수업 중 실습)

| 파일 | 설명 |
|------|------|
| `ch02_pandas_basic.ipynb` | Ch.02 pandas 기초 — DataFrame 생성, 인덱싱, 기초 통계 등 수업 중 함께 따라하는 실습 노트북 |
| `ch03_practice.ipynb` | Ch.03 실습 노트북 — 수업 중 강사와 함께 따라하는 학습 자료 |
| `health2018.csv` | 실습에 사용하는 샘플 데이터 (2018년 건강 데이터) |

### 실습 과제

| 파일/폴더 | 설명 |
|-----------|------|
| `ch03_test.ipynb` | Ch.03 실습 과제 문제 — `health2018.csv`를 활용하여 직접 풀어보는 과제 |
| `test/` | **수업 중 제출 폴더** — 완성한 과제 노트북을 이 폴더에 저장하여 제출 |
| `test_additional/` | **추가 제출 폴더** — 추가 과제 또는 보완 제출 시 사용 |

---

## 과제 제출 방법

### 기본 방법: 로친에서 작업 후 GitHub 웹에서 업로드

1. `ch03_test.ipynb`를 다운로드하여 로컈 Jupyter Notebook에서 문제를 풀어주세요.
2. 완성된 `.ipynb` 파일을 준비합니다.
3. 이 repository의 `test/` 폴더로 이동합니다.
   - GitHub 웹에서 `test/` 폴더를 클릭한 후 **Add file → Upload files** 선택
   - 파일을 드래그앱드롭하거나 선택하여 업로드
   - **Commit changes** 버튼을 눌러 저장 (이것이 공 제출입니다)
4. 추가 제출이 필요한 경우 `test_additional/` 폴더를 동일한 방식으로 사용합니다.

> ⚠️ 이전에 제출한 파일이 있다면 동일한 파일명으로 업로드하면 자동으로 덮어씁니다. 마직막 commit 기준으로 제출본이 결정됩니다.

---

### 다른 제출 방법 (선택 사항)

<details>
<summary>클릭하여 확인</summary>

**Git 명령어 (Git 설치 시)**
```bash
git clone <본인 repository URL>
cd PNU-IntroData-01-<학번>
# 과제 파일을 test/ 폴더에 복사한 후
git add test/
git commit -m "과제 제출"
git push
```

**GitHub Desktop 사용 시**
1. repository를 클론하여 로카로 다운로드
2. `test/` 폴더에 완성한 파일 저장
3. GitHub Desktop에서 Commit 후 Push

</details>

---

> 문의사항은 강의 채널 또는 Issues 탭을 이용해주세요.
