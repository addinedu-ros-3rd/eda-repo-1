# eda-repo-1
EDA 프로젝트 1조 저장소. 리그오브레전드의 승률 요인 분석

# Requirement
1. 주제 선정이유
2. 티어별 선호 챔피언 분석
3. 어떤 아이템과 챔피언을 사용하는게 유저의 승률을 높일수 있는가?
4. 유저의 개인 데이터를 사용하여 유저의 선호 챔피언이 유저에게 적합한지 판단

# Requirement skills
1. 데이터 크롤링을 위한 selenium, beautifulsoup
2. 데이터 프레임 생성을 위한 pandas
3. 데이터 관리를 위한 mysql
4. 데이터 시각화를 위한 seaborn

# LOL에 대한 간단한 배경지식
레드팀(위), 블루팀(아래)로 상대팀과  5:5 대결
승패는 상대편의 넥서스를 먼저 파괴하는 팀이 승리한다.     
총 다섯 라인(역할군) 존재 
- 탑, 정글, 미드, 바텀, 서폿 
KDA : Kill/Death/Assistance로 상대방 챔피언을 직접 처치하거나 도움을 줄 시, 골드 생성 
생성된 골드로 아이템 구매 가능 
메타마다 게임의 흐름이 바뀜
ex) 챔피언, 아이템
현재까지 총 164명의 챔피언이 존재 (2023.09 기준)

# 데이터 크롤링 사이트
[LOL](https://www.leagueoflegends.com/ko-kr/champions/)
[LOL_Inven](https://lol.inven.co.kr/dataninfo/item/list.php)
[LOL_PS](https://lol.ps/)
[OP.GG](https://www.op.gg/)
