E-course "3D modelling" logs' data
------------------------------

Olga Ovtsarenko

doctoral student of Vilnius Tech, 
Vilnius, Lithuania


------------------------------
Background 
------------------------------

E-course "3D modelling" usage data (free choice of students) for the period 29.01-15.04.2024.
The popularity of the "3D modeling course" in the AutoCAD program is high since AutoCAD is a very common Autodesk product.

------------------------------
Dataset
------------------------------
Data were extracted from the Moodle educational platform of the TTK University of Applied Sciences, Tallinn, Estonia,
after the completion of the academic work of the spring semester of 2024, 
and student assessment results were added from the Tahvel platform of the Estonian Ministry of Education.

------------------------------
Goal
------------------------------
The goal is to use data to explore the behavior, priorities, 
and perhaps challenges of a specific group of students when using educational materials.

------------------------------
Preparation
------------------------------

  To prepare the data: 
     - the names of students were replaced with registration codes on the Moodle platform, 
     - the names of the resources used were replaced with registration codes in the e-course repository, 
     - data on personal IP addresses and system data that could not be used were removed,
     - added data on the number of clicks, 
     - time of use of resources during the lesson, 
     - time of day.

------------------------------
Files
------------------------------

- Readme.txt
- logs.csv : 18 students logs data aggregated on logs count basis. Records: 6096 logs

------------------------------
Dataset characteristics
------------------------------	

Data have the following fields
	
	- time : recording the date and time of resource use
	- usid : user ID 
	- tid : tool ID
        - log : tool use by click 
	- les : lessons - if lesson time is the same as tool use - 1, otherwise is 0.
	- day_period : 4 hours day period
		- 1: 8 am - 12 am
		- 2: 12 am - 4 pm
		- 3: 4 pm - 8 pm
		- 4: 8 pm - 12 pm
		- 5: 12 pm - 4 am
		- 0: 4 am - 8 am

------------------------------
Tools codes
------------------------------

        - 2949: (1429)
        - 244208: (452)
        - 233217: Fail: Tutvustus (9)
        - 233140: Veebileht: AutoCAD install (21)
        - 233179: H5P (sisupank): AutoCAD ülevaade (8)
        - 233213: H5P (sisupank): 2D-Joonestamise ja muutmise käsud (61)
        - 233214: H5P (sisupank): Modelleerimise käsud (54)
        - 233215: H5P (sisupank): Muutmise käsud (42)
	- 233212: H5P (sisupank): AutoCAD 3D ülevaade (98)
        - 233186: H5P (sisupank): 1.kodutöö (14)
        - 233187: Ülesanne: 1.kodutöö - kontroll (31)
        - 233226: H5P (sisupank): Koostu detailid (81)
        - 233220: H5P (sisupank): 1.kodutöö - harjutused lihtsamate mudelitega (328)
	- 233223: H5P (sisupank): H5P (sisupank): Harjutused detailidega (158)
        - 233224: Fail: Puks (7)
	- 233150: Foorum: Teated õppijatele / News Forum (40)
        - 256945: Foorum: Koostu detailid (209)
	- 233242: H5P (sisupank): 3.kodutöö (259)
        - 233219: H5P: TTK meene modelleerimine (32)
        - 233238: H5P (sisupank): Treppidest (55)
        - 233239: H5P (sisupank): Trepi mudel (168)
        - 257734: Fail: Trepi abijooned (24)
        - 233146: Lipik: RKE-138/32 AINEKAVA (66)
        - 233262: Fail: Insenerigraafika (19)
        - 233235: H5P (sisupank): Mööbli ese - pink (134)
        - 233246: H5P (sisupank): Mööbli spetsifikatsioon (89)
        - 233257: H5P (sisupank): 2.kontrolltöö - 10v (45)


------------------------------
Contact
------------------------------
	
For further information about this dataset please contact Olga Ovtsarenko (olga.ovtsarenko@vilniustech.lt
