<h1 align="center">서재철 · Jaecheol Seo</h1>
<p align="center">
  국립군산대학교 소프트웨어학과 3학년 · 피지컬 AI와 엣지 AI를 만들고 측정합니다<br>
  Software undergrad at Kunsan National University · building and measuring physical & edge AI
</p>
<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/C%23-.NET-512BD4?style=flat-square&logo=dotnet&logoColor=white" alt="C# .NET">
  <img src="https://img.shields.io/badge/ROS%202-22314E?style=flat-square&logo=ros&logoColor=white" alt="ROS 2">
  <img src="https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white" alt="Kotlin">
  <img src="https://img.shields.io/badge/Java-007396?style=flat-square&logo=openjdk&logoColor=white" alt="Java">
</p>

---

## 📄 Publication

**INT8 PTQ 객체 탐지에서 캘리브레이션 데이터의 객체 크기 분포에 따른 성능 영향 분석**<br>
*Performance Impact Analysis of Object Size Distribution in Calibration Data for INT8 PTQ Object Detection*<br>
**서재철**, 이석훈, 정동원, 정현준 · 한국정보기술학회 2026 하계종합학술대회 · [DBpia](https://www.dbpia.co.kr/journal/articleDetail?nodeId=NODE12901098)

> COCO 2017과 YOLO26으로 캘리브레이션 데이터의 객체 크기 분포(무작위·대형·소형·균형)를 바꿔 INT8 PTQ 성능을 비교했습니다. 치우친 분포는 특정 크기 객체의 성능을 선택적으로 떨어뜨렸고, 균형 분포는 기준선 근처에서 안정적이었습니다.<br>
> Skewed calibration sets selectively hurt specific object sizes under INT8 PTQ; a size-balanced set stays near baseline.

## 🔬 Research in progress

**[go2-local-navigation](https://github.com/SeoJCalive/go2-local-navigation)** · Unitree Go2 + Jetson AGX Orin · ROS 2, SLAM Toolbox, Nav2
- 센서·TF 계약 검증부터 장애물 후보, Nav2 local costmap, SLAM 지도 생성까지 단계적으로 확장하는 자율주행 파이프라인
- AGX에서 30분 soak 테스트(46 PASS · 1 WARN), 리플레이 기반 SLAM 연속성 튜닝
- *Status: candidate* — 실주행·localization·목적지 주행은 검증 중 (physical driving & localization not yet verified)

## 🛠 Open source

**[Filee](https://github.com/KnifeLemon/Filee)** · Collaborator · [21 merged PRs](https://github.com/KnifeLemon/Filee/pulls?q=is%3Apr+author%3ASeoJCalive+is%3Amerged)<br>
180+ 포맷을 오프라인에서 드래그로 변환하는 오픈소스 파일 변환기 (C# / .NET) · A drag-and-drop offline file converter
- 기능: 이미지 배경 제거, 원근 보정 크롭, `.fon` 비트맵 폰트 → TTF/OTF/WOFF, Garmin FIT · iCalendar · Apple Voice Memos 읽기, macOS 백그라운드 모드
- 품질: 언어 리소스 일괄 게시로 App 테스트 CI 약 10배 단축, DDS 색상 채널 뒤바뀜 수정

## 🧩 Projects

| Project | Stack | 설명 · Description |
|---|---|---|
| [network-systems-lab](https://github.com/SeoJCalive/network-systems-lab) | Python (stdlib) · TCP/JSON | 장애 시 ACK·재시도·우회 경로를 관찰하는 교육용 네트워크 시뮬레이터 · Failover routing simulator with web UI |
| HANKAN | C# · ASP.NET · SQLite | Windows 폴더를 웹 파일 공유 공간으로 만드는 서비스. AES-256-GCM 저장 암호화, DPAPI 키 보호, 공유 만료·변조 감지 · Self-hosted file sharing with encrypted storage |
