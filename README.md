# Rose Moderator

Man kann Rose einfach in die Gruppe einladen wie einen normalen Nutzer und dann über Chatbefehle (alles, was mit `/` anfängt zählt i.d.R. als Kommando / Befehl) konfigurieren. Es gibt aber auch eine etwas elegantere Methode, damit keiner  sieht, was du mit dem Bot machst etc:

## User-ID herausfinden

Auch wenn wir Namen sehen kennt Telegram eigentlich nur IDs für User. Wenn du die ID eines Users herausfinden willst schreib einfach `/id <@username>` in den Chat. Das hat erstmal ncihts mit Rose zu tun:

```
/id @day420day
```

**User haben immer positive, 8 stellige IDs.**
## Gruppen-ID herausfinden

Tippe `/id` in den Gruppenchat, zu dem du Rose einladen willst. Gruppen haben immer negative 8 stellige Zahlen als IDs. Solltest du eine positive Zahl bekommen ist das eine User-ID und damit falsch.

```
/id

```

Als Beispiel nehmen wir ID -12345678 und ziehen das Ganze exemplarisch durch.

## Rose "anwerben"

Mit der Gruppen-ID können wir Rose (den tatsächlichen Telegram Nutzer des Bots) anchatten und anweisen sich mit unserer Gruppe zu verbinden.

```
/connect -12345678

```

**Ab diesem Moment ist dein privater Chat mit Rose quasi deine Administrator-Oberfläche!**

## Private Chat mit Rose statt Gruppenchat

Sobald Rose in der Gruppe ist, kannst du zu jedem Zeitpunkt mit `/connect` deinen Chat mit ihr wieder aufmachen. Hier wirst du die meisten Befehle absetzen.

Wenn du Rose aus der Gruppe loswerden willst, machst du das mit `/disconnect`, um sie wieder zu holen `/reconnect`. Infos über den momentanen Zustand von Rose gibt es mit `/connection`.


```
```


## Sprache ändern

`/setlang de` stellt auf deutsche Sprache. `/setlang en` stellt wieder auf englisch.

## Interaktion mit Usern

### Kick (rauswerfen)

**Ein gekickter User kann immer wiederkommen!**

Um einen User zu kicken gibt es 2 Möglichkeiten:

```
/kick <@username or UserID>
```
### Mute (stumm schalten)
### Ban (verbannen)

