# 부처핸섬 - 손쉬운 화상회의 지원 시스템




손 동작을 모션인식하여 다양한 기능들을 On/Off 할 수 있는 프로그램입니다.

## 작품 개요
코로나 이후 회사 회의나 대학교 강의 등에서 비 대면 화상회의가 급증했다. 이 때 대다수의 참여자가 재택에서 화상회의에 참여함에 따라 사생활 유출 문제도 커졌다.
다양한 사생활 보호 기능을 간단한 손동작만으로 동작할 수 있게 하여 사생활 유출 문제를 최소화한다.<br><br>

## 기술 스택
![image](https://github.com/user-attachments/assets/6c3d9f70-c52c-4304-8741-0db11132211e) <br><br>


## 작품 구성도
![image](https://github.com/user-attachments/assets/220e185d-a880-4669-9fb7-d28e07649200) <br><br>

## 시연 영상
https://www.youtube.com/watch?v=_uvWURgyNB8&feature=youtu.be <br><br>

## 이미지 Blur 처리 기능 알고리즘
![image](https://github.com/user-attachments/assets/c8c22cf7-7e9a-4cdb-82d7-988600486fb5) <br>
사전에 ‘Two’로 학습시킨 손동작이 인식되면 Blur 모드를 작동 <br>
카메라 화면 전체에 Blur 처리를 한 후 MediaPipe 라이브러리를 사용하여 사람을 인식하고, Segmentation 기능을 사용하여 사람의 영역만 추출 후 해당 영역에만 Blur 처리를 해제<br>
만약 다시 ‘Two’라는 동작이 인식된다면 Blur 모드 해제 <br><br>


코드와 보고서 첨부되어있습니다.


![스크린샷 2024-06-12 141507](https://github.com/YuNyuk/Intel_Edge_AI_SW_Academy/assets/142381053/ecf0dac0-2315-4ebf-a602-40bd86a32662)
