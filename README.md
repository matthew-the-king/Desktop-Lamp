# Desktop-Lamp
Runs on a 12V source
<img width="952" height="592" alt="LED_Lighting" src="https://github.com/user-attachments/assets/1bc4ccbe-8efb-4c6f-b2bf-a8f540d78849" /><br>


## PCB Production
| Designator | Footprint | Quantity | Value | Link | Price |
|:---|:---|:---|:---|:---|:---:|
C1, C2, C5 | 0402 | 3 | 0.1uF | [Link](https://www.digikey.com/en/products/detail/murata-electronics/GCM155R71H104KE02D/4903704) | $0.30 |
C10 | 0402 | 1 | 10nF | [Link]() | |
C11, C12, C3, C6, C8 | 1210 | 5 | 10uF | [Link]() | |
C13 | 0603 | 1 | 1nF | [Link]() | |
C4 | 0603 | 1 | 1uF | [Link]() | | 
C7 | 0402 | 1 | 100pF | [Link]() |
C9 | CAP_A768EB_6.8x6.8_KEM | 1 | 100uF | [Link]() | |
D1 | TO-277A | 1 | D | [Link]() | |
L1 | SMD2_CDRH127_SUM | 1 | 33uH | [Link]() | | 
LED1, LED10, LED2, LED3, LED4, LED5, LED6, LED7, LED8, LED9 | LED_CREE_XPE | 10 | XPEBWT-L1-0000-00CE7 | [Link]() | | 
R1 | 1206 | 1 | 0.57Ω | [Link]() | |
R2, R5 | 0603 | 2 | 100Ω | [Link]() | |
R3 | 0402 | 1 | 10kΩ | [Link]() | | 
R4 | 0402 | 1 | 7.6kΩ| [Link]() | |
U1 | WSON8_DSG_TEX | 1 | TPS923650D2DSGR | [Link]() | |
U2 | SOT-223-3_TabPin2 | 1 | AMS1117 | [Link]() | |

## 3D Printed Parts Production

## Power Input
<img width="281" height="203" alt="image" src="https://github.com/user-attachments/assets/27400bc2-1484-4492-9160-04feb5dca708" /><br>
The PCB was designed for a 12V input source. The Power+ pad connects to the positive side of the power supply. The SWITCH_IN and SWITCH_OUT pads connect to a switch

## Using Dimmer
<img width="421" height="209" alt="image" src="https://github.com/user-attachments/assets/81954d59-e54b-424d-bfb2-048e35033757" /><br>
The PCB uses a potentiometer to control the brightness of the LEDs; there are two ground pads. You can connect to either, but the other one is used for the GND of the Power input.<br>
The DIM pad is the input pad for the middle pin of the potentiometer, and the POT+ is the positive regulated source for the potentiometer.


## Purpose Of Project
The purpose of designing and building a custom desktop lamp for me is to learn more about power PCBs and controlling LEDs. 

