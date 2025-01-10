# tp-sentry
> [!CAUTION]
> **WORK IN PROGRESS!**  
> Documentation isn't complete and this is an ongoing project. Don't use it yet :)

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
URLs are provided for reference, but use whatever you have. 

| Supply | URL | Notes |
| ------ | --- | ----- |
| 26AWG Silicon Wire | https://www.amazon.com/gp/product/B01KQ2NURG?th=1 | I prefer to use this because it's flexible and can be stripped with fingernails, but use whatever you have as long as it works. |
| Solder | https://www.amazon.com/gp/product/B003CLBL2U | My preference is SAC lead-free with a no-rinse rosin core |
| Flux | https://www.amazon.com/dp/B08KJPG3NZ?th=1 | Use flux. Flux cleans the metal from oxidation and helps the solder flow. Flux is your friend. If your solder isn't flowing or sticking, you need more flux. |
| Soldering Iron | https://pine64.com/product/pinecil-smart-mini-portable-soldering-iron/ | Make sure you use a soldering iron with a temperature control. Don't use the cheap ones from the big box stores. A [Pinecil](https://pine64.com/product/pinecil-smart-mini-portable-soldering-iron/) is a great choice for the occasional hobbyist! |
| M3 Nylon Washers | https://www.amazon.com/gp/product/B07KQVNQ95 | Make sure you use nylon to prevent accidental shorts | 
| M3x5mm Screws | https://www.amazon.com/gp/product/B07VNDFYNQ | A good assortment is always useful to have! |
| M1x4mm Screws | https://www.amazon.com/gp/product/B07X1N69FM | Another good assortment to have. | 

## Assembly

## Firmware
1. Install the ESPHome firmware on the ESP32. There are multiple ways to do this, the primary two are listed here:
   - Install via a new device in the ESPHome addon for Home Assistant (preferred since it simplifies things): https://esphome.io/guides/getting_started_hassio.html
   - Install via the ESPHome web installer: https://web.esphome.io/
2. Configure the YAML
   - ADD CONFIG INFO HERE
3. Upload the YAML

## Installation and Calibration

## Automations

## To-Do

