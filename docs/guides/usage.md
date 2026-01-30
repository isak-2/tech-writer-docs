---
layout: default
title: 사용 가이드
nav_order: 3
---
# 사용 가이드

LogBird를 활용하여 효과적으로 로그를 관리하고 분석하는 방법을 설명합니다.

### 1. 로그 파일 감시 (`watch`)
LogBird의 핵심 기능은 로그 파일을 실시간으로 추적하는 것입니다.
* **단일 파일 감시:** `logbird watch server.log`
* **특정 줄 수 지정:** `-n` 옵션을 사용하여 마지막 50줄부터 출력을 시작할 수 있습니다.
  `logbird watch server.log -n 50`

### 2. 필터링 활용하기
수만 줄의 로그 중 필요한 정보만 골라내는 방법입니다.
* **에러만 보기:** `logbird watch server.log --filter "ERROR"`
* **다중 키워드:** 대괄호를 사용하여 여러 키워드를 지정합니다.
  `logbird watch server.log --filter ["ERROR", "CRITICAL"]`

### 3. 결과 내보내기 (`export`)
분석한 로그를 파일로 저장하여 보고서에 활용할 수 있습니다.
`logbird export --output my_report.json --format json`
