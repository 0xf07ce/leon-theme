# Leon Themes

JetBrains의 **Leon Light** / **Leon Dark** 컬러 스키마(`.icls`)를 Visual Studio Code로 이식한 테마입니다. JetBrains IDE(CLion 등)와 VS Code를 오가며 쓸 때 동일한 look & feel을 유지하기 위해 만들었습니다.

포함된 테마:

- **Leon Light** — 시력 보호를 위해 아주 옅은 초록빛 배경(`#f6fcf7`)을 입힌 라이트 테마
- **Leon Dark** — Darcula 계열의 다크 테마 (배경 `#000000`)

## 설치

### 방법 1 — `.vsix` 설치 (권장)

[Releases](https://github.com/0xf07ce/leon-theme/releases)에서 최신 `.vsix`를 받아:

```bash
code --install-extension leon-theme-1.1.0.vsix
```

또는 VS Code에서 `Cmd+Shift+P` → **Extensions: Install from VSIX...** 로 선택.

### 방법 2 — 저장소 clone

```bash
git clone https://github.com/0xf07ce/leon-theme.git
cp -r leon-theme/vscode ~/.vscode/extensions/leon-theme
```

설치 후 VS Code를 재시작(또는 `Cmd+Shift+P` → **Developer: Reload Window**)합니다.

## 사용

`Cmd+K Cmd+T` (Windows/Linux: `Ctrl+K Ctrl+T`) → **Leon Light** 또는 **Leon Dark** 선택.

### OS 다크모드 자동 전환

OS 테마에 따라 라이트/다크를 자동 전환하려면 `settings.json`에 추가:

```jsonc
"window.autoDetectColorScheme": true,
"workbench.preferredLightColorTheme": "Leon Light",
"workbench.preferredDarkColorTheme": "Leon Dark"
```

## 색상 개요

| 요소 | Light | Dark |
|------|-------|------|
| 에디터 배경 | `#f6fcf7` | `#000000` |
| 전경 | `#2e2e2e` | `#c0c0c0` |
| 키워드 | `#009800` | `#77b767` |
| 함수/메서드 | `#e0218a` | `#cc3333` |
| 클래스·타입 | `#0036f0` | `#0080ff` |
| 문자열 | `#009fcc` | `#6897bb` |
| 숫자 | `#b85600` | `#e1e100` |
| 주석 | `#a0a0a0` | `#606060` |

> VS Code의 TextMate/시맨틱 토큰 분류는 JetBrains의 PSI 기반 분류와 완전히 같지 않아 언어별로 미세한 차이가 있을 수 있습니다.

## 라이선스

[MIT](./LICENSE)
