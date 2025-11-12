# esp-32-s3-muhammad-hisyam-arrafi-3223600018-task2
# ESP32-S3 Multitasking Peripheral Control

Menampilkan implementasi **multitasking FreeRTOS** pada **ESP32-S3** untuk mengontrol berbagai periferal seperti OLED, LED, buzzer, tombol, potensiometer, rotary encoder, motor stepper, dan servo.

Link Video: [Video Hasil Percobaan Semua Peripheral](https://drive.google.com/file/d/1gZBGjFDgAgjhzbgmneUae_K-EvhZoiEe/view?usp=sharing) 

---

## Hardware yang Digunakan

| Komponen        | Pin ESP32-S3                  | Keterangan          |
|-----------------|------------------------------|---------------------|
| **OLED**        | SDA = 8, SCL = 9              | I2C interface       |
| **LED**         | GPIO 7                        | Output              |
| **Buzzer**      | GPIO 6                        | Output              |
| **Tombol 1**    | GPIO 5                        | Input (Pull-up)     |
| **Tombol 2**    | GPIO 4                        | Input (Pull-up)     |
| **Potensiometer** | GPIO 1                      | Analog input        |
| **Encoder**     | CLK = 10, DT = 11             | Rotary input        |
| **Stepper Motor** | IN1 = 18, IN2 = 17, IN3 = 16, IN4 = 15 | 4 Coil Output  |
| **Servo**       | GPIO 42                       | PWM Output          |

## Library yang Diperlukan
- `Adafruit SSD1306`
- `Adafruit GFX`
- `AccelStepper`
- `ESP32Servo`
