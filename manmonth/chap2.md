# 계획이 실패하는 이유

## 1. Optimism


## 2. Man-Month
"한 사람이 한 달 동안 할 수 있는 일" 로 작업의 사이즈를 측정하는 것은 사람이 많아지고 사람 간 작업의 연관성이 많아질수록 좋은 방법이 아니다.

1. 작업이 Partition 가능하지 않을 수 있음
2. 작업간의 dependency가 있을 경우 communication overhead 발생 -> overhead가 작업 분할 효과보다 클 경우에는 사람을 추가하는 것이 오히려 부정적인 효과를 준다

## 3. System Testing
1. 1/2 Planning/Design
2. 1/6 Coding
3. 1/4 Unit/Component Testing and Early System Testing
4. 1/4 Full System Testing

->테스트에도 많은 시간을 사용해야 함

## 4. 고객을 위한 일정 선정
고객이 일정 선정에 관여할 수 있다. 계획을 고객과 공유하는 것이 필요

## 5. Regenerative Schedule Disaster
계획이 딜레이 되었을 때: 
1. Reschedule에 충분한 시간을 사용해야 한다.
2. 기한을 미룰 수 없을 때: 작업량을 줄여야 한다.
3. 작업 완성 기한은 Sequential한 task의 양에 의해 정해지고, 필요한 프로그래머의 수는 Parallel 한 task의 양에 의해 정해진다.
4. 완성이 가까운 프로젝트에서 새 프로그래머를 팀에 추가하는 것은 많은 지연을 유발한다.
