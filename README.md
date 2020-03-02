# DevilFarm_DEVLOG
> [Project Tumblebug link](https://tumblbug.com/devilsfarm)
## 개요
```
모바일 게임 '농사대마왕' 개발 일지이다.
```
## 개발노트
#### 0.1.9.8b 패치노트
```
1. 새로운 마왕 등장!
- 부자가 된 마왕
- 나 마왕 아니다
- 매드 사이언티스트
- 좀비 마왕
- 슬라임 마왕
- 농사의 달인

2. 신규 시나리오 추가
- 새로운 시나리오 추가
- 기존 시나리오 리소스 개편

3. 사운드
- 인게임 내 다수 적용
  1. 물 주기
  2. 피격
  3. 이동
  4. 배경음
- 로비 버튼 각각 테마에 맞는 효과음 적용

4. 시스템
- 코스튬 인앱 결제
- 보상을 받을 수 있는 선택형 광고
- 주간 랭킹 보상 지급
- 우편 수신함
- 텀블벅 쿠폰 적용 가능
- 이전에 사용했던 코스튬 저장
- 크레딧

5. 버그 수정
- 하기쉬룸의 독에 당할 시 스턴 모션이 아닌 피격 모션이 나오던 문제 수정
- 코스튬 구입에 드는 보석의 수가 75개로 고정이던 현상 수정 (전 개발자가 남긴 오래된 유산)
- 마룡과 수확 애니메이션 수정
- 인게임 내 종료 버튼 누를시 무한 로딩되던 현상 수정
```
#### 2020-03-02
```
1. 우편 UI 개편
- 새로운 우편 UI 리소스 적용

2. 버그 수정
- 코스튬 구입에 드는 보석의 수가 75개로 고정이던 현상 수정 (전 개발자가 남긴 오래된 유산)
```
#### 2020-03-01
```
1. 우편 발송
- 관리자 우편 발송 기능 추가
- 아이템 발송 기능 추가

2. 주간 랭킹 보상
- 우편을 통한 주간 랭킹 지급 기능 구현
```
#### 2020-02-29
```
1. 인앱 결제
- 구글 플레이스토어 결제 기능 추가
- 코스튬 구입 가능

2. 광고
- 광고를 통해 보석 획득 가능

3. 크레딧
- 개발진, 출처 표기 등
```
#### 2020-02-28
```
1. 코스튬 추가
- 부자가 된 마왕

2. 코스튬 수정
- 좀비
  1. 스킬 발동 시 식물을 수확 -> 스킬 발동 시 식물을 먹음
  2. 식물 먹히는 연출 변경
- 매드 사이언티스트
  1. 왼쪽 물 주는 모션 수정
  2. 스킬 발동 후 코스튬이 빨갛게 물듬
- 슬라임, 좀비, 매드 사이언티스트 등 스킬을 발동할 때 딜레이가 있는 스킨들은 이제 화면이 어두워지고 게임이 잠시 일시정지됨

3. 쿠폰
- 텀블벅 쿠폰 사용 가능

4. 사운드
- 인게임 내 다수 적용
  1. 물 주기
  2. 피격
  3. 이동
  4. 배경음
- 로비 버튼 각각 테마에 맞는 효과음 적용

5. 기타 수정 사항
- 하기쉬룸의 독에 당할 시 스턴 모션이 아닌 피격 모션이 나오던 문제 수정
```
#### 2020-02-27
```
1. 코스튬 추가
- 나 마왕 아니다
- 매드 사이언티스트
- 좀비 마왕
- 슬라임 마왕
- 농사의 달인
```
#### 2020-02-18
```
1. 로비
- 시나리오 해금 공식 변경
  (변경 전) 5000점 단위 해금
  (변경 후) 자유로운 단위 해금
- 코스튬 해금 버튼 추가
```
#### 2020-01-08
```
1. 버그 수정
- 마룡과 수확 애니메이션 수정
- iOS 자동 로그인 무한 로딩 현상 수정
- 인게임 내 종료 버튼 누를시 무한 로딩되던 현상 수정
```
#### 2020-01-07
```
1. 로비
- 랭킹 UI 대규모 개편
  1. 랭킹 초기화 날짜 표시
  2. 현재 랭킹에 따라 받을 수 있는 보상 표시
  3. 플레이어의 경쟁자 랭크가 이제 하단에 표시됨
  4. 1~3 등 달성시 이벤트 발생
```
#### 2020-01-04
```
1. 인게임
- 미션 매커니즘 변경
  (변경 전) 식물 무작위 할당
  (변경 후) 현재 필드에 나와있는 식물을 파악하여 미션 할당
- 새로운 식물 '개나소나무' 추가
- 보스 스폰 순서 무작위로 변경

2. 로비
- 식물 미리보기 이미지 추가
```
#### 2020-01-02
```
1. 인게임
- 하기쉬룸 중독 이펙트 추가

2. 로비
- 랭킹 UI 업데이트
```
#### 0.1.9.5 패치노트
```
1. 새로운 식물 추가 및 식물 해금 시스템
 -특정 식물을 일정 횟수만큼 수확하면 새로운 식물이 해금됩니다. 수확 횟수는 매 판마다 누적됩니다. ex) 켈베로풀을 20회 수확 시 발바나나가 등장합니다.
 [새로운 식물] 
 -뭐임오렌지나무
 -발바나나
 -능구렁쿨
 -메롱
 -하기쉬룸
 -마룡과
 -아오밥나무

2. 알프레드의 미션
 -게임 진행 중 알프레드가 등장하여 플레이어에게 미션을 제공합니다. 미션의 성공 여부에 따라 보상 또는 페널티가 주어집니다.

3. 보석 획득
 -식물 수확 시 낮은 확률로 보석 획득이 가능합니다. (단, 게임이 정상적으로 종료되어야 해당 게임에서 누적된 보석을 획득하실 수 있습니다.)

4. 시각 정보 업데이트
 -식물에게 물을 줄 때 하트 효과가 생깁니다.
 -보석 획득 시 보석 효과가 생깁니다.
 -식물이 위협할 때도 수확 가능 여부를 확인 할 수 있습니다.
 -로비에서 상호 작용이 가능한 오브젝트들의 가시성을 높였습니다.

5. 도감 UI 변경
 -도감 미리보기를 식물 정보와 함께 확인할 수 있습니다.

6. 기타 수정 사항
 -조작 민감도를 개선하였습니다.
 -잘못 적용되었던 점수 계산 공식을 수정하였습니다.
 -게임 속도가 비정상적으로 빨라지던 현상을 수정하였습니다.
 -튜토리얼이 멈추던 현상을 수정하였습니다.
 -카운터 애니메이션이 게임 속도에 영향을 받던 것을 수정하였습니다.
```
#### 2019-12-29
```
1. 인게임
- 새로운 식물 '아오밥나무' 추가
- 하기쉬롬 이펙트 변경
- 식물 가꿀 시 하트 이펙트 추가

2. 로비
- 도감 이미지 업데이트
```
#### 2019-12-22
```
1. 인게임
- 물풍선 애니메이션 속도 증가
- 미션 시스템 추가
  1. 일정 간격으로 플레이어에게 미션이 주어짐
  2. 해결 여부에 따라 보상 또는 페널티가 주어짐
- 식물 배치 알고리즘 변경
- 최소 조작 범위 증가(터치만 해도 움직이던 문제 완화)

2. 로비
- 새로운 도감 UI 리소스 추가

3. 버그 수정
- 식물이 수확됬는데도 공격 표시가 뜨던 문제 수정
- 식물들의 공격효과 애니메이션 속도 조정
```
#### 2019-12-07
```
1. 시스템
- 식물 해금 시스템 UI 구축
```
#### 2019-11-30
```
1. 인게임
- 게임 종료 후 최종 결과창 더 빠르게 확인 가능
- 씨앗 터지는 단계 세분화, 이제 공격 하는 식물에게 물 주는 것이 가능한지 확인 가능

2. 시스템
- 회원가입 UI 나가기 버튼 추가
- 식물 해금 기초 스크립트 작성
```
#### 2019-11-26
```
[회의록]
1. 게임 종료 결과창 더 빠르게 뜨기
2. 회원가입 UI에 나가기 버튼 추가
3. 물풍선 애니메이션이 timeScale에 영향을 받지 않도록 하기
4. 물풍선 애니메이션 단계 나누기
5. 토끼 코스튬 패시브 적용
6. 식물 수확 시 일정 확률로 보석 드랍하기
7. 미션 시스템 추가
8. 식물 해금 이벤트
9. 튜토리얼 수정
```
#### 2019-11-20
```
1. 인게임
- 게임 종료 후 보너스 점수 중 '물 준 횟수'에 대한 공식 변경
  (기존) 물 준 횟수 * 20
  (변경)
  1  ~ 20회 -> 물 준 횟수 * 10
  21 ~ 40회 -> 물 준 횟수 * 20
  41 ~ 60회 -> 물 준 횟수 * 25
  61 ~      -> 물 준 횟수 * 30
- 게임 종료 후 스코어창에서 보너스 점수 집계 속도 증가

2. 시스템
- 로딩 패널 이미지 크기 증가

3. 버그 수정
- 플레이어가 스턴 상태에서도 식물에게 물을 주던 현상 수정
```
#### 2019-11-18
```
1. 튜토리얼
- 튜토리얼 진행 속도 상향
  1. 안내선 반짝임 효과 횟수 감소
  2. 대화 스크립트 간 간격 감소

2. 시스템
- 동기 로딩 대부분을 비동기로 수정 및 로딩 패널 적용

3. 인게임
- 게임 시작 시, 그리고 일시정지 후 다시 시작시 3초간의 딜레이 카운터 추가

4. 버그 수정
- 튜토리얼 멈춤 현상 수정
- 딜레이 카운터가 timeScale에 영향을 받던 문제를 숮ㅇ
```
#### 2019-11-16
```
1. 인게임
- 게임 종료 시 주어지는 보너스 점수 기준 중 '수확 횟수'가 '물 주는 횟수'로 변경됨
- 터치 감도 수정

2. 로비
- 식물 해금 조건 UI 리소스 교체
- 스킬 설명 UI 위치 조정

3. 시나리오
- 아직 공개되지 않은 시나리오에 대한 미리보기 이미지 추가
- '5000'점 시나리오 추가

4. 시스템
- 모든 비동기 로딩에 로딩 패널 추가

5. 버그 수정
- 게임 종료 시 인게임에 적용되던 시간 가속효과가 다른 씬에도 적용되던 문제 수정
```

#### 2019-11-10
```
1. 버그 수정
- iOS 로그인 씬 무한 로딩 문제 수정
- 시나리오 패널 액자 크기가 해상도에 따라 깨지던 문제 수정
- 특정 점수 달성 시 보여지는 시나리오 씬이 나타나지 않던 문제 수정
- 게임이 일시정지 됬는데도 플레이어가 움직이던 문제 수정
```
