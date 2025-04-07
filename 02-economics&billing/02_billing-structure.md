# 📦 AWS 요금 구조 이해

---

## ✅ AWS 과금 방식

- 대부분의 서비스는 `pay-as-you-go` 모델
- 시간/초 단위 요금: EC2, Lambda, RDS
- 저장 용량 기반 요금: S3, EBS

## ✅ 요금 구성 요소 예시 (EC2)

| 항목 | 설명 |
|------|------|
| 인스턴스 타입 | vCPU / RAM 기준 |
| OS | Linux vs Windows 요금 차이 |
| 스토리지 | EBS 타입, 용량 |
| 네트워크 | 아웃바운드 트래픽 |

## ✅ 비용 도구

- AWS Cost Explorer
- Billing Dashboard
- 예산 알림 (Budgets)