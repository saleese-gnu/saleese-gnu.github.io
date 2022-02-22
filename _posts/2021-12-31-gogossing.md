---
author: kwonGB
type: youtube
yt-video-id: aAkfp-yFjbg
homedisplay: iframe
title: 고고씽 [2021]
tags: [demo video, scooter, python, sensor]
category: [RaspberryPi, safety]
layout: post-material-sidebar-left
---
##### 킥보드 사용자의 안정성 확보를 위한 프로젝트입니다.
<br><br>
#### 기능적 요구사항
* 헬멧 착용 및 두 명 이상 탑승 여부에 따라 모터를 제어한다.
* 모터 제어가 불가능한 이유를 디스플레이에 출력한다.
* 전방 1.5m이내에 물체가 감지될 경우 경보음이 울린다.
* 전방 0.5m이내에 물체가 감지될 경우 모터 RPM을 80%로 감속한다.
* 킥보드가 넘어진 상태로 10초 이상 유지 시, 경보음이 울린다.
* 킥보드가 넘어진 상태로 60초 이상 유지 시, 지인에게 GPS데이터를 메일로 보낸다.

<br>
#### 품질적 요구사항
* 헬멧보드에서 웹서버로 데이터를 write할 때, 1초 이내로 write 해야 한다. 
* 메인보드에서 웹서버로 데이터를 read할 때, 1초 이내로 read 해야 한다.                
* 디스플레이에 경고 메시지는 모터 제어가 불가능한 이유를 1초 이내로 출력되어야 한다.
* 전방 1.5m 이내 물체 탐지 시 0.5초 내에 경고음이 발생해야 한다.

<br>
#### 제약사항
* 항상 인터넷이 연결되어 있는 환경이어야 한다.

<br>
#### UseCase Diagram
![UseCase Diagram](/img/gogossing_ucd.png "gogossing UseCase Diagram")