### 1. My bussiness card link
https://hihello.me/p/db5da52c-99b3-4945-b2f9-259e398f6541

### 2. converted to [tinyURL](https://tinyurl.com/app)
https://tinyurl.com/bdbw2mb3

### 3. convert via [hex converter](https://onlinehextools.com/convert-ascii-to-hex)

only non https part `tinyurl.com/bdbw2mb3`=> 0x74 0x69 0x6e 0x79 0x75 0x72 0x6c 0x2e 0x63 0x6f 0x6d 0x2f 0x62 0x64 0x62 0x77 0x32 0x6d 0x62 0x33

https is stated by last bit on page 6 `04` - refer [this](https://learn.adafruit.com/adafruit-pn532-rfid-nfc/ndef)

drop `0x`

### 4. replace lines 7-11 with hex codes. Change 1 bit of page 12 to `FE`

### 5. line 1-6 link prep (WIP)
```
Page 0: 04 39 91 24
Page 1: C2 FC 67 80
Page 2: D9 48 00 00
Page 3: E1 10 12 00
Page 4: 01 03 A0 0C
Page 5: 34 03 19 D1
Page 6: 01 15 55 04
```
---

[sauce](https://github.com/UberGuidoZ/Flipper/tree/main/NFC/Fun_Files)
