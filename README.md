# EspSerialPassthrough
ESP8266 / ESP-01 Serial Passthrough for flashing using Arduino SAMD MCU

This Arduino sketch allows you to send AT commands, watch bootloader messages or flash on an ESP-01/ESP8266 through a SAMD21/SAMD51 or similar MCU. 
The MCU should be operating at 3.3V, if not, voltage level shifters must be used on the connections to ESP.
The program might also work on other ESPs, but have only been tested with ESP8266 in the form of a ESP-01 board.

Developed and tested with a Arduino MKR board, SAMD21-based, with native USB connection to PC.
The program might work on MCUs without native USB, but no guarantees! :-)

Sending AT commands has been tested using the Arduino serial monitor, Visual Micro serial monitor and Putty in serial mode.
The same goes for watching bootloader output.
Firmware upgrade/flashing has been done with the official ESP8266 Flash Download Tool from https://www.espressif.com/en/support/download/other-tools, 
with firmware downloaded from https://www.espressif.com/en/support/download/at


Copyright 2021 Kåre Smith (Kaare Smith)

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

  http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
