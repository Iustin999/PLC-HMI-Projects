# Automatic Pressure Control System

## Description (EN)

This project simulates an industrial-style pressure control system using Rockwell Automation hardware and software. Unlike a fully virtual exercise, this implementation involved downloading logic to a physical Allen-Bradley PLC via Ethernet/IP, acquiring live analog input from a pressure sensor module (1734-IE2C), and linking a FactoryTalk View HMI to controller tags through RSLinx Enterprise. Although no physical actuator (e.g., compressor) was activated, the control logic closely replicates a real industrial setup.

Designed as a hands-on learning experience, the system reads raw analog data from a sensor, converts it into engineering units, compares it to a user-defined reference pressure, and activates a virtual compressor output if the pressure falls below the threshold.

### Key Features
- Real PLC download and Ethernet/IP setup  
- Live data acquisition from a 1734-IE2C analog input module  
- Raw-to-engineering unit conversion using CPT instructions  
- Ladder logic comparison to trigger the `Compressor_ON` tag  
- FactoryTalk View Studio HMI with real-time pressure display and control buttons  
- Seamless PLC–HMI communication via RSLinx Enterprise  

### Documentation
Full technical documentation is available here:  
[Documentation Automatic Pressure Control System.pdf](./Documentation%20Automatic%20Pressure%20Control%20System.pdf) (written in English)

---

## Descriere (RO)

Acest proiect simulează un sistem industrial de control automat al presiunii, folosind hardware și software Rockwell Automation. Spre deosebire de o simulare exclusiv virtuală, implementarea a implicat descărcarea logicii într-un PLC Allen-Bradley real, conectat prin Ethernet/IP, preluarea în timp real a unui semnal analogic de la un senzor de presiune (modul 1734-IE2C) și conectarea interfeței HMI realizate în FactoryTalk View la variabilele controllerului prin RSLinx Enterprise. Deși nu s-a acționat fizic un compresor, logica replică fidel un proces industrial funcțional.

Sistemul citește o valoare brută de la senzor, o convertește în unități inginerești, o compară cu o valoare de referință introdusă de utilizator și activează un tag virtual `Compressor_ON` dacă presiunea este sub pragul setat.

### Funcționalități
- Descărcarea logicii în PLC fizic și configurarea rețelei Ethernet/IP  
- Achiziție de date în timp real de la modulul analogic 1734-IE2C  
- Conversie a valorii brute în unități de inginerie cu bloc CPT  
- Comparație în ladder logic între presiune și setpoint pentru activarea tagului `Compressor_ON`  
- Interfață HMI în FactoryTalk View cu afișaj presiune și butoane START/STOP  
- Comunicare în timp real PLC–HMI prin RSLinx Enterprise  

### Documentație
Documentația completă este disponibilă aici:  
[Documentation Automatic Pressure Control System.pdf](./Documentation%20Automatic%20Pressure%20Control%20System.pdf) (scrisă în Engleză)

