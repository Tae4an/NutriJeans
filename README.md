# NutriJeans - OCR 기반 영양 관리 시스템

**NutriJeans**는 OCR과 자연어 처리 기술을 활용해 음식 제품의 영양 정보를 자동 추출하고, 개인 맞춤형 건강 관리를 지원하는 시스템입니다.  
사진 한 장으로 간편하게 영양 정보를 분석하고 시각화된 결과를 통해 건강한 식습관을 형성할 수 있도록 돕습니다.

## 프로젝트 개요

| 항목 | 내용 |
|------|------|
| 프로젝트명 | OCR과 자연어 모델을 활용한 영양 관리 시스템 |
| 팀명 | 대들보 |
| 개발 기간 | 2024.07.01 ~ 2024.07.08 |
| 참여 인원 | 4명 (프론트엔드 2명, 백엔드 2명) |

## 팀 소개

| 이름 | 역할 |
|------|------|
| 박민주 | 팀장 / OCR 처리, 시각화, 마이페이지(프론트) |
| 최태산 | 텍스트-DB 매칭, DB 저장/조회, 히스토리(백엔드) |
| 최재훈 | 자연어 처리 모델, 마이페이지·로그인(백엔드) |
| 이은범 | 로그인·회원가입, 사진 업로드, 히스토리(프론트) |

---
## 시연 영상
[https://youtube.com/shorts/CZ7b2R2IDlM?si=f9rNvvtNi4ciuIdn
](https://www.youtube.com/shorts/CZ7b2R2IDlM)

## 시스템 구조도
![아키텍처222](https://github.com/user-attachments/assets/3e11c28f-c44e-4df0-93a4-ccaa65302809)




---

## 핵심 기능

- **OCR 기반 텍스트 추출**: 음식 라벨 이미지를 촬영하거나 업로드하면 텍스트 자동 인식
- **자연어 기반 정보 분석**: 추출된 텍스트를 식품 영양 DB와 매칭하여 성분 추출
- **맞춤형 영양 분석**: 사용자 정보를 기반으로 BMR, TDEE 계산 후 섭취량 비교
- **영양 정보 시각화**: 하루 및 주간 통계를 시각적으로 표현
- **회원 관리 기능**: 로그인/회원가입, 마이페이지, 프로필 수정 등 제공
- **섭취 이력 관리**: 히스토리 기능을 통해 과거 섭취 영양 정보 확인 가능

---

## 기술 스택

### 프론트엔드
- React Native
- Expo
- React Navigation

### 백엔드
- FastAPI
- Python
- Pydantic
- MongoDB

### AI / OCR
- Google Cloud Vision API
- 자연어 매칭 모델 (영양 성분 추출)

### 기타
- GitHub, Notion, Google Docs
- VS Code, HeidiSQL, ChatGPT

---
![image](https://github.com/user-attachments/assets/52ca8eaa-af08-4869-80c5-6769aaf784a6)
---
![image](https://github.com/user-attachments/assets/b60e381d-de6b-4749-84f5-2e2f70a17103)

