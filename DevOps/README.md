# DevOps

## DevOps 시작하기

### DevOps의 필요성

- 2008년 애자일 컴퍼런스에서 앤드루 클레이 쉐이퍼와 패트릭 드부와가 "Agile Infrastructure"에 대해 논의하며 사용
- **소통, 협업, 통합 및 자동화를 강조하는 소프트웨어 개발 방법론**
- 개발과 운영이 상호의존적으로 대응해야함
- 개발과 운영사이의 역할

툴체인

- Jira
- Confluence
- Bitbucket
- Jenkins

업무환경(클라우드)

- CLOUD server(EC2, S3, RDS) -> AWS
- DOCKER

### Jira, Confluence

개발 프로세스

코드 -> 빌드 -> 테스트 -> 패키지 -> 릴리즈 -> 모니터링 -> 코드 (반복)

### AWS와 Docker의 필요성

AWS(클라우드 서버 구축 서비스)

- 전통적 IDC(International Data Corporation)
- 점차 클라우드 서비스 중요도 증가

Docker(오픈소스 컨테이너 프로젝트로 만들어진 도커)

- 간단한 프로젝트 도커로 만들기
- 프로젝트 환경 스택(Jva, RDS, Maven, Spring Boot, Spring Security, S3(이미지))
- 카카오 로그인 + 오프라인 후기 서비스 -> 도커 관리

#### AWS의 장잔점

장점

- 탄력적인 웹 규모 컴퓨팅
- 다양한 Command(API) 제공
- 유연한 클라우드 호스팅 서비스
- 통합
- 안전성
- 보안

단점

- 베어 메탈 성능을 원할 때
- 웹페이지가 몇개뿐일때
- 솔루션에 적합
- 가격

#### AWS의 종류

- Server : EC2(Elastic Compute Cloud), Lambda, VPC(Virtual Private Cloud)
- Storage : S3, EBS(Elastic Block Store)
- Database : RDS, DynamoDB, RedShift, AuroraDB
- Management : Cloud Watch
- Analysis : Kinesis

#### Docker의 장점

- 실행시점에 상관없이 구성시점을 고를 수 있음(눈송이 서버)
  - 버젼 관리 차원에서 동시에 배포가 가능 (이미지화)
  - 눈송이 서버 : 서버가 많아질때 각 서버별로 버젼이 상이함 -> 이미지를 똑같이 컨테이너에 배포하게 되면 많은 문제를 해결할 수 있음
- 개발 프로그램 설치와 삭제가 용이함
  - Java, mysql, oracle, elk, nginx 등 서버 프로그램 설치와 삭제가 용이함
- 운영체제 도커 실행 소스 일관성, 유연함
  - 초기 인프라 환경 설정은 복잡하나 어려움, 쉽고 일관성이 있게 만들어줌
- 이미지 용량이 크게 줄어듬
  - 도커는 리눅스 컨테이너를 사용함
- 여러군데 배포할 수 있는 확장성
  - GITHUB와 비슷, Push/Pull이 용이

<br/>

## 협업 툴.

[공식 Doc](https://www.atlassian.com/ko)

- [ATLASSIAN]
- [JIRA]

Cloud Server(AWS) <-> Docker <-> Jira Software

지라도 API 지원 (이슈 삭제 및 생성 등의 기능 지원)

- [Jira API Document](https://docs.atlassian.com/software/jira/docs/api/REST/7.6.1/)

## 스프링 프로젝트 세팅

## BitBucket

## Jenkins 소개 및 세팅

## AWS Server
