# ESP32
<img width="597" height="631" alt="Screenshot 2026-11-20 163231" src="https://github.com/user-attachments/assets/1c702b9e-92be-46c2-9f35-3e53315bb078" />

So I made a custom devboard based on ESp-Wroom-32 . It has a USB-C for power and signal and has interval voltage regulator to regulate the voltage down to 3.3V prior to that we have onboard LEDs and  USB to UART circuit and it has 2 sets of 15 connectors that connectes to power , gnd and multiple pins on the ESP32.

## features 
- Based onc interface
-   ESP - WROOM -32
- Has USB-C interface
- Has 3.3V voltage regulator
- Has USB to UART  circuit

# Schamtics 
<img width="978" height="630" alt="Screenshot 2026-11-20 165541" src="https://github.com/user-attachments/assets/817014d2-40aa-4129-aabc-ef02ad8545dd" />

# PCB
<img width="715" height="392" alt="Screenshot 2026-11-20 163212" src="https://github.com/user-attachments/assets/c52608bb-e7ea-4a55-a7da-ad4abc068376" />

# CAD
<img width="597" height="631" alt="Screenshot 2026-11-20 163231" src="https://github.com/user-attachments/assets/2362dc92-e137-4566-8a50-5e921c3b0a99" />



# BOM

| Category | Component / Charge | Designator | Quantity | Total Price (USD) | Link | Note |
|---|---|---|---:|---:|---|---|
| Component | 100nF ceramic capacitor | C1,C3,C4,C5,C6 | 25 | 0.1375 | https://jlcpcb.com/partdetail/YAGEO-CC0603KRX7R9BB104/C14663 | YAGEO CC0603KRX7R9BB104 |
| Component | 10uF/16V aluminum electrolytic capacitor | C2 | 5 | 0.892 | https://jlcpcb.com/partdetail/HonorElec-UD2E100M1010/C88697 | Honor Elec UD2E100M1010 |
| Component | B5819W Schottky diode | D1 | 20 | 0.344 | https://jlcpcb.com/partdetail/hongjiacheng-B5819W/C7420330 | hongjiacheng B5819W |
| Component | Red 0603 LED | D2 | 20 | 0.074 | https://jlcpcb.com/partdetail/XINGLIGHT-XL_1608SURC06/C965799 | XINGLIGHT XL-1608SURC-06 |
| Component | Blue 0603 LED | D3 | 20 | 0.082 | https://jlcpcb.com/partdetail/XINGLIGHT-XL_1608UBC04/C965807 | XINGLIGHT XL-1608UBC-04 |
| Component | USB-C receptacle, USB 2.0, 16-pin | J1 | 2 | 4.1262 | https://jlcpcb.com/partdetail/XKBConnection-USB31_TYPE_CFSABC/C2880583 | XKB Connection USB31-TYPE-C-FSABC |
| Component | SS8050 NPN transistor | Q1,Q2 | 12 | 0.1392 | https://jlcpcb.com/partdetail/hongjiacheng-SS8050/C7420370 | hongjiacheng SS8050 |
| Component | 5.1kΩ resistor, 0603 | R1,R2 | 20 | 0.03 | https://jlcpcb.com/partdetail/23913-0603WAF5101T5E/C23186 | UNI-ROYAL 0603WAF5101T5E |
| Component | 1kΩ resistor, 0603 | R3 | 20 | 0.032 | https://jlcpcb.com/partdetail/21904-0603WAF1001T5E/C21190 | UNI-ROYAL 0603WAF1001T5E |
| Component | 10kΩ resistor, 0603 | R4,R5,R6 | 20 | 0.034 | https://jlcpcb.com/partdetail/26547-0603WAF1002T5E/C25804 | UNI-ROYAL 0603WAF1002T5E |
| Component | 220Ω resistor, 0603 | R7 | 20 | 0.034 | https://jlcpcb.com/partdetail/23689-0603WAF2200T5E/C22962 | UNI-ROYAL 0603WAF2200T5E |
| Component | Push-button switch | SW1,SW2 | 4 | 2.0892 | https://jlcpcb.com/partdetail/55982-DSIC01LHGET/C54957 | DongGuan KINGTEK DSIC01LHGE |
| Component | ESP32-WROOM-32 module | U1 | 2 | 8.892 | https://jlcpcb.com/partdetail/EspressifSystems-ESP32_WROOM_32N4/C82899 | Espressif ESP32-WROOM-32-N4 |
| Component | CH340C USB-to-serial converter | U2 | 2 | 1.1916 | https://jlcpcb.com/partdetail/WCH_Jiangsu_Qin_Heng-CH340C/C7464026 | WCH CH340C |
| Component | AMS1117-3.3 voltage regulator | U3 | 2 | 0.4016 | https://jlcpcb.com/partdetail/Advanced_MonolithicSystems-AMS1117_33/C6186 | Advanced Monolithic Systems AMS1117-3.3 |

## Order Cost

| Category | Component / Charge | Total Price (USD) |
|---|---|---:|
| Order cost | PCB fabrication | 4.00 |
| Order cost | PCBA setup fee | 25.75 |
| Order cost | Stencil | 8.27 |
| Order cost | Panel | 0.00 |
| Order cost | Large size | 0.00 |
| Subtotal (informational) | Components subtotal (15 items) | 18.50 |
| Order cost | Feeders loading fee | 21.70 |
| Order cost | SMT assembly | 0.94 |
| Order cost | Hand-soldering labor fee | 3.61 |
| Order cost | Manual assembly | 0.40 |
| Order cost | Packaging fee | 0.50 |
| Order cost | Special components fee | 0.06 |
| Shipping | Shipping | 9.27 |
| Discount | Discount | -10.00 |
| **Total** | **Grand Total** | **83.00** |

