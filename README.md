## Bikers Alarm: Safety LED & Alert System

This is a safety system created for bikers at night, utilizing a flex PCB that wraps around the arm and opens up 3 LEDs with the push of a button! Have a light on you as you're biking around at night so that cars can see you, and when you're within 5 meters of a person, a buzzer will automatically buzz to alert them of your presence/you of their presence. 

*Created during the Hack Club: Fallout event in Shenzhen, China* 

### Design 

<img width="942" height="437" alt="image" src="https://github.com/user-attachments/assets/45659937-7045-44c3-8196-28bae9e256e8" />

*Schematic* 


<img width="411" height="771" alt="image" src="https://github.com/user-attachments/assets/78d9771d-c1ca-487c-818c-9904de9fcf08" />

*PCB Design* 


<img width="592" height="556" alt="image" src="https://github.com/user-attachments/assets/9f902cd3-6fb7-40e2-9e01-4de0dcc0e7d8" />

*3D View* 


### Bill of Materials 

Reference | Description | Value | Qty | MOQ | Price Per Unit ($) | Total Price ($) | Datasheet | Footprint | MPN | Link
---|---|---|---|---|---|---|---|---|---|---
BT1 | Single-cell battery | Battery_Cell | 1 | 1 | 3.87 | 3.87 | N/A | Battery:BatteryHolder_Keystone_3034_1x20mm | N/A | [Link](https://www.aliexpress.us/item/3256808925172396.html?spm=a2g0o.productlist.main.11.6e1523a2T5o5mT&algo_pvid=a7f5d709-8287-4bd9-877e-4b7454d07aea&algo_exp_id=a7f5d709-8287-4bd9-877e-4b7454d07aea-10&pdp_ext_f=%7B%22order%22%3A%22115%22%2C%22eval%22%3A%221%22%2C%22fromPage%22%3A%22search%22%7D&pdp_npi=6%40dis%21USD%215.38%213.87%21%21%2136.32%2126.15%21%4021032f3717820018898186181ef57d%2112000047954562112%21sea%21US%217756416958%21X%211%210%21n_tag%3A-29911%3Bd%3A882c3b75%3Bm03_new_user%3A-29895&curPageLogUid=gVBhZCgn1w6G&utparam-url=scene%3Asearch%7Cquery_from%3A%7Cx_object_id%3A1005009111487148%7C_p_origin_prod%3A)
BZ1 | Buzzer, polarized | Buzzer | 1 | 10 | 0.0572 | 0.57 | N/A | Buzzer_Beeper:Buzzer_12x9.5RM7.6 | 1207-P6.5MM | [Link](https://www.lcsc.com/product-detail/C49246964.html)
D1,D2,D3 | Light emitting diode | LED | 3 | 20 | 0.022 | 0.44 | N/A | LED_THT:LED_D5.0mm | BAT54,215 | [Link](https://www.lcsc.com/product-detail/C85084.html?s_z=n_q_t_diode&spm=wm.fly.bg.7.xh___wm.ssy.tc.1.tz&lcsc_vid=R1YMUQAHQVVeVlBXQgcPXgZQQFAPU1RVFlkIU1cHQwMxVlNeRFFdX1JfRVVfVTsOAxUeFF5JWBYZEEoKFBINSQcJGk4eFQsCAgIaSgADAwAHC0slQlNdXlxQRU8GEwkK)
R1,R2,R3 | Resistor | 300 | 3 | 100 | 0.0016 | 0.16 | N/A | Resistor_THT:R_Axial_DIN0207_L6.3mm_D2.5mm_P7.62mm_Horizontal | FRC0402J301 TS | [Link](https://www.lcsc.com/product-detail/C2906927.html?s_z=n_q_t_resistor&spm=wm.fly.bg.6.xh___wm.ssy.tc.0.tz&lcsc_vid=R1YMUQAHQVVeVlBXQgcPXgZQQFAPU1RVFlkIU1cHQwMxVlNeRFFdX1xTQFVdXzsOAxUeFF5JWBYZEEoKFBINSQcJGk4eFQsCAgIaSgADAwAHC0slT1ReX1BIHxUDCw%3D%3D)
SW1 | Switch, single pole double throw | SW_SPDT | 1 | 20 | 0.0298 | 0.6 | N/A | N/A | 1TS005F-1600-4301A2-CT | [Link](https://www.lcsc.com/product-detail/C22391231.html?s_z=n_q_t_button&spm=wm.fly.bg.0.xh___wm.ssy.tc.1.tz&lcsc_vid=R1YMUQAHQVVeVlBXQgcPXgZQQFAPU1RVFlkIU1cHQwMxVlNeRFFdXlRQQVFZUTsOAxUeFF5JWBYZEEoKFBINSQcJGk4NBhADEA4cHktQQlBADxALGw%3D%3D)
U1 | 20MHz, 16kB Flash, 2kB SRAM, 256B EEPROM, SOIC-20 | ATtiny1616-S | 1 | 1 | 1.71 | 1.71 | [Link](http://ww1.microchip.com/downloads/en/DeviceDoc/ATtiny3216_ATtiny1616-data-sheet-40001997B.pdf) | Package_SO:SOIC-20W_7.5x12.8mm_P1.27mm | ATTINY1616-SNR | [Link](https://www.lcsc.com/product-detail/C609652.html?s_z=n_q_ATtiny1616-S&spm=wm.fly.bg.4.xh&lcsc_vid=R1YMUQAHQVVeVlBXQgcPXgZQQFAPU1RVFlkIU1cHQwMxVlNeRFFdXlVfTlZdUjsOAxUeFF5JWBYZEEoKFBINSQcJGk4eFQsCAgIaSgADAwAHC0slRVNdXlVURFBADxALGw%3D%3D)
U2 | 5m distance ranging ToF sensor, 3x3 zones, LGA-12 | TMF8820 | 1 | 1 | 11.98 | 11.98 | [Link](https://ams.com/documents/20143/6015057/TMF882X_DS000693_8-00.pdf) | Sensor_Distance:AMS_OLGA12 | TMF8820-1AM | [Link](https://www.lcsc.com/product-detail/C17336360.html?s_z=s_p_TMF8820-1AM&spm=wm.fly.bg.0.xh&lcsc_vid=R1YMUQAHQVVeVlBXQgcPXgZQQFAPU1RVFlkIU1cHQwMxVlNeRFFdXldXRlJdVTsOAxUeFF5JWBYZEEoKFBINSQcJGk4dAgUUFAk%3D)
Total |  |  | 11 |  |  | 19.33 |  |  |  |
