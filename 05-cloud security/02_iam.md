# 👤 IAM (Identity and Access Management)

---

## ✅ IAM 주요 개념

- **User**: 로그인 가능한 개별 계정
- **Group**: 사용자 집합, 공통 권한 부여
- **Role**: 일시적 권한 위임을 위한 엔티티
- **Policy**: JSON 문법의 권한 정의 문서

---

## 🔒 IAM 정책 예시

```json
{
  "Version": "2012-10-17",
  "Statement": [
    {
      "Effect": "Allow",
      "Action": "s3:*",
      "Resource": "*"
    }
  ]
}
```

- 모든 S3 리소스에 대해 전체 권한 허용

## ✅ MFA (다중 인증)

- 사용자 계정 보호 강화
- AWS Console, CLI 모두 적용 가능