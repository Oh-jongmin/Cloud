# 📦 Amazon EBS (Elastic Block Store)

## ✅ 개요
- EC2에 연결하는 블록 스토리지
- SSD/HDD 유형 존재, 스냅샷 가능

## ✅ 볼륨 유형
| 유형 | 특징 | 용도 |
|------|------|------|
| gp3 | 범용 SSD | 기본 워크로드 |
| io2 | 고속 IOPS | DB, 성능 필요 |
| sc1 | Cold HDD | 백업 등 비정기 접근 |

## ✅ 실습 예시
```bash
aws ec2 create-volume --availability-zone ap-northeast-2a --size 10 --volume-type gp3
```