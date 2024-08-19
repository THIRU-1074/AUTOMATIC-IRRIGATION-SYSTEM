The project consists of 8051 Microcontroller Program for operating the **Solenoid Valve**(for irrigation) and **UV LED**(for pest capturing at night) 
with the readings from the pre calibrated **Soil Moisture** Sensor and **LDR Sensor** Modules.

The inputs fromt the sensor modules are given to the two **External Interrupts** (**INT0 && INT1**) of 8051 MC. The polling is employed at the ISR(Interrupt Service Routine) to return back to the state. The **actuations** are made **stable** and **external interference** **resistant** by the use of carefully designed **checkers** which checks if the **trigger** is **genuine** by **sampling** the interrupt pins for specific time intervals.
