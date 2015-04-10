# Anleitung #

## Voraussetzungen ##

  * Contao 2.9 oder neuer
  * Neuste Version der AdSense-Erweiterung


## AdSense-Information ermitteln ##

Bevor die Erweiterung genutzt werden kann, müssen einige Informationen bekannt sein:
  * Die AdSense-Kundennummer (Publisher-Id)
  * Die Id der anzuzeigenden Werbung
  * Die Höhe und Breite des Werbeblocks

Alle Informationen können innerhalb von Google AdSense ermittelt werden.

### AdSense-Kundennummer (Publisher-Id) ###

Nach der Anmeldung bei Google AdSense, können Sie die Publisher-Id in der rechten oberen Ecke unter Ihrere E-Mail-Addresse sehen:

![http://contao-adsense.googlecode.com/svn/manual/publisher-id_en.png](http://contao-adsense.googlecode.com/svn/manual/publisher-id_en.png)

Sie beginnt mit "pub-" und muss komplett angegeben werden.

### Id, Höhe, Breite der Werbung ###

Diese Angaben können Sie beim Erstellen eines Werbeblocks ermitteln. Wollen Sie einen bereits erstellen Werbeblock nutzen, gehen Sie bitte wie folgt vor:
  * Melden Sie sich bei Google AdSense an
  * Klicken Sie auf "AdSense Setup"
  * Klicken Sie auf "Manage Ads"
  * Suchen Sie sich den anzuzeigenen Werbeblock heraus

Die Informationen sind in der Übersicht bereits enthalten:

![http://contao-adsense.googlecode.com/svn/manual/manage-ads_en.png](http://contao-adsense.googlecode.com/svn/manual/manage-ads_en.png)

Die Id befinden sich unter "Name". Breite und Höhe unter Size.



## Die Erweiterung nutzen ##

### Das Modul zur Seite hinzufügen ###

Wie gewohnt ein Modul zur Contao-Seite hinzufügen. Als Typ muss "Google AdSense" angegeben werden:

![http://contao-adsense.googlecode.com/svn/manual/selectmoduletype_de.png](http://contao-adsense.googlecode.com/svn/manual/selectmoduletype_de.png)

In den folgenden Einstellungsfeldern die Kundennummer, Id, Höhe und Breite eingeben

![http://contao-adsense.googlecode.com/svn/manual/addmodule_de.png](http://contao-adsense.googlecode.com/svn/manual/addmodule_de.png)

Damit ist das Modul erstellt und kann nun in ein Seitenlayout eingebunden und genutzt werden.