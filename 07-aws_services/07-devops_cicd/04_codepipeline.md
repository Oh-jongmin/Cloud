# 🔁 AWS CodePipeline

## ✅ 개요
- 전체 CI/CD 파이프라인 자동화
- 소스 → 빌드 → 테스트 → 배포 흐름 구성 가능

## ✅ 특징
- 이벤트 기반 실행 (예: Git push 시 자동 트리거)
- 각 단계는 CodeCommit/Build/Deploy 연동

## ✅ 예시 아키텍처
```
[CodeCommit] → [CodeBuild] → [CodeDeploy] → [배포 완료]
```

## ✅ CLI 예시
```bash
aws codepipeline create-pipeline --cli-input-json file://pipeline.json
```