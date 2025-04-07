# 🔐 AWS KMS (Key Management Service)

## ✅ 개요
- 데이터를 암호화할 수 있는 키를 생성 및 제어하는 완전관리형 서비스

## ✅ 기능
- 대칭 및 비대칭 키 지원
- 자동 키 교체, 키 사용 로그 (CloudTrail과 연동)
- S3, EBS, RDS 등과 통합 가능

## ✅ CLI 예시
```bash
aws kms create-key --description "Example Key"
```