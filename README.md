# BwapiBotByBwmirror

자세한 설명 : https://sscaitournament.com/index.php?action=tutorial

# 개발에 필요한 요소들

- Download and unzip [StarCraft 1.16.1](http://www.cs.mun.ca/~dchurchill/starcraftaicomp/files/Starcraft_1161.zip) from Memorial University, hosted with permission from Activision Blizzard. Newer versions of StarCraft like Remastered are incompatible with BWAPI.
  - 위 링크를 통해 게임을 받고 원하는 최상위 루트에 StarCraft 폴더에 저장한다.
- Download the [SSCAI map pack](https://sscaitournament.com/files/sscai_map_pack.zip) and extract the included sscai directory into Starcraft/maps/
  - 맵을 다운받아서 설치한 게임에 maps 하위에 압축 해제한다.
- Install the latest [BWAPI](https://github.com/bwapi/bwapi/releases). At time of writing, this is version 4.4.0
  - BWAPI를 받아서 설치한다. 설치 할때 게임 위치를 지정해준다. Starcraft\BWAPI\Chaoslauncher 위치에 런처가 있고 코드를 실행할 때 런처를 구동해줘야 한다.
- Chaoslauncher 설정
  - plugins : BWAPI Injector (Release), W-MODE 체크
    - W-MODE는 윈도우를 창모드로 실행하게 해준다.(해상도가 낮기 때문에 충돌이슈로 무조건 체크 해주는게 이득)
  - settings : Warn about missing adminprivilegues 체크 해제

