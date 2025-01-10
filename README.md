# tp-sentry
[!CAUTION] WORK IN PROGRESS! Documentation isn't complete and this is an ongoing project. Don't use it yet :)

Are you tired of your kids leaving the TP roll empty for you to discover only once you're in need? The TP Sentry is the solution to your crappy problem!

At the heart of the TP Sentry is an ESP32, which communicates with Home Assistant to report when the TP roll is empty and when it's been refilled. A Time-of-Flight (ToF) ranging sensor is utilized to measure the distance between the sensor and the TP left on the roll. 

## Hardware
| Part | URL | Notes |
| ---- | --- | ----- |
| ESP32-C3 | https://www.amazon.com/gp/product/B0B94JZ2YF/?th=1 | Other variants of this formfactor may work, but have not been tested. This one was chosen only for the delivery speed :) |
| GY-530 VL53L0X Ranging Sensor Module | https://www.amazon.com/gp/product/B0B1M79WMP | One needed for each roll to be monitored. Others may work for this as well, but this is what I built with | 
| LDO 3.3v Voltage Regulator | TBD | |
| Printed Holder | Tinkercad URL | Print this yourself | 

## Supplies
| Supply | Notes |
| --- | --- |
| Silicon Wire | I prefer to use this because it's flexible and can be stripped with fingernails |
| Solder | My preference is SAC lead-free with a no-rinse rosin core |
| Flux | Use flux. Flux is your friend |
| Soldering Iron | Make sure you use a soldering iron with a temperature control. Don't use the cheap ones from the big box stores. A [Pinecil](https://pine64.com/product/pinecil-smart-mini-portable-soldering-iron/) is a great choice for the occasional hobbyist! |

## Building

## Firmware

## To-Do

