# Jstris 가이드

간단한 온라인 멀티플레이어 블록 게임 Jstris를 찾아오신 여러분을 환영합니다.
Jstris는 랙 없이 쾌적한 게임플레이를 기반으로 세계의 재능있는 플레이어들을 불러들이고 있습니다. 이 가이드에서는 게임의 기본 기능들에 대해 안내합니다.

> *문서 내의 용어들은 한국어 인터페이스에서도 영어로 표시되는 경우, 한국 커뮤니티 내에서 정의된 용어들이 있을 것이라 판단하여 임시로 만든 나름의 한국어 표기와 영어 표기를 병행하였습니다.*  
> *병행 표기는 목차, 혹은 가장 처음에 나오는 부분에서만 하였습니다.*  
> *멀티플레이어 방의 경우는 모든 언어에서 영어로 표기되므로 영어로만 표기해두었습니다.*

- - -

**목차**

- [개요](#개요)
- [멀티플레이어](#멀티플레이어)
  - [Bot Room](#bot-room)
  - [1v1 Room](#1v1-room)
  - [Cheese Room](#cheese-room)
  - [Speed Limit Room](#speed-limit-room)
  - [Team Room](#team-room)
- [싱글플레이어](#싱글플레이어)
  - [스프린트](#스프린트)
  - [치즈 레이스](#치즈-레이스)
  - [울트라](#울트라)
  - [생존](#생존)
  - [맵](#맵)
- [설정](#설정)
  - [공격 및 콤보 딜량 표 (Attack and Combo table)](#공격-및-콤보-딜량-표)
  - [쓰레기 분배 방식 (Garbage Distribution)](#쓰레기-분배-방식)
  - [쓰레기 방어 방식 (Garbage Blocking)](#쓰레기-방어-방식)
  - [랜더마이저 (Randomizer)](#랜더마이저)
  - [넥스트 (Previews)](#넥스트)
  - [솔리드 가비지 (Solid Garbage)](#솔리드-가비지)
  - [클리어 딜레이 (Clear Delay)](#클리어-딜레이)
  - [쓰레기 딜레이 (Garbage Delay)](#쓰레기-딜레이)
  - [난잡도 (Messiness)](#난잡도)
- [자주묻는 질문](#자주-묻는-질문)
  - [Q: 게임 결과 표의 줄임말들은 무슨 뜻인가요?](#q-게임-결과-표의-줄임말들은-무슨-뜻인가요)
  - [Q: DAS가 뭔가요?](#q-das가-뭔가요)
  - [Q: ARR이 뭔가요?](#q-arr이-뭔가요)
  - [Q: 피네스(Finesse)가 뭔가요?](#q-피네스가-뭔가요)
  - [Q: 비밀 방을 만들 수 있나요?](#q-비밀-방을-만들-수-있나요)
  - [Q: Jstris를 오프라인으로 플레이할 수 있나요?](#q-jstris를-오프라인으로-플레이할-수-있나요)
- [추가 정보](#추가-정보)

- - -

# 개요

Jstris에서는 많은 블록 게임에서 쓰는 기본 메커니즘인 가이드라인 룰을 사용합니다. Jstris의 중요한 특징 중 하나는 광범위하게 사용되는 리플레이 기능입니다. 게임 모드에 상관없이 플레이를 마칠 때마다 리플레이가 만들어집니다. 자신의 플레이를 보고 분석하는 것은 실력 향상을 위해 필수적이며, Jstris의 리플레이 기능은 이를 정말 쉽게 만들어줄 것입니다.

다른 사이트와는 달리 Jstris의 리더보드는 핵이나 치트로부터 완전히 보호되고 있습니다. 모더레이터들이 밤낮으로 수상한 기록들을 찾아 제거하며 세계 기록들의 신뢰성을 보장하기 위해 노력하고 있습니다.

Jstris 계정을 만들어보세요. 화면 우측 상단의 *가입*을 클릭해 만들 수 있으며, 이메일, 이름, 암호만 쓰면 됩니다. 계정을 만들면 각종 싱글플레이어 최고 기록, 멀티플레이어 통계, 실력 향상 통계, 리플레이 등 다양한 통계를 확인하실 수 있습니다. 그리고 리더보드에도 이름을 올릴 수 있습니다 (계정이 없는 플레이어의 기록은 리더보드에 올라가지 않습니다).

![introduction][image2]
- - -

# 멀티플레이어

## Bot Room

사이트에 접속하는 모든 플레이어는 **Bot Room**에 입장하게 됩니다. 언제나 한 명의 봇 플레이어가 상주하고 있기 때문에 Bot Room이라고 부릅니다. 봇은 항상 모든 상대 유저들 사이에서 좌측 상단에 위치하고 있으며, 빨간 색 필드를 보고 구별할 수 있습니다.

![MisaMino bot in opponents view][image4]

Jstris에는 총 4개의 봇이 있습니다. 아래에 봇의 이름과 해당 봇을 사용하는 명령어를 봇의 강한 정도에 따라 나열하였습니다.

- MisaMino: `/changeBot misamino`
- Real_Block: `/changeBot real`
- ~~jez_Block: `/changeBot jez`~~ (2018.09.21에 없어짐)
- ~~Fool bot: `/changeBot fool`~~ (2018.09.21에 없어짐)

*\*모든 명령어는 게임이 시작되기 전에 입력해야 합니다. 게임 진행중에는 명령어의 효과가 없습니다.*

MisaMino는 지원하는 봇 중에서 현재 가장 강한 봇입니다. 아마 현존하는 가장 강력한 블록 놓기 봇일 것입니다. 최고 속도인 5 PPS(초당 피스(piece) 수)를 적용하면 가장 강력한 플레이어들도 일대일 모드에서 손쉽게 부숴버릴 수 있는 무시무시한 상대가 됩니다. 하지만 Bot Room에 5명 이상의 사람이 있을 경우 성능이 떨어져 순식간에 Top out 하기 쉽습니다.

다음으로 알려드릴 명령어는 `/botPPS`입니다. 봇의 속도를 변경하려면 `/bot ?`를 입력하세요. 이 때 ? 는 0.3 ~ 5 사이의 숫자입니다. 예를 들어 봇이 2 PPS의 속도로 플레이하게 하려면 `/bot 2`를 입력합니다. 1.73 PPS로 플레이하게 하려면 `/bot 1.73`을 입력합니다.

Bot Room은 때로 가혹한 경기장이 될 수 있습니다. Jstris의 특징은 이제 갓 시작한 초보자들과 세계구급 고수들, 그리고 그 사이의 모든 플레이어들을 한 곳에 섞어놓는다는 것입니다. 더 이상 플레이하지 않고 구경만 하고 싶어질 때는, `/spectate`또는 `/spec`을 입력하세요. 다시 플레이하려면 `/play`를 입력합니다.

## 1v1 Room

Bot Room만 있는 것이 아닙니다. 전체 방 목록을 보려면 플레이필드 좌측 하단의 *로비*를 클릭하세요. Jstris에서 Bot Room 다음으로 가장 사람이 많은 방은 **1v1 Room** 입니다. 최대 2명의 플레이어가 입장할 수 있지만 방이 찼을 경우 누구나 들어와서 관전을 할 수 있습니다. 친구와 합의점을 찾아야 할 때나 실력이 맞는 플레이어와 맞붙어보고 싶을 때 이 방을 사용하세요. 점수를 초기화하고 싶을 때는 `/resetCounter`를 입력합니다.

## Cheese Room

쓰레기 혹은 치즈는 멀티플레이어 모드에서 상대를 녹아웃(knock out)시키기 위한 주된 방법이며, 그러므로 이 치즈를 지워내려가는 것은 중요한 기술일 것입니다. **Cheese Room**에서 쓰레기 줄을 빠르게 지우는 연습을 하세요. 이 방에서는 10줄의 쓰레기를 받고 게임을 시작하며, 이를 첫번째로 모두 지운 사람이 승리합니다. 10줄이 너무 쉬운가요? 그렇다면 `/set height ?` 명령어를 써서 줄 수를 바꿔봅시다. ? 에는 1~20 사이의 숫자를 입력합니다.

## Speed Limit Room

친구와 플레이하고 싶은데 실력의 차이가 너무 크다구요? 혹은 이제 막 시작한 초보자인데 프로들로 가득찬 Bot Room에서 시작하자마자 지기만 하는 것에 질렸나요? 이런 분들을 위해 Speed Limit Room이 있습니다. 이 방의 기본 속도 값은 1.5 PPS이며, 이는 플레이어가 1.5 PPS를 초과할 수 없다는 뜻입니다. 이보다 더 빠르게 플레이하려고 할 경우 플레이어의 입력이 잠시동안 막힐 것입니다. 모든 Speed Limit Room은 다음과 같은 속도계 아이콘을 통해 구별할 수 있습니다 - [SPEEDOMETER_ICON]. 플레이어가 만든 룸은 0~20 PPS 사이의 속도 제한을 가질 수 있습니다.

![the lobby, where you can join and create rooms][image5]

## Team Room

마지막으로 보여드릴 기본 방은 **Team Room**입니다. 빨강과 파랑 중에서 들어갈 팀을 고르고, 팀의 영광을 위해 플레이하세요.

![team game in progress][image11]

- - -

# 싱글플레이어

## 스프린트

기본적이고 제일 간단한 모드인 **스프린트**는 Jstris에서 가장 인기 있는 싱글플레이어 모드입니다. X 줄을 가능한 빨리 지우세요. Jstris에서는 20, 40, 100, 1000라인 스프린트를 플레이할 수 있습니다.

## 치즈 레이스

스프린트보다 조심스럽고 신중한 모드인 **치즈 레이스**는 쓰레기 줄을 최대한 효율적으로 지워야하는 모드입니다. Jstris에서는 10, 18, 100, ∞ 라인 치즈 레이스를 플레이할 수 있습니다.

## 울트라

스코어 중심의, 티스핀과 백투백 등의 고급 기술을 활용해야 하는 **울트라**는 멀티플레이어 모드에서 필요한 공격 기량을 기를 수 있는 훌륭한 모드입니다.

## 생존

아마도 싱글플레이어 모드 중에서도 제일 도전적인 모드일 **생존**은 치즈 레이스와 유사하지만 쓰레기가 초당 1줄씩 올라오는 모드입니다. 올라오는 줄들을 지워가며 가능한 오랫동안 버티세요.

## 맵

**맵** 모드가 Jstris에 새롭게 추가되었습니다. 맵 모드는 약간의 창의력과 함께 난해하고 특이한 상황에서의 다운스택 효율성을 요구합니다. *맵 디자이너*에서 맵을 만드세요. 만든 맵을 발표하면 세계 각지에서 최단 시간을 두고 플레이어들이 경쟁할 수 있습니다. 하루 최대 5개의 맵을 발표할 수 있으며, 발표하지 않은 맵은 최대 10개까지 보유할 수 있습니다. 맵 모드에도 리더보드가 있습니다. 각 맵에서는 상위 3명까지 금은동 메달을 부여합니다. 여러 맵에서 메달을 얻어 리더보드에 이름을 올리세요!

*\*맵 리더보드는 매 시 30분마다 업데이트 되므로, 순위 변동은 즉각적으로 표시되지 않습니다.*

- - -

# 설정

현재 접속한 방의 설정을 보려면 `/config`을 입력하세요. 이 장에서는 설정의 각 항목에 대해 알아보겠습니다.

## 공격 및 콤보 딜량 표

Jstris의 기본 공격 및 콤보 공격은 아래의 표와 같습니다. 이는 방을 만들 때 바꿀 수 있습니다.

| 공격             |    줄 수 |   | 콤보 | 줄 수 |
| :--------------- | -------: | - | ---: | ----: |
| 0줄              |  **0** ||    0 | **0** |
| 1줄 (싱글)       |  **0** ||    1 | **0** |
| 2줄 (더블)       |  **1** ||    2 | **1** |
| 3줄 (트리플)     |  **2** ||    3 | **1** |
| 4줄              |  **4** ||    4 | **1** |
| 티스핀 더블      |  **4** ||    5 | **2** |
| 티스핀 트리플    |  **6** ||    6 | **2** |
| 티스핀 싱글      |  **2** ||    7 | **3** |
| 티스핀 미니 싱글 |  **0** ||    8 | **3** |
| 퍼펙트 클리어    | **10** ||    9 | **4** |
| 백투백           | **+1** ||   10 | **4** |
|                  |        ||   11 | **4** |
|                  |        ||  12+ | **5** |

## 쓰레기 분배 방식

멀티플레이어 게임에서 쓰레기를 보내는 방식은 4가지가 있습니다.

- 목표 (Targets) `/set garbage targets`
- 분배 (Divide) `/set garbage divide`
- 전부 (To all) `/set garbage toAll`
- 최소 (To least) `/set garbage toLeast`

**목표**는 가장 널리 쓰이는 방식으로서 Team Room을 제외한 모든 방의 기본값입니다. 이 방식에서는 일정 시간마다 공격 목표가 방 안의 다음 상대로 바뀝니다. 공격을 보내는 순간에 목표로 지정되어 있었던 상대가 쓰레기를 받습니다.

**분배** 방식의 쓰레기 분배 시스템(GDS, Garbage Distribution System)에서는 공격으로 발생하는 쓰레기를 모든 상대에게 균등하게 나눠서 보냅니다. 예를 들어 2명의 상대가 있는 방 안에서 티스핀 더블(4줄)을 만들었을 경우, 상대 플레이어들은 2줄의 쓰레기를 받습니다.

**전부** 방식의 GDS에서는 공격으로 발생하는 쓰레기를 모든 상대에게 보냅니다. 예를 들어 4명의 상대가 있는 방에서 퍼펙트 클리어(10줄)를 만들었을 경우, 4명의 상대 모두가 10줄을 받아 총 40줄의 쓰레기가 발생합니다. 예시에서 볼 수 있듯 전부 방식을 쓰는 방은 빠르게 올라오는 쓰레기와 특유의 짧은 게임 시간 때문에 게임이 정신 없이 바빠지는 경향이 있습니다.

**최소** 방식의 GDS에서는 공격으로 발생하는 쓰레기가 그 시점에서 가장 적은 쓰레기를 받은 상대에게 갑니다. 예를 들어 3명의 상대가 있는 방 안에서 4줄을 만들었고, 이 때까지 이 게임에서 각 상대가 받은 쓰레기가 50, 53, 58줄이라고 하면, 가장 쓰레기를 적게 받은 첫 번째 상대가 4줄을 받게 됩니다.

## 쓰레기 방어 방식

Jstris에는 쓰레기를 막는 방식이 4가지 있습니다.

- 최대 (Full)
- 제한적 (Limited)
- 없음 (None)
- 즉시 (Instant)

**최대**는 Jstris의 기본값입니다. 이 방식을 쓰는 다른 게임으로는 *TF*(e+ 방), *TOP*가 있습니다. 최대 방식에서는 들어오는 쓰레기가 필드 오른쪽에 빨간 막대의 형태로 나타납니다. 블록을 내려놓기 전까지는 이 쓰레기가 필드에 올라오지 않습니다. 들어오는 쓰레기는 (4줄 등으로) 쓰레기를 만들어서 줄일 수 있고, 콤보를 진행중인 경우 이를 끝낼 때까지 멈춰 있습니다.

**제한적** 방식은 최대 방식과 비슷하며 한 가지의 차이점을 갖고 있습니다. 들어오는 쓰레기는 콤보의 진행 여부와 상관없이 블록을 놓자마자 올라옵니다. 즉 최대 방식과는 달리 콤보가 진행되고 있어도 막을 수 없습니다. 최대 방식과 마찬가지로 쓰레기를 만들어서 줄일 수 있습니다. 이 방식을 쓰는 다른 게임으로는 *PPT*, *TB*, *TF*(e+ 방 제외)가 있습니다.

**없음** 방식에서는 들어오는 쓰레기를 줄이거나 상쇄할 수 없습니다. 들어오는 쓰레기는 (최대와 제한적 방식에서처럼) 빨간 막대로 표시되며 이 후 블록을 내려놓자마자 올라옵니다. 상대가 10줄을 보냈을 경우, 다음 블록으로 4줄를 만들어도 쓰레기는 6줄로 줄어들지 않습니다. 대신 필드에 들어오는 쓰레기와 별개로 상대에게 4줄을 보냅니다.

**즉시** 방식에서는 빨간 막대가 나타나지 않습니다. 공격을 받는 순간에 필드에 쓰레기가 올라오며, 방어할 수 없습니다.

|        | 빨간 막대 (큐) | 방어 |
| ------ | :------------: | :--: |
| 최대   |       ○        |  ○   |
| 제한적 |       ○        |  ○   |
| 없음   |       ○        |  ×   |
| 즉시   |       ×        |  ×   |

## 랜더마이저

랜더마이저는 블록을 가져오는 순서를 정하는 방법입니다. Jstris에는 4가지의 랜더마이저가 있습니다.

- 7-bag (세븐백)
- 14-bag
- 클래식 (Classic)
- 단일 블록 (One block)

**7-bag**은 표준 랜더마이저로서 기본값으로 쓰입니다. 7가지의 블록이 하나씩 들어있는 작은 가방을 생각해봅시다. 이 가방에서 블록을 하나씩 꺼내고, 가방이 비면 같은 가방을 하나 더 구해와서 다시 반복합니다. 7-bag은 이런 방식으로 작동합니다.

**14-bag**은 7-bag과 유사하며 가방의 크기가 두 배라는 차이점이 있습니다. 7가지의 블록이 두 개씩 들어있는 가방에서 하나씩 꺼내고, 가방이 비면 다시 가져와 반복합니다.

**클래식**은 완전히 무작위로 블록을 가져옵니다. 블록을 쌓는 것이 굉장히 어려워지는 랜더마이저입니다.

**단일 블록**은 지원하는 랜더마이저 중에서 제일 독특한 랜더마이저입니다. 게임을 시작할 때 임의의 블록을 정하고 게임 내내 이것만 가져옵니다.

## 넥스트

Jstris에서는 기본적으로 5개의 넥스트를 보여줍니다. 방을 만들 때 넥스트 수를 0~5 사이에서 바꿀 수 있습니다.

## 솔리드 가비지

솔리드 가비지는 게임이 무한히 길어지는 걸 막고 플레이어들을 재촉하기 위해 올라오는 지울 수 없는 쓰레기 줄입니다. 기존의 쓰레기 줄보다 어두운 색을 띱니다. Bot Room에서는 게임 시작 후 2분 째에 올라옵니다. 방을 만들 때 솔리드 가비지가 올라오는 시간도 바꿀 수 있습니다.

![Solid Garbage][image7]

## 클리어 딜레이

클리어 딜레이는 줄을 지운 직후에 발생하는 일정 길이의 시간을 가리킵니다. 이 시간동안은 아무것도 할 수 없습니다. PPT를 포함한 많은 클래식 블록 게임에서 클리어 딜레이를 씁니다. Jstris에서는 기본적으로 클리어 딜레이를 쓰지 않습니다만, 필요한 경우 방을 만들 때 0~6000ms 안에서 정할 수 있습니다.

## 쓰레기 딜레이

쓰레기 딜레이는 쓰레기가 빨간 막대기로 나타나는 때와 쓰레기가 실제로 필드에 올라오는 때 사이의 시간을 가리킵니다. 기본값은 500ms입니다. 방을 만들 때 0~1000ms 사이에서 정할 수 있습니다. 쓰레기 딜레이 값이 클수록 쓰레기가 올라오기 전까지 더 많은 블록을 쓸 수 있습니다. 달리 말하면 쓰레기를 효율적으로 막을 기회가 더 늘어나는 것입니다. 쓰레기 딜레이를 이런 식으로도 정의할 수 있습니다. "들어오는 쓰레기가 블록을 내려놓는 것과 상관없이 빨간 막대를 거쳐야 하는 최소한의 시간".

## 난잡도

쓰레기 난잡도는 특정 유형의 쓰레기를 지우는 어려움의 정도를 나타냅니다. 방 안에서 난잡도를 변경하려면 `/set messiness ?` 명령어를 입력하세요. 이 때 ? 는 -100~100 사이의 숫자입니다. -100일 때 쓰레기 난잡도가 제일 낮으며, 게임이 진행되는 동안 쓰레기의 구멍이 한 열에서만 나타납니다. 100일 때 쓰레기 난잡도가 제일 높으며 쓰레기의 구멍이 10열 중 어디에서나 나타날 수 있습니다. 이 경우 쓰레기 줄을 지우는 것이 훨씬 더 어려워집니다.

![Unmessy (-100)][image10] 
![Messy (100)][image1]

- - -

# 자주 묻는 질문

## Q: 게임 결과 표의 줄임말들은 무슨 뜻인가요?

A: 줄임말들의 의미는 다음과 같습니다.  
B2B = 백투백 (back-to-back)  
B2Bpm = 분당 백투백 수 (back-to-back per minute)  
APM = 분당 공격 수 (attack per minute)  
SPM = 분당 보낸 쓰레기 줄 수 (sent per minute)  
PPS = 초당 피스 수 (pieces per second)  
Rep = 리플레이 (replay)

![game results table][image9]

## Q: DAS가 뭔가요?

A: DAS(Delayed Auto Shift)는 가로 방향 감도의 한 가지입니다. 블록을 원하는 방향으로 이동시키기 위해서 좌우 키를 누르고 있어야 하는 시간을 의미합니다. DAS를 매우 낮은 값으로 설정하면 키를 살짝만 눌러도 블록이 움직이기 시작하고, 매우 높은 값으로 설정하면 훨씬 더 오랫동안 키를 누르고 있어야 블록이 움직이기 시작합니다. 프로들은 보통 낮은 DAS를 쓰는데, 이로써 얻는 높아진 감도를 이용해 더 빠르게 게임을 플레이할 수 있기 때문입니다. Jstris에서의 DAS 기본값은 133입니다. 기본값이 너무 민감하다면 안정적으로 플레이할 수 있을 때까지 값을 높여보고, 너무 둔하다면 낮춰보세요. 조정해가면서 자신에게 맞는 값을 찾아냅시다.

## Q: ARR이 뭔가요?

A: ARR(Auto Repeat Rate)도 가로 방향 감도의 일종입니다. 블록이 좌우로 움직이는 빈도를 의미합니다. DAS 보다는 조금 더 이해하기 쉬운 개념입니다. ARR을 매우 낮은 값으로 설정하면 좌우 키를 충분히 오랫동안 눌렀을 때 블록이 순식간에 해당 방향으로 날아가고, 매우 높은 값으로 설정하면 좌우 키를 계속 누르고 있어도 해당 방향으로 굉장히 느리게 움직입니다. Jstris에서의 ARR 기본값은 0이며, 이는 블록을 한 순간에 옮겨버리는 빠른 값입니다 (Jstris는 가장 빠른 블록 게임 중 하나입니다). 기본값이 너무 빠르다면 안정적으로 플레이할 수 있을 때까지 값을 높여보세요.

## Q: 피네스가 뭔가요?

A: 피네스는 블록을 움직이는 가장 효율적인 방법을 의미합니다. 더 부드럽고 빠른 플레이를 위해서는 좋은 피네스를 갖추는 것이 중요합니다. 피네스에 표시되는 수치는 발생한 피네스 오류의 수를 나타냅니다. 피네스 수치가 0 이라면 어떤 피네스 오류도 내지 않았다는 뜻이죠. 이상적으로는 0에 가까울 수록 좋습니다. 피네스는 배우고 나서야 활용할 수 있는 기술 중 하나입니다. 온라인에 이를 설명하는 자료들이 많습니다. 다음 비디오는 피네스를 익히기 위한 좋은 출발점이 될 것입니다. [Tetris Tutorial: How to Play Fast!](https://youtu.be/_QBs703nOnk?t=502)

## Q: 비밀 방을 만들 수 있나요?

A: 네, 만들 수 있습니다. *로비* -> *새로운 방*을 클릭한 다음 *비공개* 체크 박스를 체크하세요. 방의 링크를 복사해서 같이 플레이하고 싶은 사람에게 알려주세요. 한 가지 팁을 드리자면, `/link` 명령어를 써서 공개/비공개 여부와 상관 없이 현재 접속한 방의 링크를 얻을 수 있습니다.

## Q: Jstris를 오프라인으로 플레이할 수 있나요?

A: 네, 온라인에서 Jstris를 다운로드하면 오프라인으로 플레이할 수 있습니다. 홈페이지에서 우클릭을 하고 "다른 이름으로 저장" 을 눌러 html 파일을 저장하세요. 오프라인에서는 싱글 플레이어 모드만 이용할 수 있으며, 점수가 저장되지 않습니다.

- - -

# 추가 정보

Jstris는 온전히 기부를 통해서만 운영되며, 광고 등을 넣지 않습니다. 많은 양의 리플레이와 게임 데이터를 관리하기 위해서 Jstris는 성능 좋은 서버를 필요로 합니다. 모든 기부에 정말 감사드리며, 기부금은 향후 Jstris를 건강하게 운영하는 데에 도움이 될 것입니다. [Jstris에 대해](/about) 섹션을 참조하세요.

[image2]: ./images/guide-intro.png "소개"
[image4]: ./images/image4.png "상대 플레이어 화면에 표시된 MisaMino 봇"
[image8]: ./images/image8.png "Speed Limit Rooms에 표시되는 속도계 아이콘"
[image5]: ./images/image5.png "새로 방을 만들거나 다른 플레이어가 만든 방에 참여할 수 있는 로비"
[image11]: ./images/image11.png "진행중인 팀 게임"
[image7]: ./images/image7.png "솔리드 가비지"
[image10]: ./images/image10.png "깔끔함 (-100)"
[image1]: ./images/image1.png "난잡함 (100)"
[image9]: ./images/image9.png "게임 결과 표"