[점검결과 보고 v28 PWA 설치 및 배포 방법]

1. GitHub 저장소(Repository)를 하나 만듭니다. (예: patrol-app)
2. 압축을 푼 아래 5개 파일을 모두 저장소 최상단에 업로드(Commit)합니다.
   - index.html
   - manifest.json
   - sw.js
   - icon-192.png
   - icon-512.png
3. 저장소 상단 [Settings] -> 좌측 [Pages] -> Branch를 main (/root)로 선택 후 [Save].
4. 1~2분 뒤 생성되는 https://아이디.github.io/저장소명/ 주소로 스마트폰(크롬 또는 삼성 인터넷)에서 접속합니다.
5. 브라우저 메뉴(⋮ 또는 ≡)에서 [앱 설치] 또는 [홈 화면에 추가]를 누르면 일반 앱처럼 아이콘이 생성되고, 오프라인 현장에서도 바로 실행됩니다.

※ 단독으로 바로 열어 쓰실 때는 index.html 파일만 클릭해도 동일하게 작동합니다.
