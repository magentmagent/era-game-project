# Era 게임 프로젝트

**Emuera1821+v8.exe**를 기반으로 한 Era 게임 프로젝트입니다.

Grok이 직접 작성한 기본 템플릿입니다.

## 🚀 사용 방법

1. 이 저장소의 모든 파일을 다운로드 (또는 `git clone`)
2. 제공받은 `Emuera1821+v8.exe` 파일을 **이 폴더 루트**에 복사하세요.
3. `Emuera.exe` (또는 Emuera1821+v8.exe)를 더블클릭하여 실행
4. 게임이 시작됩니다!

## 📁 프로젝트 구조

```
era-game-project/
├── README.md
├── GAMEBASE.CSV
├── EVENT.ERB
├── 0_SYSTEM.ERH
├── .gitignore
└── sav/          (실행 시 자동 생성)
```

## 🎮 현재 게임 내용

- 간단한 환영 메시지와 메뉴
- 기본 Era 스크립트 문법 사용
- 캐릭터 상호작용 확장 가능

## ✏️ 수정 방법

`EVENT.ERB` 파일을 열어 스크립트를 자유롭게 수정하세요.
Era 문법 예시:
- `PRINTL` : 줄바꿈 출력
- `INPUT` : 플레이어 입력 받기
- `CALL` : 함수 호출
- `IF RESULT == 0` : 선택지 처리

## ⚠️ 주의사항

- Era 게임은 성인 콘텐츠를 다룰 수 있습니다.
- Emuera는 Windows 전용입니다.
- 인코딩은 UTF-8을 사용했습니다. 필요시 Shift-JIS로 변환하세요.

## 다음 단계

- 캐릭터 데이터 추가 (CHARA*.CSV)
- 더 많은 이벤트와 선택지 추가
- ABL, TALENT, CFLAG 등 Era 변수 시스템 활용

이 프로젝트를 기반으로 당신만의 Era 게임을 만들어 보세요!

---
Powered by Grok & Emuera