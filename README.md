# PhishGuard AI

**Gmail Spear-Phishing Detection / Gmail 스피어피싱 탐지**

## English

PhishGuard AI is our team research project: a Chrome extension that combines local checks and AI analysis to identify potential phishing emails in Gmail.

**My contribution:** I participated in the project and worked on code modifications related to API integration and local API functionality.

This is my personal portfolio copy of the [team repository](https://github.com/orientaition/phishguard). The original project history and team attribution are preserved.

### Project materials

- [Research paper (latest Word version)](papers/TalkFile_PhishGuard_AI_%E1%84%82%E1%85%A9%E1%86%AB%E1%84%86%E1%85%AE%E1%86%AB_%E1%84%80%E1%85%A2%E1%84%89%E1%85%A5%E1%86%AB-2.docx.docx)
- [Project presentation (PDF)](papers/TalkFile_PhishGuard%20AI_%20Gmail%20%E1%84%91%E1%85%B5%E1%84%89%E1%85%B5%E1%86%BC%20%E1%84%86%E1%85%A6%E1%84%8B%E1%85%B5%E1%86%AF%20%E1%84%90%E1%85%A1%E1%86%B7%E1%84%8C%E1%85%B5%20Chrome%20%E1%84%92%E1%85%AA%E1%86%A8%E1%84%8C%E1%85%A1%E1%86%BC%20%E1%84%91%E1%85%B3%E1%84%85%E1%85%A9%E1%84%80%E1%85%B3%E1%84%85%E1%85%A2%E1%86%B7%20%283%29.pdf.pdf)
- [Original project instructions](README.upstream.md)

### Run

1. Download or clone this repository.
2. Run `npm run build` (or `npm.cmd run build` on Windows).
3. Open `chrome://extensions/`, enable Developer mode, and load the `dist/` folder.
4. Select an AI provider and enter your own API key in the extension settings. For the local API option, prepare Ollama and select Ollama Local.
5. Refresh Gmail and open an email to use the extension.

## 한국어

PhishGuard AI는 Gmail에서 피싱 위험을 탐지하기 위해 로컬 검사와 AI 분석을 결합한 Chrome 확장 프로그램을 개발한 팀 연구 프로젝트입니다.

**개인 기여:** 팀 프로젝트에 참여하여 API 연동 관련 코드 수정과 로컬 API 기능을 담당했습니다.

이 저장소는 [팀 저장소](https://github.com/orientaition/phishguard)를 복사한 개인 포트폴리오입니다. 원본 프로젝트 이력과 팀 출처를 보존했습니다.

### 프로젝트 자료

- [연구 논문 (최신 Word 버전)](papers/TalkFile_PhishGuard_AI_%E1%84%82%E1%85%A9%E1%86%AB%E1%84%86%E1%85%AE%E1%86%AB_%E1%84%80%E1%85%A2%E1%84%89%E1%85%A5%E1%86%AB-2.docx.docx)
- [프로젝트 발표 자료 (PDF)](papers/TalkFile_PhishGuard%20AI_%20Gmail%20%E1%84%91%E1%85%B5%E1%84%89%E1%85%B5%E1%86%BC%20%E1%84%86%E1%85%A6%E1%84%8B%E1%85%B5%E1%86%AF%20%E1%84%90%E1%85%A1%E1%86%B7%E1%84%8C%E1%85%B5%20Chrome%20%E1%84%92%E1%85%AA%E1%86%A8%E1%84%8C%E1%85%A1%E1%86%BC%20%E1%84%91%E1%85%B3%E1%84%85%E1%85%A9%E1%84%80%E1%85%B3%E1%84%85%E1%85%A2%E1%86%B7%20%283%29.pdf.pdf)
- [기존 프로젝트 실행 설명](README.upstream.md)

### 실행 방법

1. 이 저장소를 다운로드하거나 복제합니다.
2. `npm run build`를 실행합니다. Windows에서는 `npm.cmd run build`를 사용할 수 있습니다.
3. `chrome://extensions/`에서 개발자 모드를 켜고 `dist/` 폴더를 로드합니다.
4. 확장 설정에서 AI 제공사와 본인의 API 키를 설정합니다. 로컬 API는 Ollama를 준비하고 Ollama Local을 선택합니다.
5. Gmail을 새로고침하고 메일을 열어 확장 기능을 사용합니다.

