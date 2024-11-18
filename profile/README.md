# 공유 Todo LIST 'Plan With ME'

- ### 서비스 URL : [pwm.ssc.co.kr](https://pwm.ssc.co.kr)

<img src="../photo/front.jpg"/>

</br>

# 프로젝트 소개

```
- 개인을 넘어선, 친구, 가족 등 원하는 사람과 함께 쓰는 달력형 To do list
- 팔로우 유저간 자신의 Todo list 공유
- 여러명과 함께 쓰는 Todo list
```

<img src="../photo/ppt/ppt (4).jpg">

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

# Source Repository

### [PWM-FRONT (pwm-fe)](https://github.com/plan-with-me/pwm-fe)<br>

![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=React&logoColor=black)
<img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=TypeScript&logoColor=white"/>

### [PWM-BACK (api server)](https://github.com/plan-with-me/api-server)<br>

![PostgrSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![Python](https://img.shields.io/badge/Python-14354C?style=for-the-badge&logo=python&logoColor=white)
<img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=FastAPI&logoColor=black"/>

</br>

# 프로젝트 PPT

[최종 발표 ppt](https://github.com/plan-with-me/.github/blob/main/photo/%EC%B5%9C%EC%A2%85_Plan%20With%20Me.pptx)

# 서비스 구성도

<img src="../photo/ppt/ppt (6).jpg">

# Infra 구성

<div style="display: flex; gap: 10px;">
    <img src="https://img.shields.io/badge/Proxmox-E57000?style=for-the-badge&logo=Proxmox&logoColor=black"/>
    <img src="https://img.shields.io/badge/Rocky Linux-10B981?style=for-the-badge&logo=RockyLinux&logoColor=black"/>
    <img src="https://img.shields.io/badge/Jenkins-D24939?style=for-the-badge&logo=Jenkins&logoColor=black"/>
    <img src="https://img.shields.io/badge/NGINX-009639?style=for-the-badge&logo=NGINX&logoColor=black"/>
</div>
<br>
<img src="../photo/1.JPG"/>

<img src="../photo/ppt/ppt (5).jpg">
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
  [![Video Label](../photo/front.jpg)](https://www.youtube.com/watch?v=reBLQGE7SNM)

<br/>

# 기능 소개

## 로그인 화면

- 카카오, 구글 로그인 연동 구현
<div style="text-align: center;">
    <img src="../photo/screenshot/login.png" width="300" alt="login"/>
</div>
</br>

## 개인 Todo list

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

- ### 일기 작성
  - 일기 아이콘을 눌러 일기 페이지로 이동
  - 해당 날짜의 일기를 작성할 수 있으며, 날씨와 공개 여부를 설정할 수 있음
    <img src="../photo/screenshot/pc/diary.png">

## 지인의 Todo list

- ### 팔로잉 유저의 홈 화면 탐색

<div style="display: flex; gap: 10px;">
        <img src="../photo/screenshot/mobile/search.png" height="475"/>
        <img src="../photo/screenshot/pc/follow.png" width="590"/>
</div>

</br>

## 그룹 Todo list

- ### 그룹 Todo list 생성 및 초대

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

## 라운지

<img src="../photo/ppt/ppt (9).jpg">
