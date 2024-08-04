# 목차
- 🍙 프로젝트 소개 (개요)
- 🗺 Architecture
- 🗂 파일 디렉토리 구조
- 📱 주요 화면 및 구현 기능
    1. 1️⃣ STEP1. Onboarding 화면 구현
        - 관련 PR
        - 고민한 점
        - Trouble Shooting
        - 키워드
    1. 2️⃣ STEP2. 네트워크 및 TabBar 화면/설정 화면 구현
        - 관련 PR
        - 고민한 점
        - Trouble Shooting
        - 키워드
    1. 3️⃣ STEP3. 게임 화면 및 애니메이션 구현
        - 관련 PR
        - 고민한 점
        - Trouble Shooting
        - 키워드
    1. 4️⃣ STEP4. 게임결과 화면 구현
        - 관련 PR
        - 고민한 점
        - Trouble Shooting
        - 키워드
  1. 🌙 업데이트 및 리팩토링 계획
- 배운 점
- 오류 해결방안
- 시연영상

---

## 🍙 프로젝트 소개 (개요)

미니게임으로 사용자의 취향을 분석하여 혼자 또는 여럿이서 먹을 식사메뉴를 추천하는 iOS 앱<br>

Firebase사용법과 Delegate패턴, MVC패턴, 코드로 UI구현을 학습하기 위한 기능학습 프로젝트 입니다.<br>

My: HTML과 CSS를 학습하기 위한 기능학습 프로젝트 입니다. 학원 수업에 추가적으로 예습 복습 내용의 실질적인 활용을 위해 개인 프로젝트를 시작했습니다.

🔗 앱 다운로드 링크 image

개인 프로젝트

진행 기간
개발 : 2024.07.29 ~ 2024.08.30 (9주)

기술 스택
개발 환경
iOS : swift 5, xcode 13.4
서버 : Java 17, IntelliJ IDEA
라이브러리
iOS : RxSwift, Firebase, Realm, SwiftLint, Lottie
서버 : Spring boot
Deployment Target : iOS 14.0

Github: https://github.com/<br>
Skills: ActiveLabel, CocoaPods, Firebase, MVC

---

## 구현 기능

게시글 올리기
댓글
맨션
좋아요
해시태그
알람 받기
DM메시지 보내기
프로필 편집하기

🍖 Onboarding 화면 - 못먹는 음식을 알려주시면 추천 메뉴에서 제외해요
🙌 함께메뉴결정 탭의 그룹생성하기 시나리오 - 팀원들에게 PIN 번호를 알려주세요. 인원 제한 없이 누구나 참여할 수 있어요
🔢 함께메뉴결정 탭의 PIN으로 입장하기 시나리오 - Host가 알려준 PIN 번호를 입력하여 간단히 참여해봐요
🕹️ 게임 / 게임결과대기 / 게임결과 화면 - Host가 결과확인 버튼을 탭할 때까지 게임을 진행해주세요
🎲 Home 탭 - 게임을 하기 귀찮다면 랜덤메뉴도 있어요
⚙️ 설정 화면 - 못먹는 음식을 수정하거나, 개발자에게 피드백을 남길 수 있어요 
⚠️ 오류 화면 - 네트워크 연결이 불안정하면 알려드려요

My:


---

## 오류 해결방안

---

## 배운 점

반응형 웹이 진짜 힘들다..

---

## structure drawing

---

## how I studied

모르는 것은 먼저 구글 서칭으로 배우고 스스로 코드를 작성한 후: 질문과 답으로 메모.
실제 코드와 비교: 다른점, 고칠점 메모. 변수 이름 정하는 것도 보기

---

## Questions

#### 01 Aug
- display: inline-block; margin-top: 60px; text-align: center;  Why doesn't this work?<br />
A: text-align should be marked to the parent tag. Others to child tag.
- Which tags to use to parent elements or child elements?<br/>
A: CSS Cascade: Styles are applied based on specificity and importance. Inline styles override external or internal styles, and ID selectors override class selectors, etc. The "Styles" pane will show you the source of each rule (e.g., line number in a CSS file).
- CSS override rules: Inline override others
- Which tags are used to which occasions to seperate areas
- Imac over 왼쪽 오른쪽 시작 나는 법<br/>
A: div parent elemetn 하나 더 만들어서 margin쓰기. display와 justify-content는 부모요소에.

## 공부 방법
1. 코드를 스스로 작성한다.
2. 웹사이트 페이지 원본 보기 기능으로 실제 코드와 비교해본다.