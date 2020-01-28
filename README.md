# FHEM_MQTT_ESP8266_1
a room device with button, temp-, humidity- and motion-sensor, 3 pwm and a buzzer communicating via MQTT(s) with FHEM

 * Lights and more via MQTT
 * LOLIN WeMOS D1 Mini R2
 * ESP8266-12(x)
 * V1.0
 * use this without warranty
 * (C) 2020 Familienpapi

 * 3x PWM (RGB possible)
 * 1x button
  * 4 funct.: 1, 2 and 3 times and long
 * 1x buzzer
 * 1x motion sensor
 * 1x TSL2561 light sensor
 * 1x BME280 temp and humi via I2C
  * or HTU21 temp and humi via I2C
 * send data via MQTT(s)
 
 * used Pins:
 *   0 [D3]: button
 *   2 [D4]: WS2812 LED
 *   4 [D2]: I2C SDA
 *   5 [D1]: I2C SCL
 *  12 [D6]: IR receiver
 *  13 [D7]: pwm1
 *  14 [D5]: pwm2
 *  15 [D8]: pwm3
 *  16 [D0]: buzzer
 * ADC [A0]: motion
 
