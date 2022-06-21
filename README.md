# Pose-Correct-App
### _자세 교정 프로그램_
>경상국립대학교 컴퓨터과학과
>팀장 박주철(19학번), 팀원 김정민(17학번)

# 개요
자세 교정 프로그램(Pose Correct)는 사람의 자세를 옆면에서 감지한 다음, 신체 각 지점의 각도와 길이에 따라 올바른 자세 여부를 판별한다. 그리고 판별 결과에 따라 부위마다 자세 상황을 알려주는 안드로이드 기반의 도우미 애플리케이션이다.

***
# 상세
### 개발 인원
 - 팀장 박주철
   - 프로젝트 지휘, 계획, 관리
   - 머신러닝 및 영상 처리 및 각종 최적화
   - 자세 감지 페이지 개발
   - 영상 분석 후 올바른 자세에 대한 판별
 - 팀원 김정민
   - 상세 유저 인터페이스 설계
   - 로딩 및 시작 페이지 제작
   - 영상 분석 후 올바른 자세에 대한 판별

### 개발 기술
본 프로젝트 개발에 사용된 라이브러리 및 파이프라인입니다.
- [Flogger] - Java용 Fluent interface 로깅 API
- [Android Jetpack] - 고품질 개발 라이브러리 및 툴 모음집
- [Mediapipe] - 라이브 머신러닝 파이프라인

### 개발 환경
| 종류 | 목록 |
| ------ | ------ |
| 사용 언어 | Java(1.8), Python(3.7), C++ |
| 개발 도구 | Android Studio(2021.1.1.) - SDK(30.0) & NDK(20.1.5948944), Github |
| OS 환경 | Windows 10, Ubuntu 22.04 LTS |

### 사용 방법
본 프로젝트의 결과물을 시연하는 방법입니다.
- 해당 프로젝트를 다운로드 받고, 안드로이드 스튜디오에서 실행시킵니다.
- 다만 해당 프로젝트는 스마트폰 카메라를 사용하는 관계로 안드로이드 애뮬레이터에서는 작동하지 않습니다.
- 안드로이드 스튜디오에서 .apk 형식으로 빌드합니다.
- 애플리케이션을 스마트폰으로 옮긴 다음 실행합니다.

### 클론 및 모듈
본 프로젝트의 클론 혹은 별도로 분리되어 개발된 모듈 목록입니다.
- [Original Repository] - 본래 개발이 진행되던 Repository입니다. 오류로 인해 중단되었습니다.
- [Now Repository] - Original Repository 중단 이후 새로 만든 Repository입니다. 현 Repository입니다.

### 자료
본 개발을 하면서 작성된 보고서 및 발표 자료입니다. 
| 보고서 자료 | 발표 자료 |
| ------ | ------ |
| 보고서 없음 | [초기 제안 발표 PPT 링크](https://docs.google.com/presentation/d/1WvH068HB0_oV0GnSzxVA0q2KVF5VYlyO/edit?usp=sharing&ouid=106667079864051075882&rtpof=true&sd=true) |
| [1차 보고서 PDF 링크](https://drive.google.com/file/d/1qA5ArMzdRrgRU8YWum507_YhT55ssndE/view?usp=sharing) | [1차 발표 PPT 링크](https://docs.google.com/presentation/d/1MkpIK95KpTUsb0bEsdpteb6aeZcvfOE2/edit?usp=sharing&ouid=106667079864051075882&rtpof=true&sd=true) |
| [2차 보고서 PDF 링크](https://drive.google.com/file/d/15lNZAOidlDvyWHB-62x10fNYhBu7XZN_/view?usp=sharing) | 발표 없음 |
| [3차 보고서 PDF 링크](https://drive.google.com/file/d/1EtlbNVMa2nJLJjvqZi64jHhZX5ZMRa_3/view?usp=sharing) | [2차 발표 PPT 링크](https://docs.google.com/presentation/d/1tTL2lqRdPgfzS42PzaqOIpeQzdoVB1IQ/edit?usp=sharing&ouid=106667079864051075882&rtpof=true&sd=true) |
| [최종 보고서 PDF 링크](https://drive.google.com/file/d/1bnOeUdG_CZ4BzFehB6OtGcO1cwp-I1lv/view?usp=sharing) | [최종 발표 PPT 링크](https://docs.google.com/presentation/d/1jZEnRu1DV4QA9h08FVvsk4NmVvzFLcxh/edit?usp=sharing&ouid=106667079864051075882&rtpof=true&sd=true) |

***
# 향후 계획
- 디자인 개선: 어플리케이션의 전반적인 디자인과 UI/UX 개선
- 편의성 개선: 어플리케이션에서 사용자의 편의와 다른 어플리케이션과의 차별성을 위해 부가기능 개발
- 최적화 개선: 머신러닝을 기반으로 한 어플리케이션인 만큼, 현재 플랫폼인 스마트폰에서 원활한 사용을 위해 최적화 진행
- 기능 개선: 사용자가 자세에 대해 적절한 피드백을 받게 하기 위해 피드백 방식에 대한 기능 개선


   [Flogger]: <https://github.com/google/flogger>
   [Android Jetpack]: <https://github.com/androidx/androidx>
   [Mediapipe]: <https://github.com/google/mediapipe>


   [Original Repository]: <https://github.com/wncjf2000/correctPose>
   [Now Repository]: <https://github.com/wncjf2000/Pose-Correct-App>
