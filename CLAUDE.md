---
active: true
status: "운영 중 — GitHub Pages 배포 및 Cloudflare DNS·HTTPS 활성화 완료"
updated: 2026-10-07
---

# why5682.me 프로젝트 안내

## 목적

`why5682.me` 루트 도메인에서 공개 연구 도구와 오픈소스 프로젝트를 소개하는
정적 GitHub Pages 허브다. 운영 백엔드는 이 저장소에 넣지 않고 각 서브도메인으로
분리한다.

## 현재 상태

- Namecheap에서 `why5682.me` 등록 완료
- GitHub Pages 사용자 사이트와 사용자 도메인 연결 완료
- Cloudflare 네임서버(`clint`, `kimora`) 활성화 완료
- Cloudflare 엣지의 `why5682.me`, `*.why5682.me` HTTPS 인증서 발급 확인
- 약제·수가·KCD 검색 서비스는 향후 `drug.why5682.me`로 연결

## 정본

- `index.html`: 공개 페이지 구조와 문구
- `styles.css`: 화면 스타일과 반응형 레이아웃
- `CNAME`: GitHub Pages 사용자 도메인
- `CHANGELOG.md`: 변경 이력

## 원칙

- 공개 가능한 도구와 공개 저장소만 링크한다.
- 연구자료, 운영 데이터, 개인 연락처, 내부 IP, API 키를 넣지 않는다.
- 외부 글꼴과 자바스크립트 의존성 없이 정적으로 동작하게 유지한다.

## 다음 할 일

- Cloudflare Tunnel을 만들어 `drug.why5682.me` 연결
- 실제 운영 서비스가 늘어나면 프로젝트 카드와 상태 문구 갱신
