# 니...미루니?


## ERD
<img width="400" alt="image" src="https://github.com/user-attachments/assets/24f3297b-a1de-45d2-8f24-a11f726da300" />


---
## GitHub Repository 

https://github.com/5th-PARD-SERVER-PART/short_Gyeongmi/

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

  findByTaskid로 JPA extend한 repo가 자동으로 삭제해줌~

