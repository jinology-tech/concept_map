# 개념 배치·분류·연결 도구 (GitHub Pages)

이 저장소는 단일 `index.html`만으로 동작합니다.

## 배포 방법 (GitHub Pages)
1. GitHub에서 새 저장소를 만듭니다. 예) `concept-map`
2. 이 저장소에 `index.html` 파일을 업로드(커밋)합니다.
3. 저장소 **Settings → Pages** 로 이동하여:
   - **Source**: `Deploy from a branch`
   - **Branch**: `main` / `/ (root)` 선택 후 **Save**
4. 몇 초 후 **Pages** 섹션에 배포된 URL이 표시됩니다. 보통 `https://<username>.github.io/<repo>/`

## 사용 방법
- 좌측 목록의 **개념**을 우측 스테이지로 드래그하면 노드가 생성됩니다. (개념은 1회 사용)
- **연결 모드**를 켜고 노드 두 개를 차례로 클릭하면 **라벨**을 입력해 연결선을 만들 수 있습니다.
- 연결/노드를 선택 후 **Delete** 키 또는 상단 버튼으로 삭제 가능합니다.
- **JSON 내보내기**로 현재 배치/연결을 파일로 저장할 수 있습니다.

## 문제 해결
- GitHub Classroom/Drive의 **미리보기**는 보안상 스크립트가 막혀 동작하지 않을 수 있습니다. **Pages URL**을 링크로 공유하세요.
- 선이 안 보이면 새로고침 후 다시 시도하고, 브라우저는 Chrome 최신 버전을 권장합니다.
