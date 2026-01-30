# 명령어 참조 (CLI Reference)

LogBird에서 지원하는 모든 명령어와 옵션 목록입니다.

| 명령어 | 설명 | 주요 옵션 |
| :--- | :--- | :--- |
| `watch` | 지정한 로그 파일을 실시간 모니터링합니다. | `-f`, `--filter`, `-n` |
| `export` | 분석된 로그 데이터를 파일로 추출합니다. | `-o`, `--output`, `--format` |
| `config` | LogBird의 전역 설정(색상, 경로 등)을 변경합니다. | `--set`, `--get` |
| `version` | 현재 설치된 LogBird의 버전을 확인합니다. | - |

> **참고:** 모든 명령어 뒤에 `--help`를 붙이면 자세한 도움말을 볼 수 있습니다. (예: `logbird watch --help`)
