![이전배치목록4](https://github.com/user-attachments/assets/16621df7-503c-4706-a7cb-15157eeb0f43)# Silverithm

## 해결하고자 하는 문제

**요양기관 자차 송영 서비스 차량 배치를 작성하기 위해 불필요한 직원들의 노동과 시간 소요**

## Solution

1. **최적화 알고리즘인 유전 알고리즘을 도입하여 차량 배치 알고리즘 완성**
2. **가까운 거리에 있는 어르신일수록 가중치를 주어 가까운 거리에 있는 어르신들을 최대한 묶어줌**
3. **어르신 고정, 앞자리 고정 등 다양한 조건 반영**
4. **Tmap API를 활용하여 실시간 교통상황 반영**

## 왜 유전 알고리즘을 사용하였는가?
장기요양기관의 특수성을 반영한 차량 배치 알고리즘을 완성하기 위해서는 해 탐색을 위해 매우 높은 시간 복잡도를 가지는 일반 알고리즘으로 한계가 있다.
이를 극복하기 위해 전역 최적해를 빠르게 탐색할 수 있고 장기요양기관의 특수하고 복잡한 조건들을 반영 가능한 유전 알고리즘을 사용하였다.
유전 알고리즘은 생물학적 진화를 유도하는 과정인 자연 선택에 기반한 것으로, 제약 조건이 있는 최적화 문제와 제약 조건이 없는 최적화 문제를 모두 풀 수 있는 방법이므로 차량 배치 프로젝트에 적합하다고 판단하였다.


## 비즈니스 모델
<img width="1263" alt="스크린샷 2024-06-20 오전 1 08 36" src="https://github.com/silverithm/.github/assets/52617204/e7a6019e-f801-4501-bba2-4ad78e2a3122">


## 서비스 흐름
<img width="1149" alt="스크린샷 2024-06-20 오전 2 17 44" src="https://github.com/silverithm/.github/assets/52617204/3c92bba1-0b7f-4290-a93e-3d14d8d9413d">


## 로그인
![로그인2](https://github.com/user-attachments/assets/f5192949-ab38-41ab-a89a-5d62ec5392aa)

## 회원가입
![회원가입1](https://github.com/user-attachments/assets/0e298a90-f24f-49a8-bc40-2115e25df79d)

## 직원 및 어르신 추가
![직원어르신추가6](https://github.com/user-attachments/assets/70cc465c-bc2c-40b5-8f07-faecdae4e015)

## 부부 어르신 추가
![부부어르신추가9](https://github.com/user-attachments/assets/5807d913-75ab-4b37-9690-7f31ae0aafbf)

## 수정 기능
![수정7](https://github.com/user-attachments/assets/09f96432-5ba2-4cdb-9df2-3821226a54aa)

## 삭제 기능
![삭제8](https://github.com/user-attachments/assets/6d6c1401-026d-4b45-b141-09742b70849a)

## 어르신 고정
![배치고정10](https://github.com/user-attachments/assets/27ff36cb-14a5-4299-a071-f8c1ff25748e)

## 단일 경로 길 찾기
![단일경로길찾기3](https://github.com/user-attachments/assets/1aa4e91f-d9d9-47fe-8f08-9104fb600eb4)

## 이전 배치 목록
![이전배치목록4](https://github.com/user-attachments/assets/02906773-7a9b-40a0-8925-751a67dd0c0d)

## 인공지능 차량 배치
![차량배치결과5](https://github.com/user-attachments/assets/3b914087-9355-4d6c-a5ea-257b7bd9fafc)


