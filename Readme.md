## MMORPG 거래 네트워크 분석을 통한 부정행위 탐지
게임 내 봇 사용자와 작업장(gold farming group)을 탐지하기 위해, '블레이드&소울'의 거래데이터 1000만건에 대한 네트워크 분석을 하였습니다.  
이후 봇과 일반 유저의 플레이 스타일에 대한 segmentation을 토대로, 특정된 네트워크 노드들과 비교 분석하였습니다.    
분석 에세이 전문과 데이터셋은 아래에서 확인하실 수 있습니다.
- [Analysis report](https://zest-cloud-1fd.notion.site/MMORPG-gfg-f4c75a27e42c4ee089bead0eaed53816)
- [Dataset](https://danbi-ncsoft.github.io/OpenData/)

### Network analysis
- community detection
- k-means clustering by network features
- visualization by Gephi

  <img src="img/cluster2.png" width="350" height="350">
  <img src="img/cluster1.png" width="350" height="350">

### User clustering
- Personal activities
- Raid / Inzone
- Battle
- Social activities

<img src="img/segment1.png" width="800" height="300">
<img src="img/segment2.png" width="800" height="300">
