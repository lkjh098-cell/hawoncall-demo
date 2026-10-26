# Pleos 화면 구성 참조 · v0.9

현대자동차그룹의 2026-04-30 Pleos Connect 공개 자료와 Pleos Playground의 Display Layout을 보고 시연 화면의 구조를 다시 구성했습니다. 공식 지도·소스·차량 OS를 가져온 결과물이 아닙니다.

- 공식 공개 자료: https://www.hyundaimotorgroup.com/ko/news/hyundai-motor-group-redefines-in-vehicle-experience-with-pleos-connect-next-generation-infotainment-system
- 공식 화면 배치 가이드: https://document.pleos.ai/docs/connect/guide/docs-design/getting-started/layout
- 참조한 공식 내비 이미지: https://www.hyundaimotorgroup.com/image/upload/asset_library/MDA00000000000078920/00b8ec3b0fe040b0a61fb7e0519ef74c.jpg
- 공식 분할 앱 화면: https://www.hyundaimotorgroup.com/image/upload/asset_library/MDA00000000000078921/075262c30f4e4e899c9bea676bf152fd.jpg

확인한 구성은 상단 상태바, 좌측 주행 정보, 우측 애플리케이션 창, 하단 공조·앱 GNB입니다. 내비의 목적지·ETA·회전 안내는 지도 위의 작은 플로팅 모듈이며, 하원콜은 이 지도에 붙는 작은 보조 앱으로 제안했습니다.

지도 지리와 저장된 서울 경로는 실제 자료입니다. 별도 차량 주행 뷰의 차선·주변 차·속도·기어와 보호자 상태는 가상 시연입니다. 표시는 차량의 실제 ADAS 인식·제어 기능이 아닙니다. 공식 이미지 자체를 시연 배경이나 지도 데이터로 사용하지 않습니다.

## v1.2 앱 탐색 및 공조 패널

2026-10-26에 다음 공식 가이드의 실제 탐색 링크를 확인했습니다.

- [Global Navigation Bar](https://document.pleos.ai/docs/connect/guide/docs-design/components/gnb): 차량 설정, 공조 패널의 열기/닫기, 앞·뒤 유리 성에 제거, 고정 내비게이션, 앱 라이브러리와 앱 진입을 참조했습니다.
- [App library](https://document.pleos.ai/docs/connect/guide/docs-design/components/app-library): 상단 차량 제어, 구분선, 하단 앱 격자 구조를 참조했습니다. 넓은 화면에서 최대 7열을 사용하고 좁은 시연 화면에서는 열 수를 줄입니다.
- [Display Layout](https://document.pleos.ai/docs/connect/guide/docs-design/getting-started/layout): 주행뷰·상태바·GNB를 유지한 채 우측 앱 창을 전환하는 구성을 따릅니다.

음악·라디오·전화·차량 설정·공조·앱 라이브러리는 시연용 로컬 화면입니다. 음악과 라디오는 음원 없이 재생/정지 상태와 선곡을 체험하며, 전화는 가상 연락처와 키패드 미리보기만 제공합니다. 공조의 온도·풍량·열선·성에 제거 설정은 실제 차량과 연결되지 않습니다. ‘오늘 일정 음성’은 하원콜의 기존 일정 안내창으로 연결됩니다. 내비게이션과 하원콜로 돌아와도 기존 경로 진행 상태를 유지합니다.

공식 양산 OS 화면이나 공식 앱을 실행한 결과가 아니며, 공식 디자인의 픽셀 단위 복제를 주장하지 않습니다. 가로형 브라우저 시연에 맞춘 독립적인 화면 재현입니다.
