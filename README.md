# 니...미루니?


## ERD
<img width="400" alt="image" src="https://github.com/user-attachments/assets/24f3297b-a1de-45d2-8f24-a11f726da300" />

---
## API 명세서 

https://www.notion.so/API-1fc5cf54b8c0807eb5b2d68b25be9bc9?pvs=4

---
## 🔁 콜백 연결표 (미루니 API)

| 순서 | 기능 설명             | API Endpoint         | 메서드 | 비고                           |
|------|----------------------|----------------------|--------|--------------------------------|
| 1    | 모든 Task 목록 조회   | `/task`              | GET    | 전체 과제(Task) 리스트 조회    |
| 2    | Task 상세 조회        | `/task/{task_id}`    | GET    | 특정 Task ID 기준 상세 조회   |
| 3    | Task 생성 (응답 저장) | `/task`              | POST   | 질문 응답 및 키워드 저장      |
| 4    | Task 삭제             | `/task/{task_id}`    | DELETE | 특정 Task 삭제                |

---

## 기능 1

- user가 입력한 모든 task 띄우기

  <img width="300" alt="image" src="https://github.com/user-attachments/assets/b2cb2bdd-33c3-4729-8b00-c4f37a585761" />

  List<TaskResDto>로 return한다.

## 기능 2

- task_id로 해당 task의 상세내용 출력하기

    <img width="300" alt="스크린샷 2025-05-24 오전 7 28 04" src="https://github.com/user-attachments/assets/d5a67d07-aee8-4b32-b00d-3ad1b6a47fbe" />

  TaskResDto로 return한다.

## 기능 3

- 새로운 task를 입력한다.

  <img width="300" alt="스크린샷 2025-05-24 오전 7 29 42" src="https://github.com/user-attachments/assets/92d28e89-868c-4f77-8641-c85607365eb3" />

  TaskReqDto형식의 Body로 request 받는다.

## 기능 4

- task_id로 완료한 task 삭제

  <img width="300" alt="스크린샷 2025-05-24 오전 7 31 11" src="https://github.com/user-attachments/assets/f694bd24-dca7-4771-b5b3-f9e5140631de" />

  findByTaskid로 JPA extend한 repo가 자동으로 삭제해zoom

---
## 나이가들었나보다스물셋에밤샘이버거워

<img width="600" alt="image" src="https://github.com/user-attachments/assets/eeca0a8e-c5df-444f-bd06-a926444cda2c" />

