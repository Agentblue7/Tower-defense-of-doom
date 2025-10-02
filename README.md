Sprint 0 - Game Design Document : Tower Defense


Naam: Joey
Klas: Sd2a
Datum: 15/09/2025

Titel: Tower Defense of doom
Elevator Pitch: Het is een super normale Tower Defense maar als de waves doorgaan word het steeds meer chaotischer en dat beinvloed de game.

3. Schets van je level en UI
<img width="1152" height="720" alt="Level 1" src="https://github.com/user-attachments/assets/6dfa8452-6456-42cc-b498-160c2c4d8b89" />

4. Torens
Toren 1
naam: sniper
range:10-15,
damage: 20,
unieke eigenschap.

Toren 2 
naam: beserker
bereik 0-5
schade: 30 
unieke eigenschap.

Eventuele extra torens:



5. Vijanden
Vijand 1
naam: tank
snelheid: slow
levens:25
speciale eigenschap: Schiet terug om torens te disabelen.

Vijand 2 
naam: Sprinter
snelheid: super fast 
levens: 5 
speciale eigenschap: is snel.

Eventuele extra vijanden:



6. Gameplay loop

  1. koop torens
  2. versla vijanden
  3. krijg meer geld

7. Progressie
elke wave komen er moeilijkere enemys met meer health en damage waardan uiteindelijk de boss komt.



9. Risico’s en oplossingen volgens PIO
Probleem 1: kogels van de tower doet geen damage

Impact: groot

Oplossing: hitboxes checken en eventueel fixen

Probleem 2: Je kan towers kopen al heb je niet genoeg geld

Impact: groot

Oplossing: Ik check de code voor fouten of herschrijf ze

Probleem 3: Ui misaligned

Impact: klein

Oplossing: ik probeer het te fixen

9. Planning per sprint en mechanics
Schrijf per sprint welke mechanics jij oplevert in de build. Denk aan voorbeelden zoals vijandbeweging over een pad, torens plaatsen, doel kiezen en schieten, waves starten, UI voor geld en levens, upgrades, jouw unieke feature.

Sprint 1 mechanics: Towers schieten

Sprint 2 mechanics: Towers kopen

Sprint 3 mechanics: enemy's 

Sprint 4 mechanics: wave system

Sprint 5 mechanics: ui en main menu



10. Inspiratie
ik heb niet echt een inspiratie persee maar ik vind bloons td systeem heel erg leuk



11. Technisch ontwerp mini
Lees dit korte voorbeeld en vul daarna jouw eigen keuzes in.

Voorbeeld ingevuld bij 11.1 Vijandbeweging over het pad

Keuze: Vijanden volgen punten A, B, C en daarna de goal.
Risico: Een vijand loopt een punt voorbij of blijft hangen.
Oplossing: Als de vijand dichtbij genoeg is kiest hij het volgende punt. Bij de goal gaat één leven omlaag en verdwijnt de vijand.
Acceptatie: Tien vijanden lopen van start naar de goal zonder vastlopers en verbruiken elk één leven. Alle tien vijanden bereiken achtereenvolgens elk waypoint binnen één seconde na elkaar.

11.2 Doel kiezen en schieten
Keuze: Torens schieten de eerste enemy die in range komt en houden dat totdat de enemy uit de range loopt of dood is.
Risico: De torens gaan na de eerste enemy niet verder met een andere schieten
Oplossing: alle torens moeten alle enemys in range schieten maar moeten de gene die ze schieten vasthouden
Acceptatie: de torens schieten en volgen de enemy zonder te blijven haken aan de verkeerde.

11.3 Waves en spawnen
Keuze: Nadat de alle set enemy's dood zijn gaat na een hoeveelheid tijd een andere wave beginnen met een hoeveelheid sterkere enemy's
Risico: Het gaat niet verder naar een andere wave
Oplossing: ik zet een ultieme timer voordat de volgende wave begint
Acceptatie: Als een wave eindigt krijg je genoeg tijd om torens te kopen voordat de volgende wave begint.

11.4 Economie en levens
Keuze: elke enemy doet een hoeveelheid damage en geeft een hoeveelheid geld
Risico: Enemy's doen geen damage
Oplossing: ik maak dat al de hitboxes
Acceptatie: als ik enemy's dood maak krijg ik geld voor torens en als dat mij niet lukt krijg ik damage

11.5 UI basis
Keuze: Ik heb UI design voor: waves, money, towers, health and an main menu.
Risico: ik ben ass in UI
Oplossing: ik word goed in UI
Acceptatie: ik heb een UI
