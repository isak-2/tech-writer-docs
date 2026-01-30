# Quick Start

LogBird를 설치하고 첫 번째 로그를 분석하는 데는 1분이 채 걸리지 않습니다.

### 1. 서비스 실행
터미널에서 샘플 로그 파일을 생성하고 모니터링을 시작합니다.
$ logbird sample-start

### 2. 실시간 에러 필터링
특정 키워드(예: ERROR)가 포함된 로그만 실시간으로 출력합니다.
$ logbird watch --filter "ERROR"

### 3. 결과 내보내기
필터링된 로그를 JSON 파일로 저장하여 보고서를 준비합니다.
$ logbird export --format json --output report.json
