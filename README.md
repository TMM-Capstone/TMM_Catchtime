# [19팀 TMM] CatchTime - 캣치타임

## 설명
캣치타임은 효율적인 시간 관리를 돕는 타이머 기반 모바일 2D 캐릭터 육성 게임입니다. 사용자는 자유롭게 일과 휴식 시간 타이머 시간을 설정하여, 일과 휴식의 분리를 통해 보다 효율적인 업무가 가능해집니다. 타이머를 사용할 때마다 주어지는 인게임 재화를 이용하여 메인 화면을 꾸밀 수 있습니다. 이 프로젝트는 시간 관리를 보다 즐겁고 효과적으로 할 수 있도록 하는 것이 목표입니다.<br><br>

## 소스 코드
### 주요 소스 코드 구조에 대한 개요입니다.
- Assets/: 게임의 에셋과 스크립트가 위치한 폴더.<br>
- Assets/Scenes/: 게임의 씬이 위치한 폴더.<br>
- Packages/: 유니티에 설치된 패키지가 위치한 폴더.<br>
- ProjectSettings/: 장면 전환에 필요한 빌드 세팅이 저장된 폴더.<br><br>

## 빌드 방법
### 유니티 에디터로 유니티 프로젝트를 빌드하는 방법입니다.
1. 유니티 허브에서 Android Build Support, iOS Build Support 두 모듈이 설치된 에디터를 통해 프로젝트를 엽니다.
2. File -> Build Settings를 선택합니다.
3. Android로 Switch Platform을 선택합니다.
4. Scenes 폴더에 있는 씬들을 scenes in build에 모두 추가하고 빌드 타겟을 선택한 후, Build 버튼을 클릭합니다.<br><br>

## 설치 방법
### 모바일 기기에 프로젝트를 설치하는 방법입니다.
1. 빌드된 .apk 파일을 모바일 안드로이드 기기에 다운로드합니다.
2. 파일에서 어플리케이션 설치를 실행하고, 설치된 어플리케이션을 구동합니다.<br><br>

## 테스트 방법
### 유니티 에디터로 프로젝트를 테스트하는 방법입니다.
1. 유니티 에디터 2022.3.21f1 버전에서 프로젝트를 엽니다.
2. file -> build settings를 선택합니다.
3. android로 switch platform을 선택합니다.
4. Scenes 폴더에 있는 씬들을 scenes in build에 추가합니다.
5. 테스트하고자 하는 씬(1번 씬: Title)을 열고, 상단의 Play 버튼을 클릭합니다.
6. 테스트 계정 : 이메일 - tmm19@ewha.ac.kr , 비밀번호 - catchtime<br><br>

## 사용된 데이터베이스 또는 데이터
### 프로젝트에서 사용된 데이터베이스입니다.
- Firebase: 유저 데이터를 저장하기 위해 사용.<br><br>

## 사용된 오픈 소스 구성 요소
### 프로젝트에서 사용된 오픈 소스입니다.
- TextMeshPro: 텍스트 렌더링을 위해 사용.<br>
- 폰트 이름: Galmuri14<br>
  - 라이선스: SIL Open Font License 1.1<br>
  - 출처: https://galmuri.quiple.dev/<br>
  - 저작권자: quiple
