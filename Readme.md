<p align=center>
<img width="630" height="590" alt="Screenshot 2026-10-28 041446" src="https://github.com/user-attachments/assets/fad13d77-feaf-4bfe-831d-c4f2608e5d29" />
</p>

<p align=center>This Project is a Tribute to the increadible show called Mr. ROBOT</p>

## About

The Jammer is inspired by bluejammers work it works by injecting the firmware into the ESP32 and also has can charge with the TP4056 Module
The firmware allows the NFR antenna's to create a disturbance wave which distrurbs any type of radio wave wether it be wifi or bluetooth

## PCB design

The design was inspired by Mr. ROBOT and the design behind is WHITEROSE I intialy wanted to copy the design flow of blueJammer but then pivoted since it then wouldn't be
mine tho the system still follows the same principal to fit the firmware, The original had alot of aspect which is way better then mine and I would say that he made it more
convenient.


<p align=center>
<img width="701" height="676" alt="Screenshot 2026-10-28 041519" src="https://github.com/user-attachments/assets/e6f2c8f6-9ebb-4028-ab98-766915e93260" />
<img width="725" height="682" alt="Screenshot 2026-10-28 041502" src="https://github.com/user-attachments/assets/8ed06391-8453-4853-91f7-181fffe41765" />
</p>

## CAD design

The design is bulky and atrocious but it was my second attempt at a Cad incasing so chill out and I know how bad everything fits but I Like the way it looks all techy 
so I will improve the design for better design but I will not change the bulky feeling as it stands out from those thin casings and also how else would I fit the Name
Elliot alderson if I don't have space.

The Antenna's are my Best work and it made me feel really smart of how went about fitting antenna's.
<p align=center>
<img width="480" height="623" alt="Screenshot 2026-10-27 065155" src="https://github.com/user-attachments/assets/c0bcad67-3fe5-481a-8e63-aed95640bb5a" />
<img width="747" height="593" alt="Screenshot 2026-10-27 065208" src="https://github.com/user-attachments/assets/f52ee2ce-e973-4c0c-9f83-8ef549bb2b01" />
<img width="945" height="690" alt="Screenshot 2026-10-27 065137" src="https://github.com/user-attachments/assets/064ff886-396e-4576-b53b-067dcdd80584" />
</p>

## Tribute 

Mr. ROBOT was one of those shows that makes you be more senseable in how you view the world in my prespective Elliot alderson is a hero of the slum and a victim of his
father's abuse his usage of drugs to ease the pain almost never works out and is shown multiple times yet he goes back to it he said he wasent addicted but he comes back anyway
at the end he faces the truth not bec he wanted but bec the enovirenement forced it to, This character is the definition of pure Cinema and I love it.

## Process

The whole thing is documented with Lapse and my struggles to build it.

https://lapse.hackclub.com/timelapse/RKgoAYn0gdhi
https://lapse.hackclub.com/timelapse/c7LD85HKvazp
https://lapse.hackclub.com/timelapse/GZly2jAn0SyG
https://lapse.hackclub.com/timelapse/8Luba1dF0wwt
https://lapse.hackclub.com/timelapse/mDnerefs9IRr
https://lapse.hackclub.com/timelapse/ZzycG_YzoOne
https://lapse.hackclub.com/timelapse/5GctGso8MU3v
https://lapse.hackclub.com/timelapse/K8lTaUW__fx5

## BOM

ESP32-RF DIY-PCB: This PCB can fit an ESP32-wroom-32U/E DevKitC and 2 nRF-modules, along with an 0.96" I2C OLED, LEDs and switches.
Remember: It is not intended for illegal use!
For this one, all you need is listed below:

Required:

[ESP32 Dev Module](https://www.aliexpress.com/item/1005006613312645.html?aff_fcid=7ec6c453e03e47f791e1678c5771be76-1793961471865-07212-_onYIVKr&tt=CPS_NORMAL&aff_fsk=_onYIVKr&aff_platform=shareComponent-detail&sk=_onYIVKr&aff_trace_key=7ec6c453e03e47f791e1678c5771be76-1793961471865-07212-_onYIVKr&terminal_id=f9433f24f032435b9e382b8b3f625bf6&afSmartRedirect=y) (Recommended: ESP32-32U CP2102, any ESP32 should work as long as it has the needed pins, 38P required!)
[nRF24L01+PA+LNA (2x)](https://www.aliexpress.com/item/1005007038556192.html?aff_fcid=5de9656f55384a399be70db537b09490-1793961555054-04715-_oma5UQx&tt=CPS_NORMAL&aff_fsk=_oma5UQx&aff_platform=shareComponent-detail&sk=_oma5UQx&aff_trace_key=5de9656f55384a399be70db537b09490-1793961555054-04715-_oma5UQx&terminal_id=f9433f24f032435b9e382b8b3f625bf6&afSmartRedirect=y)
[10-100uF Capacitor (2x)](https://www.aliexpress.com/item/1005002524973878.html?aff_fcid=685913518df2482ebd5012ebd063c496-1793961584165-05330-_oFvFeYX&tt=CPS_NORMAL&aff_fsk=_oFvFeYX&aff_platform=shareComponent-detail&sk=_oFvFeYX&aff_trace_key=685913518df2482ebd5012ebd063c496-1793961584165-05330-_oFvFeYX&terminal_id=f9433f24f032435b9e382b8b3f625bf6&afSmartRedirect=y) (any voltage above 5V)
[0.96" OLED Display I2C](https://www.aliexpress.com/item/1005006700828250.html?aff_fcid=a986efb889bc494199cd5f82151d975c-1793961610670-04507-_oCdkjPX&tt=CPS_NORMAL&aff_fsk=_oCdkjPX&aff_platform=shareComponent-detail&sk=_oCdkjPX&aff_trace_key=a986efb889bc494199cd5f82151d975c-1793961610670-04507-_oCdkjPX&terminal_id=f9433f24f032435b9e382b8b3f625bf6&afSmartRedirect=y)
[Slide Switch (2x)](https://www.aliexpress.com/item/1005004402594340.html?aff_fcid=a6e0bf51c0d84fa6a6275c6dae7452cb-1793961629990-07832-_c4eQKm5D&tt=CPS_NORMAL&aff_fsk=_c4eQKm5D&aff_platform=shareComponent-detail&sk=_c4eQKm5D&aff_trace_key=a6e0bf51c0d84fa6a6275c6dae7452cb-1793961629990-07832-_c4eQKm5D&terminal_id=f9433f24f032435b9e382b8b3f625bf6&afSmartRedirect=y)
[LEDs: 3mm LED box](https://www.aliexpress.com/item/1005004543292837.html?aff_fcid=2ad85a6d1a264c419fcf93a48db1c6eb-1793961652512-08271-_c4dAH9sF&tt=CPS_NORMAL&aff_fsk=_c4dAH9sF&aff_platform=shareComponent-detail&sk=_c4dAH9sF&aff_trace_key=2ad85a6d1a264c419fcf93a48db1c6eb-1793961652512-08271-_c4dAH9sF&terminal_id=f9433f24f032435b9e382b8b3f625bf6&afSmartRedirect=y)
[Resistor kit](https://www.aliexpress.com/item/1005002364388450.html?aff_fcid=a6d7a041cf834c739d29717820f169e7-1793961680917-08025-_oCoJ7LO&tt=CPS_NORMAL&aff_fsk=_oCoJ7LO&aff_platform=shareComponent-detail&sk=_oCoJ7LO&aff_trace_key=a6d7a041cf834c739d29717820f169e7-1793961680917-08025-_oCoJ7LO&terminal_id=f9433f24f032435b9e382b8b3f625bf6&afSmartRedirect=y)

## Additional:

[TP4056 Charging Module (Micro-USB/Type-C)](https://www.aliexpress.com/item/1005011903177016.html?spm=a2g0o.productlist.main.1.25927b03AX15MR&algo_pvid=98bfcc08-5d2e-4fb3-a08d-f70a8dd02a52&pdp_ext_f=%7B%22order%22%3A%2230%22%2C%22spu_best_type%22%3A%22price%22%2C%22eval%22%3A%221%22%2C%22fromPage%22%3A%22search%22%7D&utparam-url=scene%3Asearch%7Cquery_from%3A%7Cx_object_id%3A1005011903177016%7C_p_origin_prod%3A)
[JST PH 2.0 Connector](https://www.aliexpress.com/item/32665588344.html?aff_fcid=b2b83f5e036140cd9e04a603137ea045-1793961761739-01549-_ooSOhDd&tt=CPS_NORMAL&aff_fsk=_ooSOhDd&aff_platform=shareComponent-detail&sk=_ooSOhDd&aff_trace_key=b2b83f5e036140cd9e04a603137ea045-1793961761739-01549-_ooSOhDd&terminal_id=f9433f24f032435b9e382b8b3f625bf6&afSmartRedirect=y)
[3.7V Li-Ion Battery](https://www.aliexpress.com/item/1005005739065266.html?spm=a2g0o.productlist.main.4.50ff3971CezIQU&aem_p4p_detail=202611060243231576742317027980000193746&algo_pvid=5a5dd219-bca3-46a7-aa50-4ba3bf587e2b&pdp_ext_f=%7B%22order%22%3A%22305%22%2C%22eval%22%3A%221%22%2C%22fromPage%22%3A%22search%22%7D&utparam-url=scene%3Asearch%7Cquery_from%3A%7Cx_object_id%3A1005005739065266%7C_p_origin_prod%3A&search_p4p_id=202611060243231576742317027980000193746_1)
[3rd Antenna: **IPEX to SMA-F pigtail](https://www.aliexpress.com/item/1005007039901040.html?aff_fcid=deaede1fcf40455fb344425aee921f82-1793961832664-09513-_oFDpn1V&tt=CPS_NORMAL&aff_fsk=_oFDpn1V&aff_platform=shareComponent-detail&sk=_oFDpn1V&aff_trace_key=deaede1fcf40455fb344425aee921f82-1793961832664-09513-_oFDpn1V&terminal_id=f9433f24f032435b9e382b8b3f625bf6&afSmartRedirect=y)
