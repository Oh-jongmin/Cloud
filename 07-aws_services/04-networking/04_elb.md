# ⚖️ Elastic Load Balancing (ELB)

## ✅ 개요
- 여러 인스턴스 간 트래픽을 자동 분산
- 가용성 및 확장성 향상

## ✅ 유형
| 유형 | 설명 |
|------|------|
| ALB | HTTP/HTTPS, 계층 7 |
| NLB | TCP, 계층 4 |
| CLB | 이전 세대 로드 밸런서 |

## ✅ 예시 아키텍처
```
사용자 → ELB → EC2 인스턴스 (Auto Scaling 그룹)
```