# 👤 AWS IAM (Identity and Access Management)

## ✅ 개요
- 사용자 및 리소스에 대한 접근 제어를 설정하는 AWS의 권한 관리 서비스

## ✅ 구성 요소
- 사용자(User), 그룹(Group), 역할(Role), 정책(Policy)
- 정책은 JSON 형식으로 권한을 정의

## ✅ 정책 예시
```json
{
  "Version": "2012-10-17",
  "Statement": [{
    "Effect": "Allow",
    "Action": "s3:*",
    "Resource": "*"
  }]
}
```

## ✅ MFA, 액세스 키, 권한 경계 등 고급 기능 제공