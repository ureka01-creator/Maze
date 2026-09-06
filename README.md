# 구슬 미로 v0.2.0

기울기로 조작하는 모바일 HTML Canvas 게임. HTTPS에서 index.html 실행 후 시작하기로 센서와 오디오를 활성화합니다.

- 500×1500 월드, 구슬을 따라가는 세로 카메라
- 구멍 함정 12개, 낙하 후 출발점 복귀 (시간과 실패 횟수 유지)
- 중심 맞추기, 처음부터, 백그라운드 일시정지
- 실제 구슬 녹음 기반 속도별 구르기와 충돌음

## 소리 출처
모두 CC0. 공개 MP3 프리뷰를 받아 모노 변환, 구간 편집, 페이드 및 음량 조정 후 audio-recordings.js에 포함했습니다. 런타임 외부 다운로드 없음.
- Solar01, Glass Marbles Rolling on Wood.wav: https://freesound.org/people/Solar01/sounds/661650/ (1.05초부터 3.15초 구간)
- Ryanz-Official, Marble Impact: https://freesound.org/people/Ryanz-Official/sounds/639754/ (0.065초부터 0.19초 구간)
- 라이선스: https://creativecommons.org/publicdomain/zero/1.0/

## 검증
JavaScript 문법, 벽 관통 방지, 전체 맵 완주, 함정 회피 경로, 낙하와 복귀, 초기화 시뮬레이션 통과. 실제 모바일 청취와 센서 실기기 검증은 미수행.
