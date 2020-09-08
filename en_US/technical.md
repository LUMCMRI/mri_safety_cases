
# Technische achtergrond

## Veldsterkte en frequentie

Een overzicht van de verschillende gyromagnetische ratio's kun je
[hier](https://en.wikipedia.org/wiki/Gyromagnetic_ratio) vinden. Voor protonen
geldt dat de gyromagnetische ratio gelijk is aan 42.576 MHz/T. Hiermee komt de frequentie van 
een 1.5T scanner op ongeveer 64 MHz uit, een 3T scanner op 128 MHz en een 7T scanner op 298 MHz.
<br>
<br>

## Golflengtes (in vacuum)

| Type of wave     | Typical frequency [Hz]  | Typical wavelength |
|------------------|-------------------------|--------------------|
| Radio            | \\(~10^8\\) (100 MHz)   | ~3 m               |
| Microwave        | \\(~10^{10}\\) (10 GHz) | ~3 cm              |
| Infrared         | \\(~3 \times 10^{13}\\) | ~10 \\(\mu\\)m     |
| Ultraviolet      | \\(~3 \times 10^{16}\\) | ~10 nm             |
| X-ray            | \\(~3 \times 10^{18}\\) | ~0.1 nm            |
| \\(\gamma\\)-ray | \\(~3 \times 10^{20}\\) | ~1 pm              |

Maximale energie-overdracht, en daarmee de kans op temperatuurstijging, vindt 
plaats in objecten met een lengte = golflengte/2.<br>
**Let op:** In weefsel is de golflengte korter vanwege dielectrische effecten.
Met bijvoorbeeld de [Tissue property calculator](http://niremf.ifac.cnr.it/tissprop/htmlclie/htmlclie.php) kun je
een idee krijgen van de golflengte in weefsels bij verschillende veldsterktes.
<br>
<br>

## SAR

SAR staat voor Specific Absorption Rate en geeft een indicatie van mogelijke
opwarming van de persoon in de scanner. SAR wordt uitgedrukt in W/kg. 

Volgens IEC60601-2-33 ed. 3 (2015-06) is de SAR gelimiteerd als volgt:

| Averaging time          | 6 minutes      |
|-------------------------|----------------|------------------|----------|
| Body region             | Whole body SAR | Partial body SAR | Head SAR |
| Operating mode          | (W/kg)         | (W/kg)           | (W/kg)   |
| NORMAL                  | 2              | 2-10             | 3.2      |
| FIRST LEVEL CONTROLLED  | 4              | 4-10             | 3.2      |
| SECOND LEVEL CONTROLLED | >4             | >(4-10)          | >3.2     |
<br>
<br>

## Temperatuurlimieten

Volgens IEC60601-2-33 ed. 3 (2015-06) moet MRI-apparatuur de opwarming van de patiënt beperken tot de volgende waarden:

| Operating mode          | Maximum CORE TEMPERATURE (°C) | Maximum Local tissue temperature (°C) | Rise of CORE TEMPERATURE (°C) |
| ----------------------- | ------------------------- | --------------------------------- | ------------------------    |
| NORMAL                  | 39                        | 39                                | 0.5                         |
| FIRST LEVEL CONTROLLED  | 40                        | 40                                | 1                           |
| SECOND LEVEL CONTROLLED | >40                       | >40                               | >1                          |
<br>
<br>

## Spatiële gradient

In de eisen aan een implantaat wordt vaak ook een maximale spatiële gradient
genoemd. Het gaat hier dan *niet* om het schakelen van de gradiënten van de
scanner maar om het verloop van het \\(B_0\\)-veld in de ruimte, de zogeheten \\( \Delta B_0 \\).
Van elke scanner is een plot beschikbaar met het verloop van dit hoofd-magnetisch veld. De kracht
die op een implantaat werkt is ruwweg proportioneel met \\( B_0 \times \Delta B_0 \\).
De spatiële gradient wordt uitgedrukt in de eenheid T/m, maar Gauss/cm wordt ook wel gebruikt.
Voor het omrekenen geldt dat 100 G/cm gelijk is aan 1 T/m.

![Horizontaal aanzicht](extra_materiaal/1_5_Ing_SpatGradHorz.png) 
![Verticaal aanzicht](extra_materiaal/1_5_Ing_SpatGradVert.png)  
Horizontaal en verticaal aanzicht van de spatiële gradient in het hoofd-magnetisch veld van een Philips Ingenia CX 1.5 Tesla MRI-scanner.

![Horizontaal aanzicht](extra_materiaal/3_0_Ing_SpatGradHorz.png) 
![Verticaal aanzicht](extra_materiaal/3_0_Ing_SpatGradVert.png)  
Horizontaal en verticaal aanzicht van de spatiële gradient in het hoofd-magnetisch veld van een Philips Ingenia CX 3.0 Tesla MRI-scanner.


