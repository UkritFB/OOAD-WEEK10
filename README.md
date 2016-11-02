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
title Washing machine
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
![](http://www.plantuml.com/plantuml/img/JOwnRi8m48RtUueRoy0BPAW0WzeGOgCqLiKObGWYaI21ym1im5ofGkh6nbXrSDxc7gKNguOizltVTtUwmTvaErEN6p25sUJudktNHRN2CllWFuT8AOdzProeSQhb2mOuhutO5XM2Hsn7AXcpIlIe9U0YO_4w4L6iv6J1yX6UUj0n_-C1JhMKMleElsEg4lGELJX3kDyqr_5REapIGCn24N7YCSywLxL3IdPMSa_BUEimb3gEdOH1NYth4iZUoFvISo9xSRKb-qdsGFQ7xDKHvb_kPV9DpT4L5sguvymA_W00)

