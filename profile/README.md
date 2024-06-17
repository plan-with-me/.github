# 공유 Todo LIST 'Plan With ME'
- ### 서비스 URL : [pwm.ssc.co.kr](https://pwm.ssc.co.kr)

<img src="../photo/front.jpg"/>

</br>

# 프로젝트 소개
```js
- 개인을 넘어선, 친구, 가족 등 원하는 사람과 함께 쓰는 달력형 To do list
- 팔로우 유저간 자신의 Todo list 공유
- 여러명과 함께 쓰는 Todo list

[구현 예정]
- 공통의 목표를 가진 사람과 할 일을 라운지에 공유 하여 가이드 라인과 동기 부여 제공
```

</br>

# Source Repository
### [PWM-FRONT (pwm-fe)](https://github.com/plan-with-me/pwm-fe)<br>
![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=React&logoColor=black)
<img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=TypeScript&logoColor=white"/>

### [PWM-BACK (api server)](https://github.com/plan-with-me/api-server)<br>
![PostgrSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![Python](https://img.shields.io/badge/Python-14354C?style=for-the-badge&logo=python&logoColor=white)
<img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=FastAPI&logoColor=black"/>



</br>

# 팀원 구성
<table>
<tr>
    <td align="center" style="word-wrap: break-word; width: 150.0; height: 150.0">
        <a href=https://github.com/kwyoung96>
            <img src=https://avatars.githubusercontent.com/u/166985125?s=64&v=4 width="100;"  style="border-radius:50%;align-items:center;justify-content:center;overflow:hidden;padding-top:10px" alt=kwyoung96/>
            <br />
            <sub style="font-size:14px"><b>Wonyoung Kang</b></sub><br>
            <sub style="font-size:12px"><b>Infra, UI/UX</b></sub>
        </a>
    </td>
    <td align="center" style="word-wrap: break-word; width: 150.0; height: 150.0">
        <a href=https://github.com/hyeonhe>
            <img src=https://avatars.githubusercontent.com/u/63030323?v=4 width="100;"  style="border-radius:50%;align-items:center;justify-content:center;overflow:hidden;padding-top:10px" alt=hyeonhe/>
            <br />
            <sub style="font-size:14px"><b>Hyunhee Kim</b></sub><br>
            <sub style="font-size:12px"><b>Front-End</b></sub>
        </a>
    </td>
    <td align="center" style="word-wrap: break-word; width: 150.0; height: 150.0">
        <a href=https://github.com/cheon40>
            <img src=https://avatars.githubusercontent.com/u/50188274?v=4 width="100;"  style="border-radius:50%;align-items:center;justify-content:center;overflow:hidden;padding-top:10px" alt=cheon40/>
            <br />
            <sub style="font-size:14px"><b>GyeongCheon Jo</b></sub><br>
            <sub style="font-size:12px"><b>Front-End</b></sub>
        </a>
    </td>
    <td align="center" style="word-wrap: break-word; width: 150.0; height: 150.0">
        <a href=https://github.com/B4NG8ANG>
            <img src=https://avatars.githubusercontent.com/u/50348034?v=4 width="100;"  style="border-radius:50%;align-items:center;justify-content:center;overflow:hidden;padding-top:10px" alt=B4NG8ANG/>
            <br />
            <sub style="font-size:14px"><b>Inho Bang</b></sub><br>
            <sub style="font-size:12px"><b>Front-End</b></sub>
        </a>
    </td>
    <td align="center" style="word-wrap: break-word; width: 150.0; height: 150.0">
        <a href=https://github.com/5pponent>
            <img src=https://avatars.githubusercontent.com/u/95746645?v=4 width="100;"  style="border-radius:50%;align-items:center;justify-content:center;overflow:hidden;padding-top:10px" alt=kwyoung96/>
            <br />
            <sub style="font-size:14px"><b>Taemin Lee</b></sub><br>
            <sub style="font-size:12px"><b>Back-End</b></sub>
        </a>
    </td>
</tr>
</table>
</br>

# Infra 구성
<div style="display: flex; gap: 10px;">
    <img src="https://img.shields.io/badge/Proxmox-E57000?style=for-the-badge&logo=Proxmox&logoColor=black"/>
    <img src="https://img.shields.io/badge/Rocky Linux-10B981?style=for-the-badge&logo=RockyLinux&logoColor=black"/>
    <img src="https://img.shields.io/badge/Jenkins-D24939?style=for-the-badge&logo=Jenkins&logoColor=black"/>
    <img src="https://img.shields.io/badge/NGINX-009639?style=for-the-badge&logo=NGINX&logoColor=black"/>
</div>
<br>
<img src="../photo/1.JPG"/>

</br>

```js
Server : Rocky OS 8.6
CI/CD  : Jenkins 2.440.2
```
</br>

# ERD 구성 
<img src="../photo/ERD.JPG"/>


</br>

# 시연 동영상
- ### Youtube Link
[![Video Label](../photo/front.jpg)](https://www.youtube.com/watch?v=bzp8BReGXdU)

<br/>

# 기능 소개
## 로그인 화면
- 카카오, 구글 로그인 연동 구현
<div style="text-align: center;">
    <img src="../photo/screenshot/login.png" width="300" alt="login"/>
</div>
</br>

## 개인 To-do list
 - ### 홈 화면

<div style="display: flex; gap: 10px;">
    <img src="../photo/screenshot/mobile/home.png" height="475"/>
    <img src="../photo/screenshot/pc/home.png" width="590"/>
</div>
</br>

 - ### 상위 목표 생성
    - 고정할 상위 목표 설정
    - 상위 목표는 날짜와 상관없이 노출
    - 공개 범위 설정 (나만 보기, 팔로워 공개, 전체공개)
    - 색상 지정 가능

<img src="../photo/screenshot/pc/tgoal.png">

</br>

 - ### 하위 목표 생성
    - 생성한 상위목표를 클릭하면 하위 목표 생성 가능
    - 하위 목표는 생성한 날짜에만 노출

<img src="../photo/screenshot/pc/sgoal.png">

</br>

## 지인의 To-do list
 - ### 팔로잉 유저의 홈 화면 탐색

<div style="display: flex; gap: 10px;">
        <img src="../photo/screenshot/mobile/search.png" height="475"/>
        <img src="../photo/screenshot/pc/follow.png" width="590"/>
</div>

</br>

## 그룹의 To-do list
 - ### 그룹 To-do list 생성 및 초대
    <div style="display: flex; gap: 10px;">
        <img src="../photo/screenshot/mobile/group1.png" height="500"/>
        <img src="../photo/screenshot/mobile/group2.png" height="500"/>
        <img src="../photo/screenshot/mobile/search.png" height="500"/>
    </div>

 - ### 그룹 인원 관리 및 그룹 홈 화면

<div style="display: flex; gap: 10px;">
        <img src="../photo/screenshot/mobile/member.png" height="475"/>
        <img src="../photo/screenshot/pc/grouphome.png" width="590"/>
</div>

</br>

## 모두의 To-do list
- 24년 하반기 오픈 예정

</br>

[![Hits](https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2Fplan-with-me&count_bg=%2379C83D&title_bg=%23555555&icon=&icon_color=%23E7E7E7&title=hits&edge_flat=false)](https://hits.seeyoufarm.com)
