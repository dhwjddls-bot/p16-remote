# P16 리모트

Behringer P16-M / P16-HQ 개인 모니터 믹서를 MIDI로 조작하는 웹 컨트롤러입니다.

- 주소: https://dhwjddls-bot.github.io/p16-remote/
- 파일 하나(`index.html`)로 동작합니다. 빌드 과정이 없습니다.
- 연결: 블루투스 MIDI(Web Bluetooth) 또는 MIDI 장치(Web MIDI)
- 보내는 신호: 채널 1~16 = MIDI 채널 1~16의 CC 7·10·11·21~24, 메인 = MIDI 채널 1의 CC 31~36, 본체 프리셋 = 프로그램 체인지 0~15
- 실제 장비 호환 시험은 아직 하지 않았습니다.
