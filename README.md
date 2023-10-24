# 6MinK.github.io

# [ 목차 ]
### 1. [컨셉](#1)
### 2. [관련 이미지](#2)
### 3. [대표 이미지 그리고 컨셉과 대표이미지 기반 작품 묘사](#3)
### 4. [구성 요소](#4)
### 5. [게임 시스템 디자인](#5)
### 6. [요구사항(1년차)](#6)
### 6a. [플로우차트](#6a)
### 6b [키보드 이벤트에 대한 흐름도](#6b)
### 6c. [용어 정리](#6c)
### 6d. [스토리보드](#6d)

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
# [요구사항(1년차)]<a name='6'></a>
- ### [플로우차트]<a name='6a'></a>
- ### 6b [키보드 이벤트에 대한 흐름도]<a name='6b'></a>
- ### 6c. [용어 정리]<a name='6c'></a>
- ### 6d. [스토리보드]<a name='6d'></a>
