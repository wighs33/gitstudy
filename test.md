# 1. 게임의 소개

- 제목 : 크레처디펜스

- 워크래프트에 있는 원피스 랜덤 디펜스를 카피했습니다.
  
  이 게임은 유닛을 랜덤으로 얻어서 조합하여 더 강한유닛을 만들어서 사각형을 도는 몬스터들을 처치하는 게임입니다.
  
  스테이지가 늘어날수록 몬스터의 체력이 많아지고 몬스터가 일정 수를 넘으면 게임오버가 되고 스테이지를 전부 깨면 클리어가 됩니다.
  
  스테이지가 늘어나는데 스토리모드를 다 못깨도 게임오버가 됩니다. 스토리모드를 깨려면 스토리 건물을 파괴해야 합니다.
  
  ![Alt text](https://media.discordapp.net/attachments/374730378738532352/719922277067784293/Warcraft_III_2020-06-09_11_31_23.png?width=814&height=458)

- 크레처디펜스는 유닛을 조합하여 강한 유닛으로 만들고 몬스터를 처치하는 디펜스 게임입니다.

  유닛뿐만 아니라 몬스터를 공격하는 건물도 설치할 수 있습니다.
  
  보스몬스터는 유닛을 공격합니다.
  
  몬스터를 쓰러트릴 때마다 골드를 얻을 수 있고 골드로 기본유닛과 조합유닛을 구매할 수 있습니다.
  
  스테이지를 완료할 때마다 기본유닛을 랜덤으로 3개 얻을 수 있습니다.
  
  스테이지가 늘어날수록 몬스터의 체력이 많아지고 몬스터가 일정 수를 넘으면 게임오버가 되고 스테이지를 전부 깨면 클리어가 됩니다.

# 2. GameState (Scene) 의 수 및 각각의 이름

scene의 수 4개

로고화면, 타이틀화면, 게임플레이화면, 클리어기록화면

# 3. 각 GameState 별 다음 항목

## 로고화면

- 한국산업기술대로고가 나타난다.

- 3초뒤에 타이틀화면으로 넘어간다.

## 타이틀화면

- play버튼을 누르면 게임이 플레이되고 exit버튼을 누르면 게임이 종료되고, record버튼을 누르면 클리어기록이 나타난다.

- play버튼, exit버튼
```
  마우스 좌클릭 : 해당 버튼의 이벤트를 실행한다.
```
- play버튼을 누르면 게임플레이화면으로 넘어간다.

## 게임플레이화면

- 게임을 플레이할 수 있는 화면이다.

- 유닛, 몬스터, 건물, 맵
```
  wasd : 화면의 이동
  
  마우스 드래그 : 유닛그룹선택
  
  마우스 좌클릭 : 유닛/건물 선택
  
  마우스 우클릭 : 유닛이동
```
- 게임오버하면 타이틀화면으로 넘어가고 클리어하면 클리어기록화면으로 넘어간다.

## 클리어기록화면

- 게임클리어했을 때 이름과 상위조합유닛을 기록한다.

- 입력버튼(누르면 입력이된다.), 취소버튼(입력을 취소한다.)
```
  마우스 좌클릭 : 해당 버튼의 이벤트를 실행한다.
```
- 기록이 끝나거나 취소하면 타이틀화면으로 넘어간다.

# 4. 필요한 기술

- 다른 과목에서 배운 기술 : 파일입출력

- 이 과목에서 배울 것으로 기대되는 기술 : 파일입출력
