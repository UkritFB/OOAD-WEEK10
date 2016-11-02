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
POWERAMP -> SPEAKER
@endum
```
![](http://www.plantuml.com/plantuml/img/bP2n3e8m48RtFiMDClW238Q3wq20NjCM3QE932RWeENzFL0HHxjS-t_t9TVB7l5yZzCug7YDGmzDwyi2R8sTTgfYDh0_G1wafa17UXDWiqj0BVdCsP5m7z1GtcqqZwN5MQsOrFhy6i1M6mX8y4Axv0-vgDdhNtaXqk4qqZnjkjo4gK-ocLOR0iA0gsNvf1qsTlwgvDm6smQrfjBXhSPA5YCdws-NQLHF)

รูปที่ 3
