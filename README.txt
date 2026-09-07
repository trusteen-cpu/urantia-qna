유란시아서 천문천답 웹앱 — 올리는 방법 (GitHub Pages)

이 폴더에는 index.html과 data.json 두 파일이 들어 있습니다.
두 파일은 반드시 같은 폴더 안에 함께 있어야 합니다.

1. github.com 에서 새 저장소(Repository)를 만듭니다.
   예: urantia-qna  (Public으로 설정, README 추가 안 해도 됨)

2. GitHub Desktop으로 그 저장소를 컴퓨터에 Clone(복제)합니다.

3. Clone된 폴더 안에 index.html, data.json 이 두 파일을 복사해 넣습니다.

4. GitHub Desktop에서 변경사항을 확인하고 Commit(커밋) → Push(푸시) 합니다.

5. GitHub 웹사이트에서 그 저장소의 Settings → Pages 로 들어갑니다.
   Branch를 main(또는 master)으로 선택하고 Save를 누릅니다.
   잠시 후 아래와 같은 주소가 생깁니다.
   https://<계정이름>.github.io/<저장소이름>/

6. 이 주소를 카카오톡에 링크로 공유하면 됩니다.
   (예: https://<계정이름>.github.io/urantia-qna/)

이후 새 질문을 추가할 때는:
- "질문 추가해줘"라고 말씀하시면서 새 질문과 답변을 채팅으로 주시면
  data.json이 갱신된 새 index.html + data.json을 다시 만들어 드립니다.
- 받으신 두 파일을 기존 저장소 폴더에 덮어쓰고 다시 Commit → Push 하면
  같은 주소에 새 질문이 자동으로 반영됩니다. (주소는 바뀌지 않습니다)
