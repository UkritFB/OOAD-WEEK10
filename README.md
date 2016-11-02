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
สิ้นสุดการสนทนาผ่านแชท
```

