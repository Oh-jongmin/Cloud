# 🏗️ 글로벌 백본 네트워크 아키텍처 (Backbone Architecture)

---

## ✅ AWS 글로벌 인프라 구성

- 리전 → AZ → 엣지 로케이션 → 로컬 존(Local Zone)
- 글로벌 트래픽 라우팅 최적화 구조

## ✅ 연결 구성도 예시

```
[사용자] → [엣지 로케이션] → [CloudFront/Accelerator] → [AZ 내 EC2, ALB 등]
```

## ✅ 고가용성 설계 팁

- 다중 AZ 배포 → 장애 격리
- Multi-Region 구성 → 재해 복구(DR) 대비
- Route 53을 통한 지능형 라우팅 가능

> 💡 글로벌 아키텍처의 핵심은 "이중화 + 위치 분산"