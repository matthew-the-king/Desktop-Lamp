# Desktop-Lamp
Runs on a 12V source
<img width="952" height="592" alt="LED_Lighting" src="https://github.com/user-attachments/assets/1bc4ccbe-8efb-4c6f-b2bf-a8f540d78849" /><br>


## PCB Production
Designator,Footprint,Quantity,Value,LCSC Part #
+POWER,SolderWirePad_1x01_SMD_5x10mm,1,SWITCH_IN,
"C1, C2, C5",0402,3,0.1uF,
C10,0402,1,10nF,
"C11, C12, C3, C6, C8",1210,5,10uF,
C13,0603,1,1nF,
C4,0603,1,1uF,
C7,0402,1,100pF,
C9,CAP_A768EB_6.8x6.8_KEM,1,100uF,
D1,TO-277A,1,D,
DIM,SolderWirePad_1x01_SMD_5x10mm,1,POT_MIDDLE,
GND_2,SolderWirePad_1x01_SMD_5x10mm,1,-POT,
GND,SolderWirePad_1x01_SMD_5x10mm,1,-POWER,
L1,SMD2_CDRH127_SUM,1,33uH,
"LED1, LED10, LED2, LED3, LED4, LED5, LED6, LED7, LED8, LED9",LED_CREE_XPE,10,XPEBWT-L1-0000-00CE7,
POT+,SolderWirePad_1x01_SMD_5x10mm,1,+POT,
R1,1206,1,0.57Ω,
"R2, R5",0603,2,100Ω,
R3,0402,1,10kΩ,
R4,0402,1,7.6kΩ,
SWITCH_IN,SolderWirePad_1x01_SMD_5x10mm,1,+POWER,
SWITCH_OUT,SolderWirePad_1x01_SMD_5x10mm,1,SWITCH_OUT,
U1,WSON8_DSG_TEX,1,TPS923650D2DSGR,
U2,SOT-223-3_TabPin2,1,AMS1117,

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

