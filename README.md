# 강호생존기 (江湖生存記)

사방에서 몰려드는 적을 베고 살아남는 무협 로그라이크 웹 게임입니다.
브라우저에서 바로 실행되며 설치가 필요 없습니다.

## 플레이
- 이동: WASD / 방향키 (모바일은 화면을 누른 채 끌기)
- 공격: 자동
- 경공(앞으로 도약): Space 또는 오른쪽 아래 버튼
- 필살기: E 또는 경공 위 버튼 (기 게이지가 가득 차면)
- 일시정지: Esc

## 랭킹 서버 연결 (선택)
랭킹은 Supabase에 저장됩니다. `index.html`에서 아래 두 줄의 따옴표 안에
Supabase 프로젝트 값을 넣으면 공용 랭킹이 켜집니다. 비워 두면 각 기기에만 최고 점수가 저장됩니다.

```js
const SB_URL='';   // Project URL
const SB_KEY='';   // anon public 키
```

## 크레딧
- 캐릭터·타일 그래픽: [Ninja Adventure Asset Pack](https://pixel-boy.itch.io/ninja-adventure-asset-pack)
  by pixel-boy & AAA — CC0 라이선스, 재채색·수정하여 사용
- 그 외 아이템 아이콘, 늑대·박쥐 도트, 게임 코드: 자체 제작
