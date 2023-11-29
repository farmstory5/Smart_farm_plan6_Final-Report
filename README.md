# 5조 팜스토리 스마트팜 Node-red
# Smart_farm_plan6_Final-Report
## 팀명: 팜스토리
## 작품: 스마트팜
## 구성원: 오상우, 윤현호, 박세린, 이병현, 권용만
## 개요<br/>• 작품사진 <br/>• 블록도 <br/>• 순서도 <br/>• 노드 && 플로우 <br/>• 기능 <br/>• 시연영상
### 작품사진
사물인터넷 기반으로 만든 스마트팜 프로젝트입니다.<br/>
라즈베리파이를 사용하여 아날로그/디지털 데이터 I/O 센서를 시스템과 연결하고,<br/>
큰 전압을 요구하는 하드웨어는 규격에 맞는 전원 어댑터를 따로 단선 후, 병렬 연결했습니다.<br/>
마지막으로 원격 접속을 위해 포트포워딩 관련 네트워크 작업을 했습니다.

<p align="center">
<img src="https://github.com/farmstory5/Smart_farm_plan6_Final-Report/assets/130550405/3cca2347-31c7-4008-a3fe-8a4315d204a6" width="30%" height="30%">
<img src="https://github.com/farmstory5/Smart_farm_plan6_Final-Report/assets/130550405/4504d50d-84fe-4653-bcae-7679178454c5" width="30%" height="30%">
<img src="https://github.com/farmstory5/Smart_farm_plan6_Final-Report/assets/130550405/2d095bc0-20aa-4a23-8826-914946640a6e" width="30%" height="30%">
</p>
　　　• 정면도　　　　　　　　　　　　　　　　• 사시도　　　　　　　　　　　　　　　　• 측면도
<br/><br/>

### 블록도
<p>
<img src=https://github.com/farmstory5/Smart_farm_plan6_Final-Report/assets/130550405/4ada5ea3-c3b3-495e-8d7a-aa7121b99da9
</p> <br/><br/>
  
### 순서도
<p>
<img src=https://github.com/farmstory5/Smart_farm_plan6_Final-Report/assets/130550405/68c5e838-deb1-4bd3-acae-cccc5bf053f3
</p> <br/><br/>

### 노드 && 플로우 <br/>JSON 소스코드: https://github.com/farmstory5/Smart_farm_plan6_Final-Report/tree/main/SourceCode_.jsonFile
<p>
<img src=https://github.com/farmstory5/Smart_farm_plan6_Final-Report/assets/130550405/ec756bdf-1ed1-41b4-a669-c4760eab611b
</p><br/>
• 디지털신호 DHT-11 온습도센서<br/>
<p>
<img src=https://github.com/farmstory5/Smart_farm_plan6_Final-Report/assets/130550405/2bd2b472-a5b8-4893-a7e6-2a965e660add
</p><br/>
• 아날로그신호 조도, 수분감지센서<br/>
<p>
<img src=https://github.com/farmstory5/Smart_farm_plan6_Final-Report/assets/130550405/d89138d2-90de-4e5f-a432-3140644e766a
</p><br/>
• 임베디드시스템(RasRaspberry Pi 4) 온도체크<br/>
<p>
<img src=https://github.com/farmstory5/Smart_farm_plan6_Final-Report/assets/130550405/fda9a0d9-35a3-445b-91d6-de5418b34e5c
</p><br/>
• 릴레이에 연결된 LED, 환풍기팬<br/>
<p>
<img src=https://github.com/farmstory5/Smart_farm_plan6_Final-Report/assets/130550405/d227f88c-821c-4642-b755-1821d0ea5f5d
</p><br/>
• 카메라<br/><br/>

### 기능
#### 1. 로그인
• 네트워크환경에서 외부인 접속방지를 위한 보안설정<br/>
<p>
<img src=https://github.com/farmstory5/Smart_farm_plan6_Final-Report/assets/130550405/ad5bd0fa-8843-4004-9784-60d99ac9cda7
</p>
<br/>
플로우창 로그인화면<br/><br/>
<p>
<img src=https://github.com/farmstory5/Smart_farm_plan6_Final-Report/assets/130550405/f9e72f05-96c8-42bb-b982-fcc1357d4cbb
</p>
<br/>
UI 로그인화면<br/><br/>
  
#### 2. 포트포워딩으로 다른 네트워크에서 접속가능
<p align="center">
<img src=https://github.com/farmstory5/Smart_farm_plan6_Final-Report/assets/130550405/2e1e2a78-1baf-4aae-af24-4874b6384458
</p>
<br/>
모바일 5G 네트워크환경에서 접속<br/><br/>

#### 3. 네트워크환경에서 임베디드시스템 하드웨어 원격제어
• 릴레이에 연결된 하드웨어 전원ON/OFF<br/>
• 실시간 카메라 스트리밍<br/>
<p align="center">
<img src=https://github.com/farmstory5/Smart_farm_plan6_Final-Report/assets/130550405/93188534-1f6f-4e6c-b6b1-e773c352751a
</p>
<br/>
구현테스트<br/><br/>

### 시연영상
<p>
<img src="https://github.com/farmstory5/Smart_farm_plan6_Final-Report/assets/130550405/a77207f8-d765-4ac3-9241-d44ba773e52e" width="60%" height="60%"
</p><br/>
https://www.youtube.com/watch?v=ihR365DoWcY<br/>
<p>
<img src=https://github.com/farmstory5/Smart_farm_plan6_Final-Report/assets/130550405/a6f24a92-0d52-4b89-b838-1a99779ffea5" width="60%" height="60%"
</p><br/>
https://www.youtube.com/watch?v=yIbspmrn14s&list=PL6eTMuAQkpIIqmaPZM9ysZ-hKNT0LrCyx&index=7<br/>
