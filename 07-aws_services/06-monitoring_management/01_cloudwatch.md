# 📊 Amazon CloudWatch

## ✅ 개요
- AWS 리소스 및 애플리케이션의 로그, 지표, 이벤트 모니터링
- 실시간 대시보드, 경보(Alert), 자동화 작업 가능

## ✅ 주요 기능
- 지표(Metrics), 로그(Log Groups), 대시보드(Dashboards)
- CloudWatch Alarm → SNS → 자동 대응

## ✅ CLI 예시
```bash
aws cloudwatch put-metric-alarm --alarm-name HighCPU --metric-name CPUUtilization ...
```