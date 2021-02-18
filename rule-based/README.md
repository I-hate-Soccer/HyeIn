# AI Soccer

## Rule-Based Algoritm

### 1. rulebasedE(player.py)
**상대 팀 골대에 일렬로 서서 방어하는 Agent**
> 우리 팀 5명 모두 상대 팀 골대에 일렬로 서서 상대 팀이 자책골을 넣는 경우를 방어하고,
상대 팀이 점수를 많이 낼 수 있도록 하는 Agent 
    
* players.py 파일에서 포지션마다 (x, y) 좌표를 수정하여 골대 앞에 서 있도록 구현
    
### 2. rulebasedH(player.py)
**Penalty Area밖에서 수비하는 Agent**
>골키퍼를 제외한 우리 팀이 우리 팀 골대 앞 Penalty Area 바깥에서 각자 지정된 영역에서 수비
    
* 포지션별로 위치하는 영역을 변경하고, 골키퍼는 기존 위치에서 기존 역할을 수행
* 특수한 상황 즉, PENALTYKICK, KICKOFF, CORNERKICK 등을 제외하고는 각자 정해진 위치에서 수비 역할을 수행
