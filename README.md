# 자전거갈까 (bikego)

서울 따릉이 위치 기반 대여소 현황 앱.  
대여 가능 대수 + 반납 가능 칸수 실시간 표시.

## GitHub Pages 배포

1. 이 레포 → Settings → Pages
2. Source: Deploy from branch
3. Branch: main / (root) → Save
4. `https://유저명.github.io/bikego` 로 접속

## API 연결 (프록시 확정 후)

`index.html` 상단 CFG에서:
```js
USE_REAL_API: true,
API_URL: "https://프록시주소/api/bike",
```
