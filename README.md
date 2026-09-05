# AI 객관식 퀴즈

주제와 난이도(쉬움/보통/어려움)를 입력하면 Claude가 그 자리에서 객관식 퀴즈 5문제를 만들어주는 웹앱입니다.

- 보기 4개, 정답 확인, 문항별 한 줄 해설, 최종 점수, 다시 풀기 기능 제공
- 한국어 · 모바일 친화 UI
- 별도 API 키 없이, Claude Artifact의 `sample` 기능으로 앱 안에서 직접 Claude를 호출합니다

## 실행 방법

이 앱의 퀴즈 생성 기능은 **Claude 아티팩트로 열었을 때만** 동작합니다(`window.claude`가 Claude 뷰어 안에서만 제공되기 때문). 아래 링크로 열어 사용하세요.

- 실행 링크(AI 퀴즈 생성 동작): https://claude.ai/code/artifact/b23b1b11-35a9-4d03-b54e-e41fb7ee13ca
- GitHub Pages(정적 미리보기, AI 생성 비활성): https://eeeeve-star.github.io/ai-quiz-app/

`index.html`을 GitHub Pages 등 일반 정적 호스팅으로 열면 화면 UI는 보이지만, 퀴즈 생성 버튼은 "이 페이지에서 AI 퀴즈 생성을 사용할 수 없어요" 안내와 함께 비활성화됩니다.

## 파일 구성

- `index.html` — 앱 전체(단일 파일, 별도 빌드 과정 없음)
