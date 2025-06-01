# OctaDeck

A modular bike handlebar dock and a small ~~cube-shaped~~ octagonal smart display and sensor unit. It acts as a speedometer, odometer, trip computer, and weather station, showing current speed, average speed, max speed, total distance, trip duration, temperature, humidity, and pressure. 
Powered by a Raspberry Pi Pico and a LiPo battery that charges from a bike dynamo when the bike is in motion.

The dock will also include powerful front and rear lights powered directly by the dynamo or controlled by the MCU via a 3-position switch, allowing lights to run off the dynamo, independently on battery, or be off.

The display unit is detachable and slides into a dock mount fixed on the handlebar. The dock provides power and sensor connections through two metal pins.

## Key Features
- Speedometer & Odometer using a Hall effect sensor detecting wheel rotation
- Trip computer showing trip time, total distance, average and max speed
- Weather station using a BME280 sensor measuring temperature, humidity, and atmospheric pressure
- Small OLED/LCD display (will probably use 1.3”)
- Power supplied by LiPo battery (3.7V) rechargeable from a bicycle dynamo
- Dynamo output rectified and regulated for charging and powering electronics
- Front and rear high-power LED bike lights on the dock, with modes: off, on (dynamo-only), on (always), controlled by a 3-position switch and MCU
- Detachable ~~display cube~~ octagonal display connecting via three metal pins to the dock for power and sensor inputs
- PCB, firmware, and all mechanical parts, including the dock and display enclosure, will be custom-made by me!! 

## So basically,
- Speedometer, odometer, avg/max speed, trip & lifetime stats
- Clock & ride duration
- Onboard weather station (BME280)
- Dynamo + LiPo power with charging logic
- Modular dock system with pogo pins
- Light control: OFF / Always ON / Auto (dynamo)
- Custom 3D-printed shell

