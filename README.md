## [UNITY 3D] BonfireSimulator
## 1. 소개
<img width="2560" height="1440" alt="10" src="https://github.com/user-attachments/assets/94f11586-9a08-47b2-8c3a-55f8a621cc3a" />
<img width="2560" height="1440" alt="6" src="https://github.com/user-attachments/assets/82b1b27f-8ccf-4dbe-89eb-773e156e83e1" />
<img width="1920" height="1080" alt="2026-03-19 17 31 40" src="https://github.com/user-attachments/assets/bab430af-66fa-48b2-a8a8-70063c948f86" />

- Unity Built-in Render Pipeline 으로 제작된 3D시뮬레이션 게임입니다.
- 모닥불에 연소재를 넣고 태우면 화력을 감지하여 불이 옮겨붙고 점수를 획득하는 방식입니다.
- 무작위로 생성되는 불씨를 모아 모닥불을 강화하고 다양한 콘텐츠를 해금할 수 있습니다.
- 기획자, 디자이너 없이 개발한 1인개발 프로젝트입니다. 필요한 리소스는 에셋스토어, AI를 활용하였습니다.

## 2. 개발환경
- UNITY 2020.3.15f2 / Built-in Render Pipeline / C#
- Visual Studio 2022
- Windows 10
- 2025.01 ~ 2026.04 (16개월)

## 3. 사용기술
- 디자인 패턴 : Single Tone 패턴으로 매니저 관리
- Object Pooling : 연소재를 포함한 생성되는 객체를 풀링
- Save : 데이터를 json으로 변환화여 저장
- Steam API : 스팀연동 및 업적, 리더보드 구현
- PostProcessing : 앰비언트 오클루전 및 뎁스 오브 필드 사용, 후처리

## 4. 기능구현
- 불이 붙는 오브젝트 : Ignis - Interactive Fire 에셋사용
    연소재로 설정된 오브젝트에 불이 붙고 옮겨붙는 매커니즘과 비주얼 이펙트를 사용하였습니다.
- 연소 완료된 오브젝트 파괴 : RayFire for Unity - Obsolete 에셋사용
    연소가 종료된 오브젝트가 조각나 파괴되며 텍스쳐를 변경합니다.
- 인게임 이벤트
    세션별 환경에 맞는 고유 이벤트를 맵별 7종씩 구현하였습니다.
- 번역
    자체 스크립트로 한국어와 영어 세팅에 따라 텍스트가 번역되도록 제작하였습니다.

## 5. 플레이영상
- 공식영상: https://youtu.be/fBikegZzxp0?si=7YVe6WWaxVvqXpH2
- https://youtu.be/0hD4RGMVt0I?si=RXO2B32bZbqi4WII
- https://youtu.be/WxlNr_-e1V0?si=6D4gd2wi31g_lXJD

## 6. 링크
- https://store.steampowered.com/app/3920940/_/
