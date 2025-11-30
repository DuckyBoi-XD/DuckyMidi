# DuckyMidi
The DuckyMidi is a Midi keyboard made from the mini midi magic guide which has a theme of Ducks
<img width="887" height="452" alt="Screenshot 2025-11-22 at 9 00 30 PM" src="https://github.com/user-attachments/assets/b8539f3e-9d30-4d8c-adce-456797e4c28b" />

## Features

The DuckyMidi has all these features:

- 2 octaves for wide range of sounds
- LCD display for menu display
- 2 rotary knobs for menu/Midi control
- 12 macro keys
- Orpheus Pico microcontroller
- Gateron Pro black switches to feel like a piano key
- Manual on/off switch

## Inspiration

The DuckyMidi was created using the help of the guide from the mini midi magic and was created for many reasons. I'm experienced in music and when I saw the guide for the midi made me intreseted in making a Midi keyboard myself. This was also a great time to revise/practise my PCB designing and CAD modeling.

## Construction
The DuckyMidi is created with a custom PCB and case.

### PCB
The DuckyMidi's PCB:

<img width="1035" height="425" alt="Screenshot 2025-11-25 at 2 12 49 PM" src="https://github.com/user-attachments/assets/29c8ef59-6488-46b7-9968-04beff7de913" />
<img width="752" height="477" alt="Screenshot 2025-11-30 at 7 53 48 PM" src="https://github.com/user-attachments/assets/b27343d5-5c7e-4d5b-bfc2-2697f7ff0046" />

### Case

The DuckyMidi's Case:

<img width="724" height="296" alt="Screenshot 2025-11-30 at 7 02 26 PM" src="https://github.com/user-attachments/assets/91da4daa-f73c-4998-b615-0b62eb53bfd6" />
<img width="812" height="208" alt="Screenshot 2025-11-30 at 7 53 29 PM" src="https://github.com/user-attachments/assets/4d1f87a0-0010-4312-985c-ab8a64818596" />
<img width="1294" height="202" alt="Screenshot 2025-11-30 at 7 04 42 PM" src="https://github.com/user-attachments/assets/74b60100-ae7b-4381-8b7c-69c8704104ab" />

## BOM

| Component | Quantity | Description | Base Price | Extra Costs | Link | 
|-----------|----------|-------------|------------|-------------|------|
| Raspberry Pi Pico Board RP2040 | 1 | MCU (Microcontroller Unit) | $3.03 | (**GST**) | https://www.aliexpress.com/item/1005006087823796.html?spm=a2g0o.productlist.main.2.309b77b7b9P5jN&aem_p4p_detail=2025111416335911325003001759620000252286&algo_pvid=ee387e86-e232-4153-b3f9-458bd4187391&algo_exp_id=ee387e86-e232-4153-b3f9-458bd4187391-1&pdp_ext_f=%7B%22order%22%3A%22930%22%2C%22eval%22%3A%221%22%2C%22fromPage%22%3A%22search%22%7D&pdp_npi=6%40dis%21USD%212.89%212.63%21%21%2120.42%2118.62%21%402101e80f17631668397588042e85f8%2112000044713099471%21sea%21NZ%216394433987%21X%211%210%21n_tag%3A-29911%3Bd%3A53947009%3Bm03_new_user%3A-29895&curPageLogUid=tcKrQuvSvlbc&utparam-url=scene%3Asearch%7Cquery_from%3A%7Cx_object_id%3A1005006087823796%7C_p_origin_prod%3A&search_p4p_id=2025111416335911325003001759620000252286_1 | 
| PCM5102APWR | 1 | DAC (Digital to Analog Converter) (Digikey) | $4.43 | (**GST**) | https://www.digikey.co.nz/en/products/detail/texas-instruments/PCM5102APWR/3727211?s=N4IgTCBcDaIAoGECyBWAjABjAQTgdQCUQBdAXyA |
| MAX9722AEUE+ | 1 | AMP (Audio Amplifier) (Digikey) | $1.52  | (**GST**) | https://www.digikey.co.nz/en/products/detail/analog-devices-inc-maxim-integrated/MAX9722AEUE/1495288 | 
| SJ1-3514N | 1 | 3.5mm Headphone Jack (Digikey) | $1.19  | (**GST**) | https://www.digikey.co.nz/en/products/detail/same-sky-formerly-cui-devices/sj1-3514n/738685 | 
| PTN092-H50115K1A | 1 | Potentiometer (Digikey) | $2.00  | (**GST**) | https://www.digikey.co.nz/en/products/detail/same-sky-formerly-cui-devices/PTN092-H50115K1A/24767692 |
| EC11E18244A5 | 1 | Rotary Encoder (Digikey) | $4.85 | (**GST**) | https://www.digikey.co.nz/en/products/detail/alps-alpine/ec11e18244a5/21721665 |
| 404070001 | 1 | ESD Safe Tweezers (Straight) (Digikey) | $2.50 | (**GST**) | https://www.digikey.co.nz/en/products/detail/seeed-technology-co-ltd/404070001/5488233 |
| 422 | 1 | ESD Safe Tweezers (Curved) (Digikey) | $3.95 | (**GST**) | https://www.digikey.co.nz/en/products/detail/adafruit-industries-llc/422/7241434 |
| 1007-20-1-2000-001-1-TD | 25 feet | Wires | $11.87 | (**GST**) | https://www.digikey.co.nz/en/products/detail/cnc-tech/1007-20-1-2000-001-1-TD/17799227 |
| 20-0600-21 | 2 (20 pins each) | Male pin headers | $7.66 | (**GST**) | https://www.digikey.co.nz/en/products/detail/aries-electronics/20-0600-21/4207162 |
| 97790603211 | 10 | Screws | $2.58 | (**GST**) | https://www.digikey.co.nz/en/products/detail/w%C3%BCrth-elektronik/97790603211/10056392 |
| 97791003111 | 10 | Screws | $2.24 | (**GST**) $7.92 | https://www.digikey.co.nz/en/products/detail/w%C3%BCrth-elektronik/97791003111/10056389 | 
| 1.3 Inch Oled Module Witte Kleur | 1 | OLED screen 4 pin (Aliexpress) | $5.40 | (**TAX**) | https://www.aliexpress.com/item/1005007451015054.html?spm=a2g0o.productlist.main.3.5c94BkFLBkFLwI&algo_pvid=c05ab788-0f62-4cac-8ecf-0ac50b96f1c8&algo_exp_id=c05ab788-0f62-4cac-8ecf-0ac50b96f1c8-2&pdp_ext_f=%7B%22order%22%3A%221408%22%2C%22eval%22%3A%221%22%7D&pdp_npi=4%40dis%21NZD%215.36%211.68%21%21%213.15%210.99%21%402103247917505815500323989e2c7f%2112000040806152742%21sea%21NZ%216394433987%21ABX&curPageLogUid=4GgHuLqPJwAs&utparam-url=scene%3Asearch%7Cquery_from%3A |
| Ultra Short Switch | 2 | Buttons No LED 3-6V 16mm black momentary (Aliexpress)| $9.34 | (**TAX**) | https://www.aliexpress.com/item/1005004920346156.html?spm=a2g0o.productlist.main.7.7f7d5f2722dp5N&algo_pvid=88ea1ebf-ed98-4122-ae48-2b34d2cbcef4&algo_exp_id=88ea1ebf-ed98-4122-ae48-2b34d2cbcef4-6&pdp_ext_f=%7B%22order%22%3A%221272%22%2C%22eval%22%3A%221%22%7D&pdp_npi=4%40dis%21NZD%214.19%211.70%21%21%2117.53%217.11%21%402103247417506694259818233e29c3%2112000039500055503%21sea%21NZ%216394433987%21ABX&curPageLogUid=AdxbPFQrTg6S&utparam-url=scene%3Asearch%7Cquery_from%3A |
| Hexagon Fine Thread Thin Nuts | 1 M7 (20 pieces) | Nuts for Rotary encoders and Potentiometer (Aliexpress) | $3.84 | (**TAX**) + $5.49 (Shipping) | https://www.aliexpress.com/item/1005006173995318.html?spm=a2g0o.productlist.main.15.7dbd4ebaNansD7&algo_pvid=bbffa5d8-f689-4588-a6f6-ce0996436945&algo_exp_id=bbffa5d8-f689-4588-a6f6-ce0996436945-14&pdp_ext_f=%7B%22order%22%3A%22151%22%2C%22eval%22%3A%221%22%7D&pdp_npi=4%40dis%21NZD%211.85%211.39%21%21%217.88%215.91%21%40210308a417510851180067032e73ba%2112000036120140725%21sea%21NZ%216394433987%21ABX&curPageLogUid=mVYjfbvrU5vv&utparam-url=scene%3Asearch%7Cquery_from%3A |
| Brass melting heat insert | 1 M3 OD 5mm length 5mm (50 pieces) (Aliexpress) | Heat inserts for case and PCB (Aliexpress) | $4.71 | (**TAX**) | https://www.aliexpress.us/item/1005003582355741.html?spm=a2g0o.productlist.main.5.24ac12d7m7D9Ol&algo_pvid=870e099a-1be4-4b3b-9495-46eae48c9ac9&algo_exp_id=870e099a-1be4-4b3b-9495-46eae48c9ac9-4&pdp_ext_f=%7B%22order%22%3A%2218759%22%2C%22eval%22%3A%221%22%7D&pdp_npi=4%40dis%21NZD%213.79%211.66%21%21%212.26%210.99%21%402103244b17515900105603223eeccf%2112000026370649721%21sea%21NZ%216394433987%21ABX&curPageLogUid=PvX1sJbDEX6O&utparam-url=scene%3Asearch%7Cquery_from%3A |
| Mini Micarta Soldering Iron Stand Holder | 1 | Soldering stand for Pinecil (Aliexpress) | $3.21 | (**TAX**) | https://www.aliexpress.com/item/1005006352272696.html?spm=a2g0o.store_pc_home.promoteRecommendProducts_2004652237334.1005006352272696 | 
| Type-C Mini Hot Plate PCB SMD | 1 | Hot plate for small components (Aliexpress)| $2.85 | (**TAX**) | https://www.aliexpress.com/item/1005006511319731.html?spm=a2g0o.productlist.main.1.60d741e0IoXroY&algo_pvid=6e3b7f9e-e587-4607-8ce7-bc63e0be9c8f&algo_exp_id=6e3b7f9e-e587-4607-8ce7-bc63e0be9c8f-0&pdp_ext_f=%7B%22order%22%3A%221244%22%2C%22eval%22%3A%221%22%7D&pdp_npi=4%40dis%21NZD%2147.35%212.35%21%21%21201.83%219.99%21%402103277f17516748696561900e3da4%2112000037477574263%21sea%21NZ%216394433987%21ABX&curPageLogUid=GBlzTiUO8Kkx&utparam-url=scene%3Asearch%7Cquery_from%3A |
| Monolithic Ceramic Capacitor Kit | 1 | Ceramic Capacitor kit  0.1uf - 10uf  500 pcs (Aliexpress) | $10.93 | (**TAX**) | https://www.aliexpress.com/item/1005006772301578.html?spm=a2g0o.productlist.main.32.28fd4d9dNmQm8b&algo_pvid=481dbf38-0228-437b-89a1-11371636bc9c&aem_p4p_detail=2025070516251011559118486215700004231565&algo_exp_id=481dbf38-0228-437b-89a1-11371636bc9c-25&pdp_ext_f=%7B%22order%22%3A%2268%22%2C%22eval%22%3A%221%22%7D&pdp_npi=4%40dis%21NZD%2110.93%211.66%21%21%216.50%210.99%21%402101effb17517579108254835e8b56%2112000038249154392%21sea%21NZ%216394433987%21ABX&curPageLogUid=EixJBf52480q&utparam-url=scene%3Asearch%7Cquery_from%3A&search_p4p_id=2025070516251011559118486215700004231565_7 | 
| Electrolytic Capacitor Kit | 1 | Aluminium Electrolytic Capacitors Kit 1uf - 470uf 120 pcs (Aliexpress) | $5.82 | (**TAX**) | https://www.aliexpress.com/item/1005005626707702.html?spm=a2g0o.productlist.main.1.33696zwd6zwdiq&algo_pvid=888a458f-cf4b-4112-82b8-b34241255c81&algo_exp_id=888a458f-cf4b-4112-82b8-b34241255c81-0&pdp_ext_f=%7B%22order%22%3A%221412%22%2C%22eval%22%3A%221%22%7D&pdp_npi=4%40dis%21NZD%215.82%211.66%21%21%2124.81%217.08%21%402101ea7117517609208091735e0dee%2112000033796706983%21sea%21NZ%216394433987%21ABX&curPageLogUid=mk4afSyCFG9E&utparam-url=scene%3Asearch%7Cquery_from%3A |
| Resistor Kit | 1 | Metal Film Resistor Pack Assorted Kit 10ohm - 1m ohm 300pcs (Aliexpress) | $4.47 | (**TAX**) $9.08 | https://www.aliexpress.com/item/1005005855324735.html?spm=a2g0o.productlist.main.1.1b22578fKSCLRh&algo_pvid=85089809-d842-4483-bf22-11a567e35ac0&algo_exp_id=85089809-d842-4483-bf22-11a567e35ac0-0&pdp_ext_f=%7B%22order%22%3A%223547%22%2C%22eval%22%3A%221%22%7D&pdp_npi=4%40dis%21NZD%214.35%211.66%21%21%212.59%210.99%21%402101e07217517039549628903eb221%2112000034587357832%21sea%21NZ%216394433987%21ABX&curPageLogUid=GUVoHuNTQhAN&utparam-url=scene%3Asearch%7Cquery_from%3A |
| PCB | 5 | Custom PCB I made | $2.00 | $6.40 | N/A (CUSTOM JLCPCB) |
| Printing Legion | 1 | 3d printed case | $5.00 | N/A | N/A (CUSTOM PRINT) |
| Total: | $109.85 (BASE COMPONENTS TOTAL) | $138.42 (ALL TOTAL) | 
|--------|---------------------------------|---------------------|
