# AWS EC2 Express Server Deployment

이 프로젝트는 AWS EC2(Ubuntu) 환경에서 Node.js와 Express를 활용하여 웹 서버를 구축하고, **PM2**를 통해 백그라운드 프로세스로 안정적으로 배포 및 관리하는 방법을 실습하기 위한 예제 저장소입니다.

## 🚀 기술 스택 (Tech Stack)
* **Runtime:** Node.js (v22+)
* **Framework:** Express
* **Process Manager:** PM2
* **OS:** Ubuntu 24.04.5 LTS (AWS EC2)

---

## 🛠️ 시작하기 (Getting Started)

서버 환경에서 프로젝트를 클론하고 실행하는 과정입니다.

### 1. 저장소 클론 및 패키지 설치
```bash
git clone [https://github.com/JSCODE-BOOK/aws-ec2-express.git](https://github.com/JSCODE-BOOK/aws-ec2-express.git)
cd aws-ec2-express
npm install
