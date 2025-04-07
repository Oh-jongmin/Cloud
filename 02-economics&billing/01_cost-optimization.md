# 💰 비용 최적화 (Cost Optimization)

---

## ✅ 불필요한 리소스 제거

- 사용하지 않는 EC2, RDS, EBS, Elastic IP 등 정리
- CloudWatch 알림, 자동 종료 스크립트 활용

## ✅ 예약 인스턴스 활용

- 1년 또는 3년 단위 예약 구매로 비용 최대 75% 절감 가능
- `EC2 Reserved Instances`, `Savings Plans` (AWS 기준)

## ✅ 스팟 인스턴스 사용

- 최대 90% 할인된 요금
- 비중요 워크로드나 테스트에 적합

## ✅ Auto Scaling + ELB

- 수요에 따라 인스턴스 자동 조절 → 낭비 최소화