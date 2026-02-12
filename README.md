Unreal Engine Listen Server Practice

언리얼 엔진의 리슨 서버(Listen Server) 시스템을 학습하고 구현한 연습 프로젝트입니다.

📸 Preview

<img src="./Images/LS.png" width="300" alt="Listen Server Preview">

🛠 주요 구현 내용

리슨 서버 환경에서 클라이언트 간의 동기화 및 서버 호스팅의 기초를 다루었습니다.

사용된 핵심 코드 및 에셋

0_Listen 폴더: 리슨 서버 전용 로직 및 통신 관련 스크립트 포함

📂 Project Structure

ProjectRoot/
├── 0_Listen/             # 리슨 서버 연습 핵심 폴더
│   ├── Scripts/          # 통신 및 동기화 로직
│   └── Blueprints/       # 리슨 서버 설정 블루프린트
├── Source/               # C++ 소스 코드
├── Content/              # 프로젝트 에셋
└── README.md             # 프로젝트 설명서


🚀 시작하기

레포지토리를 클론합니다.

.uproject 파일을 우클릭하여 Generate Visual Studio project files를 실행합니다.

프로젝트를 빌드한 후 언리얼 에디터에서 실행합니다.

Play 모드를 Listen Server로 설정하여 테스트를 진행합니다.

Author: kwon