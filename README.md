# RJs-Road
Steam Cities: Skyline Road Assets.

# RJs Road?

* 이 도로 에셋은 현재 테스트 중입니다. 처음 만들어 본 도로로, 부족한 점이나 버그가 있을 수 있습니다. 본인의 도시에 바로 적용하지 않는 것을 추천합니다. 제작자의 업로드 혹은 업데이트로 인해 도시의 초기화 문제가 있을 수 있습니다.

* 제작자 마음대로 만든 도로입니다. 사용해보시고 이슈를 알려주시면, 빠르지 않더라도 다음 패치에 염두에 두겠습니다.

* 이 도로의 제작 목적은 '여러 모드의 도움을 받아 최소한의 노력으로 괜찮은 한국 도로의 퀄리티를 내자'입니다. 모드에 의존한다는 것을 기반으로 제작된 도로 에셋으로 모드 없이 사용하면 조금 예쁘지 않을 수 있습니다.

* Small 도로 끼리 같은 텍스처 파일(_d, _p, _r)을 공유합니다. Loading Screen Mod를 사용하시면 메모리 측면에서 절약할 수 있게 고려하여 제작하였지만, 실제로 완벽하게 공유되는지 테스트는 하지 않았습니다.

* 한국 도로의 대부분이 평지인 점을(도로 모델링과 작업량을) 고려하여, 평지에서만 사용 가능한 BASIC 도로 세트입니다. Elevated, Bridge, Slope, Tunnel은 없습니다. 추후 지하도로, 고가도로를 출시할 '수'도 있습니다.

* 1+1, 2+2 등의 대칭 도로는 노드에 정지선과 횡단보도가 그려지며, 1+2 등의 비대칭 도로는 정지선 없이 횡단보도만 그려집니다.

## RJs Road - Small List

### RJs Road - Small (Korea) [TEST]
https://steamcommunity.com/workshop/filedetails/?id=2483978911

|Name (Grid / Parking)|Normal|Front|Alley White|Alley Yellow|One Way|
|---:|:---:|:---:|:---:|:---:|:---:| 
|1 (1.5 / X)|||<img src="_CSL_asset_thumb/_Small/asset_thumb Small 1 AW.png" width="100">|<img src="_CSL_asset_thumb/_Small/asset_thumb Small 1 AY.png" width="100">|<img src="_CSL_asset_thumb/_Small/asset_thumb Small 1 OneWay.png" width="100">|
|1+1 (2 / O)|<img src="_CSL_asset_thumb/_Small/asset_thumb Small 1+1.png" width="100">||<img src="_CSL_asset_thumb/_Small/asset_thumb Small 1+1 AW.png" width="100">|<img src="_CSL_asset_thumb/_Small/asset_thumb Small 1+1 AY.png" width="100">|<img src="_CSL_asset_thumb/_Small/asset_thumb Small 1+1 OW.png" width="100">|
|1+2 (2 / X)|<img src="_CSL_asset_thumb/_Small/asset_thumb Small 1+2.png" width="100">|<img src="_CSL_asset_thumb/_Small/asset_thumb Small 1+2 Front.png" width="100">|||<img src="_CSL_asset_thumb/_Small/asset_thumb Small 1+2 OW.png" width="100">|
|2+2 (2 / X)|<img src="_CSL_asset_thumb/_Small/asset_thumb Small 2+2.png" width="100">|<img src="_CSL_asset_thumb/_Small/asset_thumb Small 2+2 Front.png" width="100">|||<img src="_CSL_asset_thumb/_Small/asset_thumb Small 2+2 OW.png" width="100">|

### RJs Road - Medium (Not yet)

|Name (Grid / Parking)|Normal|Surface|Median (Concrete)|Median (Grass)|
|---:|:---:|:---:|:---:|:---:|
|2+2 (5 / X)||<img src="_CSL_asset_thumb/_Medium/asset_thumb Medium 2+2 S.png" width="100">|<img src="_CSL_asset_thumb/_Medium/asset_thumb Medium 2+2 MC.png" width="100">|<img src="_CSL_asset_thumb/_Medium/asset_thumb Medium 2+2 MG.png" width="100">|
|2+3 (5 / X)||<img src="_CSL_asset_thumb/_Medium/asset_thumb Medium 2+3 S.png" width="100">|<img src="_CSL_asset_thumb/_Medium/asset_thumb Medium 2+3 MC.png" width="100">|<img src="_CSL_asset_thumb/_Medium/asset_thumb Medium 2+3 MG.png" width="100">|
|2+4 (5 / X)|<img src="_CSL_asset_thumb/_Medium/asset_thumb Medium 2+4.png" width="100">||||
asset_thumb Medium 2+2 MC.png
### RJs Road - Large (Next)

|Name (Grid / Parking)|Normal|Front|U Turn|
|---:|:---:|:---:|:---:|
|3+3 (4 / X)|<img src="_CSL_asset_thumb/_Large/asset_thumb Large 3+3.png" width="100">|<img src="_CSL_asset_thumb/_Large/asset_thumb Large 3+3 Front.png" width="100">|<img src="_CSL_asset_thumb/_Large/asset_thumb Large 3+3 UT.png" width="100">|
|3+4 (4.25 / X)|<img src="_CSL_asset_thumb/_Large/asset_thumb Large 3+4.png" width="100">|<img src="_CSL_asset_thumb/_Large/asset_thumb Large 3+4.png" width="100">||
|4+4 (4.5 / X)|<img src="_CSL_asset_thumb/_Large/asset_thumb Large 4+4 Front.png" width="100">|<img src="_CSL_asset_thumb/_Large/asset_thumb Large 4+4 Front.png" width="100">|<img src="_CSL_asset_thumb/_Large/asset_thumb Large 4+4 UT.png" width="100">|
|4+5 (4.75 / X)||||
|5+5 (5 / X)||||

### RJs Road - Overpass/Underpass (Not yet)

|Name (Grid / Parking)|Normal||
|---:|:---:|:---:|
||||

### RJs Road - BRT (Not yet)

|Name (Grid / Parking)|Normal||
|---:|:---:|:---:|
||||


## 도로 라인과 횡단보도의 관계

### Basic 
**A+A** = Segment (S or M or L) / Node SL (ex: 1+1, 3+3, 4+4 ...)

**A+B** = Segment (S or M or L) / Node NSL (ex: 1+2, 3+4, 4+5 ...)

* SL: Stop Line
* NSL: No Stop Line


## Node Controller를 위한 RGBA

White 145 145 145 255

Yellow 150 140 50 200

## 함께 사용하길 '적극' 권장하는 모드 (퀄리티)

Loading Screen Mod
https://steamcommunity.com/sharedfiles/filedetails/?id=667342976

Move It
https://steamcommunity.com/sharedfiles/filedetails/?id=1619685021

TM:PE V11 STABLE (Traffic Manager: President Edition)
https://steamcommunity.com/sharedfiles/filedetails/?id=1637663252

Hide TMPE crosswalks V3.0 [stable]
https://steamcommunity.com/sharedfiles/filedetails/?id=1934023593

Network Skins (Sunset Harbor compatible)
https://steamcommunity.com/sharedfiles/filedetails/?id=1758376843

Intersection Marking Tool 1.7.1
https://steamcommunity.com/sharedfiles/filedetails/?id=2140418403

Node Controller Renewal 3.0 (단독 사용)
https://steamcommunity.com/sharedfiles/filedetails/?id=2472062376

Node controller V2.2 [Beta] (단독 사용)
https://steamcommunity.com/sharedfiles/filedetails/?id=2085403475

## 함께 사용하길 권장하는 모드 (편리함)

Fine Road Anarchy 2.0.2
https://steamcommunity.com/sharedfiles/filedetails/?id=1844440354

Fine Road Tool 2.0.4
https://steamcommunity.com/sharedfiles/filedetails/?id=1844442251

Advanced Road Tools
https://steamcommunity.com/sharedfiles/filedetails/?id=1925527132

## 인지하고 있는 이슈

* 횡단보도 제거 시 잔상이 남는 문제
 2+2를 제외한 나머지 도로는 RM Mode 3.0으로 횡단보도 제거 시 검성색의 잔상이 생깁니다. 시티즈의 세그먼트와 노드 렌더링에 깊게 관여할 수 없기 때문에 생기는 문제로 예상됩니다. 또한, 잔상이 남지 않아도 보행자 도로 부분의 텍스처가 살짝 뭉개지는 현상이 있습니다.

* 비대칭 도로의 Bend 부분 텍스처가 정확하게 출력되지 않는 문제
 Move It으로 아주 미세하게 조정해야 정확하게 표현되는 문제가 있습니다. 도로 제작의 경험치가 쌓이고 많은 시간을 들여 연구해야 메커니즘을 조금 알게 될 때, 고칠 수 있을 것으로 생각됩니다. 이에 관한 팁이 있다면 알려주시면 감사하겠습니다.
Node Controller 모드를 이용하여 조정할 수 있습니다.

* 사용하시고 발생한 오류나 이슈를 제보해주세요!
