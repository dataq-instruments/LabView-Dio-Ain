# LabView-Dio-Ain
A Labview example employing one analog input channel along with digital input and output

This LabView example demonstrates how to acquire continuous waveforms from one analog and one digita channel from DI-2008, using DataqSDK ActiveX. At the same time, allowing user to toggle the state of D6 as digital output

See https://github.com/dataq-instruments/Labview for more discussion and other examples

![alt text](https://www.dataq.com/resources/repository/labviewdio.gif "ScreenCapture by LICECap")

Footnotes: 

Use dataqxc.chm under c:\windows\help as reference in the following instructions:<br/>
To enable digital input channel, see ADCChannelList <br/>
To select the direction of DIO port, see Setting Bidirectional Digital Bits under DigitalOuput section<br/>
To output to Digital port, see DigitalOuput <br/>
The digital bits are in the higher byte of the raw data returned by GetData
