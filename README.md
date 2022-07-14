# @jeanpaultoday - Briefgezwitscher aus der Zeit um 1800 in den Social Media von heute

Der Twitter-Account [@jeanpaultoday](https://twitter.com/jeanpaultoday) macht täglich 280 Zeichen aus den Briefen des Dichters Jean Paul im Twitterverse verfügbar. Die Tweets, bei denen es sich um die Briefanfänge an verschiedene Empfängerinnen handelt, basieren auf folgender Edition:

_Digitale Neuausgabe der Briefe von Jean Paul (in der Fassung der von Eduard Berend herausgegebenen 3. Abteilung der Historisch-kritischen Ausgabe 1952–1964). Überarbeitet von Markus Bernauer, Norbert Miller und Frederike Neuber (Hrsg.), Berlin-Brandenburgischen Akademie der Wissenschaften 2018, in: Jean Paul - Sämtliche Briefe digital, dies. (Hrsg.), 2018ff. [Link zur digitalen Edition](https://www.jeanpaul-edition.de/) | [Datensatz auf Zenodo](https://doi.org/10.5281/zenodo.4109518)_ 



**Datengrundlage**

Für die Tweets wurden die Daten der digitalen Edition mit XSLT weiterverarbeitet. Für jeden im Volltext vorliegenden Brief wurden die ersten 280 Zeichen der Briefanfänge ausgelesen. Briefe, deren Länge 280 Zeichen unterschreitet, sind folglich auch kürzere Tweets. Briefkopf und Datumszeile wurden grundsätzlich aus den Tweets ausgeschlossen. Empfängerinnen wurden als (fiktive) @Twitteraccounts den Brieftexten vorangestellt. Die so generierten 4467 Briefanfänge wurden mit Brieftitel, Quelle, Datum und Link als XML/TEI gespeichert. 

Da 4467 Briefanfänge auf ein Jahr gerechnet rund 12 Tweets pro Tag bedeuten würde, wurde die Anzahl der Tweets auf drei pro Tag beschränkt. Dazu wurde für jeden Briefanfang eine beliebige Zahl generiert (tei:item/@n), auf deren Basis pro Tag jeweils nur die drei Breifanfänge mit dem höchsten Zahlenwert ausgewählt wurden. 

**Twitterbot**

Pro Tag werden max. drei Briefanfänge um 9:00, 14.00 und 19:00 Uhr getweetet. Die Tweets selbst beinhalten den Brieftitel, den Link zur Edition und die Hashtags #briefgezwitscher #jeanpaul #jeanpaultoday

Der eigentliche Brieftext ist einer Flashcard zu entnehmen, die in der Gestaltung einem Tweet nachempfunden ist.

**Repositorium**

Folgende Dateien/Formate stellt das Repositorium zur Verfügung:

* Tweets von 15.7.2022-15.7.2023: 
  * tweets_2022.xml (Datengrundlage in XML/TEI) 
  * tweets_2022.tsv (Tweettexte für den Twitter-Bot)
  * flashcards_2022 (Tweetbilder als jpgs für den Twitter-Bot)
* Noch unpublizierte Tweets: tweets_UNPUBLISHED.xml

**Credits**

Für die Erstellung der Flashcards wurde eine Verarbeitungroutine von Torsten Roeder für den Twitter-Account [@satzomat](https://twitter.com/satzomat/) übernommen und angepasst. Die Tweets werden automatisiert vom webservice [Autochirp](https://autochirp.spinfo.uni-koeln.de/) veröffentlicht.

**Zitation und Lizenz**

Bitte zitieren Sie dieses Repositorium folgendermaßen:

Frederike Neuber: @jeanpaultoday - Briefgezwitscher aus der Zeit um 1800 in den Social Media von heute (GitHub-Repositorium), 2022, https://github.com/FrederikeNeuber/jeanpaultoday.

Für das Repositorium gilt die Lizenz CC-BY-SA 4.0.

![Erster Tweet am 15.7.2022](first-tweet.jpg)
