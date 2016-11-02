# OOAD-WEEK10
Sequence Diagram


README.md 
md เป็นภาษา Markdown นิยมใช้ใน wiki ของ github 

ตัวอย่างโค้ด
```
# Heading ระดับ 1 
## Heading ระดับ 2
### Heading ระดับ 3
 
```

ผลที่ได้
# Heading ระดับ 1 
## Heading ระดับ 2
### Heading ระดับ 3


## Code ภาษาซี

ตัวอย่างโค้ด
<pre>
  ``` c
  #include <stdio.h>
  Main()
  {
     Printf("Hello");
  }
  ```
</pre> 
ผลที่ได้
  ``` c
  #include <stdio.h>
  Main()
  {
     Printf("Hello");
  }
  ```
  รูปที่ 1 
  
 ```
@startuml
title SEAL OIL
KOON -> YODTUNG : PutCoin 
YODTUNG -> BORD : RUBTUNG
BORD -> CHECKMONEY : CHECKMONEY()
CHECKMONEY -> BORD: JUNNUNMONEY()
BORD -> JOR : JUNNUN OIL 

KOON -> PUMSTART:CLICKPUM()
PUMSTART -> BORD : OIL ON()
BORD -> PUMOIL : JAINUMMON()

@endum

```
![](http://www.plantuml.com/plantuml/img/JOwz3e9048JxVOejjV05A0nm4ENdTid15PGcKf3ma-Zn_kuHJobdlfd9n6_tUBbjdi2DRXgmpPCQkQYXOYQyNB7dhBDqmmYRpQbrN1229JHbamaoDlKEx59iTSzLfPdoNk1VdCvm8DzwXAKbiXGIOQDaWu7vHmY_JutLRPUOBb9reIfHKWlUuPKlCHqc9UCzMKqAibhl4E9XUMxp1m00)

รูปที่ 2

```
@startuml
title MUSIC PLAYER
KOON -> BTON : DVD PLAYER ON() 
BTON -> BORD : STANDBY
KOON -> BTSAIPAN : KOD
BTSAIPAN -> BORD :  OPEN TAD SAIPAN()
KOON -> BTSAIPAN : KOD
BTSAIPAN -> BORD : CLOSE TAD SAIPAN()
BORD -> READDVD : READPAN
READDVD -> BORD : SEND DATA
BORD -> POWERAMP : DATAOUTPUT
POWERAMP -> SPEAKER : SEND SOUND
@endum

```
![](http://www.plantuml.com/plantuml/img/bOyn3eCm34NtdC8Z3Bq0GuN16H0GHqbenLYf39MWGnlktuHIIiTEjl_pa-pywIyFFq-Zy3S_3j1sjYf1DzXB8sfc1OSZ52xK3EX4Am5MIGfYoIDdGu5RXugAVgTPh3H6jMOIs_WrWBLKu93WZPBq3xbisCfVUI5XmqYaU6ssT869JxAxLYe2GeURfVai3ROwlXfoxfpkdDZIi66rn3gylzgMEqKY7-xNUH8l)

รูปที่ 3
```
@startuml
title RADIO
KOON -> SW_ON :KOOD(SW_ON) 
SW_ON -> BORD_RADIO : RADIO_READY()
KOON -> VALUM :SELECT_CHANALE() 
VALUM -> BORD_RADIO :SATANEE()
BORD_RADIO -> AMPLIFILER :KAYAI_SUN_YAN()
AMPLIFILER -> SPEAKER : SOUND()
@endum

```
![](http://www.plantuml.com/plantuml/img/NOx13e8m44Jl-nLxX8C_mC6mqXeRIajQq71gJEHW0Xwq_ByBJGpnDhjlPZBb9zxVSPadYCyuZUX8A0krjGOFH_ItmABWKsIRpX7IZ-79EX4sFnOf5vmaCMJvBtybtJTOUAbbrONgGeQqpBWaWRyIJnqPoHnsN_PGqsfrLbewda83gU1x4mOoxDonTMyhgLvjw6rl17E0SdmzbXc-)

รูปที่ 4 
```
@startuml
title START MOTOCICLE
KOON -> SEB_KUN_JAA :FAII_ON() 
KOON -> SW_ON : KOOD_START()
SW_ON -> DISTART : ON_DISTART()
DISTART -> JANFAI : DISTART_PAN_JANFAI()
JANFAI -> ENGINE_START : START_MOTOCICLE()
@endum

```

![](http://www.plantuml.com/plantuml/img/HOv13e9034NtSuekOU45M1WgZ6P0MoDZN3OciY015phSt-8Cklpll_osV8VxAypJQC8GnXuwZnSF9_PSkUfeJSjCiDb2PtVINaaQH2Zsw9mmPJdy-vi2A41pBT-HB3SHQbkxk5i0awIW_OhLQ91qLON4v8pBiGMgc5hrB1qSMLddeljxLrKmPVzyp9Fv0000)

รูปที่ 5 
```
@startuml
title BUNTERM
USER -> KEYPAD : KOODPUM(KAI)
KEYPAD ->  BOAD : MODE()
BOAD -> DISPLAY : MODE()
USER -> KEYPAD : KOODPUM(NUMBER)
KEYPAD ->  BOAD : DATA(NUMBER)
BOAD -> DISPLAY : SADANG(NUMBER)
BOAD -> SERVER : CHECK_NUMBER()

USER -> KEYPAD : MONEY()
KEYPAD ->  BOAD : DATA(MONEY)
BOAD -> DISPLAY : SADANG(MONEY)

USER -> INPUTMONEy : SAIMONEY()
 INPUTMONEy -> BOAD : NUBMONEY()
 
 BORD -> SERVER : SEND_BALANCE()
 
@endum
```
![](http://www.plantuml.com/plantuml/img/VP2z3e9048JxVOeheV05A0nxt4Kln_q4E1CgOYA52LWe5Bwz1o9g4CkTRp8psVZM7QzTtpRGdRkc9jJfWcSANCupijaIoKkBZ4H46iEiKu544SAaUawe6R4oZ0SXZ9UNcSXjYkKRhEPffoZFVaKoB736o-0S6UhTmk1x3hug8icU9x9wOZzWkK0PpSjWjNd4VuedFkSARLqnYFVH8rxndy3RfWhjw6m0BsRVutEkMKKnHPqCtmE8wykfR-41)
