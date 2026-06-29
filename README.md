# Leon Theme

여러 에디터에서 동일한 look & feel을 유지하기 위한 **Leon** 컬러 테마 모음입니다. JetBrains의 `.icls` 스키마가 원본이며, 이를 다른 플랫폼으로 이식해 함께 관리합니다.

## 구성

| 폴더 | 플랫폼 | 내용 |
|------|--------|------|
| [`vscode/`](./vscode) | Visual Studio Code | Leon Light / Leon Dark 테마 확장 |
| [`jetbrains/`](./jetbrains) | JetBrains IDE (CLion 등) | `Leon_Light.icls`, `Leon_Dark.icls` (원본) |
| [`iterm/`](./iterm) | iTerm2 | `leon-light.itermcolors` |

## 설치

### VS Code

[Releases](https://github.com/0xf07ce/leon-theme/releases)의 `.vsix`로 설치하거나:

```bash
code --install-extension leon-theme-1.1.0.vsix
```

자세한 사용법(테마 선택, OS 다크모드 자동 전환)은 [`vscode/README.md`](./vscode/README.md) 참고.

### JetBrains

Settings → Editor → Color Scheme → 톱니바퀴 → **Import Scheme...** 에서 [`jetbrains/`](./jetbrains)의 `.icls` 파일 선택.

### iTerm2

Settings → Profiles → Colors → **Color Presets... → Import** 에서 [`iterm/leon-light.itermcolors`](./iterm/leon-light.itermcolors) 선택.

## 라이선스

[MIT](./LICENSE)
