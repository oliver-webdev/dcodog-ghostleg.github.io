# 🎤 디코독 경연 순서 정하기 (DCODOG Stage Order Picker)

보컬 그룹 및 버스킹 공연의 경연 순서를 화려하고 공정하게 정할 수 있는 
네온 룩앤필 테마의 사다리타기 웹 애플리케이션입니다.  

## 🔗 배포 주소 (Live Demo)
- [💡 실시간 웹앱 실행하기](https://zeonerd.github.io/dcodog-ghostleg)

---

## ✨ 핵심 기능 (Key Features)

### 1. 세련된 사이버펑크 & 네온 무대 연출
- 딥 네이비(`stage-bg`) 배경과 화려한 네온 컬러 라인, 글래스모피즘(Glassmorphic) UI를 결합하여 실제 화려한 무대 위의 전광판을 보는 듯한 긴장감과 몰입감을 줍니다.

### 2. 하이브리드 명단 세팅 모드 (Manual & Auto)
- **직접 설정:** 최소 2명부터 최대 16명까지 직관적으로 인원을 지정하여 사다리를 세팅할 수 있습니다.
- **명단 자동 세팅 (텍스트 파싱):** 단톡방이나 노션에서 사용하던 선곡 리스트(예: `1. 홍길동`, `2. 김철수`)를 그대로 복사-붙여넣기하면 번호 뒤의 이름만 깔끔하게 추출하여 자동으로 사다리를 생성합니다.

### 3. 역동적인 HTML5 Canvas 애니메이션
- 모든 참가자의 경로가 화려한 네온 빛을 내며 **동시에 실시간으로 하강**하는 Dynamic Animation을 구현했습니다.
- 바쁜 진행을 위해 애니메이션을 건너뛰고 결과를 즉시 확인하는 **'결과 바로보기(Skip)'** 기능을 지원합니다.

### 4. 경연 순서표 이미지 저장 기능 (html2canvas)
- 사다리타기가 완료되면 깔끔하게 정렬된 **'세트리스트(Setlist)' 스타일의 모달 창**이 열립니다.
- 내장된 `html2canvas` 라이브러리를 통해 결과 테이블을 **고화질 PNG 이미지로 즉시 다운로드**할 수 있어, 팀원들에게 순서표를 공유하기 매우 편리합니다.

### 5. 모바일 최적화 (Responsive Design)
- 인원수가 많아질 경우 모바일 화면에서 사다리가 깨지지 않도록 **좌우 스와이프 스크롤 시스템 및 안내 힌트**를 적용했습니다.

---

## 🛠 사용 기술 스택 (Tech Stack)

- **Frontend:** HTML5, Vanilla JavaScript (ES6+)
- **Styling:** Tailwind CSS (CDN Integration)
- **Graphics:** HTML5 Canvas API
- **Libraries:** `html2canvas v1.4.1` (결과 화면 이미지 캡처 및 다운로드)
- **Fonts:** Google Fonts (Jua, Gowun Dodum, Noto Sans KR)
- **Deployment:** GitHub Pages

---
