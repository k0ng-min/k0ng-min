# 설계 · Donut Web

[개요](2022-donut-web.md) · [내 기여](2022-donut-web-contribution.md) · [사례](2022-donut-web-cases.md)

계정, 게시글, 댓글, 프로필, 결제를 각각 Django 앱으로 나눴습니다. 이렇게 나누면 한 기능을 고칠 때 다른 기능에 미치는 영향을 줄이고, 팀원이 영역을 나눠 작업하기 쉽습니다. Docker·Nginx 설정은 개발한 앱을 서버 환경에서 실행하는 구성을 다룹니다.
