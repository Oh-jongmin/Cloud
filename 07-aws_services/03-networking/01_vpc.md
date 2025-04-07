# 🌐 Amazon VPC (Virtual Private Cloud)

## ✅ 개요
- AWS에서 가상 네트워크를 구성할 수 있는 서비스
- IP 범위, 서브넷, 라우팅 등을 사용자가 직접 설정

## ✅ 구성 요소
- 서브넷 (퍼블릭/프라이빗)
- IGW (인터넷 게이트웨이)
- NAT 게이트웨이, 라우팅 테이블, NACL, 보안 그룹

## ✅ 기본 명령 예시
```bash
aws ec2 create-vpc --cidr-block 10.0.0.0/16
```