# 📁 Amazon EFS (Elastic File System)

## ✅ 개요
- 여러 EC2 인스턴스 간 공유 가능한 파일 스토리지
- NFS 기반, 자동 확장

## ✅ 특징
- Linux 워크로드에 적합
- 두 가지 스토리지 클래스: Standard / IA
- EC2와 VPC 설정 필요

## ✅ 마운트 명령 예시
```bash
sudo mount -t nfs4 -o nfsvers=4.1 fs-xxxx.efs.ap-northeast-2.amazonaws.com:/ efs
```