
# [ 목차 ]
## 1. [컨셉](#1)
## 2. [관련 이미지](#2)
## 3. [대표 이미지 그리고 컨셉과 대표이미지 기반 작품 묘사](#3)
## 4. [구성 요소](#4)
## 5. [게임 시스템 디자인](#5)
- ### [게임오브젝트 분해](#5a)
- ### [파라미터(속성) 뽑아 보기](#5b)
- ### [행동 뽑아 보기](#5b)
- ### [상태 뽑아 보기](#5c)
- ### [플레이어 캐릭터 속성(파라미터)](#5d)
- ### [게임의 규칙](#5e)
- ### [게임에서 사용될 공식](#5f)
## 6. [요구사항(1년차)](#6)
- ### [요구사항](#6a)
- ### [플로우차트](#6b)
- ### [키보드 이벤트에 대한 흐름도](#6c)
- ### [용어 정리](#6d)
- ### [스토리보드](#6e)
## 7. [Github Blog URL](#7)
# 프로젝트명: Devil.Defense		(개발자 : 1988005 김민준)     


# [컨셉] <a name='1'></a>

## 메인컨셉 : 디펜스 

- 타워 디펜스 류 게임 과 랜덤 디펜스 류 게임의 퓨전

### 서브컨셉 1  :  

- 조합 / 각 직업의 조합을 맞춰 조합시너지를 극대화 하여 적들을 잘 막을 수 있도록 하는 컨셉.


### 서브컨셉 2 :  

- 랜덤성 / 강화 및 직업뽑기 에 랜덤성을 부여하여 난이도 조절 및 조합을 맞췄을 때 성취감을 가질 수 있다. 


### 서브컨셉 3 : 

- 라운드화 / 라운드 마다 적들의 체력및 이동속도가 빨라지게 하고, 특정 라운드 마다 보스들을 배치시켜 잡지 못하면 처음부터 다시해야하는 컨셉을 가지게 만듬. 


### 서브컨셉4 : 

- 직업특성 / 직업별로 사거리, 공격력, 공격속도, 공격효과(추가데미지,스턴) 등을 달리하여 각 직업의 특성을 구현함.


### 서브컨셉5 : 2.5D  

- Lowpoly / 2.5D LowPoly 디펜스 게임.




# [관련 이미지] <a name='2'></a>
- 이미지 1
  
  ![관련이미지1](https://github.com/6MinK/6MinK.github.io/assets/147678500/80d92135-984d-4e8e-87b6-a23861db10de)

- 이미지 2
  
  ![관련이미지2](https://github.com/6MinK/6MinK.github.io/assets/147678500/1a7deedc-81c1-45f6-8b06-86e853ffe50e)

- 이미지 3
  
  ![관련이미지3](https://github.com/6MinK/6MinK.github.io/assets/147678500/13cb12af-8c78-4a03-be1c-4552ed4e4f0f)



# [대표 이미지 구상] <a name='3'></a>

- 대표 이미지 구상
  
  ![대표 게임 이미지 구상](https://github.com/6MinK/6MinK.github.io/assets/147678500/c0119301-93d1-415b-98e8-82a83aee8813)


# [구성 요소] <a name='4'></a>
 - 마족들의 침공이 시작된 세계선의 배경으로 한 디펜스 게임 

## 1. 메커니즘 



### [도전 과제] 

- 스테이지 마다 나오는 적들을 사살하여 플레이어 체력 카운트가 다 닳아 침공이 되지 않게 막아야한다.

- 적들을 잡아 나오는 골드로 뽑기를 하여 캐릭터들을 모으거나, 캐릭터 강화를 하여 성장시킨다.

- 스테이지 중간마다 나오는 중간보스 및 최종 스테이지 보스를 잡음으로서 침공을 막아내 게임을 클리어한다.



### [재미 요소]

- 다른 타워디펜스 류의 게임과는 다르게 캐릭터를 움직일수 있으며 컨트롤 하는 재미를 느낄수있다.

- 속성간의 추가데미지를 설정하여 구성을 자유롭고 다양하게 해볼 수 있다. 

- 뽑기라는 시스템을 통하여 상위캐릭터를 얻었을 때 만족감을 이끌어 낼 수 있다. 

- 어려운 난이도를 통해서 클리어 하였을때 성취감을 이끌어 낼 수 있다. 



## 2. 이야기



[만들게 된 배경]

많은 디펜스 게임을 하며 랜덤디펜스와 컨트롤형 디펜스를 접목해있는 디펜스류 게임을 접해보지 못하여 한번 접목해서 

만들어보자 라고 생각하여 만들고 싶었습니다. 저번 캡스톤에서 쓰인 캐릭터 에셋을 또 이용해보자 하여 전사, 마법사, 궁수를 

캐릭터로서 마족류의 몬스터를 막는 컨셉으로 정하였습니다. 


### [참신함]

랜덤적인 요소와 피지컬적인 컨트롤 요소와 속성간의 데미지를 이용함으로써 덱을 짜는 지능 등 

 다양한 방면에서 자신의 운, 실력, 지능 을 이끌어 낼 수 있는점이 참신하다고 생각합니다.

 
### [카메라 관점] 

카메라는 2.5D 환경으로서 쿼터뷰로 진행됩니다. 디펜스류의 게임의 특징이자 어떻게 진행 되는지 한눈에 알기 

쉽기 때문에 쿼터뷰를 선정 하였습니다.



## 3. 미적요소



### [디자인 및 컬러]

LOW 퀄리티의 캐릭터 에셋 및 에너미 오브젝트를 씀으로서 아기자기한 느낌으로 모든 연령층이 편하게 

접근 할 수 있도록 생각했습니다. 



### [음향]

무료 음원 사이트를 참고하여 적을 공격, 이동 등에 대해서 타격감이 있는 플레이를 할 수 있습니다.



## 4. 기술

Unity Engine 을 통해 게임을 제작 

저사양으로 플레이 가능하도록 개발할 예정이다.

# [게임 시스템 디자인]<a name='5'></a>
- ### [게임오브젝트 분해]<a name='5a'></a>

- ### [파라미터(속성) 뽑아 보기]<a name='5b'></a>
    #### 1) 오브젝트 이름: 전사, 마법사, 궁수 
    |  	속성 	 |  	영문명칭 	 |  	설명 	 |  	비고 	 |
    |:---:|:---:|:---:|:---:|
    |무기 공격력|w_w_Damage<br/> w_a_Damage<br/>w_m_Damage 	 |각 직업군의 무기 공격력의 수치<br/>(강화를 통한 직접적인 수치 적용) 	 | |
    |무기 공격속도|w_w_Speed<br/> w_a_Speed	<br/>w_m_Speed 	 |각 직업군의 무기 공격속도의 수치<br/>(강화를 통한 직접적인 수치 적용) 	 |	 |
    | 공격 사거리|w_Attack_Range<br/> a_Attack_Range<br/>m_Attack_Range 	 |각 직업군의 공격 사거리<br/>전사 3, 궁수 8, 마법사 5 배율로 고정 	 | |
    | 상태|w_Status<br/>a_Status<br/>m_Status|각 직업군의 행동상태.   이동, 공격, 정지 	 | |
    | 속성|w_Type<br/>a_Type<br/>m_Type| 각 직업군의 속성.<br/>속성별 추가 데미지 및 스킬 데미지  	 | |

    #### 2) 오브젝트 이름 : 상인
    |  	 속성 	 |  	 영문명칭 	 |  	 설명 	 |  	 비고 	 |
    |:---:|:---:|:---:|:---:|
    |  	 전체 직업 랜덤 뽑기 	 |  	 all_random_pick 	  |  	 실패는 없지만 <br/>3종류의 직업이 모두 나오는 <br/> 랜덤 유닛 뽑기 	 |  	   	  |
    |  	 전사 직업 랜덤 뽑기 	 |  	 warrior_random_pick 	  |  	 실패 확률이 존재하지만 <br/> 전사직업군 만 나오는 랜덤 유닛 뽑기  	 |  	   	  |
    |  	 궁수 직업 랜덤 뽑기 	 |  	 archer_random_pick 	  |  	 실패 확률이 존재하지만<br/> 궁수직업군 만 나오는 랜덤 유닛 뽑기  	 |  	   	  |
    |  	 마법사 직업 랜덤 뽑기 	 |  	 mage_random_pick 	  |  	 실패 확률이 존재하지만 <br/> 마법사직업군 만 나오는 랜덤 유닛 뽑기  	 |  	   	  |

    #### 3) 오브젝트 이름 : 대장장이 
    |  	 속성 	 |  	 영문명칭 	 |  	 설명 	 |  	 비고 	 |
    |:---:|:---:|:---:|:---:|
    |  	 전사 강화 	 |  	 warrior_Upgrade 	  |  	 전사직업의 무기 강화 (공격력 및 공격속도 상승) 	 |  	   	  |
    |  	 궁수 강화 	 |  	 archer_Upgrade 	  |  	 궁수직업의 무기 강화 (공격력 및 공격속도 상승) 	 |  	   	  |
    |  	 마법사 강화 	 |  	 mage_Upgrade 	  |  	 마법사 직업의 무기 강화 (공격력 및 공격속도 상승) 	 |  	   	  |

    #### 4) 오브젝트 이름 : 몬스터
    |  	 속성 	 |  	 영문명칭 	 |  	 설명 	 |  	 비고 	 |
    |:------:|:---:|:---:|:---:|
    |  	 일반몬스터 <br/> 이동속도 	 |  	 common_Monster_Speed 	  |  	 일반몬스터의 이동속도  <br/> 	 스테이지 마다 이동속도 증가 	 |  	   	  |
    |  	 일반몬스터 <br/> 체력 	 |  	 common_Monster_Hp 	  |  	 일반 몬스터의 체력  <br/> 	 스테이지 마다 체력 증가 	 |  	   	  |
    |  	 일반몬스터 <br/> 속성 	 |  	 common_Monster_Type 	  |  	 일반 몬스터의 속성은 노말 고정 	 |  	   	  |
    |  	 일반 <br/> 강화 몬스터<br/>  이동속도 	 |  	 uncommon_Monster_Speed 	  |  	 일반강화 몬스터의 이동속도  <br/> 	 스테이지 마다 이동속도 증가 	 |  	   	  |
    |  	 일반 <br/> 강화 몬스터 <br/> 체력 	 |  	 uncommon_Monster_Hp 	  |  	 일반강화 몬스터의 이동속도  <br/> 	 스테이지 마다 체력 증가 	 |  	   	  |
    |  	 일반 <br/> 강화 몬스터<br/>  속성 	 |  	 uncommon_Monster_Type 	  |  	 일반강화 몬스터의 속성  <br/> 	 라운드마다 속성이 달라진다. 	 |  	   	  |
    |  	 중간<br/> 보스 몬스터 <br/> 이동속도 	 |  	 middle_Boss_Speed1  <br/> 	 middle_Boss_Speed2 	   |  	 중간보스 몬스터의 이동속도 <br/>  	 첫 번째와 두 번째 이동속도 고정  <br/> 	 게임 내 2번 고정 소환 	 |  	   	  |
    |  	 중간보스 몬스터 <br/> 체력 	 |  	 middle_Boss_Hp1 <br/> middle_Boss_Hp2 	  |  	 중간보스 몬스터의 체력  	 첫 번째와 두 번째 체력 고정  <br/> 	 게임 내 2번 고정 소환 	 |  	   	  |
    |  	 중간보스 몬스터 <br/> 속성 	 |  	 middle_Boss_Type1  <br/> 	 middle_Boss_Type2 	   |  	 중간보스 몬스터의 속성  	 첫 번째와 두 번째 속성 고정  <br/> 	 게임 내 2번 고정 소환 	 |  	   	  |
    |  	 최종보스 몬스터<br/>  이동속도 	 |  	 last_Boss_Speed 	  |  	 최종보스 몬스터의 이동속도  <br/> 	 게임 내 1번 고정소환 = 고정값 	 |  	   	  |
    |  	 최종보스 몬스터<br/>  체력 	 |  	 last_Boss_Hp 	  |  	 최종보스 몬스터의 체력 <br/>  	 게임 내 1번 고정소환 = 고정값 	 |  	   	  |
    |  	 최종보스 몬스터 <br/> 속성 	 |  	 last_Boss_Type 	  |  	 최종보스 몬스터의 속성  <br/> 	 게임 내 1번 고정소환 = 고정값 	 |  	   	  | 



- ### [행동 뽑아 보기]<a name='5c'></a>


- ### [상태 뽑아 보기]<a name='5d'></a>
    #### 1) 오브젝트 이름 : 플레이어
|  	 현상태 	 |  	 전이상태 	 |  	 전이조건 	 |
|:---:|:---:|:---:|
|  	 @@@_Hold (기본상태) 	 |  	 @@@_Attack 	  |  	 @@@의 사거리 <br/> 내에 몬스터가 있을 경우 어택 on  	 |
|  	 @@@_Attack 	  |  	 @@@_Hold(기본상태) 	 |  	 @@@의 사거리<br/>  내에 몬스터가 없을 경우 어택 off 	 |
|  	 @@@_Hold(기본상태) 	 |  	 @@@_Moving 	  |  	 @@@이 멈춰있을 경우 <br/>  특정키를 누르면 마우스 커서 쪽으로 이동한다. 	 |
|  	 @@@_Moving 	  |  	 @@@_Hold(기본상태) 	 |  	 @@@이동시 <br/> 정지(H)버튼을 누르거나 이동을 완료하면 기본 상태 로 넘어간다. 	 |
|  	 @@@_Attack 	  |  	 @@@_Moving 	  |  	 @@@공격 시 <br/> 이동을 하게 되면 공격을 멈춘 뒤 이동을 하게 된다.   	 |
- @@@에는 모든 직업군 이 들어간다. 
- 견습전사(Q), 전사(S), 광전사(Z), 견습궁수(W), 궁수(S), 신궁(X), 견습마법사(E), 마법사(D), 대마법사(C)
- 정지(H) 

* 전이조건에 적혀있는 특정키는 괄호 안에 적혀있다.
    #### 2) 오브젝트 이름 : 몬스터
|  현상태 | 전이상태 |전이조건 |
|:----:|:----:|:----:|
|monster_Moving(기본상태)|monster_Slow|이동 중 <br/>  특정 이동속도 저하 스킬을 맞았을 경우<br/> 슬로우상태가 된다.|
|   monster_Slow| monster_Moving(기본상태)|슬로우 상태가 된 후<br/>   일정 시간이 지난 후<br/>   기본상태 로 돌아가게 된다. |
|  	 monster_Moving(기본상태) | monster_Stun| 이동 중 <br/>  스턴 스킬을 맞았을 경우 <br/>  정지 상태 (스턴 상태) 가 된다. |
|  	 monster_Stun| monster_Moving(기본상태)| 정지 상태가 된 후 <br/>  일정 시간이 지난 후 기본 상태로 돌아가게 된다.  |
|  	 monster_Slow| monster_Stun| 이동속도가 저하된 상태에서 <br/>  스턴 스킬을 맞았을 경우 정지 상태 (스턴 상태)가 된다. |
|  	 monster_Stun| monster_Slow| 정지 상태가 된 후 <br/>  풀린뒤 슬로우 상태의 시간이 남아있다면<br/>   슬로우 상태가 된다. |

- ### [플레이어 캐릭터 속성(파라미터)]<a name='5e'></a>
|속성|영문명칭|설명|비고|
|:----:|:----:|:----:|:----:|
|견습전사|page|전사 직업군의 1단계 전사, 바람 속성 이다.|
|견습궁수|novice Archer|궁수 직업군의 1단계 궁수, 빛 속성 이다.|
|견습마법사|mage|마법사 직업군의 1단계 마법사, 얼음 속성 이다.|
|전사|warrior|전사 직업군의 2단계 전사, 얼음 속성 이다.|
|궁수|archer|궁수 직업군의 2단계 궁수, 바람 속성 이다.|
|마법사|archmage|마법사 직업군의 2단계 마법사, 화염 속성 이다.|
|광전사|berserker|전사 직업군의 3단계 전사, 빛 속성 이다.|
|신궁|bow Master|궁수 직업군의 3단계 궁수, 화염 속성 이다.|
|대마법사|grand Mage|마법사 직업군의 3단계 마법사, 얼음 속성 이다.|

- 얼음 속성은 빛 속성과 시너지가 좋다.
- 바람 속성은 화염 속성과 시너지가 매우 좋으며, 얼음 속성과 빛 속성은 시너지가 안 좋다.
- 화염 속성은 바람 속성과 시너지가 좋으며, 빛 속성과 시너지가 안 좋다.
- 빛 속성은 모든 속성과 시너지를 이루지만, 좋은 편은 아니다.

- ### [게임의 규칙]<a name='5f'></a>
#### 1) 핵심 규칙

 - 체력 카운트는 20이다. 이 체력 카운트가 모두 없어지면 게임이 끝난다. (실패 처리)
 - 유저는 상인에게서 처음 지급되는 골드로 캐릭터를 뽑을 수 있으며, 대장장이에게서 캐릭터를 강화 할 수 있다.
 - 골드는 몬스터 일정 수를 잡거나, 이벤트 몬스터 및 중간보스를 잡으면 얻을 수 있고,미션을 클리어 했을 때 
 보너스 골드를 획득 할 수 있다.
 - 총 라운드는 40라운드 까지 있으며, 5라운드,10라운드, 20라운드, 30라운드에는 중간보스가 일반몬스터, 일반강화 몬스터와 같이 나오며 마지막 40라운드에서는 최종보스 몬스터만 나온다.
 - 한 라운드는 몬스터를 다 잡을 때 까지 유지되며 다 잡은 뒤 10초의 정비시간을 준다. 
 - 일반 몬스터 및 일반강화 몬스터, 중간보스 몬스터를 못 잡을 경우 체력카운트가 줄어든다.
   (일반 몬스터 = 1, 일반강화 몬스터 = 3, 중간보스 몬스터 = 10)
 - 최종 보스 몬스터를 못 잡을 시 게임이 끝난다. (실패 처리)

   * 이벤트 몬스터는 못 잡을 경우 체력카운트가 줄어들진 않지만 골드를 못 얻게 된다.
     └ 이벤트 몬스터는 일반 강화 몬스터 잡을 시 일정 확률로 등장한다.

 - 40라운드 까지 진행을 하고 최종보스를 잡을 경우 게임이 클리어 된다.


 
#### 2) 보조 규칙

- 3라운드 이전 견습 전사, 견습 궁수, 견습 마법사 모두 모을시 보너스 골드 지급
- 6라운드 이전 전사, 궁수, 마법사 모두 모을시 보너스 골드 지급
- 10라운드 이전 광전사, 신궁, 대마법사 모두 모을시 보너스 골드 지급
- 20라운드 이전 이벤트 몬스터 5회 처치시 보너스 골드 지급 

- ### [게임에서 사용될 공식]<a name='5g'></a>
- 체력 카운트 20 고정 

- 스테이지 마다 몬스터 30마리 고정 5마리당 10골드

- 직업 강화 일반공격력, 공격속도, 스킬 데미지는 레벨 디자인을 통해 수정 예정 
- 전사 : 일반 공격력 강화당 수치 +3 공격속도 + 0.03 
- 궁수 : 일반 공격력 강화당 수치 +1 공격속도 + 0.06
- 마법사 : 일반 공격력 강화당 수치 +5 공격속도 + 0.1 

- 전체직업 랜덤 뽑기 10gold
    - 견습전사(20%), 방패전사(8%), 광전사(5%)
    - 견습궁수(20%), 궁수(8%), 신궁(5%)
    - 견습마법사(20%), 마법사(8%), 대마법사(5%)
    - 골드10gold 반환(1%), 골드 비용 : 10gold

 - 전사직업 랜덤 뽑기 10gold
    - 견습전사(45%), 전사(15%), 광전사(5%)
    - 실패(35%)

 - 궁수직업 랜덤 뽑기 10gold
    - 견습궁수(45%), 궁수(15%), 신궁(5%)
    - 실패(35%)

 - 마법사직업 랜덤 뽑기 10gold
     - 견습마법사(45%), 마법사(15%), 대마법사(5%)
    - 실패(35%)

 - 각 직업군 이동속도 및 사거리 고정
    - 이동속도 : 전사 1, 궁수3, 마법사2 로 고정 (Unity Engine 기준)
    - 사거리 :  전사 5, 궁수 10, 마법사 8 로 고정 (Unity Engine 기준)

 - 특정 스킬의 경우 다른 속성의 스택을 필요로 할 경우 있음

 - 얼음 속성의 스킬 스택이 쌓였을 경우 빛 속성 스킬 데미지 1.2배 증가

 - 바람 속성의 스킬 스택이 쌓였을 경우 화염 속성 스킬 데미지 1.8배 증가 
     - 얼음 속성과 빛 속성 스킬 데미지는 0.6배 감소

 - 화염 속성의 스킬 스택이 쌓였을 경우 바람 속성 스킬 데미지 1.4배 증가 
     - 빛 속성 스킬 데미지 0.8배 감소

 -  빛 속성의 스킬 스택이 쌓였을 경우 모든 속성 스킬 데미지 1.1배 증가 

# [요구사항(1년차)]<a name='6'></a>

- ### [요구사항] <a name='6a'></a>
 Devil Defense 게임의 요구사항
- 시작화면, 시작화면-설정, 게임화면-설정, 게임화면 총 4개의 화면이 있다.
- 시작화면에는 시작하기, 게임설정, 게임종료 버튼이 있다.  
- 게임설정 클릭 시 시작화면-설정 으로 넘어간다.
- 게임종료 클릭 시 게임이 종료된다.
- 시작화면-설정 에는 게임 음악 볼륨을 on, off 하는 버튼, 볼륨 조절 할 수 있는 바, 
게임플레이 설명창 버튼, 뒤로가기 버튼이 있다.
- 게임플레이 설명창에서는 캐릭터 간 이동버튼 설명서와 NPC 이용 방법 설명서 및 뒤로가기 버튼이 있다.
- 시작화면에서 시작하기 클릭 시 게임화면으로 변경된다.

- 게임화면에는 게임화면-설정 버튼, 게임화면, 남은 골드를 표시하는 UI, 체력카운트UI, 상인NPC, 대장장이NPC 가 있다. 
- 게임화면-설정창에는 이어하기, 처음부터, 시작화면으로, 게임플레이 설명창 버튼 이 있다. 
(* 게임플레이 설명창은 시작화면-설정창에 있는 게임플레이 설명창과 동일)
- 이어하기 클릭시, 게임화면으로 돌아간다.
- 처음부터 클릭시, 게임이 처음부터 시작된다.
- 게임플레이 설명창 클릭시 게임플레이 설명창으로 넘어간다. 
- 라운드는 40라운드 까지 있으며, 5라운드마다 강화몬스터 (첫 5라운드만 중간보스 등장), 10라운드마다 중간보스 몬스터, 마지막 40라운드에서 최종보스 몬스터가 등장한다. 
- 라운드 별 몬스터들의 체력 및 이동속도가 일정하게 증가한다.
- 상인NPC 를 통해 전체직업 랜덤 뽑기(10gold), 전사직업 랜덤 뽑기 (10gold), 궁수직업 랜덤 뽑기 (10gold), 마법사직업 랜덤 뽑기 (10gold) 을 할 수 있다. (*확률은 게임에서의 이용할 공식 참고)
- 직업 조작은 견습전사(Q), 전사(S), 광전사(Z), 견습궁수(W), 궁수(S), 신궁(X), 견습마법사(E), 마법사(D), 대마법사(C), 정지(H) 이다.

- 게임 종료 조건은 체력카운트를 남기고 최종보스를 잡아 클리어 하거나, 체력카운트가 0이 되어 클리어 실패를 하면 종료되고 팝업이 뜬다. 
- 체력카운트 UI 에서는 남은 체력카운트, 시간(준비시간, 라운드 남은시간, 보스 남은시간)이 표시된다.  
- 게임 클리어시 게임 클리어 팝업이 뜨고 시작화면으로 돌아간다.
- 게임 클리어 실패 시 게임 클리어 실패 팝업이 뜨고 시작화면으로 돌아간다.
- ### [플로우차트]<a name='6b'></a>

- ### [키보드 이벤트에 대한 흐름도]<a name='6c'></a>

- ### [용어 정리]<a name='6d'></a>
	

- ### [스토리보드]<a name='6e'></a>
	- 해당사항 없음 
# [Github Blog URL]<a name='7'></a>
- 6MinK.github.io
