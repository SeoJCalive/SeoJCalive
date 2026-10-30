<p align="center"><img src="https://capsule-render.vercel.app/api?type=waving&color=0:FFE0A3,100:F2994A&height=200&section=header&text=10%5E8%20Doggy&fontSize=58&fontColor=4A3428&fontAlignY=36&desc=%EC%84%9C%EC%9E%AC%EC%B2%A0%20%C2%B7%20Jaecheol%20Seo&descAlignY=58&descSize=20&animation=fadeIn" width="100%" alt="10^8 Doggy"></p>

<p align="center"><img src="https://readme-typing-svg.demolab.com?font=Noto+Sans+KR&weight=700&size=22&duration=2600&pause=900&color=E07A2E&center=true&vCenter=true&width=560&lines=Building%20physical%20%26%20edge%20AI;Go2%20%2B%20ROS%202%20%EC%9E%90%EC%9C%A8%EC%A3%BC%ED%96%89%20%EA%B0%9C%EB%B0%9C%20%EC%A4%91;Researching%20INT8%20quantization;Filee%20%EC%98%A4%ED%94%88%EC%86%8C%EC%8A%A4%20Collaborator" alt="Building physical & edge AI"></p>

<p align="center">
  국립군산대학교 소프트웨어학과 3학년 · 피지컬 AI와 엣지 AI를 만들고 측정합니다<br>
  Software undergrad at Kunsan National University · building and measuring physical & edge AI
</p>

<p align="center"><img src="https://skillicons.dev/icons?i=python,cs,dotnet,ros,kotlin,java,linux,git&theme=light" alt="Python, C#, .NET, ROS, Kotlin, Java, Linux, Git"></p>

## 🦴 Publication
**※모든 연구는 교수님들의 자문을 받아 연구 설계, 실험, 분석 및 논문 작성 전반을 독립적으로 수행되었습니다.※**

**INT8 PTQ 객체 탐지에서 캘리브레이션 데이터의 객체 크기 분포에 따른 성능 영향 분석**<br>
*Performance Impact Analysis of Object Size Distribution in Calibration Data for INT8 PTQ Object Detection*<br>
**서재철**, 이석훈†, 정동원†, 정현준† · 한국정보기술학회 2026 하계종합학술대회 · [DBpia](https://www.dbpia.co.kr/journal/articleDetail?nodeId=NODE12901098)

> COCO 2017과 YOLO26으로 캘리브레이션 데이터의 객체 크기 분포(무작위·대형·소형·균형)를 바꿔 INT8 PTQ 성능을 비교했습니다. 치우친 분포는 특정 크기 객체의 성능을 선택적으로 떨어뜨렸고, 균형 분포는 기준선 근처에서 안정적이었습니다.<br>
> Skewed calibration sets selectively hurt specific object sizes under INT8 PTQ; a size-balanced set stays near baseline.

## 🐕 Research in progress

**[go2-local-navigation](https://github.com/SeoJCalive/go2-local-navigation)** · Unitree Go2 + Jetson AGX Orin · ROS 2, SLAM Toolbox, Nav2
- 센서·TF 계약 검증부터 장애물 후보, Nav2 local costmap, SLAM 지도 생성까지 단계적으로 확장하는 자율주행 파이프라인
- AGX에서 30분 soak 테스트(46 PASS · 1 WARN), 리플레이 기반 SLAM 연속성 튜닝
- *Status: candidate* — 실주행·localization·목적지 주행은 검증 중 (physical driving & localization not yet verified)

## 🎾 Open source

**[Filee](https://github.com/KnifeLemon/Filee)** · Collaborator · [21 merged PRs](https://github.com/KnifeLemon/Filee/pulls?q=is%3Apr+author%3ASeoJCalive+is%3Amerged)<br>
180+ 포맷을 오프라인에서 드래그로 변환하는 오픈소스 파일 변환기 (C# / .NET) · A drag-and-drop offline file converter
- 기능: 이미지 배경 제거, 원근 보정 크롭, `.fon` 비트맵 폰트 → TTF/OTF/WOFF, Garmin FIT · iCalendar · Apple Voice Memos 읽기, macOS 백그라운드 모드
- 품질: 언어 리소스 일괄 게시로 App 테스트 CI 약 10배 단축, DDS 색상 채널 뒤바뀜 수정

## 🏠 Projects

| Project | Stack | 설명 · Description |
|---|---|---|
| [network-systems-lab](https://github.com/SeoJCalive/network-systems-lab) | Python (stdlib) · TCP/JSON | 장애 시 ACK·재시도·우회 경로를 관찰하는 교육용 네트워크 시뮬레이터 · Failover routing simulator with web UI |
| HANKAN | C# · ASP.NET · SQLite | Windows 폴더를 웹 파일 공유 공간으로 만드는 서비스. AES-256-GCM 저장 암호화, DPAPI 키 보호, 공유 만료·변조 감지 · Self-hosted file sharing with encrypted storage |

## 🐾 Activity

<p align="center"><img src="https://streak-stats.demolab.com?user=SeoJCalive&background=FFF8EE&border=F2C94C&ring=F2994A&fire=E07A2E&currStreakNum=4A3428&sideNums=4A3428&currStreakLabel=E07A2E&sideLabels=7A5A44&dates=9A7B66&stroke=F2C94C&date_format=Y.n.j" alt="GitHub streak"></p>

<p align="center"><img src="./profile-3d-contrib/profile-season-animate.svg" width="100%" alt="3D contribution graph"></p>

<p align="center"><img src="https://ghchart.rshah.org/E07A2E/SeoJCalive" width="100%" alt="SeoJCalive contribution graph"></p>

<p align="center"><img src="https://capsule-render.vercel.app/api?type=waving&color=0:F2994A,100:FFE0A3&height=110&section=footer" width="100%" alt=""></p>
