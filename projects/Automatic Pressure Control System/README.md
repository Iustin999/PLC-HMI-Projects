# Automatic Pressure Control System

## Description (EN)

This project simulates an industrial‐style pressure regulation setup using Rockwell Automation hardware and software. Unlike a purely virtual exercise, it involved downloading code to a physical Allen-Bradley PLC over Ethernet/IP, reading live analog input from a pressure sensor module (1734-IE2C), and linking a FactoryTalk View HMI to controller tags via RSLinx Enterprise. Although no actuator (compressor) was driven physically, the logic closely mirrors a real plant scenario.

Developed as a hands-on learning step, the system reads raw sensor data, converts it to engineering units, compares it against a reference setpoint, and toggles a virtual compressor output accordingly.

### Key Features
- Real PLC download and Ethernet/IP configuration  
- Periodic data acquisition from a live pressure sensor (1734-IE2C)  
- Raw-to-engineering unit conversion using CPT block  
- Ladder logic comparison to drive `Compressor_ON` tag  
- HMI in FactoryTalk View Studio showing live pressure and control buttons  
- RSLinks Enterprise integration for real-time PLC–HMI communication  

### Documentation
Full documentation is available here:  
[Documentation Automatic Pressure Control System.pdf](./Documentation%20Pressure%20Regulation%20System.pdf) (written in English)

---

## Descriere (RO)

Acest proiect prezintă un sistem de reglare a presiunii construit pe hardware Rockwell Automation conectat la un PLC fizic. Codul a fost descărcat în controller prin Ethernet/IP, valorile analogice de la un senzor de presiune (modul 1734-IE2C) au fost transformate în unități de inginerie, iar o interfață HMI realizată în FactoryTalk View Studio afișează datele în timp real și controlează starea unui tag virtual de compresor. Deși compresorul nu a fost acționat fizic, logica este fidelă unui proces industrial real.

Proiectul a fost conceput pentru a apropia simularea de mediul de producție, combinând configurarea IP, achiziția semnalului analogic și integrarea PLC–HMI.

### Funcționalități
- Descărcarea codului în PLC fizic și configurare Ethernet/IP  
- Achiziție periodică a valorilor de presiune de la modulul analogic 1734-IE2C  
- Conversia semnalului brut în unități de inginerie cu blocul CPT  
- Comparație ladder logic pentru setarea tagului `Compressor_ON`  
- Interfață FactoryTalk View Studio cu afișaj presiune și butoane START/STOP  
- Integrare RSLinks Enterprise pentru comunicare PLC–HMI în timp real  

### Documentație
Documentația detaliată este disponibilă aici:  
[Documentation Automatic Pressure Control System.pdf](./Documentation%20Pressure%20Regulation%20System.pdf) (scrisă în Engleză)
