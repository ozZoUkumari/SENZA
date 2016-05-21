# SENZA
:::::Artistic Project:::::
"sense the environment and traduce into a scale of musical notation"
SENZA is a project in develpment created by ozZoUkumari (OscarOctavioSozaFigueroa)
the project works with an Arduino Board and a MIDI-shield
using enviromental sensors (ligth,temperature,humidity,air,noise)

is necesary download the followings libriries
//LIBRARIES
//Temp&humi
#include <TH02_dev.h>
#include "Arduino.h"
#include "Wire.h"  
//MIDI shield
#include <SoftwareSerial.h>
SoftwareSerial mySerial(2, 3); // RX, TX
//BLUETOOTH
#define RxD 7
#define TxD 8
#define DEBUG_ENABLED  1
SoftwareSerial blueToothSerial(RxD,TxD);

thanks for using SENZA is a free artistic project so you can development more!!!!
