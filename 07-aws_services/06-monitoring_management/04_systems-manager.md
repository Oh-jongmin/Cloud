# 🧰 AWS Systems Manager

## ✅ 개요
- EC2 인스턴스 및 리소스 상태를 중앙에서 관리하는 도구

## ✅ 주요 기능
- Run Command: 에이전트 기반 명령 실행
- Parameter Store: 암호/변수 저장
- Session Manager: EC2 SSH 대체 원격 접속

## ✅ 예시
```bash
aws ssm send-command --document-name "AWS-RunShellScript" --targets ...
```

> 💡 EC2 인스턴스에 SSM Agent가 설치되어 있어야 함