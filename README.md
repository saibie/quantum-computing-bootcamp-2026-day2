# 양자컴퓨팅 이론 및 실습 (12시간 집중 부트캠프) - Day 2

본 저장소는 **[양자컴퓨팅 이론 및 실습]** 4주(총 12시간) 집중 강좌 중 **2주차 (Day 2: 다중 큐비트와 양자 얽힘)** 공식 학생용 실습 및 배포 저장소입니다.  
강의 슬라이드, Day 2 렉처노트 및 실습 파일(Jupyter Notebook), 원클릭 구동 스크립트가 포함되어 있습니다.

- **강사**: 서상협 ((주)큐렌스 / QRens)
- **주제**: 2주차 - 다중 큐비트, 텐서곱, 그리고 양자 얽힘 (NumPy 기초 실습)
- **사전 요구사항**: 기본적인 파이썬 문법 이해 (파이썬이 설치되어 있지 않아도 아래 원클릭 실행기로 자동 세팅됩니다!)

---

## 📥 저장소 다운로드

### 방법 1. Git 사용 (추천)
```bash
git clone https://github.com/saibie/quantum-computing-bootcamp-2026-day2.git
cd quantum-computing-bootcamp-2026-day2
```

### 방법 2. ZIP 파일 다운로드
1. 페이지 우측 상단의 **`Code`** -> **`Download ZIP`** 클릭
2. 다운로드한 파일의 **압축을 해제**한 후 해당 폴더로 진입

---

## 🚀 3초 만에 실습 환경 시작하기

### 🪟 Windows 사용자
1. 폴더 내의 **`start_windows.bat`** 파일을 더블 클릭하여 실행합니다.
2. 검은색 터미널 창에서 자동 환경 구성 후 브라우저에 **Jupyter Lab**이 실행됩니다.

### 🍎 macOS 및 Linux 사용자
1. 터미널에서 아래 명령어 실행:
   ```bash
   chmod +x start_mac.sh
   ./start_mac.sh
   ```

---

## 📂 폴더 구조 안내

```text
├── docs/                               # 강의 교재 및 참고 문서 (PDF)
│   ├── day2_entanglement.pdf           # Day 2 강의 슬라이드 (다중 큐비트와 양자 얽힘)
│   └── lecture_notes_day2.pdf          # Day 2 핵심 수식/원리 집중 렉처노트
│
├── hands_on/                           # 실습 코드
│   └── day2_numpy_entanglement.ipynb   # [Day 2 실습] 텐서곱, CNOT, Bell 상태, 부분 측정
│
├── start_windows.bat                   # Windows 원클릭 실습 실행기
├── start_mac.sh                        # Mac/Linux 원클릭 실습 실행기
├── pyproject.toml                      # 프로젝트 메타데이터 및 의존성 정의
└── uv.lock                             # 라이브러리 버전 고정 락파일
```

---

## 💡 Day 2 핵심 학습 내용
- **Session 1**: 텐서곱($\mathbb{C}^4$)과 지수 차원 폭발($2^n$), 곱상태 vs 얽힘 상태, CNOT 게이트 행렬
- **Session 2**: Bell 상태 $|\Phi^+\rangle$ 합성, 선형대수학적 얽힘 판별식($c_{00}c_{11}-c_{01}c_{10} \neq 0$), 부분 측정 붕괴 및 No-Signaling 정리

---

## 📬 문의 및 지원
- 저작권: 본 자료의 저작권은 **(주)큐렌스** 및 강사 **서상협**에게 있습니다. 교육 목적 외 무단 배포 및 상업적 이용을 금합니다.
