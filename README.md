# eda-repo-1
EDA 프로젝트 1조 저장소. 리그오브레전드의 승률 요인 분석

# Requirement
1. 주제 선정이유
2. **티어별 선호 챔피언 분석**
   ![op gg](https://github.com/addinedu-amr-4th/eda-repo-1/assets/91608731/3baac776-2fea-41e9-a9eb-a09a1154ab6d)

   - op.gg, lol.ps 등 각종 롤 분석 사이트에서는 실력에 티어(랭킹)에 따라서 그 실력대에 잘 통하는 챔피언이 정리되어 있습니다.
     가장 효율이 좋은 챔피언인 1티어 챔피언이라 하더라도 승률이 무조건 높은것이 아니며 플레이하는 유저가 선호하지 않습니다.
     
     **이에** 저희 팀에서는 티어별, 라인별 어떠한 챔피언이 유리하며 승률과 선호률이 어떻게 되는지 파악하고
     후에 진행할 유저 게임 대전기록을 분석해 해당 유저에게 어떠한 챔피언을 하면 좋을지 추천하고자 합니다.

4. 어떤 아이템과 챔피언을 사용하는게 유저의 승률을 높일수 있는가?
5. 유저의 개인 데이터를 사용하여 유저의 선호 챔피언이 유저에게 적합한지 판단

# Requirement skills
1. 데이터 크롤링을 위한 selenium, beautifulsoup
2. 데이터 프레임 생성을 위한 pandas
3. 데이터 관리를 위한 mysql
4. 데이터 시각화를 위한 seaborn

# LOL에 대한 간단한 배경지식
- 레드팀(위), 블루팀(아래)로 상대팀과  5:5 대결
- 승패는 상대편의 넥서스를 먼저 파괴하는 팀이 승리한다.     
- 총 다섯 라인(역할군) 존재 
 - 탑, 정글, 미드, 바텀, 서폿 
- KDA : Kill/Death/Assistance로 상대방 챔피언을 직접 처치하거나 도움을 줄 시, 골드 생성 
- 생성된 골드로 아이템 구매 가능 
- 메타마다 게임의 흐름이 바뀜
 - ex) 챔피언, 아이템
- 현재까지 총 164명의 챔피언이 존재 (2023.09 기준)

# 데이터 크롤링 사이트
- [LOL](https://www.leagueoflegends.com/ko-kr/champions/)
- [LOL_Inven](https://lol.inven.co.kr/dataninfo/item/list.php)
- [LOL_PS](https://lol.ps/)
- [OP.GG](https://www.op.gg/)
