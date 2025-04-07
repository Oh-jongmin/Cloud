# 🗄️ Amazon RDS (Relational Database Service)

## ✅ 개요
- MySQL, PostgreSQL, MariaDB, Oracle, SQL Server 등 지원
- 자동 백업, 복제, 스냅샷, 장애 복구 등 관리형 기능 제공

## ✅ 특징
- Multi-AZ 배포, 리드 리플리카, 성능 인사이트
- 인스턴스 클래스, 스토리지 타입 선택 가능

## ✅ CLI 예시
```bash
aws rds create-db-instance --db-instance-identifier mydb --engine mysql --master-username admin --master-user-password password
```