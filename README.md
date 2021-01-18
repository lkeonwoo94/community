# HANU Community Guide (작성 중) 

HANU Community에 오신 것을 환영합니다! 

- [HANU Community Guide (작성 중)](#hanu-community-guide-작성-중)
  - [HANU (HAm kke NU rim; 함께 누림)](#hanu-ham-kke-nu-rim-함께-누림)
  - [프로젝트 소개](#프로젝트-소개)
    - [HANU-CI](#hanu-ci)
    - [TACOPLAY](#tacoplay)
    - [DECAPOD (DEClarative APplication Orchestration & Delivery)](#decapod-declarative-application-orchestration--delivery)
    - [HANUCTL (Incubation)](#hanuctl-incubation)
  - [Governance](#governance)
  - [How to Use](#how-to-use)
  - [How to Develop](#how-to-develop)
  - [How to Contribute](#how-to-contribute)
  - [Communication](#communication)
  - [License](#license)
  - [Support](#support)


**현재 Governance와 커뮤니티 운영을 위해 필요한 내용들을 정리하여 문서화 진행하고 있습니다.**

## HANU (HAm kke NU rim; 함께 누림) 
HANU 프로젝트는 Open Infrastructure 및 Cloud Native Computing과 관련된 다양한 기술들을 오픈소스SW로 개발하고, 이와 관련된 커뮤니티를 구성하고 활성화 하기 위한 공간입니다.

## 프로젝트 소개

HANU에는 여러 개의 오픈소스SW 프로젝트들이 있습니다. HANU의 프로젝트들은 각각 고유의 기능/구조적 특징을 가지면서, 필요 시 서로 연계할 수 있도록 되어 있습니다.

HANU의 프로젝트는 두 개로 나뉘어 집니다. 첫번째로 Incubation Project로 시작이 되며, 그 이후 충분한 기능적 완성도와 안성정을 갖추게 되면 Stable Project로 전환 될 수 있습니다.

Incubation Project는 누구든지 생성을 제안할 수 있으며, Technical Committee에서 결정합니다.

### TACOPLAY

Ansible기반의 Baremetal, Docker, Kubernetes 설치 자동화 기능을 제공하며, 설치된 Kubernetes 상에서 Airship Armada 혹은 decapod를 활용하여 컨테이너화된 OpenStack 이나 LMA (Logging, Monitoring, Alerting), 혹은 추가 Add-on tools 들을 설치할 수 있는 ansible playbook들을 제공합니다.

### DECAPOD (DEClarative APplication Orchestration & Delivery)

Kustomize 기반의 YAML Document 구조화 및 관리 기능과 Helm과 Argo를 기반 기술로 한 Declarative Application 배포 및 라이프사이클 관리 소프트웨어입니다.

### HANUCTL (Incubation)

TACOPLAY를 대체하는 Kubernetes Cluster-API 기반의 Cloud Native Infrastructure Lifecycle Management Controller입니다.   


## Governance

HANU Community는 오픈소스의 협업과 공유 정신에 따라 누구든지 참여할 수 있으며, 모든 의사결정은 투명하게 공개됩니다. 이러한 원칙을 지속하기 위해 Membership과 Group에 대한 Governance 체계를 구축하였으며, HANU에 속한 모든 프로젝트는 이러한 Governance 체계에 따라 운영됩니다. 자세한 내용은 [Governance](governance/README.md)를 살펴보세요.

## How to Use

HANU Community 내 Project는 각각의 README에서 사용/설치/운영 방법을 자세히 소개합니다. 

> `need-to-improve` 
> * DECAPOD : 
> * ... :
> * ... :

## How to Develop

HANU Commnity 내 Project를 개발하기 위해 공통적으로 필요한 내용들을 정리하였습니다. 다음 페이지를 참고하세요. : [Developing](developing/README.md)


## How to Contribute

HANU Community는 모든 소스 코드와 문서를 완전히 공개하고 커뮤니티 구성원이 협업하여 개발하는 오픈소스 개발 방식을 따릅니다. 여러분의 소중한 기여로 HANU Community의 Project는 성장할 수 있습니다. 

여기서는 HANU Project에 기여하기 위한 방법을 자세히 설명합니다. : [Contributing](contributing/README.md)


## Communication 

HANU Community는 Project별로 Mailing List와 Slack 채널을 통해 소통하고 있습니다. 

각 Project의 Mailing List 및 Slack 채널 정보는 다음 페이지에서 확인하세요. : [Communication](communication/README.md)

## License

HANU Community는 모든 Project는 다음 라이선스에 따라 배포합니다. 
* 소스 코드 : [Apache-2.0](https://spdx.org/licenses/Apache-2.0.html)
* 소스 코드 이 외의 콘텐츠 (문서, 이미지 등) : [CC-BY-4.0](https://spdx.org/licenses/CC-BY-4.0.html)


## Support

HANU Community 운영과 관련한 문의/요청이 있을 경우 [Issue](https://github.com/openinfradev/community/issues/new)를 생성해서 의견 남겨 주세요.  

