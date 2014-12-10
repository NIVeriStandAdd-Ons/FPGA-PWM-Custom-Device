## FPGA PWM Custom Device ##

The **FPGA PWM Custom Device** reads and writes to PWM IP instantiated into an NI FPGA. This allows use of FPGA PWMs in NIVS without having to pipe the data through the DMA template.

The FPGA IP to be instantiated into your FPGA VI is contained inside the *Source\IP* folder. 
After placing the FPGA IP, your indicators should be prefixed with "PWM read." and your PWM write indicators should be prefixed with "Timeout." and "PWM write.". This makes sure they are recognized by the custom device.

### LabVIEW Version ###

LabVIEW 2013

### Built Availability ###

No builds are provided.

### Quality, Limitations ###

This custom device is of good quality, but has limited use. It was developed in early 2014.

### License ###

*This repository and any materials provided by NI therein are provided AS IS. NI DISCLAIMS ANY AND ALL LIABILITIES FOR AND MAKES NO WARRANTIES, EITHER EXPRESS OR IMPLIED, INCLUDING WITHOUT LIMITATION ANY WARRANTIES OF MERCHANTABILITY, FITNESS FOR  PARTICULAR PURPOSE, OR NON-INFRINGEMENT OF INTELLECTUAL PROPERTY. NI shall have no liability for any direct, indirect, incidental, punitive, special, or consequential damages for your use of the repository or any materials contained therein.*