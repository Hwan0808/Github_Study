# Github_Study

* 깃허브 초기 설정 명령어
<pre><code>git init : 현재 디렉토리를 Git이 관리하는 프로젝트 디렉토리로 설정하고 그 안에 레포지토리(.git 디렉토리) 생성한다.</code></pre>
<pre><code>git config user.name '이름' : 현재 사용자의 아이디를 '이름'으로 설정한다.</code></pre>
<pre><code>git config user.email '이메일' : 현재 사용자의 이메일 주소를 '이메일'로 설정한다.</code></pre>

* Staging 영역으로 파일 올리기
<pre><code>git add "파일이름" : 수정사항이 있는 특정 파일을 Staging 영역으로 올린다.</code></pre>
<pre><code>git add "디렉토리명" : 해당 디렉토리 내에서 수정사항이 있는 모든 파일들을 Staging 영역에 올린다.</code></pre>
<pre><code>git reset "파일이름" : Staging 영역에 올렸던 파일 다시 내린다.</code></pre>
<pre><code>git status : Git이 현재 인식하고 있는 프로젝트 관련 내용들 출력한다.</code></pre>
<pre><code>git commit -m "커밋메시지" : 현재 Staging 영역에 있는 파일에 대한 메세지를 추가한다.</code></pre>

* 자료 올리기
<pre><code>git push : 로컬 레포지토리의 내용을 리모트 레포지토리에 보낸다.</code></pre>

* 파일 가져오기
<pre><code>git pull : 리모트 레포지토리의 내용을 로컬 레포지토리로 가져온다.</code></pre>

* 다른사람의 파일을 내 레포지토리로 가져오기
<pre><code>git clone [프로젝트의 GitHub 상 주소] : GitHub에 있는 프로젝트를 내 컴퓨터로 가져온다.</code></pre>

* 로그 관련 명령어
<pre><code>git log : 커밋 히스토리를 출력/code></pre>
<pre><code>git log --pretty=oneline : --pretty 옵션을 사용하면 커밋 히스토리를 다양한 방식으로 출력할 수 있습니다./code></pre>
<pre><code>git show [커밋 아이디] : 특정 커밋에서 어떤 변경사항이 있었는지 확인한다./code></pre>
<pre><code>git commit --amend : 최신 커밋을 다시 수정해서 새로운 커밋으로 만든다./code></pre>
<pre><code>git config alias.[별명] [커맨드] : 길이가 긴 커맨드에 별명을 붙여서 이후로 별명으로 해당 커맨드를 실행할 수 있도록 설정한다./code></pre>
<pre><code>git diff [커밋 A의 아이디] [커밋 B의 아이디] : 두 커밋 간의 차이 비교한다./code></pre>

* 출처 link : <https://github.com/yechan-9208>
