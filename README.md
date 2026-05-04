# 👑 몽유록 (Mongyurok)

> 조선 왕과 대화하며 역사를 배우는 캐릭터형 AI 챗봇

---

## 📌 SK네트웍스 Family AI 캠프 24기 4차 프로젝트

---

## 👥 1. 팀 소개

### 🏷️ Team. Historycometrue

| 이름 |
|------|
| 김현수 |
| 나혜린 |
| 류지우 |
| 정준하 |
| 황인규 |

---

## 📖 2. 프로젝트 개요

### 📛 프로젝트 명
**몽유록**

---

### 📌 프로젝트 소개

조선왕조실록과 한국사 데이터를 기반으로  
사용자가 조선의 왕과 직접 대화하는  

👉 **몰입형 캐릭터 AI 챗봇 웹 서비스**

---

### 📚 프로젝트 필요성

<img width="700" height="700" alt="image" src="https://github.com/user-attachments/assets/03bb7129-01b8-41bc-8ce6-3f04fa8ede8f" />
</br>
https://www.mk.co.kr/news/it/11983531 
  
AI 챗봇 시장에서는 정보 검색형 서비스를 넘어, 캐릭터와 대화하며 정서적 교감과 몰입을 경험하는 형태가 확산되고 있다. 실제로 2026년 2월 기준 한국인이 가장 오래 사용한 AI 챗봇 앱은 캐릭터 대화 서비스 ‘제타’로 나타났다. 이러한 흐름은 이용자들이 상호작용성과 서사성을 갖춘 AI 경험에 익숙해지고 있음을 보여준다.

<img width="534" height="491" alt="image" src="https://github.com/user-attachments/assets/c998bd6d-a7e7-4708-bc78-5be3b9754642" /><img width="1915" height="944" alt="image" src="https://github.com/user-attachments/assets/8e1d0e51-27fd-429f-a5f8-642623c98f69" />




---

### 🎯 프로젝트 목표

- 

---

## 🛠️ 3. 기술 스택

### 💻 Backend
- Django  
- FastAPI  

### 🧠 AI / LLM
- EXAONE-3.5-2.4B-Instruct  
- LangChain  
- LangGraph  

### 📚 Vector DB
- ChromaDB  
- HuggingFace Embedding (KURE-v1)  

### 🗄️ Database
- MySQL (RDS)  
- ChromaDB  

### ☁️ Infra
- AWS EC2  
- AWS RDS  
- RunPod  

### 🐳 DevOps
- Docker  
- Nginx  
- Gunicorn  

---

## 🧩 4. 시스템 구성도

  
[User]  
↓  
[Nginx]  
↓  
[Django (EC2)]  
↓  
[FastAPI (RunPod)]  
↓  
[LangGraph + LLM]  
↓  
[ChromaDB (RAG)]  
  

---

### 🔁 처리 흐름


사용자 입력  
→ Django View  
→ FastAPI (/chat)  
  
→ LangGraph 실행  
  
emotion (감정 분석)  
intent (의도 분석)  
retrieve (RAG 검색)  
king (답변 생성)  
scene (장면 묘사)  
  
→ 응답 반환  
→ DB 저장  
→ 사용자 출력  
  

---

## 📋 5. 요구사항 정의서

📌 (이미지 삽입)
  
주요 기능:  
  
- 회원가입 / 로그인    
- 캐릭터 선택  
- 페르소나 설정  
- 채팅 기능  
- 채팅 기록 저장  
- 비동기 메시지 처리  

---

## 🖥️ 6. 화면설계서

📌 (이미지 삽입)

- 캐릭터 선택 페이지  
- 페르소나 설정 모달  
- 채팅 화면  

---

## 📊 7. WBS

📌 (이미지 삽입)

---

## 🧪 8. 테스트 계획 및 결과

### ✔ 테스트 항목

- 의도 분류 테스트  
- RAG 동작 테스트  
- 캐릭터 일관성  
- 감정 반응  
- 장면 묘사  

---

### ✔ 테스트 결과

- RAG 적용 시 정확도 향상  
- 불필요한 검색 제거 → 속도 개선  
- 감정 기반 응답 → 자연스러움 증가  
- scene 추가 → 몰입감 향상  

---

## 🎬 9. 수행 결과

### 📌 주요 기능

- 왕 캐릭터 선택  
- 페르소나 설정  
- 실시간 채팅  
- RAG 기반 답변  
- 장면 묘사  

---

### 📌 프로젝트 구조


mongyurok/
├── apps/
│ ├── auths/
│ ├── users/
│ ├── characters/
│ └── scenarios/
├── templates/
├── static/
├── nginx/
├── Dockerfile
├── docker-compose.yml
└── manage.py


---

### 📌 LLM 구조


llm/
├── main.py
├── src/
│ ├── graph.py
│ ├── state.py
│ ├── nodes/
│ └── config.py
└── reference_db/


---

## 💬 10. 한 줄 회고
