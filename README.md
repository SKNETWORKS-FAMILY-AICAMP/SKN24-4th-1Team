# 👑 몽유록 (Mongyurok)

> 조선 왕과 대화하며 역사를 배우는 캐릭터형 AI 챗봇

---

## 📌 SK네트웍스 Family AI 캠프 24기 4차 프로젝트

---

## 👥 1. 팀 소개

### 🏷️ Team. Historycometrue

| 김현수 | 황인규 | 나혜린 | 류지우 | 정준하 |
|---|---|---|---|---|
| <img src="https://github.com/user-attachments/assets/0df27cbd-71e2-457d-9905-56ee1afb3ddd" width="150" height="200" style="object-fit:cover;"> | <img src="https://github.com/user-attachments/assets/2aa07da0-b6ec-4492-b504-9fb629b25567" width="150" height="200" style="object-fit:cover;"> | <img src="https://github.com/user-attachments/assets/7600d13c-15f1-4328-88a9-4931f8731f18" width="150" height="200" style="object-fit:cover;"> | <img src="https://github.com/user-attachments/assets/1cfb7026-286a-4b34-981b-84aedad5f562" width="150" height="200" style="object-fit:cover;"> | <img src="https://github.com/user-attachments/assets/5994f887-d81f-46dd-a9ce-bc464cc0813f" width="150" height="200" style="object-fit:cover;"> |
| [BarryKim34](https://github.com/BarryKim34) | [hwang-in-kyu](https://github.com/hwang-in-kyu) | [nngpfls](https://github.com/nngpfls) | [jia11234](https://github.com/jia11234) | [junhaj27-jpg](https://github.com/junhaj27-jpg) |

## 📖 2. 프로젝트 개요

### 📛 프로젝트 명
**몽유록**

---

### 📌 프로젝트 소개

조선왕조실록과 한국사 데이터를 기반으로 사용자가 조선의 왕과 직접 대화하는  

👉 **몰입형 캐릭터 AI 챗봇 웹 서비스**

---

### 📚 프로젝트 필요성

<img width="500" height="500" alt="image" src="https://github.com/user-attachments/assets/03bb7129-01b8-41bc-8ce6-3f04fa8ede8f" />
</br>
https://www.mk.co.kr/news/it/11983531  
  
위 자료는 최근 AI 챗봇 시장에서 캐릭터 기반 서비스가 얼마나 높은 이용률을 기록하고 있는지를 보여준다. 특히 캐릭터와의 대화를 중심으로 한 서비스가 사용자 체류 시간 및 사용 빈도에서 상위를 차지하고 있다는 점은, 기존의 정보 검색형 챗봇에서 벗어나 감정적 교감과 몰입형 경험을 제공하는 서비스가 주류로 자리 잡고 있음을 의미한다.  
  
<p align="center">
  <img width="500" height="500" alt="image" src="https://github.com/user-attachments/assets/970130ec-a0fd-4372-b653-98e54ddf2eb1" />
</p>  
https://n.news.naver.com/article/006/0000135557?sid=103  
  
또한 두 번째 자료에서 드라마 및 콘텐츠의 흥행은 특정 시대와 인물에 대한 대중의 관심을 급격히 증가시키는 요인으로 작용하고 있다. 특히 ‘왕과 사는 남자’와 같은 작품의 인기는 조선시대를 포함한 역사적 배경에 대한 검색량 증가와 관심 확대로 이어졌으며, 이는 단순한 콘텐츠 소비를 넘어 해당 시대와 인물에 대해 더 깊이 탐색하고자 하는 사용자 니즈로 확장되고 있음을 보여준다. 
  
<p align="center">
  <img src="https://github.com/user-attachments/assets/c998bd6d-a7e7-4708-bc78-5be3b9754642" width="500"/>
  <img src="https://github.com/user-attachments/assets/8e1d0e51-27fd-429f-a5f8-642623c98f69" width="500"/>
</p>  
이미 캐릭터 기반 챗봇 플랫폼인 제타, 크랙 등에서는 조선을 주제로 한 캐릭터가 다수 등장하고 있으며, 실제 사용자들 또한 해당 주제를 기반으로 한 대화형 콘텐츠를 적극적으로 소비하고 있는 것으로 나타난다.  

  
<p align="center">
  <img width="548" height="348" alt="image" src="https://github.com/user-attachments/assets/75ffdb25-ab5f-4beb-bfba-248d19f8d47f" />
  <img width="739" height="72" alt="image" src="https://github.com/user-attachments/assets/b6d1f37a-7614-4cee-a148-2760f35b0d53" />
</p>  
https://contents.history.go.kr/front/hm/view.do?levelId=hm_074_0050  
  
위 자료는 현재 캐릭터 기반 챗봇이 생성하는 정보의 한계를 보여준다. 왼쪽은 캐릭터 챗봇의 실제 대화 예시로, 인물의 말투와 성격을 기반으로 자연스러운 응답을 생성하고 있으나 내용 측면에서는 역사적 사실과 일치하지 않는 오류가 포함될 수 있음을 확인할 수 있다.  
오른쪽 자료는 동일한 내용에 대해 국사편찬위원회에서 제공하는 역사 원문 및 해설로, 객관적인 사료를 기반으로 해당 정보가 실제 역사적 사실과 다름을 보여주는 근거 자료이다.  
  
이는 현재의 캐릭터 챗봇이 몰입감 있는 대화 경험은 제공할 수 있으나, 정보의 정확성과 신뢰성 측면에서는 검증되지 않은 내용을 생성할 가능성이 있다는 문제를 드러낸다.  
  
#### **따라서 본 프로젝트는 이러한 시장 흐름과 사용자 니즈를 반영하여, 조선시대 인물을 기반으로 하되 단순한 캐릭터 재현을 넘어 역사적 사실과 인물의 성격을 함께 반영한 몰입형 역사 캐릭터 챗봇 서비스를 구현하고자 한다.**  
  
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
