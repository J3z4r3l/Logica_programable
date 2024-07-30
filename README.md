# Proyecto Final de Lógica Programable: Desarrollo de Juego utilizando Hardware y Software

## Descripción

Este es el proyecto final de la materia de Lógica Programable. El objetivo del proyecto es desarrollar un juego utilizando tanto hardware (FPGA) como software (Processing). El sistema está desarrollado utilizando Vivado para la síntesis y simulación de hardware, y Processing para la visualización y control del sistema.
El juego esta inspirado en el famoso anime Saint Seiya, se usaron los personajes de andromeda y cisne para este juego, las animaciones y el código se encuentran dentro de las carpetas
## Estructura del Proyecto

### Carpeta `Game`

Contiene los recursos gráficos y de audio necesarios para la visualización y el control del sistema, así como el código fuente escrito en Processing.

- **Archivos de imágenes**: `.png`
- **Archivos de audio**: `.mp3`
- **Código fuente en Processing**: `main.pde`, `player1.pde`, `player2.pde`

### Carpeta `vivado_constrains`

Contiene el archivo de restricciones de diseño para Vivado.

- **Archivo de restricciones**: `Arty-A7-35-Master.xdc`

### Carpeta `vivado_psm`

Contiene el programa para la implementación en Vivado PSM.

- **Archivo de programa PSM**: `your_program.psm`

### Carpeta `vivado_sources`

Contiene los archivos fuente del sistema escritos en VHDL.

- `baud_rate_clock.vhd`
- `embedded_kcpsm6.vhd`
- `kcpsm6.vhd`
- `modulo_spi.vhd`
- `modulo_uart.vhd`
- `pmod_accelerometer_adxl345.vhd`
- `registro_puerto_entrada.vhd`
- `spi_master.vhd`
- `top_level.vhd`
- `uart_rx6.vhd`
- `uart_tx6.vhd`
- `your_program.vhd`


## Requisitos

- Vivado Design Suite
- Processing IDE
- Dispositivo FPGA compatible

## Autores
José Jezarel Sánchez Mijares 
Angel Ramirez Ramirez
