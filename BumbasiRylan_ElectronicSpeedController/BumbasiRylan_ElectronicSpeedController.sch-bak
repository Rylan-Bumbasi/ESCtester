EESchema Schematic File Version 4
EELAYER 30 0
EELAYER END
$Descr A 11000 8500
encoding utf-8
Sheet 1 1
Title "ElectronicSpeedController"
Date "2021-08-30"
Rev "A"
Comp "SDSU Mechatronics"
Comment1 "Author: Rylan Bumbasi"
Comment2 ""
Comment3 ""
Comment4 ""
$EndDescr
$Comp
L MCU_Module:Arduino_Nano_v3.x ArduinoNano1
U 1 1 61465412
P 4850 3950
F 0 "ArduinoNano1" H 5250 2900 50  0000 C CNN
F 1 "Arduino_Nano_v3.x" H 5300 2800 50  0000 C CNN
F 2 "Module:Arduino_Nano" H 4850 3950 50  0001 C CIN
F 3 "http://www.mouser.com/pdfdocs/Gravitech_Arduino_Nano3_0.pdf" H 4850 3950 50  0001 C CNN
	1    4850 3950
	1    0    0    -1  
$EndComp
$Comp
L Device:R_US R1
U 1 1 6146C2A7
P 2700 3100
F 0 "R1" V 2495 3100 50  0000 C CNN
F 1 "200 Ω" V 2586 3100 50  0000 C CNN
F 2 "Resistor_THT:R_Axial_DIN0207_L6.3mm_D2.5mm_P10.16mm_Horizontal" V 2740 3090 50  0001 C CNN
F 3 "~" H 2700 3100 50  0001 C CNN
	1    2700 3100
	0    1    1    0   
$EndComp
$Comp
L Device:R_US R2
U 1 1 6146C6A8
P 2700 3500
F 0 "R2" V 2495 3500 50  0000 C CNN
F 1 "200 Ω" V 2586 3500 50  0000 C CNN
F 2 "Resistor_THT:R_Axial_DIN0207_L6.3mm_D2.5mm_P10.16mm_Horizontal" V 2740 3490 50  0001 C CNN
F 3 "~" H 2700 3500 50  0001 C CNN
	1    2700 3500
	0    1    1    0   
$EndComp
$Comp
L Device:R_US R3
U 1 1 6146C91C
P 2700 3900
F 0 "R3" V 2495 3900 50  0000 C CNN
F 1 "200 Ω" V 2586 3900 50  0000 C CNN
F 2 "Resistor_THT:R_Axial_DIN0207_L6.3mm_D2.5mm_P10.16mm_Horizontal" V 2740 3890 50  0001 C CNN
F 3 "~" H 2700 3900 50  0001 C CNN
	1    2700 3900
	0    1    1    0   
$EndComp
$Comp
L Device:LED LED3
U 1 1 6146FC01
P 1850 3900
F 0 "LED3" H 1843 4117 50  0000 C CNN
F 1 "RED" H 1843 4026 50  0000 C CNN
F 2 "LED_THT:LED_D5.0mm" H 1850 3900 50  0001 C CNN
F 3 "~" H 1850 3900 50  0001 C CNN
	1    1850 3900
	1    0    0    -1  
$EndComp
$Comp
L Device:LED LED2
U 1 1 61470569
P 1850 3500
F 0 "LED2" H 1843 3717 50  0000 C CNN
F 1 "YELLOW" H 1843 3626 50  0000 C CNN
F 2 "LED_THT:LED_D5.0mm" H 1850 3500 50  0001 C CNN
F 3 "~" H 1850 3500 50  0001 C CNN
	1    1850 3500
	1    0    0    -1  
$EndComp
$Comp
L Device:LED LED1
U 1 1 61470B32
P 1850 3100
F 0 "LED1" H 1843 3317 50  0000 C CNN
F 1 "GREEN" H 1843 3226 50  0000 C CNN
F 2 "LED_THT:LED_D5.0mm" H 1850 3100 50  0001 C CNN
F 3 "~" H 1850 3100 50  0001 C CNN
	1    1850 3100
	1    0    0    -1  
$EndComp
$Comp
L power:GND #PWR0101
U 1 1 61472108
P 1200 4150
F 0 "#PWR0101" H 1200 3900 50  0001 C CNN
F 1 "GND" H 1205 3977 50  0000 C CNN
F 2 "" H 1200 4150 50  0001 C CNN
F 3 "" H 1200 4150 50  0001 C CNN
	1    1200 4150
	1    0    0    -1  
$EndComp
$Comp
L Device:R_POT POT1
U 1 1 61474182
P 6750 3550
F 0 "POT1" H 6680 3504 50  0000 R CNN
F 1 "100 Ω" H 6680 3595 50  0000 R CNN
F 2 "Potentiometer_THT:Potentiometer_Alps_RK09Y11_Single_Horizontal" H 6750 3550 50  0001 C CNN
F 3 "~" H 6750 3550 50  0001 C CNN
	1    6750 3550
	-1   0    0    1   
$EndComp
$Comp
L Motor:Motor_Servo ESC1
U 1 1 61476AB9
P 2250 4650
F 0 "ESC1" H 2244 4343 50  0000 C CNN
F 1 "Basic ESC" H 2244 4434 50  0000 C CNN
F 2 "Connector_PinHeader_2.54mm:PinHeader_1x03_P2.54mm_Vertical" H 2250 4460 50  0001 C CNN
F 3 "http://forums.parallax.com/uploads/attachments/46831/74481.png" H 2250 4460 50  0001 C CNN
	1    2250 4650
	-1   0    0    1   
$EndComp
Wire Wire Line
	1700 3500 1200 3500
Wire Wire Line
	1200 3500 1200 3900
Wire Wire Line
	1700 3900 1200 3900
Connection ~ 1200 3900
Wire Wire Line
	1200 3900 1200 4100
Wire Wire Line
	1700 3100 1200 3100
Wire Wire Line
	1200 3100 1200 3500
Connection ~ 1200 3500
Wire Wire Line
	2000 3100 2550 3100
Wire Wire Line
	2000 3500 2550 3500
Wire Wire Line
	2000 3900 2550 3900
Wire Wire Line
	2850 3100 3750 3100
Wire Wire Line
	3750 3100 3750 3550
Wire Wire Line
	3750 3550 4350 3550
Wire Wire Line
	2850 3500 3500 3500
Wire Wire Line
	3500 3500 3500 3650
Wire Wire Line
	3500 3650 4350 3650
Wire Wire Line
	2850 3900 3450 3900
Wire Wire Line
	3450 3900 3450 3750
Wire Wire Line
	3450 3750 4350 3750
Wire Wire Line
	5350 3950 6200 3950
Wire Wire Line
	6200 3950 6200 3550
Wire Wire Line
	6200 3550 6600 3550
Wire Wire Line
	5050 2700 5050 2950
$Comp
L power:GND #PWR0102
U 1 1 61480FFA
P 6750 3300
F 0 "#PWR0102" H 6750 3050 50  0001 C CNN
F 1 "GND" H 6755 3127 50  0000 C CNN
F 2 "" H 6750 3300 50  0001 C CNN
F 3 "" H 6750 3300 50  0001 C CNN
	1    6750 3300
	-1   0    0    1   
$EndComp
Wire Wire Line
	2550 4750 3950 4750
Wire Wire Line
	3950 4750 3950 4350
Wire Wire Line
	3950 4350 4350 4350
Wire Wire Line
	2550 4550 2550 4100
Wire Wire Line
	2550 4100 1200 4100
Connection ~ 1200 4100
Wire Wire Line
	1200 4100 1200 4150
NoConn ~ 5350 4650
NoConn ~ 5350 4550
NoConn ~ 5350 4450
NoConn ~ 5350 4350
NoConn ~ 5350 4250
NoConn ~ 5350 4150
NoConn ~ 5350 4050
NoConn ~ 5350 3750
NoConn ~ 5350 3450
NoConn ~ 5350 3350
NoConn ~ 4950 2950
NoConn ~ 4750 2950
NoConn ~ 4350 3350
NoConn ~ 4350 3450
NoConn ~ 4350 3850
NoConn ~ 4350 3950
NoConn ~ 4350 4050
NoConn ~ 4350 4150
NoConn ~ 4350 4250
NoConn ~ 4350 4450
NoConn ~ 4350 4550
NoConn ~ 4350 4650
$Comp
L power:GND #PWR0104
U 1 1 614994AC
P 4900 5050
F 0 "#PWR0104" H 4900 4800 50  0001 C CNN
F 1 "GND" H 4905 4877 50  0000 C CNN
F 2 "" H 4900 5050 50  0001 C CNN
F 3 "" H 4900 5050 50  0001 C CNN
	1    4900 5050
	1    0    0    -1  
$EndComp
Wire Wire Line
	4850 4950 4850 5050
Wire Wire Line
	4850 5050 4900 5050
Wire Wire Line
	4950 4950 4950 5050
Wire Wire Line
	4950 5050 4900 5050
Connection ~ 4900 5050
$Comp
L BumbasiRylan_ElectronicSpeedController-rescue:power_PWR_FLAG-FeatherWing_KC5-cache #FLG0101
U 1 1 6149B2CC
P 3650 5650
F 0 "#FLG0101" H 3650 5725 50  0001 C CNN
F 1 "power_PWR_FLAG" H 3650 5823 50  0000 C CNN
F 2 "" H 3650 5650 50  0001 C CNN
F 3 "" H 3650 5650 50  0001 C CNN
	1    3650 5650
	1    0    0    -1  
$EndComp
$Comp
L power:GND #PWR0105
U 1 1 6149BB3A
P 3650 5750
F 0 "#PWR0105" H 3650 5500 50  0001 C CNN
F 1 "GND" H 3655 5577 50  0000 C CNN
F 2 "" H 3650 5750 50  0001 C CNN
F 3 "" H 3650 5750 50  0001 C CNN
	1    3650 5750
	1    0    0    -1  
$EndComp
Wire Wire Line
	3650 5650 3650 5750
NoConn ~ 2550 4650
Text Label 5850 3950 0    50   ~ 0
A0
Text Label 7350 2700 0    50   ~ 0
5V
Text Label 1200 4150 0    50   ~ 0
GROUND
Text Label 4100 3550 0    50   ~ 0
D2
Text Label 4100 3650 0    50   ~ 0
D3
Text Label 4100 3750 0    50   ~ 0
D4
Text Label 3750 4750 0    50   ~ 0
D10(PWM)
Wire Wire Line
	7350 2700 7350 3950
Wire Wire Line
	7350 3950 6750 3950
Wire Wire Line
	6750 3950 6750 3700
Wire Wire Line
	5050 2700 7350 2700
Wire Wire Line
	6750 3400 6750 3300
$Comp
L Mechanical:MountingHole_Pad H1
U 1 1 6149BD6D
P 9000 1900
F 0 "H1" V 8954 2050 50  0000 L CNN
F 1 "MountingHole_Pad" V 9045 2050 50  0000 L CNN
F 2 "MountingHole:MountingHole_3mm_Pad_Via" H 9000 1900 50  0001 C CNN
F 3 "~" H 9000 1900 50  0001 C CNN
	1    9000 1900
	0    1    1    0   
$EndComp
$Comp
L Mechanical:MountingHole_Pad H2
U 1 1 6149C7A0
P 9000 2200
F 0 "H2" V 8954 2350 50  0000 L CNN
F 1 "MountingHole_Pad" V 9045 2350 50  0000 L CNN
F 2 "MountingHole:MountingHole_3mm_Pad_Via" H 9000 2200 50  0001 C CNN
F 3 "~" H 9000 2200 50  0001 C CNN
	1    9000 2200
	0    1    1    0   
$EndComp
$Comp
L Mechanical:MountingHole_Pad H3
U 1 1 6149D0A2
P 9000 2500
F 0 "H3" V 8954 2650 50  0000 L CNN
F 1 "MountingHole_Pad" V 9045 2650 50  0000 L CNN
F 2 "MountingHole:MountingHole_3mm_Pad_Via" H 9000 2500 50  0001 C CNN
F 3 "~" H 9000 2500 50  0001 C CNN
	1    9000 2500
	0    1    1    0   
$EndComp
$Comp
L Mechanical:MountingHole_Pad H4
U 1 1 6149D8FB
P 9000 2800
F 0 "H4" V 8954 2950 50  0000 L CNN
F 1 "MountingHole_Pad" V 9045 2950 50  0000 L CNN
F 2 "MountingHole:MountingHole_3mm_Pad_Via" H 9000 2800 50  0001 C CNN
F 3 "~" H 9000 2800 50  0001 C CNN
	1    9000 2800
	0    1    1    0   
$EndComp
Wire Wire Line
	8900 1900 8900 2200
Connection ~ 8900 2200
Wire Wire Line
	8900 2200 8900 2500
Connection ~ 8900 2500
Wire Wire Line
	8900 2500 8900 2800
Connection ~ 8900 2800
Wire Wire Line
	8900 2800 8900 3000
$Comp
L power:GND #PWR01
U 1 1 6149ED97
P 8900 3000
F 0 "#PWR01" H 8900 2750 50  0001 C CNN
F 1 "GND" H 8905 2827 50  0000 C CNN
F 2 "" H 8900 3000 50  0001 C CNN
F 3 "" H 8900 3000 50  0001 C CNN
	1    8900 3000
	1    0    0    -1  
$EndComp
$EndSCHEMATC
