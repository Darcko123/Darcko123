# Daniel | Ingeniero en Electrónica

¡Bienvenido a mi perfil de GitHub!

Soy Ingeniero en Electrónica con interés en sistemas embebidos, procesamiento digital de señales, visión computacional y seguridad de hardware. Actualmente colaboro como ingeniero en [Electronic Cats](https://github.com/ElectronicCats), desarrollando herramientas de código abierto para auditoría de seguridad en NFC, RFID e inyección de fallos electromagnéticos (EMFI). Este repositorio principal recopila los proyectos, librerías y guías más relevantes que he desarrollado en C, C++ y Python.

## Repositorios principales

### STM32 Embedded Libraries and Examples

Repositorio dedicado al desarrollo de proyectos utilizando microcontroladores STM32. Incluye ejemplos prácticos, librerías personalizadas y configuraciones con STM32CubeIDE.

**Temas principales:**
- Comunicación por UART, I2C, SPI
- Uso de ADC, DAC y PWM
- Configuración de timers y DMA
- Implementación de filtros digitales FIR
- Librerías de periféricos: ILI9341, SSD1306, NV3007, PCA9685, MAX7219, MPU6050, SI7021, AHT10

[Ver repositorio STM32](https://github.com/Darcko123/STM32)

---

### HD44780_LCD - Librería para LCD en STM32

Librería para módulos LCD HD44780 por I2C basada en STM32 HAL. Fork del trabajo original de eziya al que se le añadió manejo robusto de errores mediante códigos de retorno en todas las funciones públicas, delays basados en DWT y caracteres especiales predefinidos.

**Temas principales:**
- Driver I2C sobre STM32 HAL
- Manejo robusto de errores con códigos de retorno
- Delays basados en DWT (sin bloqueos por timers)
- Caracteres personalizados predefinidos

[Ver repositorio HD44780_LCD](https://github.com/Darcko123/HD44780_LCD)

---

### Reloj Inteligente con STM32

Sistema de reloj inteligente con interfaz de menús interactiva para STM32F103. Incluye RTC DS3231 de alta precisión, monitoreo ambiental con sensor SI7021, sistema de alarmas múltiples, señal horaria por PWM y navegación jerárquica mediante botones físicos. El hardware fue diseñado en KiCad.

**Temas principales:**
- Comunicación I2C con DS3231 y SI7021
- Sistema de menús con navegación jerárquica
- Control PWM y software debounce
- Diseño de PCB en KiCad

[Ver repositorio Clock_STM32_Firmware](https://github.com/Darcko123/Clock_STM32_Firmware)

---

### Raspberry Pi Zero 2W - Ejemplos en C/C++

Este repositorio contiene ejemplos organizados por categorías para trabajar con la Raspberry Pi Zero 2W, enfocados en el control de hardware, desarrollo web y visión por computadora.

**Subcategorías:**
- **Páginas web**: Ejemplos básicos de servidores web locales.
- **Periféricos con WiringPi**: Control de GPIOs, lectura de sensores, y uso de interrupciones.
- **Visión con OpenCV**: Procesamiento de imágenes, selección de ROI, transformadas de Hough y más.

[Ver repositorio Raspberry Pi](https://github.com/Darcko123/Raspberry)

---

## Colaboración con Electronic Cats

Formo parte de la organización [Electronic Cats](https://github.com/ElectronicCats), donde contribuyo en herramientas open source de seguridad de hardware:

- **[BomberCat](https://github.com/ElectronicCats/BomberCat)** – Auditoría de terminales bancarios y tarjetas NFC/banda magnética (firmware C++ y herramientas en Python).
- **[Minino](https://github.com/ElectronicCats/Minino)** – Tabla multiprotocolo y multibanda para sniffing y ataque de dispositivos IoT (ESP32-C6).
- **[FaultyCat](https://github.com/ElectronicCats/faultycat)** – Herramienta de bajo costo de inyección de fallos electromagnéticos (EMFI): firmware, logic analyzer compatible con SUMP/OLS y TUI.
- **[PWNPet_CLI](https://github.com/ElectronicCats/PWNPet_CLI)** – Interfaz de línea de comandos BLE para el badge PwnPet.
- **[CatSniffer-Tools](https://github.com/ElectronicCats/CatSniffer-Tools)** – Suite de sniffing LoRa/Zigbee/Thread con registro de paquetes.

---

## Tecnologías y herramientas

- C / C++
- Python
- STM32CubeIDE / STM32 HAL
- KiCad
- OpenCV
- WiringPi
- Raspberry Pi OS
- Git y GitHub

---

## Estadísticas

[![GitHub Streak](https://streak-stats.demolab.com?user=Darcko123&theme=highcontrast&hide_border=true&locale=es&date_format=j%20M%5B%20Y%5D&mode=weekly)](https://git.io/streak-stats)

![Darcko123's GitHub stats](https://github-stats-extended.vercel.app/api?username=Darcko123&show_icons=true&theme=great-gatsby)

[![Logros](https://img.shields.io/badge/logros-Pull_Shark_x2_%7C_Pair_Extraordinaire-2088FF)](https://github.com/Darcko123?tab=achievements)

---

## Contacto

¿Interesado en colaborar o conocer más sobre mis proyectos?

[![Email](https://img.shields.io/badge/email-FFFFFF?style=for-the-badge&logo=email&logoColor=black)](daniel18052002@yahoo.com)
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/daniel-alejandro-ruiz-d%C3%ADaz-340b6328a)

## En desarrollo

Actualmente me encuentro ampliando mis repositorios personales con nuevas librerías para STM32, documentación y proyectos integradores que combinen seguridad de hardware y control embebido. Próximamente publicaré también los diseños de hardware (KiCad) de mis proyectos de relojes y control de clima.

> Este repositorio está en constante crecimiento como parte de mi formación y portafolio profesional. ¡Gracias por visitar!
