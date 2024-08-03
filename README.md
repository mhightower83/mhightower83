## Notes and Projects
* [Arduino ESP8266 misc](https://github.com/mhightower83/Arduino-ESP8266-misc/wiki) my notes
## Libraries
* [AbendInfo](https://github.com/mhightower83/AbendInfo) Arduino ESP8266 library - Intercept some crash events that result in Hardware or Software WDT Resets. Cache the results across reboot.
* [BacktraceLog](https://github.com/mhightower83/BacktraceLog) An Arduino ESP8266 library that generates and stores a backtrace of a crash in an IRAM or DRAM log buffer. By crunching the stack trace and code to create a list of function addresses at play when the crash occurred, we can condense the amount of data that needs to be stored for later analysis. Reducing the data to a small list allows storage in slivers of unused IRAM or noinit DRAM, which can optionally be backed up to User RTC memory.
* [MAX31855K](https://github.com/mhightower83/MAX31855K) Arduino ESP8266 Device Library for the MAX31855K with the option to apply linear corrections to non-linear thermocouple response.
   * [Troubleshooting](https://github.com/mhightower83/MAX31855K/wiki/Troubleshooting#troubleshooting) sections has some insight on issues that can occur with the ESP8266 and SPI devices.
* [SpiFlashUtils](https://github.com/mhightower83/SpiFlashUtils) An Arduino ESP8266 library that supports reclaiming the use of GPIO pins 9 and 10 on ESP8266 modules that expose access to those pins. SPI Flash Mode "DIO" or "DOUT" is required.
   * [A Review of Past Attempts](https://github.com/mhightower83/Arduino-ESP8266-misc/wiki/Pins-GPIO9-and-GPIO10#a-review-of-past-attempts)
* [JedecJep106Lib](https://github.com/mhightower83/JedecJep106Lib) SPI Flash Bank/MFG ID Lookup. Provides a wrapper to use flash manufacturer name look-up library from [tianocore/edk2](https://github.com/tianocore/edk2/blob/master/MdePkg/Library/JedecJep106Lib/JedecJep106Lib.c) on an Arduino build platform. 

<!--   
unable to position at section of the page
   * <a href="https://github.com/mhightower83/MAX31855K/wiki/Troubleshooting#troubleshooting" target="_blank">Troubleshooting</a> sections has some insight on issues that can occur with the ESP8266 and SPI devices.
   * <a href="https://github.com/mhightower83/Arduino-ESP8266-misc/wiki/Pins-GPIO9-and-GPIO10#a-review-of-past-attempts" target="_blank">A Review of Past Attempts</a>
--> 


## Tools
* [WiFiPcap](https://github.com/mhightower83/WiFiPcap) Stream WiFi packets encapsulated with PCAP to Wireshark using a USB port. It runs on an ESP32S3.

<!--
**mhightower83/mhightower83** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
