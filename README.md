# CoCoDoogy Map Editor
<img width="2880" height="1800" alt="image" src="https://github.com/user-attachments/assets/754c69ce-0ddd-430d-9693-d4b68f43bebc" />


#  CoCoDoogy
CoCoDoogy [기업협약 프로젝트] 

코코두기 플레이 영상 https://youtu.be/UZxtOPqYw3k

코코두기 Git https://github.com/lgw0317/YKW_CocoDoogy


코코두기 맵에디터 영상 https://youtu.be/SR_TgejYDHo

## 1. 코코두기 맵 에디터 소개

코코두기의 개발 과정에 레벨 디자인을 위해 제작한 커스텀 맵 에디터입니다.

Unity를 활용하여 제작하였습니다.

개발기간 : 2025.10.16 ~ 2025.12.10


## 2. 주요 기능
   
-----------------------------------------------------------
담당 Features

2.1 블록 JSON 직렬화, 저장 기능(Firebase Realtime DB)
* JSON 직렬화 DB 업로드 및 다운로드

2.2 편집 컨텍스트 기록 및 되돌리기/복원 기능
* ICommandable 인터페이스, Command 구체 클래스 => 편집 기능을 커맨드화하여 작업 내용 누적
* Undo/Redo 기능 구현


-----------------------------------------------------------


## 3. 기술 스택
   
* C#
* Unity
* Fork + Github(형상 관리)
  
-----------------------------------------------------------
기술파트

* Firebase SDK 활용, DB 업로드/다운로드 비동기 핸들링
* 편집 기능 컨텍스트화 및 Undo/Redo 기능 구현 

-----------------------------------------------------------
