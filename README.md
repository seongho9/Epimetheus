<p align='center'>
 <img src="./resources/favicon.ico">

## 프로젝트에서 수행한 것

- 각 단계별 코드를 실행하는 부분을 구현(Web API 인 web worker 이용)
- 각 단계별 코드 등록 시 해당 코드의 유효성을 검증 구현 및 도커 이미지화
- react.js를 이용한 웹페이지 구현


# EPIMETHEUS

> 목표 달성을 위한 과정을 생성하고 실현하는 자동화된 AI 플랫폼, EPIMETHEUS입니다. </br>
> An automated AI platform that actualizes user goals, innovatively generating and executing processes for goal achievement using LLMs.


![ezgif com-video-to-gif](https://github.com/UOS-CSDESIGN/Epimetheus/assets/43626362/f6c0e5eb-a00b-41fb-ab0b-1beb8e3bfdde)


이 프로젝트는 사용자가 제공한 목표를 실제로 실행할 수 있는 자동화 AI 플랫폼 구현이 주된 목표입니다. 대형 언어 모델(LLMs)이 일련의 과정을 생성 후 제공함으로써 사용자는 목표를 이루기 위한 단계를 알 수 있습니다. 

This project's primary goal is the implementation of an automated AI platform that can actually execute goals provided by users. Large Language Models (LLMs) generate and provide a series of steps, allowing users to understand the stages necessary to achieve their goals.



AI 모델의 단점인 블랙박스 특성을 없애기 위해, 목표를 달성하기 위한 각 단계의 적절한 코드를 저장소에서 가져오고, 실행한다는 점에서 기존의 서비스와는 다른 방향을 택하고 있습니다. 사용자가 직접 커스터마이징을 하여 실행할 수도 있습니다.

In order to eliminate the black box characteristic, which is a drawback of AI models, this service takes a different approach from existing services by retrieving and executing appropriate codes for each step to achieve the goals from a repository. Users can also customize and execute these steps themselves.


## 핵심 기능(Core Features)
사용자가 요청한 Task에 대해서 응답을 제공합니다. 응답은 1개 이상의 Step으로 구성됩니다.<br/>
It provides responses to the Tasks requested by the user. The response consists of one or more Steps.

> 각 Step에는 예시 코드가 함께 제공됩니다. 예시 코드를 사용자가 적절하게 수정한다면 원하는 Task가 실행될 것입니다.<br/>
> Each Step comes with example code. If the user appropriately modifies the example code, the desired Task will be executed.

> 모든 언어를 지원하고 있지만, Llama 7b 모델 특성상 영어만 높은 정확도를 제공하고 있습니다.<br/>
> We support all languages, but due to the characteristics of the Llama 7b model, only English is provided with high accuracy.


## 구성(Components)
목표를 입력하면 아래와 같이 화면이 구성됩니다. 
<br/>When you enter a goal, the screen will be arranged as follows.

- [Introduction](#introduction)
- [Step(One or more)](#stepone-or-more)
- [Description](#description)
- [Code](#code)
- [코드 수정 페이지(Code Modification Page)](#코드-수정-페이지code-modification-page)
- [Conclusion](#conclusion)
- [Run Code](#run)

<h3 id="intro">Introduction</h3>

![image](https://github.com/UOS-CSDESIGN/Epimetheus/assets/43626362/e77da2f3-48ea-49ea-95a3-8fcfeca521bc)

<h3 id="steps">Step(One or more)</h3>

![image](https://github.com/UOS-CSDESIGN/Epimetheus/assets/43626362/cb2e8652-6004-4613-b4ff-a84dea9d8b11)


<h3 id="description">Description</h3>

![image](https://github.com/UOS-CSDESIGN/Epimetheus/assets/43626362/de1272c3-f8cc-485d-aef8-848ea0637c9c)

<h3 id="code">Code</h3>

![image](https://github.com/UOS-CSDESIGN/Epimetheus/assets/43626362/3af0fdf0-077d-4e7c-a577-28f25c1ac4b2)

<h3 id="modify_cdode">코드 수정 페이지(Code Modification Page)</h3>

![image](https://github.com/UOS-CSDESIGN/Epimetheus/assets/43626362/149c77eb-593b-4954-9910-7117ced8d65a)

![image](https://github.com/UOS-CSDESIGN/Epimetheus/assets/43626362/c4463b3b-0174-42fb-9b61-97a97edf3db1)


<h3 id="outro">Conclusion</h3>

![image](https://github.com/UOS-CSDESIGN/Epimetheus/assets/43626362/1a76292a-1b61-436c-9025-c9b7eead5a35)

<h3 id="run">Run Code</h3>

![image](https://github.com/UOS-CSDESIGN/Epimetheus/assets/43626362/5b8f585b-e896-4baa-bdad-75eb894ade76)

## 기술 스택(Tech)
<img src="https://img.shields.io/badge/v3.1.3-springboot-6cb52d?logo=springboot"> <img src="https://img.shields.io/badge/v4.9.5-typescript-3078c6?logo=typescript"> <img src="https://img.shields.io/badge/v2.414.2-jenkins-f56f3c?logo=jenkins&logoColor=white"> <img src="https://img.shields.io/badge/v5.0.21-mongodb-004e3d?logo=mongodb"> <img src="https://img.shields.io/badge/v1.18.0-nginx-009639?logo=nginx"> <img src="https://img.shields.io/badge/v24.0.7-docker-2496ED?logo=docker">
