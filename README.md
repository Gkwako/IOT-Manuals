# ToDo2-sensor
Door Gloria Kwako
05-10-2022

## Introductie
Met behulp van deze handleiding kan je zelf een Ledstrip kleur, colorpicker in stellen met Adafruit IO. Dit is een andere library dan Fastled, er bestaan meerdere libraries (software) voor dezelfde hardware. Soms is de ene meer geschikt voor wat jij wil.

In deze handleiding worden de stappen die je doorloopt beschreven en ook de denkfouten. Tijdens het doorlopen van de stappen, worden de volgende aspecten beschreven:
- Focus op de problemen (daar leer je van 😊) 
- Doe dit terwijl je de stappen doorloopt 
- Maak screenshots van fouten
- Geef verwijzingen naar ALLE gebruikte bronnen

## Vereiste hardwarecomponenten
- 1x NodeMCU basado en ESP8266MOD WiFi incorporado
- 3x Jumper Wires
- 1x RGB LEDstrip Adafruit

![deck](https://user-images.githubusercontent.com/90243530/194128475-d70fe52e-7043-434e-84ad-316df1349f98.png)

## Stap 1: Installeer de Arduino IO libraries
Om de communicatie met Adafruit IO tot stand te kunnen brengen, moeten we wat extra libraries installeren met behulp van de Arduino.

Eerst sluiten we de deck aan de computer, en dan openen we Arduino. Eenmaal in Arduino gaan we meteen naar library en daar downloaden we Adafruit IO Arduino.

<img width="671" alt="Schermafbeelding 2022-10-05 om 20 10 30" src="https://user-images.githubusercontent.com/90243530/194131594-edf9e9f7-8426-4339-81da-10aec85839dd.png">
