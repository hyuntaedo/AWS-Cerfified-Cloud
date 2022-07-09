# AWS-Cerfified-Cloud
## AWS Certified cloud practitioner 대비 정리


---

# 1. 클라우드 컴퓨팅이란?

## 1.1.1 클라우드 컴퓨팅이란 무엇인가?
  * 클라우드 컴퓨팅은 IT 리소스를 인터넷을 통해 ★On-demand★로 제공하고 사용한 만큼 비용을 지불하는 것을 말한다.
  * 물리적 데이터센터와 서버를 구입, 소유 및 유지관리 하는 대신 Amzaon Web Service, Microsoft Azure 와 같은 클라우드로 부터 필요에 따라 기술 서비스에 엑세스
  * 내 컴퓨팅 리소스의 크기에 따라 서버를 작게 쓸 수 있거나 크게 쓸 수 있다.
  * 서버를 필요한 유형과 크기에 따라 유동적으로 정할 수 있다.
  
## 1.1.2 클라우드의 유형
  * Private Cloud : 외부에 노출되지 않아 자체 사설 클라우드를 가지며 완전히 제어할 수 있음 또한 보안이 강하다.
  * Public Cloud : AWS, Google Cloud, MS Azure 등이 있으며, 소유한 클라우드 리소스가 타사 클라우드 서비스에서 운영하는 공급자가 공급하는 유형
  * ★Hybrid Cloud★ : 사설, 공용 클라우드를 결합한 것이며 일부서버를 on-premise에 유지하고 필요한 기능의 일부를 클라우드로 확장하는 개념
  
  
## 1.1.3 클라우드 컴퓨팅의 특징
  * On-demand self Service : 사용자는 Resource를 rovisioning 할 수 있고 AWS 개입 없이 사용 가능
  * Broad network access : 네트워크를 통해 리소스를 사용할 수 있으며 다양한 클라이언트 플랫폼에서 액세스 가능
  * Multi-tenancy and resource pooling : 보안 강도는 똑같이 가면서도 동일한 물리적 리소스에서 여러 고객에게 서비스 제공
  * Rapid elasticity and scalability : 필요할 때 자동으로 신속하게 원하는 리소스를 획득 및 처리가 가능하며, 온디맨드 기반으로 쉽고 빠르게 확장 가능
  * Measured Service : 사용량이 측정되고 사용자는 사용한 만큼만 지불

## 1.1.4 클라우드 컴퓨팅의 장점
 * Trade capital expense (CAPEX) for operational expense (OPEX)
 * Benefit from massive economies of scale
 * Stop guessing capacity
 * increase speed and agility
 * Stop spending money running and maintaining data centers
 * Go global in minutes

## 1.1.5 클라우드 컴퓨팅 모델 유형
 * Infrastructure as a Service(IaaS) - 원시형태로 제공(Amazon EC2)
  
   - IaaS로 줄여쓰기도 하는 Infrastucture as a Service는 클라우드 IT의 기본빌딩블록을 포함하고 일반적으로는 네트워킹 기능, 컴퓨터(가상 또는 전용하드웨어) 및 데이터 스토리지 공간을 제공
   - IT 리소스에 대해 가장 높은 수준의 유연성과 관리제어를 제공하며, 오늘날 많은 IT부서와 개발자에게 익숙한 기존 IT리소스와 비슷하다.
 
 * Platform as a Service(PaaS) - 원시형태와 완제품의 중간(Amazon Beanstalk)
 
   - Platform as a Service(PaaS)를 사용하면 조직은 기본 인프라(일반적으로 하드웨어와 운영체제)를 관리할 필요가 없어 애플리케이션 개발과 관리에 집중할 수 있습니다.
   - 즉 애플리케이션 실행과 관련된 리소스구매, 용량계획, 소프트웨어 유지관리, 패치 또는 다른 모든 획일적인 작업에 대한 부담을 덜어 더욱 효율적으로 되도록 한다.
 
 * Software as a Service(SaaS) - 완제품(Amazon Rekognition)
 
   - Software as a Service는 서비스 제공업체에 의해 실행되고 관리되는 완전한 제품을 고객에게 제공
   - 대부분의 경우 Software as a Service 라고 한다면 최종 사용자 애플리케이션을 말합니다.
   - SaaS 오퍼링을 사용할 경우 서비스가 어떻게 유지관리되는지 기본 인프라가 어떻게 관리되는지 생각할 필요가 없으며, 소프트웨어의 특정부분을 어떻게 사용할지만 생각하면 됩니다.
   
 * On-premise vs IaaS vs PaaS vs SaaS
 
 ![image](https://user-images.githubusercontent.com/44853842/178099773-d4249efe-f9af-402f-bb34-c34a156dcfc0.png)


## 1.1.6 AWS Cloud Use Case

 * AWS를 통해 복잡하고 확장가능한 애플리케이션을 만들 수 있음
 * 다양한 산업분야에 적용 가능
   * Netflix, Activision, Macdonald's, FOX
   * Enterprise IT, Backup & Storage, Big Data Analysis, Create BackEnd, Gamaing

## 1.1.7 AWS Global Infrastructure
 * Refer to URL : https://infrastructure.aws/

## 1.1.8 AWS Regions

 * AWS has Region all around world
 * Names can be us-east-1, eu-west-3...
 * Region이란 데이터 센터의 집합소이다.
 * 대부분의 서비스는 특정 리전에 국한된다.

## 1.1.9 공동책임모델
 
 ![image](https://user-images.githubusercontent.com/44853842/178101885-8e9552aa-74f8-40c4-9eb4-00e2736cb157.png)

 * https://aws.amazon.com/shared-responsibility-model/

## 1.1.10 AWS Acceptable Use Policy
 
 * https://aws.amazom.com/aup/
  
  
## 1.11 오답노트

![image](https://user-images.githubusercontent.com/44853842/178102536-c9d29e2c-c60c-4886-82f8-df1f89ebbfa8.png)

  
  




