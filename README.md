# COVID_19_Vaccine_Reservation_System

- 프로젝트명 : 코로나19 백신 예약 시스템
- 개요 : 백신 예약 시스템은 백신접종자, 의사로 나뉘어 서비스 된다. 백신접종자는 본 서비스를 통해 백신접종을 예약, 예약된 내역 및 접종 내역의 조회가 가능하며 의사는 해당 서비스를 통해 자신이 포함되어 있는 병원의 미사용 백신을 관리하고 사용된 백신과 접종 환자내역을 추적할 수 있다.
- 프로젝트 참여 인원 : 4명

## 개발 환경
![image](https://user-images.githubusercontent.com/33370179/176653156-2e77064a-40cf-44b7-b6e4-3cf62a5222a7.png)

## 주요 기능

- 회원가입 및 로그인 - JWT 토큰 사용
  - 백신접종자 로그인 및 회원가입
  - 의사 로그인 및 회원가입
- 마이페이지
  - 회원 정보
  - 접종 기록
  - 회원 정보 수정
- 백신 접종 병원 예약
  - 병원명, 시/도, 시/구로 병원 검색
  - 병원별 남은 백신 개수 표시
  - 백신 접종 날짜 선택 기능
- 환자 정보
  - 환자의 백신 접종 날짜 확인
  - 환자 백신 접종완료 기능
  - 접종완료 오입력시 접종제거 기능
- 데이터 시각화(프로젝트 내부 데이터 사용)
  - 최근 일주일 접종자 수
  - 지역별 접종현황
  - 최근 일년 접종자 수
  - 접종 단계 현황
- 데이터 시각화(실제 대한민국 코로나 현황 API 사용) - 미들웨어 사용
  - 현재 실제 확진자 수 현황(최근 일주일)
  - 현재 코로나 검사자 수(최근 일주일)
  - 현재 코로나 검사자 중 확진율(최근 일주일)
  - 현재 코로나 확진자 중 사망자 수(최근 일주일)

## 코로나19 백신 예약 시스템
**- 로그인**

<img src="https://user-images.githubusercontent.com/33370179/176655996-f4ae771a-69d4-453a-a556-4f209778e61e.png" width="900" height="300"/>

**- 회원가입**

<img src="https://user-images.githubusercontent.com/33370179/176656040-1dde4783-3c14-451e-9123-ce58f3150c02.png" width="900" height="500"/>

**- 마이페이지**

<img src="https://user-images.githubusercontent.com/33370179/176657227-ce8c71e7-5bc9-4433-8946-faf279514212.png" width="450" height="300"/><img src="https://user-images.githubusercontent.com/33370179/176657232-26bacca8-cf6e-4e98-8d36-51b906b4f5dc.png" width="450" height="300"/>
<img src="https://user-images.githubusercontent.com/33370179/176657505-eb90e429-e1a1-45a4-9e92-5bd777670b10.png" width="450" height="600"/>

**- 병원예약**

<img src="https://user-images.githubusercontent.com/33370179/176656552-2d46ff8a-16df-4bd8-8f14-93c063e753f9.png" width="500" height="800"/>

![image](https://user-images.githubusercontent.com/33370179/176663445-986467a0-60d5-4c63-953b-6faa67780905.png)

**- 환자정보**

![image](https://user-images.githubusercontent.com/33370179/176663671-cfa0e9ad-e3d8-48c1-89e1-0849b87f6636.png)


**- 접종통계**

<img src="https://user-images.githubusercontent.com/33370179/176663805-8c947023-a440-4771-96ab-544be07a95a6.png" width="500" height="350"/><img src="https://user-images.githubusercontent.com/33370179/176663979-5367d283-201a-4611-815b-a09c6ce49473.png" width="500" height="350"/>
<img src="https://user-images.githubusercontent.com/33370179/176663997-b07df559-3e95-40f1-b040-37f05de7845b.png" width="500" height="350"/><img src="https://user-images.githubusercontent.com/33370179/176664039-045a85c7-cbeb-40a6-8361-c0e8304e9936.png" width="500" height="350"/>
<img src="https://user-images.githubusercontent.com/33370179/176664061-6c92d882-e54d-4fc9-aa3d-a47864e5b98f.png" width="500" height="350"/><img src="https://user-images.githubusercontent.com/33370179/176664067-ee76c313-adb1-4c0c-b292-1d36fcb443ef.png" width="500" height="350"/>
<img src="https://user-images.githubusercontent.com/33370179/176664085-c116ee17-31fd-4a77-8f38-683af0c0f78b.png" width="500" height="350"/>

