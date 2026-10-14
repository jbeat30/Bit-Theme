# 공개 배포 저장소 브랜치 규칙

- `main`은 `release/vX.Y.Z`에서 보내는 PR로만 변경합니다. `hotfix/*`에서 `main`으로 보내는 PR도 허용하지 않습니다.
- 작업 브랜치 → `feature/vX.Y.Z`는 Squash로 머지합니다.
- `feature/vX.Y.Z` → 같은 버전의 `release/vX.Y.Z` → `main`은 Merge commit으로 머지합니다.
- `main` → `feature/*`, `release/*` 백머지는 Merge commit으로 머지합니다.
- `main`, `feature/v*`, `release/v*`는 직접 push, force push, 삭제를 금지합니다.
- PR은 `branch-policy / check` 통과가 필수이며, 리뷰 승인은 요구하지 않습니다. Owner를 포함한 우회 계정은 없습니다.
- 커밋·PR 제목은 `타입: 한국어 설명` 형식을 사용하고 AI 서명을 넣지 않습니다.
- 외부 기여는 포크에서 작업 브랜치를 만든 뒤 해당 버전의 feature 브랜치로 PR을 보내세요.

이 저장소는 공개 저장소입니다. GitHub의 공개 저장소는 누구나 열람·다운로드·클론·포크할 수 있으며, 클론을 금지하고 포크만 허용하는 접근 설정은 없습니다. 사용·수정·재배포 조건은 루트의 `LICENSE`를 따릅니다.
