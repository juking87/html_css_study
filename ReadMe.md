# 새 컴퓨터에 github에 올라와있는 내용 다운받기

1. Visual Studio Code에서 projects(프로젝트들이 들어있는 부모 폴더) 폴더 열기
2. 터미널 열기 (Ctrl+Shift+`)
3. 다음 명령어를 입력
    > git clone https://github.com/juking87/html_css_study.git

# Visual Studio Code에 유용한 git extension 설치

1. Visual Studio Code에서 좌측 사이드바에서 extension 아이콘 클릭 (Ctrl+Shift+X)
2. git extension pack 검색
3. install 클릭

# git + Visual Studio Code 에서 branch 만들기

1. Visual Studio Code 에서 좌측 사이드바에서 git 아이콘 클릭(Ctrl+Shift+G G)
2. 좌측 2사이드바 하단에 Branches 아코디언 메뉴 클릭
3. 브랜치를 생성하기(+버튼)
4. Visual Studio Code 상단에서 브랜치 이름 작성하기

# git + Visual Studio Code 에서 branch 선택하기

1. Visual Studio Code 에서 좌측 사이드바에서 git 아이콘 클릭(Ctrl+Shift+G G)
2. 좌측 2사이드바 하단에 Branches 아코디언 메뉴 클릭
3. 작업할 브랜치를 선택하기 (Switch to branch) 버튼
    > 선택된 branch 우측에 체크마크가 표시됨

# git + Visual Studio Code 에서 commit 하기 (해당 PC git에 commit)

1. 변경된 소스코드가 있어야함.
2. Visual Studio Code 에서 좌측 사이드바에서 git 아이콘 클릭(Ctrl+Shift+G G)
3. 좌측 2사이드바에 Changes 아코디언 메뉴 클릭
4. 변경사항을 확인하고 변경이 confirm된 코드의 경우 + 버튼을 눌러 staged changes 항목으로 올림
5. Message에 변경사항에 대한 간략한 정보를 입력후 Ctrl+Enter

# git + Visual Studio Code 에서 github에 push 하기

1. 해당 PC에서 변경사항이 commit 된 상태이어야함.
2. Visual Studio Code 에서 좌측 사이드바에서 git 아이콘 클릭(Ctrl+Shift+G G)
3. 좌측 2사이드바 하단에 Branches 아코디언 메뉴 클릭
4. 해당 PC에서 변경사항이 commit된 상태면 변경된 branch 에 마우스 커서를 올렸을 때 push 아이콘이 있음. 해당 아이콘 클릭

# git hub에서 Pull Request 하기

1. github에서 Pull Request 메뉴 들어가기
2. New Pull Request 누르기
3. base 와 합칠 branch 선택후 작업
4. **remote(github)** 에서 작업을 한 후에는 **<u>꼭! Visual Studio Code에서 Sync 맞춰주기!</u>**
