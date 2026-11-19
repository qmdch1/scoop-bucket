# qmdch1 Scoop bucket

[![Tests](https://github.com/qmdch1/scoop-bucket/actions/workflows/ci.yml/badge.svg)](https://github.com/qmdch1/scoop-bucket/actions/workflows/ci.yml) [![Excavator](https://github.com/qmdch1/scoop-bucket/actions/workflows/excavator.yml/badge.svg)](https://github.com/qmdch1/scoop-bucket/actions/workflows/excavator.yml)

[Scoop](https://scoop.sh)으로 qmdch1의 Windows 도구를 설치하는 버킷입니다.

```powershell
scoop bucket add qmdch1 https://github.com/qmdch1/scoop-bucket
scoop install qmdch1/sshdesk
```

| 앱 | 설명 | 저장소 |
| --- | --- | --- |
| `sshdesk` | SSH 접속, 다중 Bastion 경유, 터널, 내부 웹 바로가기 관리 | [Gatedock](https://github.com/qmdch1/Gatedock) |
| `media-inspector` | 파일 검색, 중복 파일 찾기, 동영상 품질 검사 (ffprobe 포함) | [media-inspector](https://github.com/qmdch1/media-inspector) |
| `chronograph` | 활성 창 사용 시간 기록 | [chronograph](https://github.com/qmdch1/chronograph) |
| `pulse-ops` | 서버·DB·Redis·HTTP 관측 대시보드 (단독 실행 바이너리) | [pulse-ops](https://github.com/qmdch1/pulse-ops) |

업데이트는 `scoop update *`로 받습니다. 새 릴리스는 Excavator 워크플로가 4시간마다 확인해 매니페스트에 반영합니다.

Scoop은 브라우저를 거치지 않고 파일을 받으므로 보통 SmartScreen 경고가 뜨지 않습니다. 다만 Windows Defender 검사와 스마트 앱 컨트롤, 회사 PC의 실행 정책은 그대로 적용됩니다.
