# 한방 격투

브라우저에서 바로 하는 3D 종합격투 게임. `index.html`을 웹 서버(GitHub Pages 등)로 열면 된다.

- 조작: 조이스틱/WASD 이동, J 잽, K 스트레이트, L 보디훅, I 킥, 스페이스 가드, U 스텝, O 필살기, C 시점
- 퍼펙트 가드: 맞기 직전에 가드를 올리면 피해 없이 막고 상대가 휘청인다
- 필살기: 때리고 맞고 막으면 게이지가 찬다. 다 차면 가까이서 회오리 연타, 멀리서 슈퍼맨 펀치
- 혼자 하기: 세 명을 차례로 꺾는 3라운드 경기
- 친구 대전: 같은 방 번호(4자리)를 넣으면 일대일로 붙는다 (PeerJS 무료 연결 서버 사용, 둘 다 이 페이지를 열어 둬야 함)

## 에셋

선수 모델과 동작은 Quaternius의 Universal Base Characters, Universal Animation Library 1·2 (CC0)를 가공해 썼다.
`fighter.txt`, `a1.txt`, `a2.txt`는 GLB 파일을 base64 글자로 바꾼 것이다.
