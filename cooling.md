# 📌 Improving the Cooling System
One of the main issues with the device is its tendency to overheat quickly, particularly with the pre-installed Windows 10 Pro, which causes frequent freezes and even shutdowns. I suspect that overheating, combined with the device's limited RAM, is the root cause of these problems. This document will track my progress in addressing these temperature issues.

## 💻 Installing a new OS
Before I installed any cooling modifications I decided to change the OS to a lighter one since Windows 10 Pro was simply too much for the machine to handle. The new OS installation process is documented [here](os-install.md).

## 🌡️ Non-cooled temperatures test.
After instalilng a new and lighter operating system, things went much better so i decided to run an initial test on the new OS temperatures.





## 🔍 Analyzing the board.
An interesting note is that, from the manufacturer, the board did not have any thermal pad between the ram and the heatsink nor did it have cooling for the PMIC (power management integrated circuit).
![imagen](https://github.com/user-attachments/assets/7b1488bf-ae32-40f8-808b-7bad03b293b5)


## 🧊 Modelling the parts.

  ### 🧪 Prototping.

## :ballot_box_with_check: Fitting the part.



 ## stats.
 I tested temperatures just playing a video on youtube using the firefox browser. In both cases I used the same exact video from start to finish (20mins) and between tests 1 hour passed in a 30ºc airconditioned room. The device was not in the 'air shot' of the air conditioner. 
 ![imagen](https://github.com/user-attachments/assets/abda79c1-115a-49b0-aa53-dd85a2cf1241)

1. Before disassembly i tested the device for heat stats.
2. While disassembling i noticed the single thermal pad of huge dimensions.
3. I added more thermal pads and made sure they all made contact with the element and the dissipator.
4. I measured the holes, modeled and printed a test fan holder.
5. I tested temperatures with the holder on.
    - Both the before and after fan mod tests were made with a firefox windows and a 20 min long video .
    - I noticed  the wifi card disconnected and it was extremely hot to touch. I added a dissipator to it for now but must be further tested.
 
