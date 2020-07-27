Voice activated LED facemask connection instructions<br />
<br />
Precautions:<br />
When making a voice-activated lamp mask, please be careful during the welding of the circuit, so as not to burn your skin by the welding machine! Please connect the circuit correctly and choose a good charging treasure. Short circuit and poor current input of the circuit may cause accidents! The voice-activated light mask is to be attached to the face, so the choice of mask fabric is very important, please choose fire-resistant fabric! Finally, please ask the younger children to make the production accompanied by an adult.<br />
<br />
Tools Needed:<br />
Solder<br />
Soldering iron<br />
Fabric Glue or a Sewing Kit<br />
Safety goggies<br />
Tape<br />
snips<br />
<br />
Optional Useful Stuff<br />
A heat shrink (electrical tape can make due in a pinch, but the heat shrink is nice)<br />
A digital multimeter (for ensuring your connections are correct and your electronics work)<br />
A soldering mat<br />
Arduino Nano<br />
<br />
The Parts<br />
Led matrix 8x8 WS2812B<br />
Microphone max4466<br />
Arduino Nano<br />
330Ω resistor<br />
24 Gauge wire<br />
Heat shrink<br />
5V power bank&nbsp;<br />
KCD1 Switch<br />
<br />
Physical circuit diagram<br />
<img src="http://dkardu.oss-cn-hongkong.aliyuncs.com/LED%20Mask%20IDE%20operating/Circuit%20diagram.jpg" /><br />
<br />
<br />
Circuit connection<br />
Led matrix 8x8 WS2812B DIN pin------------330Ω resistor<br />
330Ω resistor------------Arduino Nano D6 Pin<br />
max4466 microphone VCC pin-------------Arduino Nano 5V Pin<br />
max4466 microphone GND pin-------------Arduino Nano GND Pin<br />
max4466 microphone OUT pin-------------Arduino Nano A7 Pin<br />
Led matrix 8x8 WS2812B 5V pin------------ Arduino Nano VIN Pin<br />
Led matrix 8x8 WS2812B GND pin------------ Arduino Nano GND pin&nbsp;<br />
KCD1 switch------------ Arduino Nano D12 pin<br />
Arduino Nano GND pin------------ KCD1 switch<br />
<br />
<br />
<br />
Production<br />
1.<span> </span>Install Library file: Open "Tools"-"Library Manager" in the Arduino development software, then search for Adafruit_NeoPixel, Adafruit_NeoMatrix, Adafruit_GFX_Library, and then install these three libraries<br />
<img src="http://dkardu.oss-cn-hongkong.aliyuncs.com/LED%20Mask%20IDE%20operating/01.jpg" /><br />
<img src="http://dkardu.oss-cn-hongkong.aliyuncs.com/LED%20Mask%20IDE%20operating/02.jpg" /><br />
<img src="http://dkardu.oss-cn-hongkong.aliyuncs.com/LED%20Mask%20IDE%20operating/03.jpg" /><br />
2.<span> </span>Select the development board as Arduino Nano, this is to choose the right.<br />
<img src="http://dkardu.oss-cn-hongkong.aliyuncs.com/LED%20Mask%20IDE%20operating/04.jpg" /><br />
<br />
3.<span> </span>Select the processor as ATmega328P(Old Bootloader), this is to choose the right.<br />
<img src="http://dkardu.oss-cn-hongkong.aliyuncs.com/LED%20Mask%20IDE%20operating/05.jpg" /><br />
<br />
4.<span> </span>Then select the port, this port should be the same as what you see in the device manager, so that you can burn the code into the development board.<br />
<img src="http://dkardu.oss-cn-hongkong.aliyuncs.com/LED%20Mask%20IDE%20operating/06.jpg" /><br />
<br />
