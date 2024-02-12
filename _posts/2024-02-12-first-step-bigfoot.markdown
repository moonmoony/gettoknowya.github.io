[용어정리]
- CI(Continuous Intergration) : 작업된 코드의 컴파일, 테스트, 패키징
- CD(Continuous Delivery) : CI된 작업물을 개발서버, 테스트서버, 운영서버 등에 배포하는 작업(수동으로 배포)
- CD(Continuous Deployment) : 상동(다만, 자동으로 전과정을 배포하는 것)
- MSA(MicroService Architecture)
- IaC(Infrastructure as Code)

[프로세스]
- Code Push
>>> git
- Continuous Build
>>> Jenkins (WAR)
- War file Deployment
>>> Apache Tomcat (WAS)
>>> docker

[plus alpha]
자동화 스크립트
jenkins CI/CD
selenium