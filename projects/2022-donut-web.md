# Donut Web

[← 프로필로](../README.md) · [원본 저장소](https://github.com/k0ng-min/2022-likelion-donut-web)

**상세 읽기:** [내 기여](2022-donut-web-contribution.md) · [설계](2022-donut-web-design.md) · [기여 사례](2022-donut-web-cases.md)

## 프로젝트 소개

계정·게시글·댓글·프로필·결제 기능을 Django 앱 단위로 나눈 팀 웹 프로젝트입니다. Docker와 Nginx 설정도 함께 포함돼 있어 애플리케이션과 배포 구성을 함께 다룹니다.

## 설계 관점

도메인별 Django 앱을 나누고, 게시글 목록·카테고리·검색/필터·지도·계정 흐름을 조합하는 방식으로 확장 가능한 서비스 구조를 시도했습니다.

## 내 기여 평가

**근거 수준: 중간.** GitHub 계정 연결이 없는 `경민` 작성자와 `kyeongmin` 브랜치의 다수 커밋이 공개 이력에 남아 있어 기여 정황은 확인됩니다. 다만 계정 연결이 없어 정확한 커밋 수를 개인 성과로 제시하지 않고, 확인 가능한 작업 사례만 적습니다.

## 대표 기여 사례

- [회원가입·로그인 뷰 추가](https://github.com/k0ng-min/2022-likelion-donut-web/commit/a16216e): 가입과 로그인 흐름을 위한 뷰 작업 기록이 남아 있습니다.
- [필터 기능 작업](https://github.com/k0ng-min/2022-likelion-donut-web/commit/39b4cfb): 목록 탐색을 위한 필터 구현 이력이 확인됩니다.
- [게시글 목록 작업](https://github.com/k0ng-min/2022-likelion-donut-web/commit/101b78f): 콘텐츠 목록 화면을 다룬 기록이 남아 있습니다.

## 포트폴리오에서 보여줄 역량

서비스를 계정·콘텐츠·프로필처럼 도메인 단위로 나누고, 팀 브랜치 협업과 병합을 경험한 초기 웹 개발 프로젝트입니다.
