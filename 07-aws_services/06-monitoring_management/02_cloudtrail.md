# 📝 AWS CloudTrail

## ✅ 개요
- AWS 계정 내 API 호출 기록을 로그로 저장
- 누가, 언제, 어떤 서비스를 호출했는지 추적 가능

## ✅ 활용 예
- 보안 감사
- 계정 활동 추적
- 이벤트 알림 연동 (SNS, Lambda 등)

## ✅ 저장 방식
- 기본적으로 90일 동안 이벤트 보기 가능
- S3 버킷에 로그 저장 가능

## ✅ CLI 예시
```bash
aws cloudtrail create-trail --name myTrail --s3-bucket-name my-trail-logs
```