# 프로젝트 Git 커밋 컨벤션

이 문서는 프로젝트에서 사용하는 Git 커밋 컨벤션에 대해 설명합니다.

# 커밋 메시지 구조

커밋 메시지는 다음과 같은 구조로 작성합니다.

```
<타입>: <메시지>
```

타입(Type): 커밋의 유형을 나타내며 다음 중 하나를 선택합니다.

- feat: 새로운 기능 추가
- fix: 버그 수정
- docs: 문서 변경
- !HOTFIX: 치명적인 버그수정
- style: 코드 포맷팅, 세미콜론 누락 등 스타일 변경
- refactor: 코드 리팩토링
- test: 테스트 코드 추가 또는 수정
- chore: 빌드 스크립트, 패키지 매니저 설정 등의 변경
- etc: 그 외 기타 변경사항
- 메시지(Message): 변경 사항에 대한 간결하고 명확한 설명을 작성합니다.

## 예시

다음은 커밋 메시지 작성의 예시입니다.

- feat: Add user registration feature
- fix: Fix null pointer exception in API endpoint
- docs: Update project documentation

## 추가적인 가이드라인

- 커밋은 가능한 작은 단위로 나누어 작성합니다. 각 커밋은 한 가지 주제에 집중해야 합니다.
- 커밋 메시지는 명령문 형식으로 작성합니다.
