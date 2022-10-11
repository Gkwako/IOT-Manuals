# Manual/Handleiding
<img src="https://user-images.githubusercontent.com/90243530/195143365-0f456411-6fc3-4781-8652-05689574f92a.png" width="1000" height="300"/>

Met behulp van deze handleiding worden de stappen die je doorloopt beschreven en ook worden de eventuele denkfouten benoemt. 
Tijdens het doorlopen van de stappen, worden de volgende aspecten beschreven:
- Focus op de problemen
- Doe dit terwijl je de stappen doorloopt 
- Maak screenshots van fouten
- Geef verwijzingen naar ALLE gebruikte bronnen

Door Gloria Kwako
05-10-2022



# Inhoudsopgave
- [Vereiste-hardwarecomponenten](#Vereiste-hardwarecomponenten)
- [ToDo-Sensor](#ToDo2-sensor)
- [ToDo-Telegram](#ToDo-Telegram)




### Vereiste-hardwarecomponenten
- 1x NodeMCU basado en ESP8266MOD WiFi incorporado
- 3x Jumper Wires
- 1x RGB LEDstrip Adafruit

<img src="https://user-images.githubusercontent.com/90243530/194128475-d70fe52e-7043-434e-84ad-316df1349f98.png" width="300" height="200"/>



# ToDo-Sensor
Met behulp van deze handleiding kan je zelf een Ledstrip kleur, colorpicker in stellen met Adafruit IO. Dit is een andere library dan Fastled, er bestaan meerdere libraries (software) voor dezelfde hardware. Soms is de ene meer geschikt voor wat jij wil.

## Stap 1: Installeer de Arduino IO libraries
Om de communicatie met Adafruit IO tot stand te kunnen brengen, moeten we wat extra libraries installeren met behulp van de Arduino.

Eerst sluiten we de deck aan de computer, en dan openen we Arduino. Eenmaal in Arduino gaan we meteen naar library en daar downloaden we Adafruit IO Arduino.

<img width="671" alt="Schermafbeelding 2022-10-05 om 20 10 30" src="https://user-images.githubusercontent.com/90243530/194131594-edf9e9f7-8426-4339-81da-10aec85839dd.png">


## Stap 2: Adafruit IO Setup
Om gebruik te kunnen maken van Adafruit IO, moeten we eerst een account en een dashboard aanmaken. 

We gaan naar deze website: https://io.adafruit.com/ om een account aan te maken.

<img width="671" alt="Schermafbeelding 2022-10-05 om 20 14 26" src="https://user-images.githubusercontent.com/90243530/194132349-644235e1-d817-47bf-8d5d-3da021333b21.png">

Deze website: https://io.adafruit.com/ is niet handig om de gele sleutel te vinden, hier raad ik aan om verder te gaan op deze link:https://learn.adafruit.com/adafruit-io-basics-digital-input?view=all. Hier wordt goed beschreven hoe je de gele sleutel kan vinden.

<img width="1425" alt="Schermafbeelding 2022-10-05 om 20 31 52" src="https://user-images.githubusercontent.com/90243530/194135641-3108e37a-865e-4712-81f1-be3e29d32540.png"> <img width="692" alt="Schermafbeelding 2022-10-05 om 20 41 12" src="https://user-images.githubusercontent.com/90243530/194137327-d102ebf0-76a9-4a02-87ac-975305429b6b.png">


## Stap 3: Adafruit IO Feed en Colorpicker aanmaken
Op deze link: https://io.adafruit.com/ kan je beter verder gaan met een dashboard maken en daarin je kleuren te ontwikkelen.

<img width="1425" alt="Schermafbeelding 2022-10-05 om 20 37 56" src="https://user-images.githubusercontent.com/90243530/194136730-8e621093-5f5f-4e7a-a57b-fde309557907.png">

<img width="347" alt="Schermafbeelding 2022-10-05 om 20 42 55" src="https://user-images.githubusercontent.com/90243530/194137621-1175b650-d07f-401c-8767-ed930a5c2165.png">


## Stap 4: Code aanpassen 
Bij stap 4 is het belangrijk om de juiste gegevens in te vullen. 
- Pas: #define PIXEL_PIN 5 aan naar #define PIXEL_PIN D5
<img width="765" alt="Schermafbeelding 2022-10-05 om 20 54 26" src="https://user-images.githubusercontent.com/90243530/194143731-1ff1118e-6ef2-411a-9874-ba17dde47016.png">

- In tab ‘config.h’: voer het wifi netwerk en wachtwoord in 
- In tab ‘config.h’: plak je Adafruit IO username en Key in
<img width="765" alt="Schermafbeelding 2022-10-05 om 21 01 21" src="https://user-images.githubusercontent.com/90243530/194143740-4e90f100-eb94-45d0-b9dd-0e844bd84158.png">

## Stap 5: Code uploaden
De serial monitor moet op 115200 baud staan, om verbinding te kunnen maken. Maar het lijkt erop verbinding maken niet lukt. Dit kan liggen aan de internet verbinding. 

<img width="948" alt="Schermafbeelding 2022-10-05 om 21 20 44" src="https://user-images.githubusercontent.com/90243530/194144460-a0fa65fb-217d-4967-b1d6-02d3a838ed88.png">


# ToDo-Telegram 









