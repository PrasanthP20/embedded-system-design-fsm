# LED FSM Project

This project demonstrates:
- ✅ Finite State Machine (FSM)-based LED control
- ✅ STM32 HAL with system abstraction
- ✅ Clean separation of `led.c`, `state_machine.c`

## 🔁 FSM States:
- `INIT` → `WAIT` → `BLINK`

## 📁 Structure:
led_fsm_project/
├── Core/
│ ├── Inc/
│ └── Src/
├── Docs/
└── README.md
## 📌 Purpose:
This is not just a blinking LED — it is my **first fully structured embedded firmware platform**, built using:
- System Design architecture
- State Machines (just like those in real SoC bootflows, PMIC sequences)
- Modular and portable code style

This is the foundation I’ll build upon in future PMIC, UART, and TurboX-level SoC projects.
