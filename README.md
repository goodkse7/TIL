# TIL

## 2022-09-21

### 리눅스 커맨드라인 기초
```
pwd //print working directory
```
```
cd //change directory
cd .. : 현재 폴더 기준으로 상위 디렉토리로 이동
```
```
ls //list
```
- ls 뒤에는 -a나 -l 옵션을 붙일 수 있음
- -a : 숨김파일도 보여줌
- -l : 상세정보를 보여줌  


### Vim 사용법 기초
#### Vim 명령어로 텍스트 파일을 만들고 수정해주자.
```
vim 123.txt // 123이 제목인 텍스트 파일을 생성
```
1. vim 에디터를 처음 키면 명령모드로 진입하기 때문에 입력을 할 수 없다. -> 입력하려면 입력모드로 바꿔야 한다.
2. 입력모드로 진입하려면 i키 (insert)등을 누른다.
3. 입력이 다 끝나고 저장 등의 명령을 컴퓨터에게 내리려면 명령모드로 다시 돌아가야 함
  - 명령모드로 바꾸려면 키보드에서 `esc`키를 누름
  - 명령모드에서 `:w`를 입력하고 `enter`키를 누르면 저장만 됨(write)
  - `:wq`를 입력하면 저장하고 에디터에서 빠져나올 수 있음(write and quit)
  - `:q`를 입력하면 에디터에서 빠져나올 수 있음(quit)

위와 같은 명령어로 텍스트 파일 뿐만 아니라 프로그래밍 언어 파일도 편집 가능하다.

### commit
#### 정의
  - The "commit" command is used to save your changes to the local repository.
  - 커밋 하나는 독립적인 버전을 나타냄
  - The git commit command captures a snapshot of the project's currently staged changes.
  - 스냅샷(사진)과 유사

#### 언제 커밋을 만드는가
  - logical한 변경이 있을때 커밋을 하나 만듬
  - 가능하면 커밋 단위는 작을 수록 좋음

### gitignore
- 프로젝트의 불필요한 환경설정 파일들이 깃에 포함되지 않도록 하는 것
- gitignore generator를 이용하여, 내가 쓴 언어와 운영체제, 텍스트 에디터 등 맞는 것을 검색해서 생성한다.
- 모든 저장소에는 gitignore 파일이 존재해야 한다!
