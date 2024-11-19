<!--
import: https://raw.githubusercontent.com/LiaTemplates/ABCjs/0.0.2/README.md
-->

# #AdventskalendOER
Willkommen zum **OER-Adventskalender**, einer interaktiven und frei zugänglichen Adventskalender-Vorlage, die für die Nutzung mit [LiaScript](https://liascript.github.io/) entwickelt wurde. Dieser Kalender bietet die Möglichkeit, Bildungsinhalte, kreative Ideen oder themenspezifische Inhalte in 24 Kapiteln oder "Türchen" zu präsentieren.

Der OER-Adventskalender ist darauf ausgelegt, täglich neue Inhalte oder kleine Lerneinheiten freizuschalten, um Lernende oder Interessierte im Advent interaktiv zu begleiten. Dieses Projekt versteht sich als freies Bildungsmaterial (OER) und lädt ein offene und kreative Lernformate miteinander weiterzuentwickeln.

## Mitmachen



# 1. Dezember
## WeihnachtshackOER
Hier kannst du Inhalte entwickeln, neue Funktionen einbinden und deinen Ideen für alle zugänglich machen. 
Mach' mit und teile deine Hacks oder digitalen Ideen, um die Weihnachtszeit zu einem interaktiven Lern- und Kreativerlebnis zu machen. Weihnachten ist offen!

### ⏳ Weihnachtscountdown
<script format="relativetime" unit="day" locale="de">
// Datum von Weihnachten
const christmasDate = new Date('2024-12-24');
// Get the current time
const currentDate = new Date();
// Unterschied in Millisekunden berechnen
const differenceInMs = currentDate - christmasDate;

// Millisekunden in Tage umwandeln
const differenceInDays = differenceInMs / (1000 * 60 * 60 * 24);
// Umrechnen in volle Tage
const WeihnachtsCountdown = Math.floor(differenceInDays);

// Return result
-WeihnachtsCountdown
</script>
!

# 2. Dezember
## 🎶 LiedOER-Buch
Heute lernen wir ABC-Notation. 
Du kannst dir hier die entstandenen Lieder anschauen, anhören, verändern, erweitern und selbst weitere Notensätze entwickeln und damit unser "Liederbuch" ergänzen und wachsen lassen

Ergänze einfach hier und stelle einen Pull-Request, dann werden deine Ideen in den AdventskalendOER aufgenommen.

Weitere Lieder mit `### Neues Lied`und dann die Notation, wie untenstehend.
Zu ABC-Notation gibt's auch noch tolle Tutorials, was alles möglich ist, z.B.:

- [Videoguides (englisch) von Chris Walshaw auf YouTube](https://abcnotation.com/videos#start)
- [Ein deutschsprachiges Tutorial von Svent Walper - Teil1](http://penzeng.de/Geige/Abc.htm) und [Teil2](http://penzeng.de/Geige/Abc2.htm)
- [Ein einfacher "ABC notation converter" zum Ausprobieren](https://notabc.app/abc-converter/)
- [NotaABC eine App für iOS (iPhone, iPad)](https://notabc.app/)
- [Jede Menge Songdatenbanken in einer Sammlung](https://abcnotation.com/tunes)




### Ich steh an deiner Krippen hier
Weiteres

``` abc  @ABCJS.render
X:150
T:Ich steh an deiner Krippen hier
T:BWV 469
C:Johann Sebastian Bach
O:Deutschland
Z:Notation CC0 Comenius-Institut
V:1 Program 1 68 %Oboe
V:2 Program 1 70 bass %Bassoon
M:4/4
L:1/8
Q:1/4=94
K:Gm
V:1 clef=treble
|: G2|c2d2 e2c2|B3_A G2B2|E3D E2F2|G4 G2:|
w:Ich steh an dei-ner Krip-pen hier, o Je-su-lein, mein Le-ben.
w:Ich kom-me, bring und schen-ke dir, was du mir hast ge- ge-ben.
V:2 clef=bass
|: C,D,|E,D,C,=B,, C,D,E,C,|D,B,, C,D,E,2 E,D,|C,G,CB, _A,G,A,2|G,4 G,,2:|
V:1 
B2|e2B2 c2B2|_A3B G2B2|e2B2 c2B2|
w:Nimm hin, es ist mein Geist und Sinn, Herz, Seel und Mut, nimm
_A3B G2G2|A2=B2 cedc|=B4 c2|]
w:al-les hin und la\ss dir's wohl_ ge--fal-len
V:2
G,F,|E,F,G,E, _A,3G,|F,E,D,B,, E,2E,D,|C,D,E,D, E,F,G,E,|
F,2B,,2 E,2C,2|F,E,F,D, E,2F,2|G,2 G,,2 C,2|]

```



# über


## Lizenz
Dieser AdventskalendOER steht als Open Educational Resource (OER) unter der Lizenz: <a target="_blank" rel="noopener noreferrer" href="https://creativecommons.org/publicdomain/zero/1.0/deed.de">CC0 1.0 <img src="https://mirrors.creativecommons.org/presskit/icons/cc.svg" style="height: 1em; margin-right: 0.125em; display: inline;"><img src="https://mirrors.creativecommons.org/presskit/icons/zero.svg" style="height: 1em; margin-right: 0.125em; display: inline;"></a>