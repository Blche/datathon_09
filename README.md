## Git 처음 등록 순서
1️⃣ 원하는 곳에서 `git clone https://github.com/Blche/datathon_09.git`
<br>(자동으로 폴더가 datathon_09라는 이름으로 생성됨)

2️⃣ members 안에 개인 이름으로 된 폴더 '문세희' 처럼 생성 후, 그 안에 파일 아무거나 하나 추가

3️⃣ `git add -A`

4️⃣ `git commit -m "000 작업 폴더 생성"`

5️⃣ `git push`

### 원하는 폴더명에 연결하고 싶은 경우
1. 폴더 원하는 이름으로 생성
2. `Git init`
3. `git remote add origin https://github.com/Blche/datathon_09.git`
4. git pull origin master
5. 2️⃣번과 동일

<br>

## Git 워크플로우 순서
1️⃣ 원격 변경사항 반영
git pull


2️⃣ 로컬 변경사항 staged
git add -A


3️⃣ 커밋 (메시지를 구체적으로)
git commit -m "설명"


4️⃣ 푸시
git push

pull이나 push에서 오류가 난다면 git push origin master의 형태로 입력
