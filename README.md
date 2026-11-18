# [PS1] 북두의권 세기말 구세주 전설 한글패치

플레이스테이션 **북두의권 세기말 구세주 전설**(北斗の拳 世紀末救世主伝説) 한글패치입니다. PS1 실기에서 구동하는 것을 목표로 작업했습니다.

- 블로그 소개글: https://dwyn.tistory.com/9
- 최신 버전 다운로드: [Releases](../../releases/latest)
- 버그 제보: [Issues → 버그 제보](../../issues/new/choose)
- 후원: https://litt.ly/dwyn

## 작업 사항 및 변경 이력

주요 작업 사항, 추가 기능, 변경 이력 등 자세한 내용은 **[블로그](https://dwyn.tistory.com/9)** 글을 참조해 주세요.

## 적용 방법

1. [Releases](../../releases/latest)에서 패치 파일을 받습니다.
2. 직접 가지고 계신 원본 이미지의 **Track 1 bin 파일**에 패치를 적용합니다.
   - PC 프로그램: Delta Patcher, xdelta UI 등 (파일이 커서 웹 패처보다 PC 프로그램을 권장합니다)
3. Track 2 bin과 cue 파일은 그대로 둡니다. 패치된 Track 1 파일 이름을 바꿨다면 cue 파일 안의 Track 1 파일 이름도 같이 고쳐 주세요.
4. cue 파일을 에뮬레이터로 열거나, 실기용으로 굽거나 ODE에 넣어 실행합니다.

### 체크섬 확인

패치는 **일본판 원본 Track 1 bin**(659,056,272바이트)에 적용해야 합니다. 패치 후 Track 1은 696,916,416바이트로 커집니다.

| 구분 | CRC32 | MD5 | SHA1 |
|---|---|---|---|
| 원본 Track 1 (일본판) | `79E9FC16` | `08665DB1BAD0D01D9BCE03E13EAB05BB` | `1F9B064CEAFEF91641BB3BBCC075A604F478489E` |
| 패치 후 Track 1 (v0.95, 696,916,416바이트) | `187F43DD` | `D4694A04B7E854845E4F0D854D73512C` | `2312DD6EC5EE0F9883A39757E1FF881F831AFAF8` |

- 원본 파일 이름: `Hokuto no Ken - Seikimatsu Kyuuseishu Densetsu (Japan) (Track 1).bin`
- Track 2(오디오 트랙)는 패치하지 않습니다.

> 이 저장소에는 패치 파일만 있습니다. 게임 이미지나 패치를 적용한 이미지는 배포하지 않으며, 요청에도 응하지 않습니다.
