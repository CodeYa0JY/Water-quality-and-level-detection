# Water-quality-and-level-detection
## 1.Project description
  This water quality monitoring programs are designed to detect and assess the quality of specific bodies of water to ensure their sustainable management and protection. This project reflects the quality of water body by measuring TDS of water body. It can also measure the water level (depth).
## 2.Function Description
### 2.1 Data collection
  The system can be connected to the water body to be measured.
  The TDS probe can capture the TDS data of the water body and transmit the data to the embedded system.
  Water level sensors can transmit data to embedded systems.
### 2.2 Data processing
  The collected TDS data and water level are processed in real time in the embedded system.
### 2.3 Data display
  The measured TDS data and water level data are displayed on the LCD screen in real time.
## 3.Hardware selection
### 3.1 Main control chip
  STM32F103ZERT6
### 3.2 TDS collection module
  TDS BOARD V1.0 + TDS probe
### 3.3 Water level module
  TM7711 + w25Q32
### 3.4 ADC module
  ADS1115
### 3.5 Display module
  TFT LCD module:Z350IT002 + controller chip:ILI9486
## 4.Software framework
### 4.1 Common layer
  Dealy + debug
### 4.1 Driver layer
  USART + FSMC + SPI + I2C
### 4.2 Hardware interface layer
  LCD + TM7711 + ADS1115 + W25Q32
### 4.3 Application layer
 Display + TDS + Water_level
