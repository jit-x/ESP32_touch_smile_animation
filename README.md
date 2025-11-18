# ESP32_touch_smile_animation
ESP32 OLED facial animation with touch-activated smile transition

## Hardware Used

Library used: `U8g2lib.h`

Display: SSD1306 128x64 I²C

Development board tested: Node32s (ESP32-WROOM)

Touch pin: T5 (configurable in `setup` and `loop`)

## Animation Structure

Idle blink animation: frames `0–7`

Touch-activated smile: frames `8–22`
Transition to idle: frames `22–8` (played in reverse)
