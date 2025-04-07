# 🛠️ AWS CodeBuild

## ✅ 개요
- 빌드 및 테스트 자동화 서비스
- GitHub, CodeCommit 등과 연동 가능

## ✅ 특징
- `buildspec.yml`로 빌드 명령 정의
- Docker 기반 실행 환경
- 시간당 과금 (초 단위)

## ✅ buildspec 예시
```yaml
version: 0.2
phases:
  build:
    commands:
      - echo Build started
```