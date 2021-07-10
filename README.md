![header](https://capsule-render.vercel.app/api?type=waving&height=140&text=Pest%20Plan&fontColor=ffffff&fontAlignY=40)

<p align="center">
    <img src="https://img.shields.io/badge/Python-3766AB?style=flat-square&logo=Python&logoColor=white"/></a>
    <img src="https://img.shields.io/badge/Java-007396?style=flat-square&logo=Java&logoColor=white"/></a>
    <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=JavaScript&logoColor=white"/></a>
    <img src="https://img.shields.io/badge/Kafka-231F20?style=flat-square&logo=Apache%20Kafka&logoColor=white"/></a>
    <img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=React&logoColor=white"/></a>
    <img src="https://img.shields.io/badge/NestJs-E0234E?style=flat-square&logo=NestJs&logoColor=white"/></a>
    <img src="https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=MongoDB&logoColor=white"/></a>
    <img src="https://img.shields.io/badge/MariaDB-003545?style=flat-square&logo=MariaDB&logoColor=white"/></a>
</p>

<br/>

## About

주제: _빅데이터 분석에 의한 IoT 트랩 모니터링 시스템 구축_  
기간: _2020년 6월 29일 ~ 2021년 6월 2일_

기존 Redis를 사용하여 패킷데이터들을 처리하는 방법은 효율성과 확장성이 떨어진다는 문제가 있습니다. Kafka를 이용하여 이러한 문제들을 해결하고 나아가 웹페이지를 통한 시각화까지 진행하였습니다.

<br/>

## Architecture

<p align="center">
    <img src="https://github.com/PestPlan/document/blob/master/images/architecture.PNG?raw=true" height=370>
</p>

<br/>

## Repository

### [document](https://github.com/PestPlan/document)

각종 문서를 저장합니다.

### producer <img style="vertical-align: middle;" src="https://img.shields.io/badge/-private-gray">

패킷을 분석하고 카프카 클러스터로 전송합니다.

### [consumer (deprecated)](https://github.com/PestPlan/consumer) <img style="vertical-align: middle;" src="https://img.shields.io/github/languages/top/PestPlan/consumer?logo=java&logoColor=E11F21&color=E11F21"> <img style="vertical-align: middle;" src="https://img.shields.io/github/license/PestPlan/consumer">

카프카 클러스터에 저장된 패킷을 읽어옵니다.

### [consumer-MongoDB](https://github.com/PestPlan/consumer-MongoDB) <img style="vertical-align: middle;" src="https://img.shields.io/github/languages/top/PestPlan/consumer-MongoDB?logo=python&logoColor=4280B2&color=4280B2"> <img style="vertical-align: middle;" src="https://img.shields.io/github/license/PestPlan/consumer-MongoDB">

카프카 클러스터에 저장된 패킷을 MongoDB에 저장합니다.

### [web-frontend](https://github.com/PestPlan/web-frontend) <img style="vertical-align: middle;" src="https://img.shields.io/github/languages/top/PestPlan/web-frontend?logo=javascript&color=F7DF1E"> <img style="vertical-align: middle;" src="https://img.shields.io/github/license/PestPlan/web-frontend">

웹 프로트엔드를 구현합니다.

### [web-backend](https://github.com/PestPlan/web-backend) <img style="vertical-align: middle;" src="https://img.shields.io/github/languages/top/PestPlan/web-backend?logo=typescript&logoColor=2F74C0&color=2F74C0"> <img style="vertical-align: middle;" src="https://img.shields.io/github/license/PestPlan/web-backend">

웹 백엔드를 구현합니다.

### [device-inserter](https://github.com/PestPlan/device-inserter) <img style="vertical-align: middle;" src="https://img.shields.io/github/languages/top/PestPlan/device-inserter?logo=python&logoColor=4280B2&color=4280B2"> <img style="vertical-align: middle;" src="https://img.shields.io/github/license/PestPlan/device-inserter">

시연을 위해 임의의 기기를 MariaDB에 저장합니다.

### packet-generator <img style="vertical-align: middle;" src="https://img.shields.io/badge/-private-gray">

시연을 위해 임의의 패킷을 MongoDB에 저장합니다.

<br/>

## Page

### Login page

> 로그인 페이지

<img src="https://github.com/PestPlan/document/blob/master/images/login%20page.PNG?raw=true">

<br/>

### Chart page

> 패킷과 기기의 현황을 차트로 나타낸 페이지

<img src="https://github.com/PestPlan/document/blob/master/images/chart%20page.PNG?raw=true">

<br/>

### Packet list page

> 패킷의 목록을 보여주는 페이지

<img src="https://github.com/PestPlan/document/blob/master/images/packet%20list%20page.PNG?raw=true">

<br/>

### Device list page

> 기기의 목록을 보여주는 페이지

<img src="https://github.com/PestPlan/document/blob/master/images/device%20list%20page.PNG?raw=true">

<br/>

### Device detail page

> 해당 기기에서 전송한 패킷의 목록과 기기의 상태를 보여주는 페이지

<img src="https://github.com/PestPlan/document/blob/master/images/device%20detail%20page.PNG?raw=true">

<br/>

## Team

-   [박현준(PL)](https://github.com/Darkeroe) : BE
-   [김동규](https://github.com/kimdg1105) : DBA
-   [배성훈](https://github.com/baesh3744) : WEB FE & BE
