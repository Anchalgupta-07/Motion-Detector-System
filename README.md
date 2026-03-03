# Motion-Detector-System
Int  pinsensor = 0; // Sensor input Void setup () { Serial.begin(9600); Pinmode(7,OUTPUT); Pinmode(10, OUTPUT);} Pinsensor = analogRead(A0); Serial.printIn(pinsensor); If(pinsensor>100){ Digital wright(7, LOW); Tone(10,60); Delay 100; No tone (10);} Else{digitalwrite(7,HIGH);} Delay(100);}
