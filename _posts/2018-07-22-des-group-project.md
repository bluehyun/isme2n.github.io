---
layout: post
title:  "des 수업 그룹 프로젝트"
subtitle:   "패스트캠퍼스 데이터 엔지니어링 수업 에서 그룹 프로젝트"
categories: data
tags: project
comments: true
---
# des 자유프로젝트

## 주제 선정 이유

> 딱히 없다.. 아이디어도 없고 해서 어쩌다 보니 관심사에 끌려서

몇일을 다들 고민 했다..

데이터를 가져와서 쌓고 분석하는 전반적으로 진행해보고 싶은데 그럼 어디서 데이터를 가져오지 부터 고민이 생겼다.

공공분야의 빅데이터 자료는 대부분 csv 형태로 제공 해 주기에 데이터를 쌓는 경험을 할 수 없었고, 또한 자료가 최신 자료가 드믈다.

다들 롤을 좋아하는 사람이다 보니 롤 관련 이야기를 하다가..

마침 상우님이 ggtics 사이트를 보여주셨다..

# 유레카!!!

opgg, fow, ggtic 처럼 롤 데이터를 기반으로 한 분석 모듈을 제안했다.
마침 포지션도 다양하다 디자이너만 없다

개발 1 , 기획 1, 마케팅 1, 전부 해보고 싶어하는 1인 4인이서 해볼 예정

## 데이터
>데이터는 많다!!!!! 롤이 하루에 몇판이 진행되는데!!! 진짜 미친듯이 많다..

롤은 api 를 제공하며 게임에 데이터를 준다.
[lol api](https://developer.riotgames.com/)

플레이어의 레벨, 아이템, 킬/데스/어시스트, 획득 금화, 주거나 받은 피해량
게다가 혼자 하는 게임이 아니라 10명이서 5:5 게임이다.

오히려 많다 보니 어느 데이터를 가져올까 란 고민이 생겨버렸다..

그건 기획에서 같이 고민하기로 했다.



## 기획
......................조만간 채워넣겠음



## 개발 방법
고민중...
파이프라인 부터 분석까지 인데 좀 더 많은 이야기가 필요하다..

***아무래도 난 죽을듯***

뜬금없이 갑툭튀 한 ***<span style="color:#f2ef10">hadoop</span>*** 생각해보니 <span style="color:blue">spark</span> 은 분석 플랫폼이지 데이터 쌓는놈이 아니다.

Apache Flume 또는 Apache sqoop 활용한 데이터 수집 으로 생각중이다.

뭐가 됐든 어떻게든 되겠지...

아!!

아마도 **python** 을 사용할꺼 같다..

>난 뱀이 싫은데..