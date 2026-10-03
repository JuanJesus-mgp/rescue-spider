# rescue-spider
Autonomous/manual quadruped search-and-rescue robot prototype

## Especificaciones de Hardware
- **Controlador Principal:** ESP32 Dev Module
- **Controlador de Servos:** PCA9685 (I2C)
- **Sensor de Distancia:** VL53L0X ToF (I2C)
- **Sensor de Audio:** Micrófono INMP441 (I2S)
- **Alimentación Dual:** Reguladores LM2596 calibrados a 5.0V (lógica) y 5.5V (servos) con GND común.

## Estructura del Proyecto
- `src/`: Código fuente en C++ para PlatformIO.
- `docs/architecture/`: Diagramas de flujo y arquitectura del sistema.
- `docs/hardware/`: Diagramas de conexión y potencia.
- `docs/roadmap/`: Planificación de Sprints y seguimiento.
- `docs/manuals/`: Guias y datasheets de componentes.

## Entorno de Desarrollo
- VS Code + PlatformIO (Framework Arduino)
- Control de versiones con Git/GitHub