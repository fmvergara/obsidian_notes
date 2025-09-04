# CPU  
* Execute instructions of program
* **What it contains:**
	- **ALU (Arithmetic Logic Unit):** Does math/logic.
	- **Registers:** Small, very fast storage.
	- **Program Counter (PC):** Keeps track of where you are in memory.
	- **Control Unit / Decoder:** Figures out what each instruction means.
	- **Optional extra units:** Cache, pipelines, floating-point unit, SIMD, etc
* Examples: 
 ![[Cortex1.webp]]
![[arm-m0.avif]]
![[m33_cortex.avif]]
# MCU
* A **chip** that includes:
	- A CPU core (e.g., Cortex-M0)
	- Flash memory (for program storage)
	- SRAM (for runtime variables)
	- Peripherals (UART, SPI, I²C, timers, ADC, DAC, GPIO)
	- Clocking and power management
 * Examples:
![[Pasted image 20250904143102.png]]
![[Pasted image 20250904143232.png]]
STM32U585 Components
![[Pasted image 20250904143442.png]]
# Development Board 
A PCB with an MCU for easy prototyping
* NUCLEO-WBA55CG
* ![[pf272736_m.webp]]
* NUCLEO-F072RB
* ![[pf260003_m_3.webp]]
