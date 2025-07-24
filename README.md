## Git 처음 등록 순서
1. 원하는 곳에서 우클릭 - git Bash 실행
2. `git clone https://github.com/Blche/datathon_09.git`
  <br>(자동으로 폴더가 datathon_09라는 이름으로 생성됨)
3. `cd datathon_09`

4.  "members" 폴더 안에 개인 이름으로 된 폴더 '문세희' 처럼 생성 후, 그 안에 파일 아무거나 하나 추가

5. `git add -A`

6. `git commit -m "000 작업 폴더 생성"`

7. `git push`

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

<br>
---

- 데이터 출처 : https://www.kaggle.com/datasets/mkechinov/ecommerce-events-history-in-cosmetics-shop/data
- 컬럼 설명

| 컬럼명 | 설명 |
| --- | --- |
| `event_time` | 이벤트 발생 시간 (예: 클릭, 장바구니 담기, 구매 등) |
| `event_type` | 이벤트 유형: `view`, `cart`, `remove_from_cart`, `purchase` |
| `product_id` | 제품 고유 ID |
| `category_id` | 제품이 속한 카테고리 ID (숫자이지만 카테고리 변수로 간주해야 함) |
| `brand` | 제품 브랜드 이름 |
| `price` | 제품 가격 |
| `user_id` | 사용자 고유 ID |
| `user_session` | 한 사용자의 한 번의 쇼핑 세션 (여러 이벤트가 포함될 수 있음) |
