# @JeanPaulToday - Briefkultur aus der Zeit um 1800 in den Social Media von heute

Der Mastdon-Account [@JeanPaulToday](https://fedihum.org/JeanPaulToday) macht seit Juni 2024 täglich 280 Zeichen aus den Briefen des Dichters Jean Paul auf den Tag genau in der Mastodon-Instanz [@fedihum.org](https://fedihum.org/) des DHd-Verbandes verfügbar. 2022-2023 erschienen die Posts in ähnlicher Form über den Twitter-Account [@jeanpaultoday](https://twitter.com/jeanpaultoday).
Die Posts, bei denen es sich um die Briefanfänge an verschiedene Empfängerinnen handelt, basieren auf folgender Edition:

_Digitale Neuausgabe der Briefe von Jean Paul (in der Fassung der von Eduard Berend herausgegebenen 3. Abteilung der Historisch-kritischen Ausgabe 1952–1964). Überarbeitet von Markus Bernauer, Norbert Miller und Frederike Neuber (Hrsg.), Berlin-Brandenburgischen Akademie der Wissenschaften 2018, in: Jean Paul - Sämtliche Briefe digital, dies. (Hrsg.), 2018ff. [Link zur digitalen Edition](https://www.jeanpaul-edition.de/) | [Datensatz auf Zenodo](https://doi.org/10.5281/zenodo.4109518)_ 


**Jean Pauls Weg auf Twitter**

Für die Tweets wurden die Daten der digitalen Edition mit XSLT transformiert. Für jeden im Volltext vorliegenden Brief wurde in bis zu 280 Zeichen des Briefanfangs sowie der/die Empfänger/in der Briefe als (fiktiver) Social-Media-Account ausgelesen. Briefkopf und Datumszeile wurden ausgeschlossen, sehr kurze Briefe ergeben ggf. Tweets unter 280 Zeichen. Die so generierten 4467 Briefanfänge wurden mit Brieftitel, Quelle, Datum und Link als XML/TEI gespeichert. Auf Basis einer zufälligen Auswahl (mittels Zahlenwerten) werden 365 bzw. 366 Posts für die Publikation bestimmt, d. h. es erscheint auf Mastodon ein Post pro Tag (ehemals drei Tweets pro Tag auf Twitter), jeweils um 9:00 Uhr.

Der Text eines Posts beinhaltet den Brieftitel, den Link zur Edition und die Hashtags #OnThisDay #JeanPaulEdition #JeanPaulToday. Der eigentliche Brieftext ist einer Flashcard zu entnehmen, deren Gestaltung einem echten Mastodon-Post (ehemals Tweet) nachempfunden ist. Der Alt-Text des Bildes ist der Brieftext.

**Hintergrund**

Die Briefkultur um 1800 und die Social Media von heute weisen einige Kontinuitäten auf, die auf einer Tagung 2021 an der Berlin-Brandenburgischen Akademie der Wissenschaften sowie in dem dazu erschienenen Tagungsband [„Soziales Medium Brief. Sharen, Liken, Retweeten im 18. und 19. Jahrhundert“](https://www.herder.de/wissen/shop/p8/86909-soziales-medium-brief-gebundene-ausgabe/) diskutiert wurden. Die Idee des Bots ist, die ‚Social-Media-haftigkeit‘ des Jean Paul‘schen Korrespondenznetzwerks nicht nur theoretisch zu diskutieren, sondern die epistolare Kommunikation in die Social Media von heute zu befördern. 

**Credits**

Für die Erstellung der Flashcards wurde eine Verarbeitungroutine von Torsten Roeder für den Twitter-Account [@satzomat](https://twitter.com/satzomat/) übernommen und angepasst. Die Tweets werden auf Mastodon automatisiert vom webservice [autodone](https://autodone.idh.uni-koeln.de/) veröffentlicht, für Twitter wurde [Autochirp](https://autochirp.spinfo.uni-koeln.de/) verwendet.

**Repositorium**

Folgende Dateien/Formate stellt das Repositorium zur Verfügung:

```
mastodon_2024 (Mastodone-Posts von 18.6.2024-18.6.2025)
    ├── posts_sources_2024-2025.xml (Datengrundlage in XML/TEI) 
    ├── posts_autodone_2024-2025_100.tsv, etc. (Texte für den Mastodon-Bot)
    ├── posts_UNPUBLISHED.xml (ausgeschlossene Posts)
    └── flashcards (Flashcards als jpgs für den Bot)
twitter_2022 (Tweets von 15.7.2022-15.7.2023)
    ├── tweets_sources_2022-2023.xml (Datengrundlage in XML/TEI) 
    ├── tweets_autochirp_2022-2023.tsv (Tweettexte für den Twitter-Bot)
    ├── tweets_UNPUBLISHED.xml (ausgeschlossene Tweets)
    └── flashcards (Tweetbilder als jpgs für den Twitter-Bot)

```

**Zitation und Lizenz**

Bitte zitieren Sie dieses Repositorium folgendermaßen:

**Frederike Neuber: jeanpaultoday (GitHub-Repositorium), 2022-2025, https://github.com/FrederikeNeuber/jeanpaultoday.**

Für das Repositorium gilt die Lizenz CC-BY-SA 4.0.






