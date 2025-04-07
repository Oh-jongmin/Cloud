# 🗃️ AWS CodeCommit

## ✅ 개요
- AWS에서 제공하는 Git 기반 소스 코드 저장소
- GitHub, GitLab과 유사하지만 AWS IAM과 통합됨

## ✅ 특징
- 무제한 리포지토리 및 파일 저장
- IAM으로 권한 제어
- AWS 리전 내 저장 → 보안 강화

## ✅ CLI 예시
```bash
aws codecommit create-repository --repository-name my-repo
```