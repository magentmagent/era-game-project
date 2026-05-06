# Era 게임 프로젝트 (개선판)

**Emuera1821+v8.exe**를 기반으로 한 **최소 Era 게임 템플릿**입니다.

> ⚠️ 이 프로젝트는 **완성된 풀 게임** 이 아닙니다. 
> Era 게임을 처음 시작하는 사람을 위한 **기본 뼈대** 입니다.

## 🚀 사용 방법

1. GitHub에서 ZIP 다운로드 또는 `git clone`
2. **Emuera1821+v8.exe**를 이 폴더에 복사
3. Emuera.exe 실행

## 📁 현재 구조 (최소 구성)

```
era-game-project/
├── README.md
├── GAMEBASE.CSV
├── EVENT.ERB          ← 메인 스크립트 (여기서 대부분 작업)
├── 0_SYSTEM.ERH
├── CHARA1.CSV         ← 기본 캐릭터 데이터 (추가됨)
├── .gitignore
└── sav/
```

## 🎮 현재 구현된 내용

- 시작 메뉴
- 간단한 캐릭터 상호작용 (대화 / 상태 확인)
- 기본 Era 문법 데모

## ✏️ 어떻게 확장하나요?

1. `EVENT.ERB` 파일을 열어서 더 많은 명령어와 이벤트를 추가
2. `CHARA*.CSV` 파일을 늘려 캐릭터 추가
3. ERB 폴더를 만들고 `#INCLUDE` 로 분리 (고급)

**필요한 경우** 제가 더 많은 파일과 기능을 직접 추가해 드릴 수 있습니다!

---
Powered by Grok