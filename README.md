# LG Safety Product Design
#### Client Name: Brad Fairman
 
## Project Requirements
### System Block Diagram
The diagram below highlights the key features required in the product:
![image](https://github.com/eSpark-Consultants/bradfairman-lgsafety-hw/assets/76909080/49c9d82f-d559-453a-a8c2-9ce39479f1c1)

Some other key points (not fully clear in system block diagram) are:
- The preference for main MCU is from STM32 series. The MCU should be selected based on performance and pin requirements whereas cost should be considered as well.
- The electronics in design should be based off of JLCPCB and peripherals not available can be arranged separately.
- The link to actuators mentioned in system BD are attached [here](https://f.hubspotusercontent40.net/hubfs/7717445/PDF%20Manuals/Actuator%20datasheets/PA-14P%20datasheet.pdf). We will go with 24V variant.
- IR Beam break as suggested by client are attached [here](https://www.adafruit.com/product/2168) but this selection is not final and open to recommendations.
- The use of ToF is optional in the product. Since the actuators have a potentiometer that will report their position, we can skip the ToF unless any use case is found to add as an additional feedback.
