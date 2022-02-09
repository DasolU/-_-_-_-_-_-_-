
# AI를 활용한 셀프 면접 연습 도우미 프로젝트

## 링크
저희 팀 [Github 링크][1] 입니다.

## 프로젝트 요약
### 전체 구조도
<img width="452" alt="image" src="https://user-images.githubusercontent.com/80796260/153201548-94a35f86-b874-42ff-a0e2-59778ae4b548.png">

### [얼굴인식]
- 얼굴 랜드마크를 분석을 통한 시선 및 고개 움직임, 눈깜빡임 추적

### [음성인식]
- STT를 활용한 면접 연습 답변 받아쓰기, CNN을 활용한 추임새 분석

<img width="452" alt="image" src="https://user-images.githubusercontent.com/80796260/153202230-2ca3abd6-44d5-43c7-a7f6-67b4addbc37a.png">

### [자연어생성]
- 면접 답변 아이디어 생성

## 사용기술
[얼굴인식]
- Gaze tracking, Head pose detection, Blink detection

[음성인식]
- Googe & CLOVA STT, 추임새 분류 CNN 모델

[자연어생성]
-  Text Generation (Ko-GPT2)
- 크롤링


## 참고 오픈소스
- [GazeTracking][6], [Headpose-Detection][7]
- [이화여대 통번역 대학원의 통번역 전사 프로젝트][2], [naverspeech][6]
- [Ko-GPT2][3], [fine tunning][4]
- [JasoAI][5]


## 서비스 개요
- 사용자를 위한 종합적인 면접 연습 자세 분석 리포트 제공
<img width="452" alt="image" src=https://user-images.githubusercontent.com/80796260/153204425-15e93aed-648f-4c06-b72e-1fbed0af58a4.png>
<img width="452" alt="image" src=https://user-images.githubusercontent.com/80796260/153205106-3e7c554e-c313-40da-9bdb-8f9e8b07bd57.png>
<img width="452" alt="image" src=https://user-images.githubusercontent.com/80796260/153205511-2a5d41fe-b36a-49b9-8c6b-940f6e025d5e.png>

[1]: https://github.com/yuuumiEL/posco_ai_project_15th_A2
[2]: https://github.com/EwhaSpeakUP/SpeakUP_ML
[3]: https://github.com/SKT-AI/KoGPT2
[4]: https://www.philschmid.de/fine-tune-a-non-english-gpt-2-model-with-huggingface
[5]: https://github.com/Yngie-C/JasoAI
[6]: https://github.com/naver/naverspeech-sdk-android
[7]: https://github.com/antoinelame/GazeTracking
[8]: https://github.com/qhan1028/Headpose-Detection

