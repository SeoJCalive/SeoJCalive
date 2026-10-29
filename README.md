<p align="center"><img src="https://capsule-render.vercel.app/api?type=waving&color=0:FFE0A3,100:F2994A&height=200&section=header&text=10%5E8%20Doggy&fontSize=58&fontColor=4A3428&fontAlignY=36&desc=%EC%84%9C%EC%9E%AC%EC%B2%A0%20%C2%B7%20Jaecheol%20Seo&descAlignY=58&descSize=20&animation=fadeIn" width="100%" alt="10^8 Doggy"></p>

<p align="center"><img src="https://readme-typing-svg.demolab.com?font=Noto+Sans+KR&weight=700&size=22&duration=2600&pause=900&color=E07A2E&center=true&vCenter=true&width=560&lines=%EB%A9%8D!%20%EC%84%9C%EC%9E%AC%EC%B2%A0%EC%9E%85%EB%8B%88%EB%8B%A4%20%F0%9F%90%BE;Woof!%20I'm%20Jaecheol%20Seo;%EB%A1%9C%EB%B4%87%20%EA%B0%95%EC%95%84%EC%A7%80(Go2)%20%EC%82%B0%EC%B1%85%EC%8B%9C%ED%82%A4%EB%8A%94%20%EC%A4%91;Teaching%20a%20robot%20dog%20to%20walk;%EB%AA%A8%EB%8D%B8%EC%9D%84%20INT8%EB%A1%9C%20%EC%A4%84%EC%9D%B4%EB%8A%94%20%EC%A4%91;Fetching%20PRs%20for%20Filee" alt="멍! 서재철입니다"></p>

<p align="center">
  국립군산대학교 소프트웨어학과 3학년 · 피지컬 AI와 엣지 AI를 만들고 측정합니다<br>
  Software undergrad at Kunsan National University · building and measuring physical & edge AI
</p>

<p align="center"><img src="https://skillicons.dev/icons?i=python,cs,dotnet,ros,kotlin,java,linux,git&theme=light" alt="Python, C#, .NET, ROS, Kotlin, Java, Linux, Git"></p>

## 🦴 Publication

**INT8 PTQ 객체 탐지에서 캘리브레이션 데이터의 객체 크기 분포에 따른 성능 영향 분석**<br>
*Performance Impact Analysis of Object Size Distribution in Calibration Data for INT8 PTQ Object Detection*<br>
**서재철**, 이석훈, 정동원, 정현준 · 한국정보기술학회 2026 하계종합학술대회 · [DBpia](https://www.dbpia.co.kr/journal/articleDetail?nodeId=NODE12901098)

> COCO 2017과 YOLO26으로 캘리브레이션 데이터의 객체 크기 분포(무작위·대형·소형·균형)를 바꿔 INT8 PTQ 성능을 비교했습니다. 치우친 분포는 특정 크기 객체의 성능을 선택적으로 떨어뜨렸고, 균형 분포는 기준선 근처에서 안정적이었습니다.<br>
> Skewed calibration sets selectively hurt specific object sizes under INT8 PTQ; a size-balanced set stays near baseline.

## 🐕 Research in progress — 로봇 강아지 산책시키기

**[go2-local-navigation](https://github.com/SeoJCalive/go2-local-navigation)** · Unitree Go2 + Jetson AGX Orin · ROS 2, SLAM Toolbox, Nav2
- 센서·TF 계약 검증부터 장애물 후보, Nav2 local costmap, SLAM 지도 생성까지 단계적으로 확장하는 자율주행 파이프라인
- AGX에서 30분 soak 테스트(46 PASS · 1 WARN), 리플레이 기반 SLAM 연속성 튜닝
- *Status: candidate* — 실주행·localization·목적지 주행은 검증 중 (physical driving & localization not yet verified)

## 🎾 Open source — 물어 온 PR들

**[Filee](https://github.com/KnifeLemon/Filee)** · Collaborator · [21 merged PRs](https://github.com/KnifeLemon/Filee/pulls?q=is%3Apr+author%3ASeoJCalive+is%3Amerged)<br>
180+ 포맷을 오프라인에서 드래그로 변환하는 오픈소스 파일 변환기 (C# / .NET) · A drag-and-drop offline file converter
- 기능: 이미지 배경 제거, 원근 보정 크롭, `.fon` 비트맵 폰트 → TTF/OTF/WOFF, Garmin FIT · iCalendar · Apple Voice Memos 읽기, macOS 백그라운드 모드
- 품질: 언어 리소스 일괄 게시로 App 테스트 CI 약 10배 단축, DDS 색상 채널 뒤바뀜 수정

## 🏠 Projects

| Project | Stack | 설명 · Description |
|---|---|---|
| [network-systems-lab](https://github.com/SeoJCalive/network-systems-lab) | Python (stdlib) · TCP/JSON | 장애 시 ACK·재시도·우회 경로를 관찰하는 교육용 네트워크 시뮬레이터 · Failover routing simulator with web UI |
| HANKAN | C# · ASP.NET · SQLite | Windows 폴더를 웹 파일 공유 공간으로 만드는 서비스. AES-256-GCM 저장 암호화, DPAPI 키 보호, 공유 만료·변조 감지 · Self-hosted file sharing with encrypted storage |

## 🐾 발자국 · Footprints

<p align="center"><img src="https://streak-stats.demolab.com?user=SeoJCalive&background=FFF8EE&border=F2C94C&ring=F2994A&fire=E07A2E&currStreakNum=4A3428&sideNums=4A3428&currStreakLabel=E07A2E&sideLabels=7A5A44&dates=9A7B66&stroke=F2C94C&date_format=Y.n.j" alt="GitHub streak"></p>

<p align="center"><img src="./profile-3d-contrib/profile-gitblue.svg" width="100%" alt="3D contribution graph"></p>

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="./profile-snake/github-snake-dark.svg">
    <img src="./profile-snake/github-snake.svg" alt="잔디 먹는 뱀 · contribution snake">
  </picture>
</p>

<p align="center"><img src="https://capsule-render.vercel.app/api?type=waving&color=0:F2994A,100:FFE0A3&height=110&section=footer" width="100%" alt=""></p>
