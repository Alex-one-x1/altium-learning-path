# PicoLimitSwitchShield

Shield для Raspberry Pi Pico — мониторинг 5 концевых выключателей, 
питание от LiPo с зарядкой через USB, связь с ПК через USB Serial.

## Статус
В разработке, первый прототип.

## Архитектура
- MCU: Raspberry Pi Pico (RP2040), съёмный
- Питание: LiPo 1S 1000-1200 mAh, зарядка TP4056 + дискретный power-path
- Входы: 5× концевик с RC-debounce и ESD-защитой
- Интерфейс: USB Serial (виртуальный COM) через micro-USB Pico