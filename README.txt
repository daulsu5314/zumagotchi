쭈마고치 앱(PWA) 올리는 방법 - GitHub Pages (무료)

[1] github.com 에서 회원가입 (이메일만 있으면 돼요)
[2] 오른쪽 위 + 버튼 -> New repository
    - Repository name: zumagotchi
    - Public 선택 -> Create repository
[3] 화면 가운데 "uploading an existing file" 글자 클릭
    - 압축 푼 zumagotchi 폴더 "안의 파일들"을 전부 끌어다 놓기
      (index.html, manifest.webmanifest, sw.js, 아이콘 png 4개)
    - 아래 초록 버튼 Commit changes 클릭
[4] 위쪽 Settings -> 왼쪽 메뉴 Pages
    - Branch: main, 폴더: / (root) 선택 -> Save
[5] 1~2분 기다린 뒤 새로고침하면 위에 주소가 떠요
    https://내아이디.github.io/zumagotchi/

폰에 설치
- 안드로이드(크롬): 주소 열기 -> "앱 설치" 또는 ⋮ -> "홈 화면에 추가"
- 아이폰(사파리): 주소 열기 -> 공유 버튼 -> "홈 화면에 추가"

나중에 새 버전으로 바꿀 때
- 저장소에서 Add file -> Upload files -> 바뀐 index.html 올리기 -> Commit changes
